---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Describe Identity
  version: 1.0.0
  description: |-
    Returns metadata related to the given identity, including when the identity was
             created and any associated linked logins.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteIdentities:
    get:
      summary: Delete Identities
      description: Deletes identities from an identity pool.
      operationId: deleteIdentities
      x-api-path-slug: actiondeleteidentities-get
      parameters:
      - in: query
        name: IdentityIdsToDelete
        description: A list of 1-60 identities that you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identities
  /?Action=DescribeIdentity:
    get:
      summary: Describe Identity
      description: |-
        Returns metadata related to the given identity, including when the identity was
                 created and any associated linked logins.
      operationId: describeIdentity
      x-api-path-slug: actiondescribeidentity-get
      parameters:
      - in: query
        name: IdentityId
        description: A unique identifier in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identities
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
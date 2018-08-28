---
swagger: "2.0"
x-collection-name: AWS CloudFront
x-complete: 0
info:
  title: AWS CloudFront API List Cloud Front Origin Access Identities
  version: 1.0.0
  description: Lists origin access identities.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListCloudFrontOriginAccessIdentities:
    get:
      summary: List Cloud Front Origin Access Identities
      description: Lists origin access identities.
      operationId: listCloudFrontOriginAccessIdentities
      x-api-path-slug: actionlistcloudfrontoriginaccessidentities-get
      parameters:
      - in: query
        name: Affinity
        description: The new affinity setting for the instance
        type: string
      - in: query
        name: HostId
        description: The ID of the Dedicated Host that the instance will have affinity
          with
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance that you are modifying
        type: string
      - in: query
        name: Marker
        description: Use this when paginating results to indicate where to begin in
          your list of origin      access identities
        type: string
      - in: query
        name: MaxItems
        description: The maximum number of origin access identities you want in the
          response body
        type: string
      - in: query
        name: Tenancy
        description: The tenancy of the instance that you are modifying
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Cloud
      - Front
      - Origin
      - Access
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
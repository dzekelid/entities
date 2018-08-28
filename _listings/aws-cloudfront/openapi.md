---
swagger: "2.0"
x-collection-name: AWS CloudFront
x-complete: 1
info:
  title: AWS CloudFront API
  version: 1.0.0
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
---
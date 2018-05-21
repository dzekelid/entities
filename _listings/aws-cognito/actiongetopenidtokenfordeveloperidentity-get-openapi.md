---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Get Open Id Token For Developer Identity
  version: 1.0.0
  description: |-
    Registers (or retrieves) a Cognito IdentityId and an OpenID Connect
             token for a user authenticated by your backend authentication process.
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
  /?Action=GetCredentialsForIdentity:
    get:
      summary: Get Credentials For Identity
      description: Returns credentials for the provided identity ID.
      operationId: getCredentialsForIdentity
      x-api-path-slug: actiongetcredentialsforidentity-get
      parameters:
      - in: query
        name: CustomRoleArn
        description: The Amazon Resource Name (ARN) of the role to be assumed when
          multiple roles were         received in the token from the identity provider
        type: string
      - in: query
        name: IdentityId
        description: A unique identifier in the format REGION:GUID
        type: string
      - in: query
        name: Logins
        description: A set of optional name-value pairs that map provider names to
          provider         tokens
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identities
  /?Action=GetId:
    get:
      summary: Get Id
      description: Generates (or retrieves) a Cognito ID.
      operationId: getId
      x-api-path-slug: actiongetid-get
      parameters:
      - in: query
        name: AccountId
        description: A standard AWS account ID (9+ digits)
        type: string
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      - in: query
        name: Logins
        description: A set of optional name-value pairs that map provider names to
          provider tokens
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identities
  /?Action=GetOpenIdTokenForDeveloperIdentity:
    get:
      summary: Get Open Id Token For Developer Identity
      description: |-
        Registers (or retrieves) a Cognito IdentityId and an OpenID Connect
                 token for a user authenticated by your backend authentication process.
      operationId: getOpenIdTokenForDeveloperIdentity
      x-api-path-slug: actiongetopenidtokenfordeveloperidentity-get
      parameters:
      - in: query
        name: IdentityId
        description: A unique identifier in the format REGION:GUID
        type: string
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      - in: query
        name: Logins
        description: A set of optional name-value pairs that map provider names to
          provider tokens
        type: string
      - in: query
        name: TokenDuration
        description: The expiration time of the token, in seconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open ID Token for Developer Identities
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
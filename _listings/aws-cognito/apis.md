---
name: AWS Cognito
x-slug: aws-cognito
description: Amazon Cognito lets you easily add user sign-up and sign-in to your mobile
  and web apps. With Amazon Cognito, you also have the options to authenticate users
  through social identity providers such as Facebook, Twitter, or Amazon, with SAML
  identity solutions, or by using your own identity system. In addition, Amazon Cognito
  enables you to save data locally on users devices, allowing your applications to
  work even when the devices are offline. You can then synchronize data across users
  devices so that their app experience remains consistent regardless of the device
  they use. With Amazon Cognito, you can focus on creating great app experiences instead
  of worrying about building, securing, and scaling a solution to handle user management,
  authentication, and sync across devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
x-kinRank: "10"
x-alexaRank: ""
tags: Entities
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Cognito API Delete Identities
  x-api-slug: aws-cognito-api
  description: Deletes identities from an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteIdentities
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiondeleteidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiondeleteidentities-get-openapi.md
- name: AWS Cognito API Describe Identity
  x-api-slug: aws-cognito-api
  description: |-
    Returns metadata related to the given identity, including when the identity was
             created and any associated linked logins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentity
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiondescribeidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiondescribeidentity-get-openapi.md
- name: AWS Cognito API Get Credentials For Identity
  x-api-slug: aws-cognito-api
  description: Returns credentials for the provided identity ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetCredentialsForIdentity
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiongetcredentialsforidentity-get-openapi.md
- name: AWS Cognito API Get Id
  x-api-slug: aws-cognito-api
  description: Generates (or retrieves) a Cognito ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetId
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiongetid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiongetid-get-openapi.md
- name: AWS Cognito API Get Open Id Token For Developer Identity
  x-api-slug: aws-cognito-api
  description: |-
    Registers (or retrieves) a Cognito IdentityId and an OpenID Connect
             token for a user authenticated by your backend authentication process.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetOpenIdTokenForDeveloperIdentity
  tags: Open ID Token for Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actiongetopenidtokenfordeveloperidentity-get-openapi.md
- name: AWS Cognito API List Identities
  x-api-slug: aws-cognito-api
  description: Lists the identities in a pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListIdentities
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionlistidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionlistidentities-get-openapi.md
- name: AWS Cognito API Lookup Developer Identity
  x-api-slug: aws-cognito-api
  description: |-
    Retrieves the IdentityID associated with a
                DeveloperUserIdentifier or the list of
             DeveloperUserIdentifiers associated with an IdentityId for an
             existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=LookupDeveloperIdentity
  tags: Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionlookupdeveloperidentity-get-openapi.md
- name: AWS Cognito API Merge Developer Identities
  x-api-slug: aws-cognito-api
  description: |-
    Merges two users having different IdentityIds, existing in the same
             identity pool, and identified by the same developer provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=MergeDeveloperIdentities
  tags: Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionmergedeveloperidentities-get-openapi.md
- name: AWS Cognito API Unlink Developer Identity
  x-api-slug: aws-cognito-api
  description: Unlinks a DeveloperUserIdentifier from an existing identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UnlinkDeveloperIdentity
  tags: Developer Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionunlinkdeveloperidentity-get-openapi.md
- name: AWS Cognito API Unlink Identity
  x-api-slug: aws-cognito-api
  description: Unlinks a federated identity from an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UnlinkIdentity
  tags: Identities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionunlinkidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/actionunlinkidentity-get-openapi.md
- name: AWS Cognito API
  x-api-slug: aws-cognito-api
  description: Amazon Cognito lets you easily add user sign-up and sign-in to your
    mobile and web apps. With Amazon Cognito, you also have the options to authenticate
    users through social identity providers such as Facebook, Twitter, or Amazon,
    with SAML identity solutions, or by using your own identity system. In addition,
    Amazon Cognito enables you to save data locally on users devices, allowing your
    applications to work even when the devices are offline. You can then synchronize
    data across users devices so that their app experience remains consistent regardless
    of the device they use. With Amazon Cognito, you can focus on creating great app
    experiences instead of worrying about building, securing, and scaling a solution
    to handle user management, authentication, and sync across devices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Entities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/aws-cognito/openapi.md
x-common:
- type: x-blog
  url: https://aws.amazon.com/cognito/dev-resources/#blogposts
- type: x-documentation
  url: http://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitosync/latest/APIReference/Welcome.html
- type: x-faq
  url: http://aws.amazon.com/cognito/faqs
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=173
- type: x-pricing
  url: http://aws.amazon.com/cognito/pricing
- type: x-sdk
  url: https://aws.amazon.com/cognito/dev-resources/#documentation
- type: x-slides
  url: https://aws.amazon.com/cognito/dev-resources/#slides
- type: x-videos
  url: https://aws.amazon.com/cognito/dev-resources/#videos
- type: x-website
  url: https://aws.amazon.com/cognito/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
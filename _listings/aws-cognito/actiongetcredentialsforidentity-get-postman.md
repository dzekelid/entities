{
  "info": {
    "name": "AWS Cognito API Get Credentials For Identity",
    "_postman_id": "2107fb1b-9537-495e-bd88-6fcf1f504552",
    "description": "Returns credentials for the provided identity ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Identities",
      "item": [
        {
          "id": "24b447b1-b13e-4f71-a7b2-c37036f3b8a6",
          "name": "deleteIdentities",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentities?IdentityIdsToDelete=IdentityIdsToDelete",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes identities from an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fc636ad-280e-4a02-a54e-af18d2252899"
            }
          ]
        },
        {
          "id": "a4162e26-8c7a-4b12-99bc-0e760a8c589e",
          "name": "describeIdentity",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentity?IdentityId=IdentityId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns metadata related to the given identity, including when the identity was\n         created and any associated linked logins."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2eb09cf-3fca-4619-a411-33b553995eaa"
            }
          ]
        },
        {
          "id": "4f00663c-6c5d-42fb-8b85-9e6b64f656ff",
          "name": "getCredentialsForIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetCredentialsForIdentity?CustomRoleArn=CustomRoleArn&IdentityId=IdentityId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns credentials for the provided identity ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfd8759e-d486-4cec-acf9-c0f0e529f83d"
            }
          ]
        }
      ]
    }
  ]
}
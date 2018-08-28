{
  "info": {
    "name": "AWS Cognito API Get Id",
    "_postman_id": "5636c2ef-8946-4a6e-a9b5-3081ba2e9e5f",
    "description": "Generates (or retrieves) a Cognito ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Identities",
      "item": [
        {
          "id": "d1d72be6-478c-4dfe-8b42-066d52c625a3",
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
              "id": "3f5d9a5f-a72d-433e-9d39-ae5d52bfc809"
            }
          ]
        },
        {
          "id": "95328eb3-873d-45e7-82e7-969317a7cf24",
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
              "id": "8462d697-7059-4741-9238-3c463c026da5"
            }
          ]
        },
        {
          "id": "98c8c655-3b16-41b0-b9fe-7c79886ead77",
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
              "id": "effe0418-4cec-412e-aeef-9798ed549c40"
            }
          ]
        },
        {
          "id": "5c6c8b60-560c-46a8-81c6-36c465717d77",
          "name": "getId",
          "request": {
            "url": "http://example.com/api/?Action=GetId?AccountId=AccountId&IdentityPoolId=IdentityPoolId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates (or retrieves) a Cognito ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60578a61-d982-4658-8ac2-676c38bc1ac7"
            }
          ]
        }
      ]
    }
  ]
}
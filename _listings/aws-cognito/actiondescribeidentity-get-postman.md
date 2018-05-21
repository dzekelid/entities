{
  "info": {
    "name": "AWS Cognito API Describe Identity",
    "_postman_id": "03f17573-9432-46ba-8b89-c2ae50a0071b",
    "description": "Returns metadata related to the given identity, including when the identity was\n         created and any associated linked logins.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Identities",
      "item": [
        {
          "id": "ed89c7d1-0282-4ea4-a2a4-cb8200b776f6",
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
              "id": "4d3e009e-2c80-4b3d-930f-914f5df1bc48"
            }
          ]
        },
        {
          "id": "32ce4d24-f52d-4110-be93-221d4eb6564d",
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
              "id": "63c03a6e-b5bf-41eb-a563-dd8acdc727b4"
            }
          ]
        }
      ]
    }
  ]
}
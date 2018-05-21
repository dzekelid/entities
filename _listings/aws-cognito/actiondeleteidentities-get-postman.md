{
  "info": {
    "name": "AWS Cognito API Delete Identities",
    "_postman_id": "69550cb2-786b-4b27-8358-d312fcd0bbc9",
    "description": "Deletes identities from an identity pool.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Identities",
      "item": [
        {
          "id": "fe217998-9086-4ec4-87c7-d41043832c5b",
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
              "id": "02f7461c-af4e-49e1-a493-7e9e86417b0a"
            }
          ]
        }
      ]
    }
  ]
}
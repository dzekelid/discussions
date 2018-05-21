{
  "info": {
    "name": "Data.gov API Get Organizations Org Discussions",
    "_postman_id": "36b1c26a-dbcd-4619-b2d8-22c29c92daac",
    "description": "List organization discussions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "organizations",
      "item": [
        {
          "id": "007f0820-a29b-4cb1-b07b-99605383f289",
          "name": "getOrganizationsOrgDiscussions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "catalog.data.gov",
              "path": [
                "api",
                "3",
                "organizations/:org/discussions/"
              ],
              "variable": [
                {
                  "id": "org",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List organization discussions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "937c3257-15f8-4cf2-b68c-149cb51bbf0f"
            }
          ]
        }
      ]
    }
  ]
}
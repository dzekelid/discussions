{
  "info": {
    "name": "Data.gov API Delete Discussions",
    "_postman_id": "79360ec1-21b1-4d10-84fa-29de0ea634e2",
    "description": "Delete a discussion given its ID",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "discussions",
      "item": [
        {
          "id": "b49d12ee-e2ee-4f00-9c2f-529bdb55d092",
          "name": "deleteDiscussions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "catalog.data.gov",
              "path": [
                "api",
                "3",
                "discussions/:id/"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a discussion given its ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f78d8897-d538-4047-b3b8-dc6b937004f6"
            }
          ]
        }
      ]
    }
  ]
}
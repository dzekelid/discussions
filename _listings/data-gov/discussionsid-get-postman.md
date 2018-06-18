{
  "info": {
    "name": "Data.gov API Get Discussions",
    "_postman_id": "3e6df4d1-64c4-4084-9433-48a78e140d2e",
    "description": "Get a discussion given its ID",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "discussions",
      "item": [
        {
          "id": "4b448cc3-5791-4ff8-8b1a-31ccaf2b944b",
          "name": "getDiscussions",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a discussion given its ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4523205-a169-4799-9659-7449973287b0"
            }
          ]
        }
      ]
    }
  ]
}
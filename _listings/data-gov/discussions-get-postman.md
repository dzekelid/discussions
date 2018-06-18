{
  "info": {
    "name": "Data.gov API Get Discussions",
    "_postman_id": "b419805c-57aa-420e-904a-7204a0d6f661",
    "description": "List all Discussions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "discussions",
      "item": [
        {
          "id": "3253b1cf-5717-451c-8cc6-905afd289d73",
          "name": "getDiscussions",
          "request": {
            "url": "http://catalog.data.gov/api/3/discussions/?closed=%7B%7D&for=%7B%7D&page=%7B%7D&page_size=%7B%7D&sort=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all Discussions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4714c7b4-d540-4e72-9a54-7c8831b83de6"
            }
          ]
        }
      ]
    }
  ]
}
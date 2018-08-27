{
  "info": {
    "name": "Data.gov API Get Me Org Discussions",
    "_postman_id": "2004d1d0-2a5a-45a7-a86a-05b36d46ce3a",
    "description": "List all discussions related to my organizations",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "me",
      "item": [
        {
          "id": "3e6907b4-defd-477e-ba1c-d8d9aa8fed91",
          "name": "getMeOrgDiscussions",
          "request": {
            "url": "http://catalog.data.gov/api/3/me/org_discussions/?q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all discussions related to my organizations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3b6bc22-6896-493d-a008-f251bfbef976"
            }
          ]
        }
      ]
    }
  ]
}
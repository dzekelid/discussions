{
  "info": {
    "name": "Steem get discussions",
    "_postman_id": "995350f4-bce4-4d17-9de4-e47171d00285",
    "description": "get discussions, | query example {\"limit\":\"10\", \"tags\":\"good-karma\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "af84b736-0231-48d5-ba4d-174b83a53df3",
          "name": "returns-version-information-of-connected-steem-nodewebsocket",
          "request": {
            "url": "http://api.steemjs.com/get_version",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns version information of connected Steem node/websocket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb942e46-e58c-4333-9f35-8d9a8d046599"
            }
          ]
        },
        {
          "id": "282bd1d8-ddd3-4243-b02d-3129fe22880e",
          "name": "get-chain-properties",
          "request": {
            "url": "http://api.steemjs.com/get_chain_properties",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get chain properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d803b4e-d3d9-4cd0-a73c-cf7686c39911"
            }
          ]
        },
        {
          "id": "16c09291-b3da-4204-8bf2-a73b4fb64878",
          "name": "get-config",
          "request": {
            "url": "http://api.steemjs.com/get_config",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get config"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a02a5d4-31ce-4e68-aa43-9b0df887ae44"
            }
          ]
        },
        {
          "id": "07812f46-e22e-4527-a820-ce3b0f0cf923",
          "name": "get-dynamic-global-properties",
          "request": {
            "url": "http://api.steemjs.com/get_dynamic_global_properties",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_dynamic_global_properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91545545-822e-4a12-823f-f415a04de54e"
            }
          ]
        },
        {
          "id": "2db1e529-5ea1-46a8-b1e3-7dc0f394ebf0",
          "name": "get-feed-history",
          "request": {
            "url": "http://api.steemjs.com/get_feed_history",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_feed_history"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a22aed4d-d314-48b0-b03f-edc91a0b737c"
            }
          ]
        },
        {
          "id": "6c76236f-e6e8-4e96-9f08-82dbc6ec9d94",
          "name": "get-current-median-history-price",
          "request": {
            "url": "http://api.steemjs.com/get_current_median_history_price",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_current_median_history_price"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c090223d-bfe1-4cbe-a8bd-ab8e348be975"
            }
          ]
        },
        {
          "id": "38d12449-981d-47c7-ba75-61e5eefc9c3d",
          "name": "get-hardfork-version",
          "request": {
            "url": "http://api.steemjs.com/get_hardfork_version",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_hardfork_version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e358cc4-c121-44fc-be7c-9b12c898dbcb"
            }
          ]
        },
        {
          "id": "931b84b8-4b3c-433b-9eb5-defcca279e9e",
          "name": "get-next-scheduled-hardfork",
          "request": {
            "url": "http://api.steemjs.com/get_next_scheduled_hardfork",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_next_scheduled_hardfork"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ad2a55f-0330-48f1-893c-82cf1ce4d4f6"
            }
          ]
        },
        {
          "id": "fdd047ef-a62b-42a9-8f00-0a5889da4629",
          "name": "get-witness-count",
          "request": {
            "url": "http://api.steemjs.com/get_witness_count",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_witness_count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dcf1d1b3-725b-43e0-8c88-2347d3f26024"
            }
          ]
        },
        {
          "id": "e62d750f-4043-4ed8-9c60-61518a2c9d4f",
          "name": "get-witness-schedule",
          "request": {
            "url": "http://api.steemjs.com/get_witness_schedule",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_witness_schedule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9edacb5-9a26-405c-86e9-94371223b513"
            }
          ]
        },
        {
          "id": "bf6c7e7f-9a8b-4122-9fd1-3f750e3e6398",
          "name": "get-witnesses",
          "request": {
            "url": "http://api.steemjs.com/get_witnesses?witnessIds=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_witnesses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1976f180-9ae2-48e3-8e96-95aad4d008f1"
            }
          ]
        },
        {
          "id": "3cdfecfc-8765-4b71-a60a-eaa0fa9a4835",
          "name": "get-witness-by-account",
          "request": {
            "url": "http://api.steemjs.com/get_witness_by_account?accountName=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_witness_by_account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d020bc00-587b-4ac6-a2ff-a32253b5bab2"
            }
          ]
        },
        {
          "id": "62804fd5-26c7-4d05-9d81-f01c71401915",
          "name": "get-witnesses-by-vote",
          "request": {
            "url": "http://api.steemjs.com/get_witnesses_by_vote?from=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_witnesses_by_vote"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9a47816-5368-4dcb-87fb-1d25571e65ac"
            }
          ]
        },
        {
          "id": "79b141a2-82b0-472f-b170-95809c30d84d",
          "name": "get-active-witnesses",
          "request": {
            "url": "http://api.steemjs.com/get_active_witnesses",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_active_witnesses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "def422c6-303e-4ade-8bc8-f43f4e8f7efd"
            }
          ]
        },
        {
          "id": "62136a34-c08c-42ba-8a79-a1d2ac9c1e52",
          "name": "get-miner-queue",
          "request": {
            "url": "http://api.steemjs.com/get_miner_queue",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_miner_queue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e0ebba7-8c64-43c7-9d7a-a28925d71f4d"
            }
          ]
        },
        {
          "id": "8133ec41-1e74-4350-86f3-7f5d12fe0624",
          "name": "get-liquidity-queue",
          "request": {
            "url": "http://api.steemjs.com/get_liquidity_queue?limit=%7B%7D&startAccount=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_liquidity_queue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b41d283f-6bd6-4c5c-9ce5-110360efaa7d"
            }
          ]
        },
        {
          "id": "1a0bbede-532c-44b8-9f65-d354b5907b03",
          "name": "get-open-orders",
          "request": {
            "url": "http://api.steemjs.com/get_open_orders?owner=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_open_orders"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d108be2-f0f4-407f-96eb-73db25eed4cb"
            }
          ]
        },
        {
          "id": "8a0643aa-4e43-4053-b2a9-cc2afe27b9b0",
          "name": "get-order-book",
          "request": {
            "url": "http://api.steemjs.com/get_order_book?limit=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_order_book"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfca4e81-01a9-433f-b525-feda810cfdfb"
            }
          ]
        },
        {
          "id": "749cacc9-0a40-430f-9ce8-51fe8f8d0c9a",
          "name": "get-tags",
          "request": {
            "url": "http://api.steemjs.com/get_active_categories?after=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "212a2e51-5330-42c6-9cb0-c3e0cfccc31d"
            }
          ]
        },
        {
          "id": "0ba1dae5-304a-4012-8034-03326714c780",
          "name": "get-tags1",
          "request": {
            "url": "http://api.steemjs.com/get_best_categories?after=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8bf15e0-f458-4d53-ba6e-7270cccfad31"
            }
          ]
        },
        {
          "id": "796bf068-b526-40bb-99bc-c500067aacd7",
          "name": "get-tags2",
          "request": {
            "url": "http://api.steemjs.com/get_recent_categories?after=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5ee64ea-60e2-46b8-b3eb-a765a36cb6ed"
            }
          ]
        },
        {
          "id": "88b23d11-7b48-4870-b709-1a6ede8c3ffd",
          "name": "get-tags3",
          "request": {
            "url": "http://api.steemjs.com/get_trending_categories?after=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d4b69ba-f945-4806-8721-d3f5a6962b84"
            }
          ]
        },
        {
          "id": "bdfc8208-42f5-4949-81e9-9cedb997d640",
          "name": "get-tags",
          "request": {
            "url": "http://api.steemjs.com/get_trending_tags?afterTag=%7B%7D&limit=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e8bd683-b63d-4cd6-a29c-3b389d384d20"
            }
          ]
        },
        {
          "id": "eaa13966-f5c8-4fa5-bebd-c35aedb16c00",
          "name": "get-content",
          "request": {
            "url": "http://api.steemjs.com/get_content?author=%7B%7D&permlink=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get content"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36927d23-38e6-4f5b-800c-8d7630357484"
            }
          ]
        },
        {
          "id": "ad961de2-af0c-48ca-bf88-5cec08c21554",
          "name": "get-content-replies",
          "request": {
            "url": "http://api.steemjs.com/get_content_replies?author=%7B%7D&permlink=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get content replies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb93ab90-2707-4254-947d-69ec42109e56"
            }
          ]
        },
        {
          "id": "479405f3-42ee-4a5b-8aed-78b2e1ebc42c",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_trending?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b941a57-e441-4baf-add9-2538b58e36c3"
            }
          ]
        },
        {
          "id": "cf34ce9b-beef-4f79-9113-0bb1944e169b",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio1",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_trending30?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0884244-5ff4-4766-8cc3-e745e2994698"
            }
          ]
        },
        {
          "id": "6eb2bd5f-4b3c-4151-b77d-7fabc1f4151c",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio2",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_created?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ebd957b1-2a24-44e3-b0e8-ea936744aa59"
            }
          ]
        },
        {
          "id": "ee45183f-f550-4b6c-8e24-4a9c3be33e9f",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio3",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_active?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "324090bb-ac07-4c69-b9c0-2cf25b4ebfcb"
            }
          ]
        },
        {
          "id": "621956c6-8eb8-48ff-94e0-246f55fb82e1",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio4",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_promoted?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39088e4f-b37c-4ef3-b06f-25ab72e2561f"
            }
          ]
        },
        {
          "id": "769be501-2bce-4f46-9846-da978e21c792",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio5",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_cashout?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2832b6f-29b4-440a-ac7e-7241234a022d"
            }
          ]
        },
        {
          "id": "3ee2d734-0355-4204-be0b-083010e4081a",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio6",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_payout?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1e43a17-c751-4700-a25a-13e1d511b5fc"
            }
          ]
        },
        {
          "id": "f08166f0-b2fb-4a0e-9af7-e239b5dde96a",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio7",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_votes?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "123fb34d-802a-424f-90f2-b99838ea39d3"
            }
          ]
        },
        {
          "id": "374b26a2-e767-4d1d-8260-25061bf6ea7c",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio8",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_children?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2979ff0f-49b2-4eab-87ed-3a021b3531f2"
            }
          ]
        },
        {
          "id": "87d616ab-520e-425c-8ac7-134bb8c1b3fd",
          "name": "get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio9",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_hot?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c044e96-cc35-4ad3-b514-d9c2a2088f87"
            }
          ]
        },
        {
          "id": "fbe888a3-cece-4703-aa7d-e3b628c8bb6b",
          "name": "get-discussions--query-example-limit10-tagsgoodkarma-or-start-authorauthor-permlinkpermlink-for-pagi",
          "request": {
            "url": "http://api.steemjs.com/get_discussions_by_feed?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get discussions, | query example {\"limit\":\"10\", \"tags\":\"good-karma\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e4bf033-b7a6-47e0-997d-68e8ee6d75f1"
            }
          ]
        }
      ]
    },
    {
      "name": "Number",
      "item": [
        {
          "id": "411d8709-bc62-4b89-98c4-34ed0e66a480",
          "name": "get-number-of-accounts-from-steem",
          "request": {
            "url": "http://api.steemjs.com/get_account_count",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get Number of Accounts from Steem"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "707250ac-edf2-4637-941e-e62001ec03cd"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "83c4854d-331b-4397-99fe-ac5678b9ee2a",
          "name": "lookup-witness-accounts-regex-search",
          "request": {
            "url": "http://api.steemjs.com/lookup_witness_accounts?limit=%7B%7D&lowerBoundName=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "lookup_witness_accounts regex search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3dfd0cab-73e4-456c-93ee-047576aa3f87"
            }
          ]
        }
      ]
    },
    {
      "name": "Witness",
      "item": [
        {
          "id": "64187e8c-9078-46b3-b5ee-2b571f17aa51",
          "name": "witness-update",
          "request": {
            "url": "http://api.steemjs.com/witness_update?block_signing_key=%7B%7D&fee=%7B%7D&owner=%7B%7D&props=%7B%7D&url=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "witness_update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "916cc177-9447-4443-8152-c7b89fe17056"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Steem get discussions",
    "_postman_id": "855ba6fa-38ea-42c9-8b69-10223dfbf92e",
    "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "a3186e9c-76a9-4fe4-8853-2a0b00be8866",
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
              "id": "1700a18b-c8f0-40bb-b878-170e12249b98"
            }
          ]
        },
        {
          "id": "45baa16c-d1ba-4b92-b5fa-3ffdb4bc8f4a",
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
              "id": "55660674-baff-4268-85f4-08c203b6691b"
            }
          ]
        },
        {
          "id": "f793dd8a-8947-4375-9063-8df1f3b30b7a",
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
              "id": "80dc92ff-a9ae-4d7c-ab78-81d84e4ed926"
            }
          ]
        },
        {
          "id": "95a68d32-ea95-43a6-923b-ec0408cf7884",
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
              "id": "3d080dc3-6e81-40e7-b2b7-c65d338b4a2d"
            }
          ]
        },
        {
          "id": "626baa83-0a90-41bf-a73f-41548fd104be",
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
              "id": "0c77fd3f-97b8-4154-8737-a1ac98398c91"
            }
          ]
        },
        {
          "id": "f1532e01-920d-41ea-8e4e-907822f010d4",
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
              "id": "44b26f7f-1b5a-446e-8682-1e09b87b36da"
            }
          ]
        },
        {
          "id": "ad1e8e10-732e-4b63-948b-adf36ecefb75",
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
              "id": "f989a89e-6728-46a8-9920-d7ab742291d3"
            }
          ]
        },
        {
          "id": "5e786168-6999-4371-92c0-71cb2cbd4002",
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
              "id": "bcf1d889-cd12-49e1-af0f-a3d4f13da0a4"
            }
          ]
        },
        {
          "id": "a72a202b-05f5-4f3e-a9ed-09f3272c20e1",
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
              "id": "c7298014-4e31-4dc2-9e2e-00f98cbeb392"
            }
          ]
        },
        {
          "id": "8792d689-7513-4722-a132-3b54a9d07f2b",
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
              "id": "83ed3581-5ed1-4acf-933b-3b8adf9fab6c"
            }
          ]
        },
        {
          "id": "f1b34570-c44e-4c66-93c5-a858ec839776",
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
              "id": "3ec1d076-71c1-496d-8981-77727a3bf10a"
            }
          ]
        },
        {
          "id": "6288ea10-175e-4ec2-b023-880004fecb27",
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
              "id": "dc1ad953-7296-4880-ad26-015d8840af02"
            }
          ]
        },
        {
          "id": "c068a3ff-258d-4f6c-a7e0-ad7e64d53e49",
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
              "id": "5d14990a-7b0a-44d4-a255-543ff6d83c8f"
            }
          ]
        },
        {
          "id": "bec6a3eb-c022-4024-b6e5-2bb9d9d36d7f",
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
              "id": "3d8d5bb0-193e-416b-933d-c14cf4f261b1"
            }
          ]
        },
        {
          "id": "bc454178-5d17-45ef-a5c4-ddf6faece055",
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
              "id": "022213d6-83b3-4537-a785-d95cefbe8090"
            }
          ]
        },
        {
          "id": "dcb1cb41-9cc7-4484-b1b3-5094f8890799",
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
              "id": "889e5737-6ad4-4b33-b3bd-e7f00c862b0c"
            }
          ]
        },
        {
          "id": "7348a593-8bf0-4532-908f-198e3c1e3abd",
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
              "id": "710e68f6-7273-489f-b7ee-9b1707ae2d2d"
            }
          ]
        },
        {
          "id": "80cfe952-667f-45ed-bc8e-3a545fbfdf36",
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
              "id": "41b52396-b193-4c1e-8bc6-695812327f96"
            }
          ]
        },
        {
          "id": "4bf4d616-c8dd-40fb-bdeb-ba632bfd4f25",
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
              "id": "3ed442e4-1f32-4599-b82b-e2e52688d996"
            }
          ]
        },
        {
          "id": "f68e19c7-47ef-4ea0-8bd9-d88ca58ea59b",
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
              "id": "149ff451-93ff-4efa-8735-46d23f25ee18"
            }
          ]
        },
        {
          "id": "0f0812de-a434-4573-b698-2a78f9976cd8",
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
              "id": "353fa8d9-312a-45dc-9114-fb18f5e6b9d4"
            }
          ]
        },
        {
          "id": "1b19658a-39d5-43d5-be8d-686dd3f7b9eb",
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
              "id": "e720c816-9b72-4507-b1c4-67315b05d37b"
            }
          ]
        },
        {
          "id": "bb312f0f-c345-42f7-8c49-c598e8d70c68",
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
              "id": "bf52ad80-51b7-4fd0-8d4e-b72f39cd42e2"
            }
          ]
        },
        {
          "id": "5365c484-6f3d-448c-9abc-12f0c8d3a115",
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
              "id": "bf79dab1-d6ea-497f-815d-4459c46ec543"
            }
          ]
        },
        {
          "id": "a38cd480-dbef-45ce-b616-e26e9210958e",
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
              "id": "358b1c2e-1666-4a80-9fdc-708d1a695da0"
            }
          ]
        },
        {
          "id": "3812c3c7-be62-43b9-a3e7-3522ffd2b541",
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
              "id": "cac113ac-1e7a-40b6-9ae2-6b99fd41ff2c"
            }
          ]
        },
        {
          "id": "e35cf68a-9a16-492a-b2c7-c3240504b127",
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
              "id": "89f98eb3-acab-4772-9988-3098a488cdec"
            }
          ]
        },
        {
          "id": "3eb3c37a-ea53-47a7-86bd-8c5b22a3ccdf",
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
              "id": "71ef77a4-7f82-4dfe-b6c6-4e25f59c5055"
            }
          ]
        },
        {
          "id": "f1b0ae69-5b50-4d7c-958d-6f3635580f25",
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
              "id": "499bce1c-9f8f-43c8-9e05-563ff9f7d3fe"
            }
          ]
        },
        {
          "id": "73ee6940-740b-437a-af83-1de2f8bc2774",
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
              "id": "46ea13a8-3892-46c7-a07c-606be4f17e53"
            }
          ]
        },
        {
          "id": "81139e3b-5c4f-4284-be99-d65b4984251a",
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
              "id": "01ecb368-49dc-4ed4-aecd-3a32c729351b"
            }
          ]
        },
        {
          "id": "86e80abe-def4-4976-a85d-ea72fa440766",
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
              "id": "6f0a7ef1-b92e-41bf-b091-df9532dc97b3"
            }
          ]
        },
        {
          "id": "9f224cfb-2ef7-4fa9-9563-fc3678825578",
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
              "id": "d152824c-34e4-4215-a1ec-6e72a6b7918a"
            }
          ]
        },
        {
          "id": "531b9da5-f554-4d04-b9fb-f25c43697788",
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
              "id": "4ef17705-4f63-4508-904a-fde06e008368"
            }
          ]
        }
      ]
    },
    {
      "name": "Number",
      "item": [
        {
          "id": "42e7b47b-5f28-43f8-8ccc-b01ddb4e2e03",
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
              "id": "e6093d10-d70a-41cf-8b7f-c28ba7e51699"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "b64026ca-07ab-4560-9aaf-0497c8efaaf6",
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
              "id": "cdbbdc7f-afef-4361-800a-c68989f46612"
            }
          ]
        }
      ]
    },
    {
      "name": "Witness",
      "item": [
        {
          "id": "ecc3d588-512a-4e47-bbf9-b2d1c4a3f8e7",
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
              "id": "7d564d33-4a33-4c9e-b038-6598b2bfc12d"
            }
          ]
        }
      ]
    }
  ]
}
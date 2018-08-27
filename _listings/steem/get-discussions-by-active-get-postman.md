{
  "info": {
    "name": "Steem get discussions",
    "_postman_id": "c3b2c589-22b6-45ed-a9ba-6b623f63fd1d",
    "description": "get discussions, | query example {\"limit\":\"10\", \"tag\":\"steem\"} OR {\"start_author\":\"author\", \"permlink\":\"permlink\"} for pagination",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "65207ec3-7b3f-43c1-85b2-ae091d8876ff",
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
              "id": "aa20e3a9-b344-45b5-8e71-7f191bc44e3b"
            }
          ]
        },
        {
          "id": "302f07b2-c5a8-4276-be3a-2007298f45b2",
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
              "id": "1e17914a-677e-4d83-944c-16965e803f25"
            }
          ]
        },
        {
          "id": "97b6afc6-944d-4a0d-bee9-566fd6dd3432",
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
              "id": "eca429f2-70cd-4d73-aee7-36c6224a9848"
            }
          ]
        },
        {
          "id": "51c9d619-ac9e-4a34-b17d-54938c6ecfe3",
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
              "id": "0d9a69fa-3850-46f7-9119-8760fb5efa8f"
            }
          ]
        },
        {
          "id": "9082e445-0544-43a8-a91e-ec2d3c61ee2d",
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
              "id": "688246b0-072d-4801-8507-0528737343ad"
            }
          ]
        },
        {
          "id": "a05c39b5-0dbb-4e60-b3ed-7fed59c3dec4",
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
              "id": "0b60ff99-b062-4df5-9e42-d87fa8597044"
            }
          ]
        },
        {
          "id": "dc19a0e4-3415-4a71-a323-61c59960fcda",
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
              "id": "3954b829-e965-4d26-a824-51ab916996bf"
            }
          ]
        },
        {
          "id": "ba1af38a-abd9-4c38-8092-2bac721fac64",
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
              "id": "d79b2dd4-f43d-417b-9e37-7b5cd42fcb1a"
            }
          ]
        },
        {
          "id": "256a27da-baa0-4f4a-9134-a282726e7037",
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
              "id": "32ac7a68-53d9-4559-abd5-8f116f68d32e"
            }
          ]
        },
        {
          "id": "ed6238c6-a17f-42d7-b797-73f599af1b14",
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
              "id": "028c7867-d165-4885-b517-f9fe9e5848f5"
            }
          ]
        },
        {
          "id": "b5c6548e-2657-4fdf-b382-c8ca215119da",
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
              "id": "9948102c-a934-4bc6-a85a-9792ed072eb3"
            }
          ]
        },
        {
          "id": "51964c7f-3592-46fd-9f4a-b17e5e25ccd6",
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
              "id": "517e0839-d889-4794-af4e-3a9654d5e14c"
            }
          ]
        },
        {
          "id": "533383a5-34c9-4e72-855f-714119bf00fd",
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
              "id": "5a5e4569-9a58-4974-94d7-6f2a1291dfa6"
            }
          ]
        },
        {
          "id": "b29039bc-87a0-40a0-a2bd-98e9671f28e0",
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
              "id": "7cb42a42-93be-4933-915c-440aef1db37e"
            }
          ]
        },
        {
          "id": "36c22ffc-f52a-493d-90c2-3a5587a90040",
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
              "id": "1b9697c4-e3b3-4cf5-b76c-f78f768b34b1"
            }
          ]
        },
        {
          "id": "4871b00d-0308-476c-ae48-7297d60361db",
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
              "id": "56c82ec8-023d-46bf-9b3b-70934c6d7a51"
            }
          ]
        },
        {
          "id": "57ff4c1b-3a87-46f3-95b7-f2b41c20db6d",
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
              "id": "c7460b94-192e-4978-8cd9-4dfc6967673d"
            }
          ]
        },
        {
          "id": "47900461-f32a-4926-948f-1fa9ceb366e7",
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
              "id": "1d1a25ba-3c1b-4d41-8265-b678b21f2a34"
            }
          ]
        },
        {
          "id": "b1188156-5d93-437b-8149-16cb527cf6a3",
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
              "id": "63cf4a89-7bc8-4990-a42f-7ec5b7943e1e"
            }
          ]
        },
        {
          "id": "d4568430-abf2-409d-9247-18a79e801faf",
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
              "id": "43fe633d-954e-41a5-9e55-7ab719e84caa"
            }
          ]
        },
        {
          "id": "609b68bd-abbd-4529-959b-31ddbb2de750",
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
              "id": "29dd3173-8f2d-456f-95a2-056c82e2d9cb"
            }
          ]
        },
        {
          "id": "9bdc86b8-e23e-4058-9884-43f747b388fa",
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
              "id": "1738a47b-daf0-4637-92f0-b880e6b721c0"
            }
          ]
        },
        {
          "id": "70ff43c2-f8d8-478b-991c-b52d824f027d",
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
              "id": "8ed9b48d-30c2-48a5-8546-5be9160a2087"
            }
          ]
        },
        {
          "id": "ba9a9dd1-e803-4a44-9e72-1540ba39e604",
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
              "id": "108f67c0-e8b9-4bd2-933b-e793b873ce37"
            }
          ]
        },
        {
          "id": "4d3e298a-cef6-4efa-b04e-3b6e732102c4",
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
              "id": "8712e9c2-2807-4a2f-9aea-a2922816e6b0"
            }
          ]
        },
        {
          "id": "cca1af5a-76dc-4a62-ac86-28d30daeabf5",
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
              "id": "74f1b37f-b214-4d72-a12e-9a513602a872"
            }
          ]
        },
        {
          "id": "4e33d282-ee61-496d-81af-c0d0f3a202b7",
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
              "id": "90975b42-dc50-4154-bdc9-273d4726a92f"
            }
          ]
        },
        {
          "id": "69875fce-bc93-4074-bf36-7a8cd3865d1d",
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
              "id": "f23c6a21-5e27-451c-b1db-ea3f149fb55c"
            }
          ]
        },
        {
          "id": "53807d42-2050-4293-a57e-4c3bdd37ba08",
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
              "id": "a335b417-d399-4c19-a66a-4882316dead2"
            }
          ]
        }
      ]
    },
    {
      "name": "Number",
      "item": [
        {
          "id": "4c0293b8-323b-4563-a23e-fa39e5578a9f",
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
              "id": "11274945-d37e-4f33-b483-66b96a46c82e"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "108a76c4-f631-4dd9-bc18-cc8234343e6b",
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
              "id": "552ba78f-1f8b-4acb-934d-f7347453de05"
            }
          ]
        }
      ]
    },
    {
      "name": "Witness",
      "item": [
        {
          "id": "7ebf53d4-c531-4287-8cf5-dbabe08feec1",
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
              "id": "292f550c-f9d1-46cc-af6f-2d9456ef3036"
            }
          ]
        }
      ]
    }
  ]
}
---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get discussions
  description: get discussions, | query example {"limit":"10", "tags":"good-karma"}
    OR {"start_author":"author", "permlink":"permlink"} for pagination
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_discussions_by_trending:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-trending-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_trending30:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-trending30-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_created:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-created-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_active:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-active-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_promoted:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-promoted-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_cashout:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-cashout-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_payout:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-payout-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_votes:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-votes-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_children:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-children-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_hot:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tag":"steem"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsteem-or-start-authorauthor-permlinkpermlink-for-paginatio
      x-api-path-slug: get-discussions-by-hot-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
  /get_discussions_by_feed:
    get:
      summary: get discussions
      description: get discussions, | query example {"limit":"10", "tags":"good-karma"}
        OR {"start_author":"author", "permlink":"permlink"} for pagination
      operationId: get-discussions--query-example-limit10-tagsgoodkarma-or-start-authorauthor-permlinkpermlink-for-pagi
      x-api-path-slug: get-discussions-by-feed-get
      parameters:
      - in: query
        name: query
        description: query object
      responses:
        200:
          description: OK
      tags:
      - Get
      - Discussions
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  description: the-meetup-api-provides-simple-restful-http-and-streaming-interfaces-for-exploring-and-interacting-meetup-platform-from-your-own-apps--the-api-is-a-set-of-core-methods-and-a-common-request-format--these-are-combined-to-form-a-url-that-returns-the-information-you-want--
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:urlname/boards:
    get:
      summary: Discussion Boards
      description: Listings of Group discussion boards
      operationId: boards
      x-api-path-slug: urlnameboards-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discussions
  /:urlname/boards/:bid/discussions:
    get:
      summary: Discussions
      description: Listings of group discussions
      operationId: boards
      x-api-path-slug: urlnameboardsbiddiscussions-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discussions
  /:urlname/boards/:bid/discussions/:did:
    get:
      summary: Discussion Posts
      description: Listing Group discussion posts
      operationId: boards
      x-api-path-slug: urlnameboardsbiddiscussionsdid-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discussions
---
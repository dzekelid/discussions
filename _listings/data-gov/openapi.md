swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 1
info:
  title: Data.gov API
  description: the-data-gov-catalog-is-powered-by-ckan-a-powerful-open-source-data-platform-that-includes-a-robust-api--please-be-aware-that-data-gov-and-the-data-gov-ckan-api-only-contain-metadata-about-datasets--this-metadata-includes-urls-and-descriptions-of-datasets-but-it-does-not-include-the-actual-data-within-each-dataset-
  version: "3"
host: catalog.data.gov
basePath: /api/3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /discussions/:
    get:
      summary: Get Discussions
      description: List all Discussions
      operationId: getDiscussions
      x-api-path-slug: discussions-get
      parameters:
      - in: query
        name: closed
        description: Filters discussions on their closed status if specified
      - in: query
        name: for
        description: Filter discussions for a given subject
      - in: query
        name: page
        description: The page to fetch
      - in: query
        name: page_size
        description: The page size to fetch
      - in: query
        name: sort
        description: The sorting attribute
      responses:
        200:
          description: OK
      tags:
      - Discussions
    post:
      summary: Add Discussions
      description: Create a new Discussion
      operationId: postDiscussions
      x-api-path-slug: discussions-post
      parameters:
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Discussions
  /discussions/{id}/:
    delete:
      summary: Delete Discussions
      description: Delete a discussion given its ID
      operationId: deleteDiscussions
      x-api-path-slug: discussionsid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Discussions
    get:
      summary: Get Discussions
      description: Get a discussion given its ID
      operationId: getDiscussions
      x-api-path-slug: discussionsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Discussions
    post:
      summary: Add Discussions
      description: Add comment and optionnaly close a discussion given its ID
      operationId: postDiscussions
      x-api-path-slug: discussionsid-post
      parameters:
      - in: path
        name: id
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Discussions
  /me/org_discussions/:
    get:
      summary: Get Me Org Discussions
      description: List all discussions related to my organizations
      operationId: getMeOrgDiscussions
      x-api-path-slug: meorg-discussions-get
      parameters:
      - in: query
        name: q
        description: The string to filter items
      responses:
        200:
          description: OK
      tags:
      - Me
      - Org
      - Discussions
  /organizations/{org}/discussions/:
    get:
      summary: Get Organizations Org Discussions
      description: List organization discussions
      operationId: getOrganizationsOrgDiscussions
      x-api-path-slug: organizationsorgdiscussions-get
      parameters:
      - in: path
        name: org
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Discussions
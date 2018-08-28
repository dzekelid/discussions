swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '{/r/subreddit}/wiki/discussions/page':
    get&nbsp;:
      summary: Get Subreddit Wiki Discussions Page
      description: Retrieve a list of discussions about this wiki page
      operationId: get&nbsp;RSubredditWikiDiscussionsPage
      x-api-path-slug: rsubredditwikidiscussionspage-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: page
        description: the name of an existing wiki page
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Wiki
      - Discussions
      - Page
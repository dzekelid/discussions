---
name: Meetup
x-slug: meetup
description: Meetup is an online social networking portal that facilitates offline
  group meetings in various localities around the world. Meetup allows members to
  find and join groups unified by a common interest, such as politics, books, games,
  movies, health, pets, careers or hobbies.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Discussions
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/apis.md
specificationVersion: "0.14"
apis:
- name: Meetup Discussion Boards
  x-api-slug: meetup
  description: Listings of Group discussion boards
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
  humanURL: http://www.meetup.com/
  baseURL: https://api.meetup.com////:urlname/boards
  tags: Events,Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/urlnameboards-get-openapi.md
- name: Meetup Discussions
  x-api-slug: meetup
  description: Listings of group discussions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
  humanURL: http://www.meetup.com/
  baseURL: https://api.meetup.com////:urlname/boards/:bid/discussions
  tags: Events,Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/urlnameboardsbiddiscussions-get-openapi.md
- name: Meetup Discussion Posts
  x-api-slug: meetup
  description: Listing Group discussion posts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
  humanURL: http://www.meetup.com/
  baseURL: https://api.meetup.com////:urlname/boards/:bid/discussions/:did
  tags: Events,Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/urlnameboardsbiddiscussionsdid-get-openapi.md
- name: Meetup
  x-api-slug: meetup
  description: Meetup is an online social networking portal that facilitates offline
    group meetings in various localities around the world. Meetup allows members to
    find and join groups unified by a common interest, such as politics, books, games,
    movies, health, pets, careers or hobbies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
  humanURL: http://www.meetup.com/
  baseURL: https://api.meetup.com//
  tags: Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/openapi.md
x-common:
- type: x-base
  url: http://api.meetup.com
- type: x-developer
  url: http://www.meetup.com/meetup_api/
- type: x-github
  url: https://github.com/meetup
- type: x-pricing
  url: http://www.meetup.com/pricing/
- type: x-privacy
  url: http://www.meetup.com/privacy/
- type: x-support
  url: http://www.meetup.com/help/
- type: x-terms-of-service
  url: http://www.meetup.com/terms/
- type: x-twitter
  url: https://twitter.com/MeetupAPI
- type: x-website
  url: http://www.meetup.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
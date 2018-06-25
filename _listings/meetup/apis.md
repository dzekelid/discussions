---
name: Meetup
x-slug: meetup
description: Find Meetups so you can do more of what matters to you. Or create your
  own group and meet people near you who share your interests.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
x-kinRank: "9"
x-alexaRank: "917"
tags: Discussions
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/apis.md
specificationVersion: "0.14"
apis:
- name: Meetup Discussion Boards
  x-api-slug: meetup
  description: Listings of Group discussion boards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/boards
  tags: Events,Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/urlnameboards-get-openapi.md
- name: Meetup Discussions
  x-api-slug: meetup
  description: Listings of group discussions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/boards/:bid/discussions
  tags: Events,Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/urlnameboardsbiddiscussions-get-openapi.md
- name: Meetup Discussion Posts
  x-api-slug: meetup
  description: Listing Group discussion posts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/boards/:bid/discussions/:did
  tags: Events,Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/urlnameboardsbiddiscussionsdid-get-openapi.md
- name: Meetup
  x-api-slug: meetup
  description: Find Meetups so you can do more of what matters to you. Or create your
    own group and meet people near you who share your interests.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com//
  tags: Discussions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/discussions/master/_listings/meetup/openapi.md
x-common:
- type: x-base
  url: http://api.meetup.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/meetup
- type: x-developer
  url: http://www.meetup.com/meetup_api/
- type: x-email
  url: privacy@meetup.com
- type: x-email
  url: abuse@meetup.com
- type: x-email
  url: api_license@meetup.com
- type: x-email
  url: arbitration-opt-out@meetup.com
- type: x-email
  url: legal@meetup.com
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
- type: x-twitter
  url: https://twitter.com/Meetup
- type: x-website
  url: http://meetup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
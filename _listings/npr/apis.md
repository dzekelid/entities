---
name: NPR
x-slug: npr
description: NPR delivers breaking national and world news. Also top stories from
  business, politics, health, science, technology, music, arts and culture. Subscribe
  to podcasts and RSS feeds.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
x-kinRank: "9"
x-alexaRank: "598"
tags: Entities
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/apis.md
specificationVersion: "0.14"
apis:
- name: NPR One API Reference - Update the following status of the logged-in user
    for a particular aggregation
  x-api-slug: identityv2following-post
  description: After a successful call, this returns a User document with an updated
    list of affiliations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2following-post-openapi.md
- name: NPR One API Reference - Update the logged-in user's favorite station(s)
  x-api-slug: identityv2stations-put
  description: Right now, only the primary station can be changed. Previously selected
    stations will not be deleted, but the new station will be moved to first in the
    array.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2stations-put-openapi.md
- name: NPR One API Reference - Get the latest state information about the logged-in
    user
  x-api-slug: identityv2user-get
  description: After a successful login, the client should send a `GET` call approximately
    once an hour to refresh the user data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2user-get-openapi.md
- name: NPR One API Reference - Copy listening data from a temporary user account
    to the logged-in user's account
  x-api-slug: identityv2userinherit-post
  description: |-
    This can and should only be used by clients who have access to the `temporary_user` grant type.
        Third-party developers do not have access to this grant type by default, and will not need this endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2userinherit-post-openapi.md
- name: NPR One API Reference - Update the following status of the logged-in user
    for a particular aggregation
  x-api-slug: identityv2following-post
  description: After a successful call, this returns a User document with an updated
    list of affiliations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2following-post-openapi.md
- name: NPR One API Reference - Update the logged-in user's favorite station(s)
  x-api-slug: identityv2stations-put
  description: Right now, only the primary station can be changed. Previously selected
    stations will not be deleted, but the new station will be moved to first in the
    array.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2stations-put-openapi.md
- name: NPR One API Reference - Get the latest state information about the logged-in
    user
  x-api-slug: identityv2user-get
  description: After a successful login, the client should send a `GET` call approximately
    once an hour to refresh the user data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2user-get-openapi.md
- name: NPR One API Reference - Copy listening data from a temporary user account
    to the logged-in user's account
  x-api-slug: identityv2userinherit-post
  description: |-
    This can and should only be used by clients who have access to the `temporary_user` grant type.
        Third-party developers do not have access to this grant type by default, and will not need this endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2userinherit-post-openapi.md
- name: NPR One API Reference - Copy listening data from a temporary user account
    to the logged-in user's account
  x-api-slug: identityv2userinherit-post
  description: |-
    This can and should only be used by clients who have access to the `temporary_user` grant type.
        Third-party developers do not have access to this grant type by default, and will not need this endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2userinherit-post-openapi.md
- name: NPR One API Reference - Get the latest state information about the logged-in
    user
  x-api-slug: identityv2user-get
  description: After a successful login, the client should send a `GET` call approximately
    once an hour to refresh the user data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2user-get-openapi.md
- name: NPR One API Reference - Update the logged-in user's favorite station(s)
  x-api-slug: identityv2stations-put
  description: Right now, only the primary station can be changed. Previously selected
    stations will not be deleted, but the new station will be moved to first in the
    array.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2stations-put-openapi.md
- name: NPR One API Reference - Update the following status of the logged-in user
    for a particular aggregation
  x-api-slug: identityv2following-post
  description: After a successful call, this returns a User document with an updated
    list of affiliations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/141-npr.jpg
  humanURL: http://npr.org
  baseURL: https://api.npr.org//
  tags: News, Radio, Getting Started Example, Federal Government, Stack Network, Stack,
    Mobile, Media, API Provider, Broadcasts, Profiles, Publish, General Data, Relative
    Data, Service API, Pedestal, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/entities/master/_listings/npr/identityv2following-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://nfusion.solutions.api.gallery.streamdata.io
- type: x-api-stack
  url: http://npr.stack.network
- type: x-base
  url: http://api.npr.org/
- type: x-codecademy
  url: http://www.codecademy.com/tracks/npr
- type: x-crunchbase
  url: https://crunchbase.com/organization/npr
- type: x-crunchbase
  url: http://www.crunchbase.com/company/npr
- type: x-developer
  url: http://dev.npr.org/
- type: x-documentation
  url: http://dev.npr.org/#accessing-the-api
- type: x-email
  url: permissions@npr.org
- type: x-email
  url: ogcstaff@npr.org
- type: x-email
  url: employment@npr.org
- type: x-email
  url: careers@npr.org
- type: x-email
  url: kroc@npr.org
- type: x-email
  url: mediarelations@npr.org
- type: x-email
  url: sponsorship@npr.org
- type: x-email
  url: ashamblin@npr.org
- type: x-email
  url: giving@npr.org
- type: x-email
  url: giftplanning@npr.org
- type: x-email
  url: NPRDonorCommunications@npr.org
- type: x-getting-started
  url: http://dev.npr.org/#quick-start
- type: x-github
  url: https://github.com/npr
- type: x-selfservice-registration
  url: http://www.npr.org/templates/reg/
- type: x-terms-of-service
  url: http://www.npr.org/about-npr/179876898/terms-of-use
- type: x-twitter
  url: https://twitter.com/NPR
- type: x-twitter
  url: https://twitter.com/NPRTechTeam
- type: x-website
  url: http://npr.org
- type: x-website
  url: http://www.npr.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
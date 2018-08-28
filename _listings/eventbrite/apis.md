---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite brings people together through live experiences. Discover
  events that match your passions, or create your own with online ticketing tools.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
x-kinRank: "9"
x-alexaRank: "643"
tags: Tracking
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite - Post Tracking Beacons
  x-api-slug: tracking-beacons-post
  description: Makes a new tracking beacon. Returns an tracking_beacon as tracking_beacon.
    Either event_id or user_id is required for each tracking beacon. If the event_id
    is provided, the tracking pixel will fire only for that event. If the user_id
    is provided, the tracking pixel will fire for all events organized by that user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beacons-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beacons-post-openapi.md
- name: Eventbrite - Get Tracking Beacons Tracking Beacons
  x-api-slug: tracking-beaconstracking-beacons-id-get
  description: Returns the tracking_beacon with the specified :tracking_beacons_id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-get-openapi.md
- name: Eventbrite - Post Tracking Beacons Tracking Beacons
  x-api-slug: tracking-beaconstracking-beacons-id-post
  description: Updates the tracking_beacons with the specified :tracking_beacons_id.
    Though event_id and user_id are not individually required, it is a requirement
    to have a tracking beacon where either one must exist. Returns an tracking_beacon
    as tracking_beacon.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-post-openapi.md
- name: Eventbrite - Delete Tracking Beacons Tracking Beacons
  x-api-slug: tracking-beaconstracking-beacons-id-delete
  description: Delete the tracking_beacons with the specified :tracking_beacons_id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-delete-openapi.md
- name: Eventbrite - Get Events Event Tracking Beacons
  x-api-slug: eventsevent-idtracking-beacons-get
  description: Returns the list of tracking_beacon for the event :event_id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/eventsevent-idtracking-beacons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/eventsevent-idtracking-beacons-get-openapi.md
- name: Eventbrite - Get Users User Tracking Beacons
  x-api-slug: usersuser-idtracking-beacons-get
  description: Returns the list of tracking_beacon for the user :user_id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Events, Tickets, Events, My API Stack, API LIfeyclessss, Stack Network, Stack,
    Marketplace, Technology, Mobile, internet, API Provider, Tickets, Profiles, Registrations,
    General Data, Relative Data, Pedestal, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/usersuser-idtracking-beacons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/usersuser-idtracking-beacons-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://europeana.api.gallery.streamdata.io
- type: x-api-stack
  url: http://eventbrite.stack.network
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/eventbrite/apidescription?format=internal&ver=1351170233000
- type: x-authentication
  url: https://developer.eventbrite.com/docs/auth/
- type: x-base
  url: https://www.eventbriteapi.com/
- type: x-blog
  url: http://blog.eventbrite.com/
- type: x-blog-rss
  url: http://blog.eventbrite.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/eventbrite
- type: x-crunchbase
  url: https://crunchbase.com/organization/eventbrite
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdks-io
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-twitter
  url: https://twitter.com/eventbrite
- type: x-website
  url: http://eventbriteapi.com
- type: x-website
  url: http://developer.eventbrite.com/
- type: x-website
  url: http://eventbrite.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
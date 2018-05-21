---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite believes that anyone can be an event organizer. That&rsquo;s
  why they offer tools that make it easy to sell tickets to all kinds of events whether
  it&rsquo;s a photography class or a sold-out concert, an inspiring conference or
  an air-guitar competition. With Eventbrite, organizers can create a customizable
  event page; spread the word with social media; collect money; and gain visibility
  into attendees and sales. Eventbrite is for anyone planning or attending an event.
  It empowers event organizers to become more efficient and effective when bringing
  people together. And people everywhere are searching Eventbrite to discover great
  events that matter to them.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
x-kinRank: "9"
x-alexaRank: ""
tags: Tracking
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite Add Tracking Beacons
  x-api-slug: eventbrite
  description: Makes a new tracking beacon. Returns an tracking_beacon as tracking_beacon.
    Either event_id or user_id is required for each tracking beacon. If the event_id
    is provided, the tracking pixel will fire only for that event. If the user_id
    is provided, the tracking pixel will fire for all events organized by that user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/
  tags: Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beacons-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beacons-post-openapi.md
- name: Eventbrite Get Tracking Beacons Tracking Beacons
  x-api-slug: eventbrite
  description: Returns the tracking_beacon with the specified :tracking_beacons_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/:tracking_beacons_id/
  tags: Tracking,Beacons,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-get-openapi.md
- name: Eventbrite Add Tracking Beacons Tracking Beacons
  x-api-slug: eventbrite
  description: Updates the tracking_beacons with the specified :tracking_beacons_id.
    Though event_id and user_id are not individually required, it is a requirement
    to have a tracking beacon where either one must exist. Returns an tracking_beacon
    as tracking_beacon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/:tracking_beacons_id/
  tags: Tracking,Beacons,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-post-openapi.md
- name: Eventbrite Delete Tracking Beacons Tracking Beacons
  x-api-slug: eventbrite
  description: Delete the tracking_beacons with the specified :tracking_beacons_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/:tracking_beacons_id/
  tags: Tracking,Beacons,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-delete-openapi.md
- name: Eventbrite Get Events Event  Tracking Beacons
  x-api-slug: eventbrite
  description: Returns the list of tracking_beacon for the event :event_id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/tracking_beacons/
  tags: Events,Event,,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/eventsevent-idtracking-beacons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/eventsevent-idtracking-beacons-get-openapi.md
- name: Eventbrite Get Users User  Tracking Beacons
  x-api-slug: eventbrite
  description: Returns the list of tracking_beacon for the user :user_id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/:user_id/tracking_beacons/
  tags: Users,User,,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/usersuser-idtracking-beacons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/usersuser-idtracking-beacons-get-openapi.md
- name: Eventbrite
  x-api-slug: eventbrite
  description: Eventbrite believes that anyone can be an event organizer. That&rsquo;s
    why they offer tools that make it easy to sell tickets to all kinds of events
    whether it&rsquo;s a photography class or a sold-out concert, an inspiring conference
    or an air-guitar competition. With Eventbrite, organizers can create a customizable
    event page; spread the word with social media; collect money; and gain visibility
    into attendees and sales. Eventbrite is for anyone planning or attending an event.
    It empowers event organizers to become more efficient and effective when bringing
    people together. And people everywhere are searching Eventbrite to discover great
    events that matter to them.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3
  tags: Tracking
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/eventbrite/openapi.md
x-common:
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
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdksio
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-website
  url: http://developer.eventbrite.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
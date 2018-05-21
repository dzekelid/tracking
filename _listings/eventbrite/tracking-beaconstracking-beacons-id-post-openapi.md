---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Add Tracking Beacons Tracking Beacons
  description: Updates the tracking_beacons with the specified :tracking_beacons_id.
    Though event_id and user_id are not individually required, it is a requirement
    to have a tracking beacon where either one must exist. Returns an tracking_beacon
    as tracking_beacon.
  version: 1.0.0
host: www.eventbriteapi.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracking_beacons/:
    post:
      summary: Add Tracking Beacons
      description: Makes a new tracking beacon. Returns an tracking_beacon as tracking_beacon.
        Either event_id or user_id is required for each tracking beacon. If the event_id
        is provided, the tracking pixel will fire only for that event. If the user_id
        is provided, the tracking pixel will fire for all events organized by that
        user.
      operationId: postTrackingBeacons
      x-api-path-slug: tracking-beacons-post
      parameters:
      - in: query
        name: event_id
        description: The Event ID of the event that this tracking beacon will fire
          in
        type: query
      - in: query
        name: pixel_id
        description: The Pixel ID given by the third party that will fire when a attendee
          lands on the page you are tracking
        type: query
      - in: query
        name: tracking_type
        description: The tracking pixel third party type
        type: query
      - in: query
        name: triggers
        description: The additional pixel data needed to determine which page to fire
          the tracking pixel on
        type: query
      - in: query
        name: user_id
        description: The User ID wherein the tracking beacon will be assigned to all
          of this user&#8217;s events
        type: query
      responses:
        200:
          description: OK
      tags:
      - Tracking
      - Beacons
  /tracking_beacons/:tracking_beacons_id/:
    get:
      summary: Get Tracking Beacons Tracking Beacons
      description: Returns the tracking_beacon with the specified :tracking_beacons_id.
      operationId: getTrackingBeaconsTrackingBeacons
      x-api-path-slug: tracking-beaconstracking-beacons-id-get
      parameters:
      - in: query
        name: return_fmt
        description: returned format
        type: query
      responses:
        200:
          description: OK
      tags:
      - Tracking
      - Beacons
      - Tracking
      - Beacons
    post:
      summary: Add Tracking Beacons Tracking Beacons
      description: Updates the tracking_beacons with the specified :tracking_beacons_id.
        Though event_id and user_id are not individually required, it is a requirement
        to have a tracking beacon where either one must exist. Returns an tracking_beacon
        as tracking_beacon.
      operationId: postTrackingBeaconsTrackingBeacons
      x-api-path-slug: tracking-beaconstracking-beacons-id-post
      parameters:
      - in: query
        name: event_id
        description: The Event ID of the event that this tracking beacon will fire
          in
        type: query
      - in: query
        name: pixel_id
        description: The Pixel ID given by the third party that will fire when a attendee
          lands on the page you are tracking
        type: query
      - in: query
        name: tracking_type
        description: The tracking pixel third party type
        type: query
      - in: query
        name: triggers
        description: The additional pixel data needed to determine which page to fire
          the tracking pixel on
        type: query
      - in: query
        name: user_id
        description: The User ID wherein the tracking beacon will be assigned to all
          of this user&#8217;s events
        type: query
      responses:
        200:
          description: OK
      tags:
      - Tracking
      - Beacons
      - Tracking
      - Beacons
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
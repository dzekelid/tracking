---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Get Tracking Settings Click
  description: |-
    **This endpoint allows you to retrieve your current click tracking setting.**

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracking_settings:
    get:
      summary: Get Tracking Settings
      description: |-
        **This endpoint allows you to retrieve a list of all tracking settings that you can enable on your account.**

        You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

        For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
      operationId: GET_tracking_settings
      x-api-path-slug: tracking-settings-get
      parameters:
      - in: query
        name: limit
        description: The number of settings to return
      - in: query
        name: No Name
      - in: query
        name: offset
        description: Where in the list of results you want to begin retrieving settings
      responses:
        200:
          description: OK
      tags:
      - Email
      - Tracking
      - Settings
  /tracking_settings/click:
    get:
      summary: Get Tracking Settings Click
      description: |-
        **This endpoint allows you to retrieve your current click tracking setting.**

        You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

        For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
      operationId: tracking_settings.click.get
      x-api-path-slug: tracking-settingsclick-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Tracking
      - Settings
      - Click
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
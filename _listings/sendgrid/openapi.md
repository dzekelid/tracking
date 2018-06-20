---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  description: the-sendgrid-web-api-v3-documentation--this-is-the-entirety-of-the-documented-v3-endpoints--we-have-updated-all-the-descriptions-parameters-requests-and-responses--authentication-every-endpoint-requires-authentication-in-the-form-of-an-authorization-header-authorization-bearer-api-key
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
    patch:
      summary: Patch Tracking Settings Click
      description: |-
        **This endpoint allows you to change your current click tracking setting. You can enable, or disable, click tracking using this endpoint.**

        You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

        For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
      operationId: tracking_settings.click.patch
      x-api-path-slug: tracking-settingsclick-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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
  /tracking_settings/google_analytics:
    get:
      summary: Get Tracking Settings Google Analytics
      description: "**This endpoint allows you to retrieve your current setting for
        Google Analytics.**\n\nFor more information about using Google Analytics,
        please refer to [Google\u2019s URL Builder](https://support.google.com/analytics/answer/1033867?hl=en)
        and their article on [\"Best Practices for Campaign Building\"](https://support.google.com/analytics/answer/1037445).\n\nWe
        default the settings to Google\u2019s recommendations. For more information,
        see [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).\n\nYou
        can track a variety of the actions your recipients may take when interacting
        with your emails including opening your emails, clicking on links in your
        emails, and subscribing to (or unsubscribing from) your emails.\n\nFor more
        information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
      operationId: tracking_settings.google_analytics.get
      x-api-path-slug: tracking-settingsgoogle-analytics-get
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
      - Google
      - Analytics
    patch:
      summary: Patch Tracking Settings Google Analytics
      description: "**This endpoint allows you to update your current setting for
        Google Analytics.**\n\nFor more information about using Google Analytics,
        please refer to [Google\u2019s URL Builder](https://support.google.com/analytics/answer/1033867?hl=en)
        and their article on [\"Best Practices for Campaign Building\"](https://support.google.com/analytics/answer/1037445).\n\nWe
        default the settings to Google\u2019s recommendations. For more information,
        see [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).\n\nYou
        can track a variety of the actions your recipients may take when interacting
        with your emails including opening your emails, clicking on links in your
        emails, and subscribing to (or unsubscribing from) your emails.\n\nFor more
        information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
      operationId: tracking_settings.google_analytics.patch
      x-api-path-slug: tracking-settingsgoogle-analytics-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Tracking
      - Settings
      - Google
      - Analytics
  /tracking_settings/open:
    get:
      summary: Get Tracking Settings Open
      description: "**This endpoint allows you to retrieve your current settings for
        open tracking.**\n\nOpen Tracking adds an invisible image at the end of the
        email which can track email opens. If the email recipient has images enabled
        on their email client, a request to SendGrid\u2019s server for the invisible
        image is executed and an open event is logged. These events are logged in
        the Statistics portal, Email Activity interface, and are reported by the Event
        Webhook.\n\nYou can track a variety of the actions your recipients may take
        when interacting with your emails including opening your emails, clicking
        on links in your emails, and subscribing to (or unsubscribing from) your emails.\n\nFor
        more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
      operationId: tracking_settings.open.get
      x-api-path-slug: tracking-settingsopen-get
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
      - Open
    patch:
      summary: Patch Tracking Settings Open
      description: "**This endpoint allows you to update your current settings for
        open tracking.**\n\nOpen Tracking adds an invisible image at the end of the
        email which can track email opens. If the email recipient has images enabled
        on their email client, a request to SendGrid\u2019s server for the invisible
        image is executed and an open event is logged. These events are logged in
        the Statistics portal, Email Activity interface, and are reported by the Event
        Webhook.\n\nYou can track a variety of the actions your recipients may take
        when interacting with your emails including opening your emails, clicking
        on links in your emails, and subscribing to (or unsubscribing from) your emails.\n\nFor
        more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
      operationId: tracking_settings.open.patch
      x-api-path-slug: tracking-settingsopen-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Tracking
      - Settings
      - Open
  /tracking_settings/subscription:
    get:
      summary: Get Tracking Settings Subscription
      description: |-
        **This endpoint allows you to retrieve your current settings for subscription tracking.**

        Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.

        You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

        For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
      operationId: tracking_settings.subscription.get
      x-api-path-slug: tracking-settingssubscription-get
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
      - Subscription
    patch:
      summary: Patch Tracking Settings Subscription
      description: |-
        **This endpoint allows you to update your current settings for subscription tracking.**

        Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.

        You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

        For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
      operationId: tracking_settings.subscription.patch
      x-api-path-slug: tracking-settingssubscription-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Tracking
      - Settings
      - Subscription
---
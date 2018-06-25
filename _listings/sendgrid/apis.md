---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "10000"
tags: Tracking
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid Get Tracking Settings
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a list of all tracking settings that you can enable on your account.**

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings
  tags: Email,Tracking, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settings-get-openapi.md
- name: SendGrid Get Tracking Settings Click
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve your current click tracking setting.**

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/click
  tags: Email,Tracking, Settings, Click
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsclick-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsclick-get-openapi.md
- name: SendGrid Patch Tracking Settings Click
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to change your current click tracking setting. You can enable, or disable, click tracking using this endpoint.**

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/click
  tags: Email,Tracking, Settings, Click
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsclick-patch-openapi.md
- name: SendGrid Get Tracking Settings Google Analytics
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current setting for Google
    Analytics.**\n\nFor more information about using Google Analytics, please refer
    to [Google\u2019s URL Builder](https://support.google.com/analytics/answer/1033867?hl=en)
    and their article on [\"Best Practices for Campaign Building\"](https://support.google.com/analytics/answer/1037445).\n\nWe
    default the settings to Google\u2019s recommendations. For more information, see
    [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).\n\nYou
    can track a variety of the actions your recipients may take when interacting with
    your emails including opening your emails, clicking on links in your emails, and
    subscribing to (or unsubscribing from) your emails.\n\nFor more information about
    tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/google_analytics
  tags: Email,Tracking, Settings, Google, Analytics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsgoogle-analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsgoogle-analytics-get-openapi.md
- name: SendGrid Patch Tracking Settings Google Analytics
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current setting for Google
    Analytics.**\n\nFor more information about using Google Analytics, please refer
    to [Google\u2019s URL Builder](https://support.google.com/analytics/answer/1033867?hl=en)
    and their article on [\"Best Practices for Campaign Building\"](https://support.google.com/analytics/answer/1037445).\n\nWe
    default the settings to Google\u2019s recommendations. For more information, see
    [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).\n\nYou
    can track a variety of the actions your recipients may take when interacting with
    your emails including opening your emails, clicking on links in your emails, and
    subscribing to (or unsubscribing from) your emails.\n\nFor more information about
    tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/google_analytics
  tags: Email,Tracking, Settings, Google, Analytics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsgoogle-analytics-patch-openapi.md
- name: SendGrid Get Tracking Settings Open
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current settings for open
    tracking.**\n\nOpen Tracking adds an invisible image at the end of the email which
    can track email opens. If the email recipient has images enabled on their email
    client, a request to SendGrid\u2019s server for the invisible image is executed
    and an open event is logged. These events are logged in the Statistics portal,
    Email Activity interface, and are reported by the Event Webhook.\n\nYou can track
    a variety of the actions your recipients may take when interacting with your emails
    including opening your emails, clicking on links in your emails, and subscribing
    to (or unsubscribing from) your emails.\n\nFor more information about tracking,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/open
  tags: Email,Tracking, Settings, Open
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsopen-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsopen-get-openapi.md
- name: SendGrid Patch Tracking Settings Open
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current settings for open
    tracking.**\n\nOpen Tracking adds an invisible image at the end of the email which
    can track email opens. If the email recipient has images enabled on their email
    client, a request to SendGrid\u2019s server for the invisible image is executed
    and an open event is logged. These events are logged in the Statistics portal,
    Email Activity interface, and are reported by the Event Webhook.\n\nYou can track
    a variety of the actions your recipients may take when interacting with your emails
    including opening your emails, clicking on links in your emails, and subscribing
    to (or unsubscribing from) your emails.\n\nFor more information about tracking,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/open
  tags: Email,Tracking, Settings, Open
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingsopen-patch-openapi.md
- name: SendGrid Get Tracking Settings Subscription
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve your current settings for subscription tracking.**

    Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/subscription
  tags: Email,Tracking, Settings, Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingssubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingssubscription-get-openapi.md
- name: SendGrid Patch Tracking Settings Subscription
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to update your current settings for subscription tracking.**

    Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/subscription
  tags: Email,Tracking, Settings, Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/tracking-settingssubscription-patch-openapi.md
- name: SendGrid
  x-api-slug: sendgrid
  description: SendGrids cloud-based email infrastructure relieves businesses of the
    cost and complexity of maintaining custom email systems. SendGrid provides reliable
    delivery, scalability and real-time analytics along with flexible APIs that make
    custom integration a breeze.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: Tracking
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/tracking/master/_listings/sendgrid/openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-crunchbase
  url: https://crunchbase.com/organization/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-email
  url: privacy@sendgrid.com
- type: x-email
  url: legal@sendgrid.com
- type: x-email
  url: dpo@sendgrid.com
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-linkedin
  url: https://www.linkedin.com/company/sendgrid
- type: x-node-js-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: http://sendgrid.com
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
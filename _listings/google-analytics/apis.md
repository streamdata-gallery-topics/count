---
name: Google Analytics
x-slug: google-analytics
description: Google Analytics gives you the digital analytics tools you need to analyze
  data from all touchpoints in one place, for a deeper understanding of the customer
  experience. You can then share the insights that matter with your whole organization.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-analytics/apis.md
specificationVersion: "0.14"
apis:
- name: Google Analytics Get Account Summary
  x-api-slug: google-analytics
  description: Lists account summaries (lightweight tree comprised of accounts/properties/profiles)
    to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accountSummaries
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-analytics/managementaccountsummaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-analytics/managementaccountsummaries-get-openapi.md
- name: Google Analytics Get Accounts
  x-api-slug: google-analytics
  description: Lists all accounts to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-analytics/managementaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-analytics/managementaccounts-get-openapi.md
- name: Google Analytics
  x-api-slug: google-analytics
  description: Google Analytics gives you the digital analytics tools you need to
    analyze data from all touchpoints in one place, for a deeper understanding of
    the customer experience. You can then share the insights that matter with your
    whole organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-analytics/openapi.md
x-common:
- type: x-blog
  url: https://analytics.googleblog.com/
- type: x-blog-rss
  url: https://analytics.googleblog.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/analytics/
- type: x-github
  url: https://github.com/googleanalytics/
- type: x-google-plus
  url: https://plus.google.com/+GoogleAnalytics
- type: x-partners
  url: https://developers.google.com/analytics/program/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/google-analytics
- type: x-support
  url: https://developers.google.com/analytics/help/
- type: x-twitter
  url: https://twitter.com/googleanalytics
- type: x-videos
  url: https://www.youtube.com/user/googleanalytics
- type: x-website
  url: https://www.google.com/analytics/#?modal_active=none
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
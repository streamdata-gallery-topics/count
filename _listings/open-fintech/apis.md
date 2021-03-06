---
name: Open FinTech
x-slug: open-fintech
description: International standards yield technological, economic and social advantages.
  Standards speed up the development of new applications and simplify the process
  of communication between the services. Data and service is available under the Open
  Database License (ODbL). It is an open standard and open data, every player of FinTech
  market can contribute to development and enhancement. All data is available through
  Rest API based on JSON API standard.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/open-fintech/apis.md
specificationVersion: "0.14"
apis:
- name: Open FinTech List of countries
  x-api-slug: open-fintech
  description: Returns all available countries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///countries
  tags: Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/open-fintech/countries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/open-fintech/countries-get-openapi.md
- name: Open FinTech Country by ID
  x-api-slug: open-fintech
  description: Returns country with specific ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1///countries/{id}
  tags: Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/open-fintech/countriesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/open-fintech/countriesid-get-openapi.md
- name: Open FinTech
  x-api-slug: open-fintech
  description: International standards yield technological, economic and social advantages.
    Standards speed up the development of new applications and simplify the process
    of communication between the services. Data and service is available under the
    Open Database License (ODbL). It is an open standard and open data, every player
    of FinTech market can contribute to development and enhancement. All data is available
    through Rest API based on JSON API standard.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/open-fintech-io.png
  humanURL: http://openfintech.io
  baseURL: https://api.openfintech.io//v1/
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/open-fintech/openapi.md
x-common:
- type: x-developer
  url: https://docs.openfintech.io/
- type: x-getting-started
  url: https://docs.openfintech.io/#section/Get-Started
- type: x-github
  url: https://github.com/openfintechio
- type: x-website
  url: http://openfintech.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
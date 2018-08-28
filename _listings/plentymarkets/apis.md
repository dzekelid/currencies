---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Currencies
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - List activated currencies
  x-api-slug: restitemssales-pricesidcurrencies-get
  description: List all currencies activated for a sales price. The ID of the sales
    price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-get-openapi.md
- name: plentymarkets REST-API - List currencies
  x-api-slug: restorderscurrencies-get
  description: List currencies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrencies-get-openapi.md
- name: plentymarkets REST-API - Activate a currency
  x-api-slug: restitemssales-pricesidcurrencies-post
  description: Activates a currency for a sales price. The ID of the sales price must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-post-openapi.md
- name: plentymarkets REST-API - Deactivate a currency
  x-api-slug: restitemssales-pricesidcurrenciescurrency-delete
  description: Deactivate a currency for a sales price. The ID of the sales price
    and the ISO code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrenciescurrency-delete-openapi.md
- name: plentymarkets REST-API - Get a currency
  x-api-slug: restorderscurrenciescurrencyiso-get
  description: Get a currency. The ISO 4217 code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescurrencyiso-get-openapi.md
- name: plentymarkets REST-API - List countries for a currency
  x-api-slug: restorderscurrenciescurrencyisocountries-get
  description: List countries for a currency. The ISO 4271 code of the currency must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescurrencyisocountries-get-openapi.md
- name: plentymarkets REST-API - Get a currency for a country
  x-api-slug: restorderscurrenciescountriescountryid-get
  description: Get a currency for a country. The ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Activate a currency
  x-api-slug: restitemssales-pricesidcurrencies-post
  description: Activates a currency for a sales price. The ID of the sales price must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-post-openapi.md
- name: plentymarkets REST-API - Deactivate a currency
  x-api-slug: restitemssales-pricesidcurrenciescurrency-delete
  description: Deactivate a currency for a sales price. The ID of the sales price
    and the ISO code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrenciescurrency-delete-openapi.md
- name: plentymarkets REST-API - Get a currency
  x-api-slug: restorderscurrenciescurrencyiso-get
  description: Get a currency. The ISO 4217 code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescurrencyiso-get-openapi.md
- name: plentymarkets REST-API - List countries for a currency
  x-api-slug: restorderscurrenciescurrencyisocountries-get
  description: List countries for a currency. The ISO 4271 code of the currency must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescurrencyisocountries-get-openapi.md
- name: plentymarkets REST-API - Get a currency for a country
  x-api-slug: restorderscurrenciescountriescountryid-get
  description: Get a currency for a country. The ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescountriescountryid-get-openapi.md
- name: plentymarkets REST-API - List countries for a currency
  x-api-slug: restorderscurrenciescurrencyisocountries-get
  description: List countries for a currency. The ISO 4271 code of the currency must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescurrencyisocountries-get-openapi.md
- name: plentymarkets REST-API - Get a currency
  x-api-slug: restorderscurrenciescurrencyiso-get
  description: Get a currency. The ISO 4217 code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescurrencyiso-get-openapi.md
- name: plentymarkets REST-API - Deactivate a currency
  x-api-slug: restitemssales-pricesidcurrenciescurrency-delete
  description: Deactivate a currency for a sales price. The ID of the sales price
    and the ISO code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrenciescurrency-delete-openapi.md
- name: plentymarkets REST-API - Activate a currency
  x-api-slug: restitemssales-pricesidcurrencies-post
  description: Activates a currency for a sales price. The ID of the sales price must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-post-openapi.md
- name: plentymarkets REST-API - Get a currency for a country
  x-api-slug: restorderscurrenciescountriescountryid-get
  description: Get a currency for a country. The ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/currencies/master/_listings/plentymarkets/restorderscurrenciescountriescountryid-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
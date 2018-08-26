---
swagger: "2.0"
x-collection-name: HitBTC
x-complete: 0
info:
  title: HitBTC Available Currency Symbols
  description: Available currency symbols.
  version: 1.0.0
basePath: /api/2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /public/currency:
    get:
      summary: Available Currencies
      description: Available currencies.
      operationId: getPublicCurrency
      x-api-path-slug: publiccurrency-get
      responses:
        200:
          description: OK
      tags:
      - Available
      - Currencies
  /public/symbol:
    get:
      summary: Available Currency Symbols
      description: Available currency symbols.
      operationId: getPublicSymbol
      x-api-path-slug: publicsymbol-get
      responses:
        200:
          description: OK
      tags:
      - Available
      - Currency
      - Symbols
  /public/currency/{currency}:
    get:
      summary: Get Currency Info
      description: Get currency info.
      operationId: getPublicCurrencyCurrency
      x-api-path-slug: publiccurrencycurrency-get
      parameters:
      - in: path
        name: currency
      responses:
        200:
          description: OK
      tags:
      - Currency
      - Info
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
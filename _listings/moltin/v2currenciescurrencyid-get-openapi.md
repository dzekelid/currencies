---
swagger: "2.0"
x-collection-name: moltin
x-complete: 0
info:
  title: Moltin API Get a Currency
  description: Get a currency.
  version: 1.0.0
host: api.moltin.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/currencies:
    get:
      summary: Get Currencies List
      description: Get currencies list.
      operationId: V2CurrenciesGet
      x-api-path-slug: v2currencies-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Currencies
      - List
    post:
      summary: Create a Currency
      description: Create a currency.
      operationId: V2CurrenciesPost
      x-api-path-slug: v2currencies-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Currency
  /v2/currencies/{currencyID}:
    get:
      summary: Get a Currency
      description: Get a currency.
      operationId: V2CurrenciesByCurrencyIDGet
      x-api-path-slug: v2currenciescurrencyid-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: currencyID
      responses:
        200:
          description: Successful response
      tags:
      - Currency
    put:
      summary: Update a Currency
      description: Update a currency.
      operationId: V2CurrenciesByCurrencyIDPut
      x-api-path-slug: v2currenciescurrencyid-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: currencyID
      responses:
        200:
          description: Successful response
      tags:
      - Currency
    delete:
      summary: Delete a Currency
      description: Delete a currency.
      operationId: V2CurrenciesByCurrencyIDDelete
      x-api-path-slug: v2currenciescurrencyid-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: currencyID
      responses:
        200:
          description: Successful response
      tags:
      - Currency
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
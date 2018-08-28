swagger: "2.0"
x-collection-name: moltin
x-complete: 1
info:
  title: Moltin
  description: -welcomethis-is-a-place-to-put-general-notes-and-extra-information-for-internal-use-to-get-started-designingdocumenting-this-api-select-a-version-on-the-left-
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
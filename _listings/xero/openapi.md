---
swagger: "2.0"
x-collection-name: Xero
x-complete: 1
info:
  title: Accounting
  description: -introductionthe-xero-accounting-api-is-a-restful-web-service-and-uses-the-oauth-v1-0a-protocol-to-authenticate-3rd-party-applications--the-accounting-api-exposes-accounting-and-related-functions-of-the-main-xero-application-and-can-be-used-for-a-variety-of-purposes-such-as-creating-transactions-like-invoices-and-credit-notes-right-through-to-extracting-accounting-data-via-our-reports-endpoint-
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Currencies:
    get:
      summary: Get Currencies
      description: Get currencies.
      operationId: getCurrencies
      x-api-path-slug: currencies-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Currencies
    put:
      summary: Put Currencies
      description: Put currencies.
      operationId: putCurrencies
      x-api-path-slug: currencies-put
      parameters:
      - in: body
        name: Currencies
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Currencies
    x-related-model:
      summary: X-related-model Currencies
      description: X-related-model currencies.
      operationId: x-related-modelCurrencies
      x-api-path-slug: currencies-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Currencies
---
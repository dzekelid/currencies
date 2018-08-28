swagger: "2.0"
x-collection-name: Akeneo
x-complete: 1
info:
  title: Official Akeneo PIM API
  description: the-akeneo-api-brought-to-youfind-out-how-this-postman-collection-works-by-visiting-httpapi-akeneo-com
  version: 1.0.0
host: example.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/v1/currencies:
    get:
      summary: currencies (2.x only)
      description: Currencies (2.x only).
      operationId: RestV1CurrenciesGet
      x-api-path-slug: restv1currencies-get
      responses:
        200:
          description: OK
      tags:
      - Currencies
      - (2
      - X
      - Only)
  /rest/v1/currencies/USD:
    get:
      summary: currency (2.x only)
      description: Assuming that the given code is the code of an existing currency
      operationId: RestV1CurrenciesUSDGet
      x-api-path-slug: restv1currenciesusd-get
      responses:
        200:
          description: OK
      tags:
      - Currency
      - (2
      - X
      - Only)
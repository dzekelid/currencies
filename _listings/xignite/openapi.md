---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Global Holidays
  description: this-web-service-provides-tradingholiday-information-for-all-exchangescurrenciesfinancial-centers-
  version: 1.0.0
host: globalholidays.xignite.com
basePath: xGlobalHolidays.json/XigniteGlobalHolidays
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListCurrencies:
    get:
      summary: List Currencies
      description: List currencies.
      operationId: ListCurrencies
      x-api-path-slug: listcurrencies-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Currencies
---
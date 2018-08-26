---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List currencies
  description: List currencies.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/items/sales_prices/{id}/currencies:
    get:
      summary: List activated currencies
      description: List all currencies activated for a sales price. The ID of the
        sales price must be specified.
      operationId: getRestItemsSalesPricesCurrencies
      x-api-path-slug: restitemssales-pricesidcurrencies-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Currencies
  /rest/orders/currencies:
    get:
      summary: List currencies
      description: List currencies.
      operationId: getRestOrdersCurrencies
      x-api-path-slug: restorderscurrencies-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - List
      - Currencies
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
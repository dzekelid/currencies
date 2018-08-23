---
swagger: "2.0"
x-collection-name: Open FinTech
x-complete: 0
info:
  title: Open FinTech List of currencies
  description: Returns all available currencies.
  version: "2017-08-24"
host: api.openfintech.io
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /currencies:
    get:
      summary: List of currencies
      description: Returns all available currencies.
      operationId: currencies.get
      x-api-path-slug: currencies-get
      parameters:
      - in: query
        name: filter[category]
        description: Filtration by category
      - in: query
        name: filter[code_estandards_alpha]
        description: Filtering by estandards code
      - in: query
        name: filter[code_iso_alpha3]
        description: Filtering by ISO code
      - in: query
        name: filter[code_iso_numeric3]
        description: Filtering by ISO number
      - in: query
        name: filter[currency_type]
        description: Filtration by currency type
      - in: query
        name: filter[search]
        description: Full text search with name, code, type, code_iso_alpha3, code_jsons_alpha,
          code_estandards_alpha, category
      - in: query
        name: No Name
      - in: query
        name: sort
        description: Sort params:| ASC | DESC ||-----|------|| name | -name || type
          | -type || category | -category || code | -code || code_iso_alpha3 | -code_iso_alpha3
          || code_iso_numeric3 | -code_iso_numeric3 || code_estandards_alpha | -code_estandards_alpha
          |
      responses:
        200:
          description: OK
      tags:
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
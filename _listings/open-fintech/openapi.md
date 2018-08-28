swagger: "2.0"
x-collection-name: Open FinTech
x-complete: 1
info:
  title: Open FinTech
  description: openfintech-io-is-an-open-database-that-comprises-of-standardized-primary-data-for-fintech-industry--it-contains-such-information-as-geolocation-data-countries-cities-regions-organizations-currencies-national-digital-virtual-crypto-banks-digital-exchangers-payment-providers-psp-payment-methods-etc-it-is-created-for-communication-of-crossintegrated-microservices-on-one-language--this-is-achieved-through-standardization-of-entity-identifiers-that-are-used-to-exchange-information-among-different-services-
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
  /currencies/{id}:
    get:
      summary: Currency by ID
      description: Returns currency with specific ID.
      operationId: currencies.id.get
      x-api-path-slug: currenciesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Currencies
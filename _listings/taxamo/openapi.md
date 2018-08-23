---
swagger: "2.0"
x-collection-name: Taxamo
x-complete: 1
info:
  title: Taxamo
  description: taxamos-elegant-suite-of-apis-and-comprehensive-reporting-dashboard-enables-digital-merchants-to-easily-comply-with-eu-regulatory-requirements-on-tax-calculation-evidence-collection-tax-return-creation-and-data-storage-
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/dictionaries/currencies:
    get:
      summary: Currencies
      description: Currencies.
      operationId: getCurrenciesDict
      x-api-path-slug: apiv1dictionariescurrencies-get
      responses:
        200:
          description: OK
      tags:
      - Currencies
---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /currencies/display:
    get:
      summary: Get Currencies Display
      description: List of supported display currencies for browsing listings
      operationId: getCurrenciesDisplay
      x-api-path-slug: currenciesdisplay-get
      responses:
        200:
          description: OK
      tags:
      - Currencies
      - Display
  /currencies/listing:
    get:
      summary: Get Currencies Listing
      description: List of supported listing currencies for shops
      operationId: getCurrenciesListing
      x-api-path-slug: currencieslisting-get
      responses:
        200:
          description: OK
      tags:
      - Currencies
      - Listing
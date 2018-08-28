swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
    post:
      summary: Activate a currency
      description: Activates a currency for a sales price. The ID of the sales price
        must be specified.
      operationId: postRestItemsSalesPricesCurrencies
      x-api-path-slug: restitemssales-pricesidcurrencies-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/currencies
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Currency
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
  /rest/items/sales_prices/{id}/currencies/{currency}:
    delete:
      summary: Deactivate a currency
      description: Deactivate a currency for a sales price. The ID of the sales price
        and the ISO code of the currency must be specified.
      operationId: deleteRestItemsSalesPricesCurrenciesCurrency
      x-api-path-slug: restitemssales-pricesidcurrenciescurrency-delete
      parameters:
      - in: path
        name: currency
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Currency
  /rest/orders/currencies/{currencyIso}:
    get:
      summary: Get a currency
      description: Get a currency. The ISO 4217 code of the currency must be specified.
      operationId: getRestOrdersCurrenciesCurrencyiso
      x-api-path-slug: restorderscurrenciescurrencyiso-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: currencyIso
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - Currency
  /rest/orders/currencies/{currencyIso}/countries:
    get:
      summary: List countries for a currency
      description: List countries for a currency. The ISO 4271 code of the currency
        must be specified.
      operationId: getRestOrdersCurrenciesCurrencyisoCountries
      x-api-path-slug: restorderscurrenciescurrencyisocountries-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: currencyIso
      responses:
        200:
          description: OK
      tags:
      - List
      - Countriesa
      - Currency
  /rest/orders/currencies/countries/{countryId}:
    get:
      summary: Get a currency for a country
      description: Get a currency for a country. The ID of the country must be specified.
      operationId: getRestOrdersCurrenciesCountriesCountry
      x-api-path-slug: restorderscurrenciescountriescountryid-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: countryId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - Currencya
      - Country
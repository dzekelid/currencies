swagger: "2.0"
x-collection-name: Standard Chartered
x-complete: 1
info:
  title: Standard Chartered
  description: standard-chartered-plc-is-a-british-multinational-banking-and-financial-services-company-headquartered-in-london-england--it-operates-a-network-of-more-than-1200-branches-and-outlets-including-subsidiaries-associates-and-joint-ventures-across-more-than-70-countries-and-employs-around-87000-people--it-is-a-universal-bank-with-operations-in-consumer-corporate-and-institutional-banking-and-treasury-services--despite-its-uk-base-it-does-not-conduct-retail-banking-in-the-uk-and-around-90-of-its-profits-come-from-asia-africa-and-the-middle-east-
  termsOfService: https://www.sc.com/terms-and-conditions
  contact:
    name: Steve Spicer
    url: https://www.sc.com
    email: steven.spicer@sc.com
  version: 1.0.0
host: developer.sc.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cib/service/s2b/api/v1/banks/scb/reference/default/holiday-calendar/currency/{currency}:
    get:
      summary: Holiday Calendar Inquiry (Currency)
      description: |-
        The ???GetHolidayCalendar??? API returns list of holidays applicable for the specified combination of:
        <ul><li>Currency</li><li>Date Range</li></lu>
      operationId: getCibServiceS2bApiV1BanksScbReferenceDefaultHolayCalendarCurrencyCurrency
      x-api-path-slug: cibservices2bapiv1banksscbreferencedefaultholidaycalendarcurrencycurrency-get
      parameters:
      - in: path
        name: currency
      - in: query
        name: endDate
      - in: query
        name: startDate
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Banking
      - Cib
      - Service
      - S2b
      - Api
      - V1
      - Banks
      - Scb
      - Reference
      - Default
      - Holay
      - Calendar
      - Currency
      - Currency
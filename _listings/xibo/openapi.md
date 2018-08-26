---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /playlist/widget/currencies/{playlistId}:
    post:
      summary: Add a Currencies Widget
      description: Add a new Currencies Widget to the specified playlist
      operationId: WidgetCurrenciesAdd
      x-api-path-slug: playlistwidgetcurrenciesplaylistid-post
      parameters:
      - in: formData
        name: backgroundColor
        description: A HEX color to use as the background color of this widget
      - in: formData
        name: base
        description: The base currency
      - in: formData
        name: dateFormat
        description: The format to apply to all dates returned by he widget
      - in: formData
        name: duration
        description: Widget Duration
      - in: formData
        name: durationIsPerPage
        description: A flag (0, 1), The duration specified is per page/item, otherwise
          the widget duration is divided between the number of pages/items
      - in: formData
        name: effect
        description: 'Effect that will be used to transitions between items, available
          options: fade, fadeout, scrollVert, scollHorz, flipVert, flipHorz, shuffle,
          tileSlide, tileBlind'
      - in: formData
        name: items
        description: Items wanted
      - in: formData
        name: itemtemplate
        description: Template for each item, replaces [itemsTemplate] in main template,
          Pass only with overrideTemplate set to 1
      - in: formData
        name: javaScript
        description: Optional JavaScript, Pass only with overrideTemplate set to 1
      - in: formData
        name: mainTemplate
        description: Main template, Pass only with overrideTemplate set to 1
      - in: formData
        name: maxItemsPerPage
        description: This is the intended number of items on each page
      - in: formData
        name: name
        description: Optional Widget Name
      - in: formData
        name: noRecordsMessage
        description: A message to display when there are no records returned by the
          search query
      - in: formData
        name: overrideTemplate
        description: flag (0, 1) set to 0 and use templateId or set to 1 and provide
          whole template in the next parameters
      - in: path
        name: playlistId
        description: The playlist ID to add a Currencies widget
      - in: formData
        name: reverseConversion
        description: (0, 1) Select 1 if youd like your base currency to be used as
          the comparison currency youve entered
      - in: formData
        name: speed
        description: The transition speed of the selected effect in milliseconds (1000
          = normal)
      - in: formData
        name: styleSheet
        description: Optional StyleSheet Pass only with overrideTemplate set to 1
      - in: formData
        name: templateId
        description: 'Use pre-configured templates, available options: currencies1,
          currencies2'
      - in: formData
        name: updateInterval
        description: Update interval in minutes, should be kept as high as possible,
          if data change once per hour, this should be set to 60
      - in: formData
        name: useDuration
        description: (0, 1) Select 1 only if you will provide duration parameter as
          well
      - in: formData
        name: widgetOriginalHeight
        description: This is the intended Height of the template and is used to scale
          the Widget within its region when the template is applied, Pass only with
          overrideTemplate set to 1
      - in: formData
        name: widgetOriginalWidth
        description: This is the intended Width of the template and is used to scale
          the Widget within its region when the template is applied, Pass only with
          overrideTemplate set to 1
      responses:
        200:
          description: OK
      tags:
      - Currencies
      - Widget
---
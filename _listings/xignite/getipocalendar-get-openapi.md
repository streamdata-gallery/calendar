---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite IPOs Get IPO Calendar
  description: Post getipocalendar
  version: 1.0.0
host: ipos.xignite.com
basePath: xIPOs.json/XigniteIPOs
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetIPOCalendar:
    get:
      summary: Get IPO Calendar
      description: Post getipocalendar
      operationId: GetIPOCalendar
      x-api-path-slug: getipocalendar-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - IPO
      - Calendar
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
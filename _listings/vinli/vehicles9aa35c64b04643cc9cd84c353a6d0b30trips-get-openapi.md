---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli List All of a Vehicle's Trips
  description: List all of a vehicle's trips.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/trips:
    get:
      summary: List All of a Vehicle's Trips
      description: List all of a vehicle's trips.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30TripsGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30trips-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Of
      - Vehicles
      - Trips
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
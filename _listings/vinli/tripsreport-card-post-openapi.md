---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli Report Card  for a Trip
  description: Report card  for a trip.
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
  /devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/trips:
    get:
      summary: List All of a Device's Trips
      description: List all of a device's trips.
      operationId: DevicesCf217c2dDf3c41f7B6108bc3e11b4b79TripsGet
      x-api-path-slug: devicescf217c2ddf3c41f7b6108bc3e11b4b79trips-get
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
      - Devices
      - Trips
  /trips/report_card:
    post:
      summary: Report Card  for a Trip
      description: Report card  for a trip.
      operationId: TripsReportCardPost
      x-api-path-slug: tripsreport-card-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Report
      - Card
      - Trip
  /trips/89abe0bd-ea2e-44e5-b573-a8a346fdfb54:
    get:
      summary: Get Details of a Trip
      description: Get details of a trip.
      operationId: Trips89abe0bdEa2e44e5B573A8a346fdfb54Get
      x-api-path-slug: trips89abe0bdea2e44e5b573a8a346fdfb54-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Trip
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
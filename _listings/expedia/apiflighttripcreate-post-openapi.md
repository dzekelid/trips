---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 0
info:
  title: Expedia Create A Trip
  description: Mobile API Flights Create Trip Operation
  version: 0.0.1
host: apim.expedia.com
basePath: x/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/flight/trip/create:
    post:
      summary: Create A Trip
      description: Mobile API Flights Create Trip Operation
      operationId: flights-create-trip
      x-api-path-slug: apiflighttripcreate-post
      parameters:
      - in: formData
        name: fareFamilyCode
      - in: formData
        name: fareFamilyTotalPrice
      - in: formData
        name: mobileShoppingKey
        description: The mobile shopping key we are going to create a trip for
      - in: formData
        name: productKey
        description: The product key, obtained from /api/flight/search, we are going
          to create a trip for
      - in: formData
        name: qualifyAirAttach
        description: Whether to return a qualified air attach product for this trip
      - in: formData
        name: tripTitle
        description: The name of this itinerary as it will appear to customer service
          and in the itinerary list
      - in: formData
        name: withInsurance
        description: Whether to return the available insurance options for this trip
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Trips
      - Airlines
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
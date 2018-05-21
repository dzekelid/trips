---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 0
info:
  title: Expedia Trips by tripId
  description: Mobile API Trips
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
  /m/api/trip/calculatePoints:
    post:
      summary: Points Conversion
      description: |-
        Converts from a given currency amount to the equivalent in rewards points.
        [Note: Works only if the User is signed-in and is the owner of the trip.]
      operationId: hotels-trip-calculate
      x-api-path-slug: mapitripcalculatepoints-post
      parameters:
      - in: formData
        name: amount
        description: The amount the user would want to convert to points
      - in: formData
        name: programName
        description: The Rewards program name
      - in: formData
        name: rateId
        description: The rate id to use for this conversion
      - in: formData
        name: tripId
        description: The trip ID of an existing trip, from /api/packages/createTrip
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Trips
  /api/trips/{tripId}:
    get:
      summary: Trips by tripId
      description: Mobile API Trips
      operationId: trips-search-id
      x-api-path-slug: apitripstripid-get
      parameters:
      - in: query
        name: currencyCode
        description: Currency parameter
      - in: query
        name: decimalPlaceCount
        description: Decimal place count for the expected amount
      - in: query
        name: decorator
        description: Nullifies complex elements of a Trip with exception of Price
          related elements and their parents
      - in: query
        name: email
        description: To pull a guest itinerary specify the email address associated
          with the trip
      - in: query
        name: expectedAmount
        description: Expected Amount during car cancellation
      - in: path
        name: tripId
        description: The trip ID
      - in: query
        name: useCache
        description: An optional flag to make a cached read trip call
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Search
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
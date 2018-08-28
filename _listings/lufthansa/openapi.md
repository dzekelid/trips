swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /baggage/baggagetripandcontact/{searchID}:
    get:
      summary: Baggage Trip and Contact
      description: Retrieve passenger trip, contact and baggage details. This service
        is only accessible for LH privileged partners
      operationId: baggage.baggagetripandcontact.searchID.get
      x-api-path-slug: baggagebaggagetripandcontactsearchid-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: searchID
        description: Bag tag number, PNR, boarding card or FQTV ID
      responses:
        200:
          description: OK
      tags:
      - Baggage
      - Trip
      - Contact
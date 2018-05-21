---
name: Expedia
x-slug: expedia
description: Expedia.com is an Internet-based travel agency and a part of Expedia,
  Inc.. It books airline tickets, hotel reservations, car rentals, cruises, vacation
  packages, and various attractions and services via the World Wide Web and telephone
  travel agents. The site uses the Sabre reservation system as their main Global reservations
  system.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
x-kinRank: "9"
x-alexaRank: ""
tags: Trips
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apis.md
specificationVersion: "0.14"
apis:
- name: Expedia Create A Trip
  x-api-slug: expedia
  description: Mobile API Flights Create Trip Operation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/flight/trip/create
  tags: Travel,Airports,Airplanes,Trips,Airlines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apiflighttripcreate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apiflighttripcreate-post-openapi.md
- name: Expedia Points Conversion
  x-api-slug: expedia
  description: |-
    Converts from a given currency amount to the equivalent in rewards points.
    [Note: Works only if the User is signed-in and is the owner of the trip.]
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/trip/calculatePoints
  tags: Travel,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/mapitripcalculatepoints-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/mapitripcalculatepoints-post-openapi.md
- name: Expedia Trips by tripId
  x-api-slug: expedia
  description: Mobile API Trips
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/trips/{tripId}
  tags: Travel,Search,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apitripstripid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apitripstripid-get-openapi.md
- name: Expedia Update Trip Name and Description
  x-api-slug: expedia
  description: Mobile API Trips update trip name and description operation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/trips/{tripId}/updateTripNameDescription
  tags: Travel,Search,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apitripstripidupdatetripnamedescription-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apitripstripidupdatetripnamedescription-post-openapi.md
- name: Expedia Get the credit card fee for a trip
  x-api-slug: expedia
  description: This api provides an accurate credit card fee that a user would have
    to pay when booking a trip.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/rails/trip/cardFee
  tags: Travel,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/mapirailstripcardfee-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/mapirailstripcardfee-post-openapi.md
- name: Expedia Associate User To Trip
  x-api-slug: expedia
  description: Mobile API User Associate To Trip
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///api/user/associateUserToTrip
  tags: Travel,Search,Trips
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apiuserassociateusertotrip-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/apiuserassociateusertotrip-post-openapi.md
- name: Expedia Create A Trip
  x-api-slug: expedia
  description: Mobile API Lx Create Trip
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x///m/api/lx/trip/create
  tags: Travel,Trips
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/mapilxtripcreate-post-openapi.md
- name: Expedia
  x-api-slug: expedia
  description: Expedia is the leader in travel and technology and is the worlds largest
    travel company. The EAN Developer Hub gives developers FREE access to our highly
    flexible APIs that power cutting-edge websites, mobile apps, and much more. Some
    of the best travel applications on the market are powered by the EAN API. Learn
    more reasons to partner with EAN by taking a look at our brochure and watching
    our video. The world of travel awaits you!
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Expedia_logo.svg.png
  humanURL: http://developer.ean.com/
  baseURL: https://apim.expedia.com/x/
  tags: Trips
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/trips/master/_listings/expedia/openapi.md
x-common:
- type: x-base
  url: http://api.ean.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/expedia
- type: x-documentation
  url: https://www.expedia.com/static/mobile/swaggerui/
- type: x-github
  url: https://github.com/Expedia
- type: x-swagger--original
  url: https://www.expedia.com/static/mobile/swaggerui/swagger.json
- type: x-twitter
  url: https://twitter.com/ExpediaEAN
- type: x-website
  url: http://developer.ean.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
{
  "info": {
    "name": "Vinli List All of a Vehicle's Trips",
    "_postman_id": "30359661-ed21-43bb-8067-a55e7e712af9",
    "description": "List all of a vehicle's trips.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "5988a043-e4b4-4765-98c5-bb15e6978a3b",
          "name": "DevicesCf217c2dDf3c41f7B6108bc3e11b4b79VehiclesGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/vehicles",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List a device's vehicles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "179d6255-9851-4b4d-97af-f9aee7472d42"
            }
          ]
        },
        {
          "id": "b219c96c-c77c-4d20-95bd-aa58554804b7",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30TripsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/trips",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all of a vehicle's trips."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08a301d1-6283-44fc-a6bb-cc5d27fda769"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Vinli Get Details of a Trip",
    "_postman_id": "d0e5dca1-f9fb-4d91-b818-f88078c43fd0",
    "description": "Get details of a trip.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Vehicle",
      "item": [
        {
          "id": "110335b2-efdf-4c5c-80ce-a797a0418903",
          "name": "VehiclesAa44769b3c0a46629bad25481cf5198fGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/aa44769b-3c0a-4662-9bad-25481cf5198f",
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
            "description": "Get vehicle details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3925f376-f234-406b-ae6c-b36e15e25d60"
            }
          ]
        }
      ]
    },
    {
      "name": "Details",
      "item": [
        {
          "id": "d935a290-3ffa-49fa-8eea-110daa35ac7c",
          "name": "Trips89abe0bdEa2e44e5B573A8a346fdfb54Get",
          "request": {
            "url": "http://events.vin.li/api/v1/trips/89abe0bd-ea2e-44e5-b573-a8a346fdfb54",
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
            "description": "Get details of a trip."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72821c17-3e6c-4445-aa35-a6a75cb6fb6f"
            }
          ]
        }
      ]
    }
  ]
}
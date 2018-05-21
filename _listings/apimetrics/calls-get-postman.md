{
  "info": {
    "name": "APIMetrics List API Calls",
    "_postman_id": "11eb11ea-46ac-4a08-a9d6-be32e4f42040",
    "description": "List API Calls",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Monitoring",
      "item": [
        {
          "id": "050bf945-cdab-41a6-9471-e545c55f3eb9",
          "name": "listAuthenticationSettings",
          "request": {
            "url": "http://example.com/api/auth/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Authentication Settings"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0deb7d9-4f8d-442a-8c0f-64be9ee785fc"
            }
          ]
        },
        {
          "id": "7237b6e5-8f4a-4f7e-b548-0d89635cd45f",
          "name": "getAnExistingAuthenticationSetting",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "auth/:id/"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an existing Authentication Setting"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65e1df64-712c-4d23-b1af-ad1a2acd08f2"
            }
          ]
        },
        {
          "id": "077e34e8-c567-45e3-babb-8883e0cc3935",
          "name": "updateAnExistingAuthenticationSetting",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "auth/:id/"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update an existing Authentication Setting"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "edbee0e6-1df4-407a-b8c4-502a638e75ee"
            }
          ]
        },
        {
          "id": "48f6c7c8-f0d0-44a2-a249-f46bd4c8b2b9",
          "name": "deleteAnAuthenticationSetting",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "auth/:id/"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an Authentication Setting"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca43a8da-91fa-47b4-9675-13e9c7018c9f"
            }
          ]
        },
        {
          "id": "0f9fb579-19e6-41d1-b7fa-77090575ec98",
          "name": "listAPICalls",
          "request": {
            "url": "http://example.com/api/calls/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List API Calls"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd9c11af-75d5-413b-853f-03be3ccacc85"
            }
          ]
        }
      ]
    }
  ]
}
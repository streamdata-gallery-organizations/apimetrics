---
swagger: "2.0"
info:
  title: APImetrics Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /calls/{id}/:
    put:
      summary: Update an existing API Call
      description: Update an existing API Call
      operationId: updateAnExistingAPICall
      parameters:
      - in: body
        name: body
        description: '{     request: {         parameters: [             { key: testing,
          value: bar },             { key: raspberry, value: 2 }         ]     } }'
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID string of API Call
      responses:
        200:
          description: OK
      tags:
      - monitoring
      - calls
definitions: []
x-collection-name: APImetrics
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
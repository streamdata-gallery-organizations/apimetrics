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
  /tokens/{id}/:
    put:
      summary: Update an Auth Token
      description: Update an Auth Token
      operationId: updateAnAuthToken
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID string of Token you are updating
      responses:
        200:
          description: OK
      tags:
      - monitoring
      - tokens
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
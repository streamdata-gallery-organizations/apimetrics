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
  /auth/{id}/:
    get:
      summary: Get an existing Authentication Setting
      description: Get an existing Authentication Setting
      operationId: getAnExistingAuthenticationSetting
      parameters:
      - in: path
        name: id
        description: ID string of authentication string youre upda
      responses:
        200:
          description: OK
      tags:
      - monitoring
      - auth
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
---
swagger: "2.0"
x-collection-name: APImetrics
x-complete: 0
info:
  title: APIMetrics List API Calls
  version: 1.0.0
  description: List API Calls
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /auth/:
    get:
      summary: List Authentication Settings
      description: List Authentication Settings
      operationId: listAuthenticationSettings
      x-api-path-slug: auth-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Auth
  /auth/{id}/:
    delete:
      summary: Delete an Authentication Setting
      description: Delete an Authentication Setting
      operationId: deleteAnAuthenticationSetting
      x-api-path-slug: authid-delete
      parameters:
      - in: path
        name: id
        description: ID string of authentication string youre upda
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Auth
    get:
      summary: Get an existing Authentication Setting
      description: Get an existing Authentication Setting
      operationId: getAnExistingAuthenticationSetting
      x-api-path-slug: authid-get
      parameters:
      - in: path
        name: id
        description: ID string of authentication string youre upda
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Auth
    put:
      summary: Update an existing Authentication Setting
      description: Update an existing Authentication Setting
      operationId: updateAnExistingAuthenticationSetting
      x-api-path-slug: authid-put
      parameters:
      - in: path
        name: id
        description: ID string of authentication string youre upda
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Auth
  /calls/:
    get:
      summary: List API Calls
      description: List API Calls
      operationId: listAPICalls
      x-api-path-slug: calls-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
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
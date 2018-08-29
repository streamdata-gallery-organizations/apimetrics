---
swagger: "2.0"
x-collection-name: APImetrics
x-complete: 0
info:
  title: APIMetrics Get an existing API Call
  version: 1.0.0
  description: Get an existing API Call
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
    post:
      summary: Create new API Call
      description: Create new API Call
      operationId: createNewAPICall
      x-api-path-slug: calls-post
      parameters:
      - in: body
        name: Body
        description: '{     meta: {         name: Minimal API test name     },     request:
          {         method: get,         url: http://httpbin'
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
  /calls/auth/{auth_id}/:
    get:
      summary: List API Calls by Authentication
      description: List API Calls by Authentication
      operationId: listAPICallsbyAuthentication
      x-api-path-slug: callsauthauth-id-get
      parameters:
      - in: path
        name: auth_id
        description: The ID of the authentication setting
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
      - Auth
      - Auth
  /calls/{id}/:
    delete:
      summary: Delete an API Call
      description: Delete an API Call
      operationId: deleteAnAPICall
      x-api-path-slug: callsid-delete
      parameters:
      - in: path
        name: id
        description: ID string of API Call
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
    get:
      summary: Get an existing API Call
      description: Get an existing API Call
      operationId: getAnExistingAPICall
      x-api-path-slug: callsid-get
      parameters:
      - in: path
        name: id
        description: ID string of API Call
      - in: query
        name: kind
        description: Granularity of data required, one of DAY, WEEK, MONTH, tYEAR
      - in: query
        name: location_id
        description: Location where the API Call was made
      - in: query
        name: time
        description: ISO formatted date string for the period you wish to view
      - in: query
        name: type
        description: Return stats for all calls in the time period specified which
          had this result
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
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
    get:
      summary: Get an existing API Call
      description: Get an existing API Call
      operationId: getAnExistingAPICall
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
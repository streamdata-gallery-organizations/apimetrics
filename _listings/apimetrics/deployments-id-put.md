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
  /deployments/{id}/:
    put:
      summary: Update an existing Deployment
      description: Update an existing Deployment
      operationId: updateAnExistingDeployment
      parameters:
      - in: body
        name: body
        description: '{     deployment: {         target_id: __PARENT_ID__,          frequency:
          15,         location_id:      } }'
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID string of deployment you are updating
      responses:
        200:
          description: OK
      tags:
      - monitoring
      - deployments
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
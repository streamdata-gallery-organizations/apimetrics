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
  /deployments/:
    post:
      summary: Create a new Deployment
      description: Create a new Deployment
      operationId: createANewDeployment
      parameters:
      - in: body
        name: body
        description: '{     deployment: {         target_id: agxkZXZ-dmlhdGVzdHNyFwsSClRlc3RTZXR1cDIYgICAgKDL6gsM,          frequency:
          12,         location_id:      } }'
        schema:
          $ref: '#/definitions/holder'
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
---
swagger: "2.0"
x-collection-name: Clearbit
x-complete: 0
info:
  title: Clearbit By Name
  description: 'TODO: Add Description'
  version: 1.0.0
host: discovery.clearbit.com
basePath: /v1/companies
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /entities:
    get:
      summary: By Name
      description: 'TODO: Add Description'
      operationId: EntitiesGet
      x-api-path-slug: entities-get
      parameters:
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Entities
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
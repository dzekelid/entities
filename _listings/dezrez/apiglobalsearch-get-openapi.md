---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez The main endpoint for a global search across all entities in the system.
  version: 1.0.0
  description: The main endpoint for a global search across all entities in the system..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/GlobalSearch:
    get:
      summary: The main endpoint for a global search across all entities in the system.
      description: The main endpoint for a global search across all entities in the
        system..
      operationId: GlobalSearch_IndexBytermByexcludeDeletedByexcludeArchivedBylastUpdated
      x-api-path-slug: apiglobalsearch-get
      parameters:
      - in: query
        name: excludeArchived
      - in: query
        name: excludeDeleted
      - in: query
        name: lastUpdated
        description: Get results from the last updated date
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: term
        description: Search term
      responses:
        200:
          description: OK
      tags:
      - The
      - Main
      - Endpointa
      - Global
      - Search
      - Across
      - ""
      - Entities
      - In
      - System
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
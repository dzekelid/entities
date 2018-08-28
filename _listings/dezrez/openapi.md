swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/accountingsystem:
    get:
      summary: Gets accounting system for a legal entity
      description: Gets accounting system for a legal entity.
      operationId: AccountingSystem_Get
      x-api-path-slug: apiaccountingsystem-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Accounting
      - Systema
      - Legal
      - Entity
  /api/stats/visited/{entityType}:
    get:
      summary: Get all recent history of 'pages' visited on Rezi for a given entity
        type.
      description: Get all recent history of 'pages' visited on rezi for a given entity
        type..
      operationId: Stats_VisitedByentityType
      x-api-path-slug: apistatsvisitedentitytype-get
      parameters:
      - in: path
        name: entityType
        description: Either Groups, Properties or will default to all if nothing passed
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Recent
      - History
      - Of
      - Pages
      - Visited
      - "On"
      - Rezia
      - Given
      - Entity
      - Type
---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Get Alerts Entity Conditions Entity  . Format
  version: 1.0.0
  description: |-
    This API endpoint allows you to list the Alerts conditions an entity is part of.

    Entity type options (Synthetics is not yet supported):

    BrowserApplication

    Application

    MobileApplication

    Server

    KeyTransaction

    Plugin
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /alerts_entity_conditions/{entity_id}.{format}:
    get:
      summary: Get Alerts Entity Conditions Entity  . Format
      description: |-
        This API endpoint allows you to list the Alerts conditions an entity is part of.

        Entity type options (Synthetics is not yet supported):

        BrowserApplication

        Application

        MobileApplication

        Server

        KeyTransaction

        Plugin
      operationId: getAlertsEntityConditionsEntity.Format
      x-api-path-slug: alerts-entity-conditionsentity-id-format-get
      parameters:
      - in: path
        name: entity_id
        description: Entity ID
        type: integer
      - in: query
        name: entity_type
        description: Entity Type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - Entity
      - Conditions
      - Entity
      - ""
      - .
      - Format
    put:
      summary: Put Alerts Entity Conditions Entity  . Format
      description: "This API endpoint allows you to add an entity to a specified Alerts
        condition.\n\nNote: Admin User???s API Key is required.\n \n  Entity type
        options (Synthetics is not yet supported):\n\nBrowserApplication\n\nApplication\n\nMobileApplication\n\nServer\n\nKeyTransaction\n\nPlugin"
      operationId: putAlertsEntityConditionsEntity.Format
      x-api-path-slug: alerts-entity-conditionsentity-id-format-put
      parameters:
      - in: query
        name: condition_id
        description: Alerts condition ID
        type: integer
      - in: path
        name: entity_id
        description: Entity id to add
        type: integer
      - in: query
        name: entity_type
        description: Entity Type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - Entity
      - Conditions
      - Entity
      - ""
      - .
      - Format
    delete:
      summary: Delete Alerts Entity Conditions Entity  . Format
      description: |-
        This API endpoint allows you to disassociate an entity with a specified Alerts condition.

        Note: Admin User???s API Key is required.

        Entity type options (Synthetics is not yet supported):

        BrowserApplication

        Application

        MobileApplication

        Server

        KeyTransaction

        Plugin
      operationId: deleteAlertsEntityConditionsEntity.Format
      x-api-path-slug: alerts-entity-conditionsentity-id-format-delete
      parameters:
      - in: query
        name: condition_id
        description: Alerts condition ID
        type: integer
      - in: path
        name: entity_id
        description: Entity id to remove
        type: integer
      - in: query
        name: entity_type
        description: Entity Type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - Entity
      - Conditions
      - Entity
      - ""
      - .
      - Format
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
---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Assets Get a snapshot of an entity at or before a specified datetime
    (ISO-8601).
  description: For detailed documentation of all available query options please refer
    to Predix Asset Documentation.
  version: 1.0.0
host: predix-apphub-arcs-prod.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{collection}/{id}:
    get:
      summary: Get entity based on  uri
      description: |-
        This is a user-defined domain object collection.

        You can create your own custom domain objects, add properties to them, define relationships, and so on.
      operationId: getV1Collection
      x-api-path-slug: v1collectionid-get
      parameters:
      - in: path
        name: collection
        description: Name of the user-defined domain object collection
      - in: query
        name: fields
        description: Fields to be returned from the entity (comma separated)
      - in: path
        name: id
        description: ID of the domain object to retrieve
      responses:
        200:
          description: Successful response
      tags:
      - Entity
      - Based
      - "On"
      - ""
      - Uri
  /v1/system/audit/snapshots:
    get:
      summary: Get a snapshot of an entity at or before a specified datetime (ISO-8601).
      description: For detailed documentation of all available query options please
        refer to Predix Asset Documentation.
      operationId: getV1SystemAuditSnapshots
      x-api-path-slug: v1systemauditsnapshots-get
      parameters:
      - in: query
        name: filter
        description: identifier={entity uri}:{before|eBefore}={ISO-8601 datetime}
      responses:
        200:
          description: Successful response
      tags:
      - Snapshot
      - Of
      - Entity
      - At
      - Before
      - Specified
      - Datetime
      - (ISO-8601)
  /v1/system/schema/entities/{type}:
    get:
      summary: Get the JSON Schema of the specified entity type
      description: Get the json schema of the specified entity type.
      operationId: getV1SystemSchemaEntitiesType
      x-api-path-slug: v1systemschemaentitiestype-get
      parameters:
      - in: path
        name: type
        description: Entity type (e
      responses:
        200:
          description: Successful response
      tags:
      - JSON
      - Schema
      - Of
      - Specified
      - Entity
      - Type
    put:
      summary: Create or update the JSON Schema of the specified entity type
      description: Create or update the json schema of the specified entity type.
      operationId: putV1SystemSchemaEntitiesType
      x-api-path-slug: v1systemschemaentitiestype-put
      parameters:
      - in: body
        name: body
        description: JSON Schema for the specified entity type
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: type
        description: Entity type (e
      responses:
        200:
          description: Successful response
      tags:
      - Update
      - JSON
      - Schema
      - Of
      - Specified
      - Entity
      - Type
    delete:
      summary: Delete the JSON Schema of the specified entity type
      description: Delete the json schema of the specified entity type.
      operationId: deleteV1SystemSchemaEntitiesType
      x-api-path-slug: v1systemschemaentitiestype-delete
      parameters:
      - in: path
        name: type
        description: Entity type (e
      responses:
        200:
          description: Successful response
      tags:
      - JSON
      - Schema
      - Of
      - Specified
      - Entity
      - Type
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
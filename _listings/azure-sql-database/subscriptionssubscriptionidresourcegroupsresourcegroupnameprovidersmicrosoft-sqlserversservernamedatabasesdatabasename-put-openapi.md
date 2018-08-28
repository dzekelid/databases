---
swagger: "2.0"
x-collection-name: Azure SQL Database
x-complete: 0
info:
  title: Azure SQL Database API Databases Create Or Update
  description: Creates a new database or updates an existing database. Location is
    a required property in the request body, and it must be the same as the location
    of the SQL server.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/databases/{databaseName}
  : put:
      summary: Databases Create Or Update
      description: Creates a new database or updates an existing database. Location
        is a required property in the request body, and it must be the same as the
        location of the SQL server.
      operationId: Databases_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-put
      parameters:
      - in: path
        name: databaseName
        description: The name of the database to be operated on (updated or created)
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The required parameters for creating or updating a database
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Databases
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
---
swagger: "2.0"
x-collection-name: Azure SQL Database
x-complete: 0
info:
  title: Azure SQL Database API Databases Failover Replication Link
  description: Sets which replica database is primary by failing over from the current
    primary replica database.
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
    delete:
      summary: Databases Delete
      description: Deletes a database.
      operationId: Databases_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-delete
      parameters:
      - in: path
        name: databaseName
        description: The name of the database to be deleted
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Databases
    get:
      summary: Databases Get
      description: Gets a database.
      operationId: Databases_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database to be retrieved
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Databases
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/databases/{databaseName}/replicationLinks/{linkId}/failover
  : post:
      summary: Databases Failover Replication Link
      description: Sets which replica database is primary by failing over from the
        current primary replica database.
      operationId: Databases_FailoverReplicationLink
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post
      parameters:
      - in: path
        name: databaseName
        description: The name of the database that has the replication link to be
          failed over
      - in: path
        name: linkId
        description: The ID of the replication link to be failed over
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Databases Failover Replication Link
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/databases/{databaseName}/replicationLinks/{linkId}/forceFailoverAllowDataLoss
  : post:
      summary: Databases Failover Replication Link Allow Data Loss
      description: Sets which replica database is primary by failing over from the
        current primary replica database. This operation might result in data loss.
      operationId: Databases_FailoverReplicationLinkAllowDataLoss
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post
      parameters:
      - in: path
        name: databaseName
        description: The name of the database that has the replication link to be
          failed over
      - in: path
        name: linkId
        description: The ID of the replication link to be failed over
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Databases Failover Replication Link Allow Data Loss
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
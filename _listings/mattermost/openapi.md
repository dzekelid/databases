swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /database/recycle:
    post:
      summary: Recycle database connections
      description: |-
        Recycle database connections by closing and reconnecting all connections to master and read replica databases.
        ##### Permissions
        Must have `manage_system` permission.
      operationId: recycle-database-connections-by-closing-and-reconnecting-all-connections-to-master-and-read-replica-
      x-api-path-slug: databaserecycle-post
      responses:
        200:
          description: OK
      tags:
      - Recycle
      - Database
      - Connections
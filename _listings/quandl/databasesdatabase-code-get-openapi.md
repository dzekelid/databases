---
swagger: "2.0"
x-collection-name: Quandl
x-complete: 0
info:
  title: Quandl Get Databases Database Code
  description: This call returns descriptive metadata for the specified database.
  version: 1.0.0
host: www.quandl.com
basePath: /api/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /databases/{database_code}/data:
    get:
      summary: Get Databases Database Code Data
      description: "You can download all the data in a premium database in a single
        call, by appending /data to your database request. You can specify whether
        you want the entire history, or merely the last day\u2019s worth of updates,
        by setting the correct query parameters."
      operationId: databases.database_code.data.get
      x-api-path-slug: databasesdatabase-codedata-get
      parameters:
      - in: path
        name: database_code
        description: The unique database code on Quandl (ex
      - in: query
        name: download_type
        description: Data returned can be either partial or complete
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Databases
      - Database
      - Code
      - Data
  /databases/{database_code}/codes:
    get:
      summary: Get Databases Database Code Codes
      description: You can download a list of all dataset codes in a database in a
        single call, by appending /codes to your database request. The call will return
        a ZIP file containing a CSV.
      operationId: databases.database_code.codes.get
      x-api-path-slug: databasesdatabase-codecodes-get
      parameters:
      - in: path
        name: database_code
        description: The unique database code on Quandl (ex
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Databases
      - Database
      - Code
      - Codes
  /databases/{database_code}:
    get:
      summary: Get Databases Database Code
      description: This call returns descriptive metadata for the specified database.
      operationId: databases.database_code.get
      x-api-path-slug: databasesdatabase-code-get
      parameters:
      - in: path
        name: database_code
        description: The unique database code on Quandl (ex
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Databases
      - Database
      - Code
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
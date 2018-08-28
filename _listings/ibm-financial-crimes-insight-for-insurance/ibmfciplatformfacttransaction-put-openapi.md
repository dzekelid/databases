---
swagger: "2.0"
x-collection-name: IBM Financial Crimes Insight for Insurance
x-complete: 0
info:
  title: IBM Financial Crimes Insight for Insurance API Insert transaction data into
    the database
  description: This method is used to insert transaction data into the database.  The
    XML schema is defined in the TRANSACTION.XSD file.
  version: 1.0.0
host: fcihost.ibm.com:9443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ibm/fci/platform/fact/account:
    put:
      summary: Insert account data into the database
      description: This method is used to insert account data into the database.  The
        XML schema is defined in the ACCOUNT.XSD file.
      operationId: putAccount
      x-api-path-slug: ibmfciplatformfactaccount-put
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Account
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/account/{id}:
    get:
      summary: Retrieve account data from the database, for the id
      description: This method is used to retrieve account data from the database
      operationId: getAccount
      x-api-path-slug: ibmfciplatformfactaccountid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Account
      - Data
      - From
      - Database
      - The
      - Id
  /ibm/fci/platform/fact/event:
    put:
      summary: Insert event data into the database
      description: This method is used to insert event data into the database.  The
        XML schema is defined in the EVENT.XSD file.
      operationId: putEvent
      x-api-path-slug: ibmfciplatformfactevent-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Event
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/event/{id}:
    get:
      summary: Retrieve event data from the database, for the id
      description: This method is used to retrieve event data from the database
      operationId: getEvent
      x-api-path-slug: ibmfciplatformfacteventid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Event
      - Data
      - From
      - Database
      - The
      - Id
  /ibm/fci/platform/fact/group:
    put:
      summary: Insert group data into the database
      description: This method is used to insert group data into the database.  The
        XML schema is defined in the GROUP.XSD file.
      operationId: putGroup
      x-api-path-slug: ibmfciplatformfactgroup-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Group
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/group/{id}:
    get:
      summary: Retrieve group data from the database, for the specific group id
      description: This method is used to retrieve specific group data from the database
      operationId: getGroup
      x-api-path-slug: ibmfciplatformfactgroupid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Group
      - Data
      - From
      - Database
      - The
      - Specific
      - Group
      - Id
  /ibm/fci/platform/fact/party:
    put:
      summary: Insert party data into the database
      description: This method is used to insert party data into the database.  The
        XML schema is defined in the PARTY.XSD file.
      operationId: putParty
      x-api-path-slug: ibmfciplatformfactparty-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Party
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/party/{id}:
    get:
      summary: Retrieve party data from the database, for the id
      description: This method is used to retrieve party data from the database
      operationId: getParty
      x-api-path-slug: ibmfciplatformfactpartyid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Party
      - Data
      - From
      - Database
      - The
      - Id
  /ibm/fci/platform/fact/physical_object:
    put:
      summary: Insert physical object data into the database
      description: This method is used to insert physical object data into the database.  The
        XML schema is defined in the PhysicalObject.XSD file.
      operationId: putPhysicalObject
      x-api-path-slug: ibmfciplatformfactphysical-object-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Physical
      - Object
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/physical_object/{id}:
    get:
      summary: Retrieve a specific physical object data from the database, based on
        its internal id
      description: This method is used to retrieve specific physical object data from
        the database, based on its internal id
      operationId: getPhysicalObject
      x-api-path-slug: ibmfciplatformfactphysical-objectid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Specific
      - Physical
      - Object
      - Data
      - From
      - Database
      - ""
      - Based
      - "On"
      - Its
      - Internal
      - Id
  /ibm/fci/platform/fact/transaction:
    put:
      summary: Insert transaction data into the database
      description: This method is used to insert transaction data into the database.  The
        XML schema is defined in the TRANSACTION.XSD file.
      operationId: putTransaction
      x-api-path-slug: ibmfciplatformfacttransaction-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Transaction
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/transaction/{id}:
    get:
      summary: Retrieve transaction data from the database, by its internal id
      description: This method is used to retrieve transaction data from the database
      operationId: getTransaction
      x-api-path-slug: ibmfciplatformfacttransactionid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Transaction
      - Data
      - From
      - Database
      - ""
      - By
      - Its
      - Internal
      - Id
  /ibm/fci/platform/fact/watchlist:
    post:
      summary: Persist the provided watchlist into the local database
      description: 'This method is used to persist the contents of a watchlist into
        the database.  Note: This method uses some data import functionality to create
        business object entries, then calls putWatchlist to create/update a watchlist
        for the provided identifier, and finally calls putWatchlistItem for every
        object created. This one also has the caveat of needing a disposition defined,
        but in this case all you need to pass in is the stereotype value.'
      operationId: uploadWatchlist
      x-api-path-slug: ibmfciplatformfactwatchlist-post
      parameters:
      - in: formData
        name: data
        description: CSV file containing an external watchlist
      - in: formData
        name: dataName
        description: CSV file name
      - in: query
        name: disposition
        description: watchlist_disposition stereotype
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: query
        name: identifier
      - in: query
        name: overwrite
      - in: formData
        name: properties
        description: 'A '
      - in: formData
        name: propertiesName
        description: Properties file name
      responses:
        200:
          description: OK
      tags:
      - Persist
      - Provided
      - Watchlist
      - Into
      - Local
      - Database
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
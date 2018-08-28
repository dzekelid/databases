---
name: Azure SQL Database
x-slug: azure-sql-database
description: Make building and maintaining applications easier and more productive.
  With built-in intelligence that learns app patterns and adapts to maximize performance,
  reliability, and data protection, SQL Database is a cloud database built for developers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Databases
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/apis.md
specificationVersion: "0.14"
apis:
- name: Azure SQL Database - Databases Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-put
  description: Creates a new database or updates an existing database. Location is
    a required property in the request body, and it must be the same as the location
    of the SQL server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-put-openapi.md
- name: Azure SQL Database - Databases Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-delete
  description: Deletes a database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-delete-openapi.md
- name: Azure SQL Database - Databases Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-get
  description: Gets a database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasename-get-openapi.md
- name: Azure SQL Database - Databases Failover Replication Link
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post
  description: Sets which replica database is primary by failing over from the current
    primary replica database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post-openapi.md
- name: Azure SQL Database - Databases Failover Replication Link Allow Data Loss
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post
  description: Sets which replica database is primary by failing over from the current
    primary replica database. This operation might result in data loss.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post-openapi.md
- name: Azure SQL Database - Databases Failover Replication Link
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post
  description: Sets which replica database is primary by failing over from the current
    primary replica database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post-openapi.md
- name: Azure SQL Database - Databases Failover Replication Link Allow Data Loss
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post
  description: Sets which replica database is primary by failing over from the current
    primary replica database. This operation might result in data loss.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post-openapi.md
- name: Azure SQL Database - Databases Failover Replication Link
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post
  description: Sets which replica database is primary by failing over from the current
    primary replica database.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidfailover-post-openapi.md
- name: Azure SQL Database - Databases Failover Replication Link Allow Data Loss
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post
  description: Sets which replica database is primary by failing over from the current
    primary replica database. This operation might result in data loss.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Databases, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/databases/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenamereplicationlinkslinkidforcefailoverallowdataloss-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.service.fabric.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.sql.database.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/sql-database/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/sql-database/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/sql-database/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/sql-database/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Asset Categories
  version: 1.0.0
  description: Get api asset categories.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/AccountExist:
    get:
      summary: Get API Account Exist
      description: Get api account exist.
      operationId: ApiAccountExistGet
      x-api-path-slug: apiaccountexist-get
      parameters:
      - in: query
        name: email
      - in: query
        name: partnerId
      responses:
        200:
          description: OK
      tags:
      - Account
      - Exist
  /api/AllAssetDescription/{id}:
    get:
      summary: Get API All Asset Description
      description: Get api all asset description.
      operationId: ApiAllAssetDescriptionByIdGet
      x-api-path-slug: apiallassetdescriptionid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Description
  /api/AllAssetPairRates:
    get:
      summary: Get API All Asset Pair Rates
      description: Get api all asset pair rates.
      operationId: ApiAllAssetPairRatesGet
      x-api-path-slug: apiallassetpairrates-get
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pair
      - Rates
  /api/AllAssetPairRates/{id}:
    get:
      summary: Get API All Asset Pair Rates
      description: Get api all asset pair rates.
      operationId: ApiAllAssetPairRatesByIdGet
      x-api-path-slug: apiallassetpairratesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pair
      - Rates
  /api/AllAssetPairs:
    get:
      summary: Get API All Asset Pairs
      description: Get api all asset pairs.
      operationId: ApiAllAssetPairsGet
      x-api-path-slug: apiallassetpairs-get
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pairs
  /api/AllAssetPairs/{id}:
    get:
      summary: Get API All Asset Pairs
      description: Get api all asset pairs.
      operationId: ApiAllAssetPairsByIdGet
      x-api-path-slug: apiallassetpairsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pairs
  /api/ApplicationInfo:
    get:
      summary: Get API Application Information
      description: Get api application information.
      operationId: ApiApplicationInfoGet
      x-api-path-slug: apiapplicationinfo-get
      responses:
        200:
          description: OK
      tags:
      - Application
      - Information
  /api/AppSettings:
    get:
      summary: Get API Application Settings
      description: Get api application settings.
      operationId: ApiAppSettingsGet
      x-api-path-slug: apiappsettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Application
      - Settings
  /api/assetcategories:
    get:
      summary: Get API Asset Categories
      description: Get api asset categories.
      operationId: ApiAssetcategoriesGet
      x-api-path-slug: apiassetcategories-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Categories
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
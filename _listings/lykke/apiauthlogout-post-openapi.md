---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Auth Logout
  version: 1.0.0
  description: Add api auth logout.
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
  /api/AssetDescription/{id}:
    get:
      summary: Get API Assetdescription
      description: Get api assetdescription.
      operationId: ApiAssetDescriptionByIdGet
      x-api-path-slug: apiassetdescriptionid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assetdescription
  /api/AssetDisclaimers:
    get:
      summary: Get API Asset Dsclaimers
      description: Get api asset dsclaimers.
      operationId: AssetDisclaimersGet
      x-api-path-slug: apiassetdisclaimers-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
  /api/AssetDisclaimers/{disclaimerId}/approve:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Approve
      description: Add api asset dsclaimers disclaimer approve.
      operationId: AssetDisclaimersApprove
      x-api-path-slug: apiassetdisclaimersdisclaimeridapprove-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: disclaimerId
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
      - Disclaimer
      - Approve
  /api/AssetDisclaimers/{disclaimerId}/decline:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Decline
      description: Add api asset dsclaimers disclaimer decline.
      operationId: AssetDisclaimersDecline
      x-api-path-slug: apiassetdisclaimersdisclaimeriddecline-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: disclaimerId
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
      - Disclaimer
      - Decline
  /api/AssetPair/{id}:
    get:
      summary: Get API Assetpair
      description: Get api assetpair.
      operationId: ApiAssetPairByIdGet
      x-api-path-slug: apiassetpairid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assetpair
  /api/AssetPairDetailedRates:
    get:
      summary: Get API Assetpairdetailedrates
      description: Get api assetpairdetailedrates.
      operationId: ApiAssetPairDetailedRatesGet
      x-api-path-slug: apiassetpairdetailedrates-get
      parameters:
      - in: query
        name: assetId
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: period
      - in: query
        name: points
      - in: query
        name: withBid
      responses:
        200:
          description: OK
      tags:
      - Assetpairdetailedrates
  /api/AssetPairRates:
    get:
      summary: Get API Assetpairrates
      description: Get api assetpairrates.
      operationId: ApiAssetPairRatesGet
      x-api-path-slug: apiassetpairrates-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: ignoreBase
      responses:
        200:
          description: OK
      tags:
      - Assetpairrates
  /api/AssetPairRates/{id}:
    get:
      summary: Get API Assetpairrates
      description: Get api assetpairrates.
      operationId: ApiAssetPairRatesByIdGet
      x-api-path-slug: apiassetpairratesid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assetpairrates
  /api/AssetPairs:
    get:
      summary: Get API Assetpairs
      description: Get api assetpairs.
      operationId: ApiAssetPairsGet
      x-api-path-slug: apiassetpairs-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Assetpairs
  /api/Assets:
    get:
      summary: Get API Assets
      description: Get api assets.
      operationId: ApiAssetsGet
      x-api-path-slug: apiassets-get
      responses:
        200:
          description: OK
      tags:
      - Assets
  /api/Assets/{id}:
    get:
      summary: Get API Assets
      description: Get api assets.
      operationId: ApiAssetsByIdGet
      x-api-path-slug: apiassetsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assets
  /api/Assets/description/list:
    post:
      summary: Add API Assets Description List
      description: Add api assets description list.
      operationId: ApiAssetsDescriptionListPost
      x-api-path-slug: apiassetsdescriptionlist-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Description
      - List
  /api/Assets/{assetId}/attributes:
    get:
      summary: Get API Assets Asset Attributes
      description: Get api assets asset attributes.
      operationId: ApiAssetsByAssetIdAttributesGet
      x-api-path-slug: apiassetsassetidattributes-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Asset
      - Attributes
  /api/Assets/{assetId}/attributes/{key}:
    get:
      summary: Get API Assets Asset Attributes Key
      description: Get api assets asset attributes key.
      operationId: ApiAssetsByAssetIdAttributesByKeyGet
      x-api-path-slug: apiassetsassetidattributeskey-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: key
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Asset
      - Attributes
      - Key
  /api/Auth:
    post:
      summary: Add API Auth
      description: Add api auth.
      operationId: ApiAuthPost
      x-api-path-slug: apiauth-post
      parameters:
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Auth
  /api/Auth/LogOut:
    post:
      summary: Add API Auth Logout
      description: Add api auth logout.
      operationId: ApiAuthLogOutPost
      x-api-path-slug: apiauthlogout-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Logout
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
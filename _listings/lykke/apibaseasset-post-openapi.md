---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Baseasset
  version: 1.0.0
  description: ""
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
      description: ""
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
      - ""
  /api/AllAssetDescription/{id}:
    get:
      summary: Get API All Asset Description
      description: ""
      operationId: ApiAllAssetDescriptionByIdGet
      x-api-path-slug: apiallassetdescriptionid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/AllAssetPairRates:
    get:
      summary: Get API All Asset Pair Rates
      description: ""
      operationId: ApiAllAssetPairRatesGet
      x-api-path-slug: apiallassetpairrates-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/AllAssetPairRates/{id}:
    get:
      summary: Get API All Asset Pair Rates
      description: ""
      operationId: ApiAllAssetPairRatesByIdGet
      x-api-path-slug: apiallassetpairratesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/AllAssetPairs:
    get:
      summary: Get API All Asset Pairs
      description: ""
      operationId: ApiAllAssetPairsGet
      x-api-path-slug: apiallassetpairs-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/AllAssetPairs/{id}:
    get:
      summary: Get API All Asset Pairs
      description: ""
      operationId: ApiAllAssetPairsByIdGet
      x-api-path-slug: apiallassetpairsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ApplicationInfo:
    get:
      summary: Get API Application Information
      description: ""
      operationId: ApiApplicationInfoGet
      x-api-path-slug: apiapplicationinfo-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/AppSettings:
    get:
      summary: Get API Application Settings
      description: ""
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
      - ""
  /api/assetcategories:
    get:
      summary: Get API Asset Categories
      description: ""
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
      - ""
  /api/AssetDescription/{id}:
    get:
      summary: Get API Assetdescription
      description: ""
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
      - ""
  /api/AssetDisclaimers:
    get:
      summary: Get API Asset Dsclaimers
      description: ""
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
      - ""
  /api/AssetDisclaimers/{disclaimerId}/approve:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Approve
      description: ""
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
      - ""
  /api/AssetDisclaimers/{disclaimerId}/decline:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Decline
      description: ""
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
      - ""
  /api/AssetPair/{id}:
    get:
      summary: Get API Assetpair
      description: ""
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
      - ""
  /api/AssetPairDetailedRates:
    get:
      summary: Get API Assetpairdetailedrates
      description: ""
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
      - ""
  /api/AssetPairRates:
    get:
      summary: Get API Assetpairrates
      description: ""
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
      - ""
  /api/AssetPairRates/{id}:
    get:
      summary: Get API Assetpairrates
      description: ""
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
      - ""
  /api/AssetPairs:
    get:
      summary: Get API Assetpairs
      description: ""
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
      - ""
  /api/Assets:
    get:
      summary: Get API Assets
      description: ""
      operationId: ApiAssetsGet
      x-api-path-slug: apiassets-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Assets/{id}:
    get:
      summary: Get API Assets
      description: ""
      operationId: ApiAssetsByIdGet
      x-api-path-slug: apiassetsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Assets/description/list:
    post:
      summary: Add API Assets Description List
      description: ""
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
      - ""
  /api/Assets/{assetId}/attributes:
    get:
      summary: Get API Assets Asset Attributes
      description: ""
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
      - ""
  /api/Assets/{assetId}/attributes/{key}:
    get:
      summary: Get API Assets Asset Attributes Key
      description: ""
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
      - ""
  /api/Auth:
    post:
      summary: Add API Auth
      description: ""
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
      - ""
  /api/Auth/LogOut:
    post:
      summary: Add API Auth Logout
      description: ""
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
      - ""
  /api/BackupCompleted:
    post:
      summary: Add API Backup Completed
      description: ""
      operationId: ApiBackupCompletedPost
      x-api-path-slug: apibackupcompleted-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BankCardPaymentUrl:
    post:
      summary: Add API Bankcardpaymenturl
      description: ""
      operationId: ApiBankCardPaymentUrlPost
      x-api-path-slug: apibankcardpaymenturl-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: input
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BankCardPaymentUrlFormValues:
    get:
      summary: Get API Bankcardpaymenturlformvalues
      description: ""
      operationId: ApiBankCardPaymentUrlFormValuesGet
      x-api-path-slug: apibankcardpaymenturlformvalues-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BankTransferRequest:
    post:
      summary: Add API Banktransferrequest
      description: ""
      operationId: ApiBankTransferRequestPost
      x-api-path-slug: apibanktransferrequest-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: transferReq
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BaseAsset:
    get:
      summary: Get API Baseasset
      description: ""
      operationId: ApiBaseAssetGet
      x-api-path-slug: apibaseasset-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
    post:
      summary: Add API Baseasset
      description: ""
      operationId: ApiBaseAssetPost
      x-api-path-slug: apibaseasset-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
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
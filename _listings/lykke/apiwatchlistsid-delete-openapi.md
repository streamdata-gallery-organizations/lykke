---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Delete API Watchlists
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
  /api/BaseAssets:
    get:
      summary: Get API Baseassets
      description: ""
      operationId: ApiBaseAssetsGet
      x-api-path-slug: apibaseassets-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BcnTransaction:
    get:
      summary: Get API Bcntransaction
      description: ""
      operationId: ApiBcnTransactionGet
      x-api-path-slug: apibcntransaction-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BcnTransaction/offchain-trade:
    get:
      summary: Get API Bcntransaction Offchain Trade
      description: ""
      operationId: ApiBcnTransactionOffchain-tradeGet
      x-api-path-slug: apibcntransactionoffchaintrade-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BcnTransactionByCashOperation/{id}:
    get:
      summary: Get API Bcntransactionbycashoperation
      description: ""
      operationId: ApiBcnTransactionByCashOperationByIdGet
      x-api-path-slug: apibcntransactionbycashoperationid-get
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
  /api/BcnTransactionByExchange/{id}:
    get:
      summary: Get API Bcntransactionbyexchange
      description: ""
      operationId: ApiBcnTransactionByExchangeByIdGet
      x-api-path-slug: apibcntransactionbyexchangeid-get
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
  /api/BcnTransactionByTransfer/{id}:
    get:
      summary: Get API Bcntransactionbytransfer
      description: ""
      operationId: ApiBcnTransactionByTransferByIdGet
      x-api-path-slug: apibcntransactionbytransferid-get
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
  /api/BitcoinCash/multisig/balance:
    get:
      summary: Get API Bitcoincash Multisig Balance
      description: ""
      operationId: ApiBitcoinCashMultisigBalanceGet
      x-api-path-slug: apibitcoincashmultisigbalance-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BitcoinCash/multisig/transaction:
    get:
      summary: Get API Bitcoincash Multisig Transaction
      description: ""
      operationId: ApiBitcoinCashMultisigTransactionGet
      x-api-path-slug: apibitcoincashmultisigtransaction-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: destinationAddress
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BitcoinCash/private/balance:
    get:
      summary: Get API Bitcoincash Private Balance
      description: ""
      operationId: ApiBitcoinCashPrivateBalanceGet
      x-api-path-slug: apibitcoincashprivatebalance-get
      parameters:
      - in: query
        name: address
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BitcoinCash/private/transaction:
    get:
      summary: Get API Bitcoincash Private Transaction
      description: ""
      operationId: ApiBitcoinCashPrivateTransactionGet
      x-api-path-slug: apibitcoincashprivatetransaction-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: destinationAddress
      - in: query
        name: fee
      - in: query
        name: sourceAddress
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BitcoinCash/broadcast:
    post:
      summary: Add API Bitcoincash Broadcast
      description: ""
      operationId: ApiBitcoinCashBroadcastPost
      x-api-path-slug: apibitcoincashbroadcast-post
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
  /api/BlockchainTransaction:
    get:
      summary: Get API Blockchaintransaction
      description: ""
      operationId: ApiBlockchainTransactionGet
      x-api-path-slug: apiblockchaintransaction-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: blockChainHash
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/BroadcastTransaction:
    post:
      summary: Add API Broadcasttransaction
      description: ""
      operationId: ApiBroadcastTransactionPost
      x-api-path-slug: apibroadcasttransaction-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: transaction
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/CashOut:
    post:
      summary: Add API Cashout
      description: ""
      operationId: ApiCashOutPost
      x-api-path-slug: apicashout-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/CashOutSwiftRequest:
    post:
      summary: Add API Cashout Swift Request
      description: ""
      operationId: ApiCashOutSwiftRequestPost
      x-api-path-slug: apicashoutswiftrequest-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ChangePinAndPassword:
    post:
      summary: Add API Changepinandpassword
      description: ""
      operationId: ApiChangePinAndPasswordPost
      x-api-path-slug: apichangepinandpassword-post
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
  /api/CheckDocumentsToUpload:
    get:
      summary: Get API Checkdocumentstoupload
      description: ""
      operationId: ApiCheckDocumentsToUploadGet
      x-api-path-slug: apicheckdocumentstoupload-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/CheckMobilePhone:
    get:
      summary: Get API Checkmobilephone
      description: ""
      operationId: ApiCheckMobilePhoneGet
      x-api-path-slug: apicheckmobilephone-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: code
      - in: query
        name: phoneNumber
      responses:
        200:
          description: OK
      tags:
      - ""
    post:
      summary: Add API Checkmobilephone
      description: ""
      operationId: ApiCheckMobilePhonePost
      x-api-path-slug: apicheckmobilephone-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: phoneModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Client/codes:
    get:
      summary: Get API Client Codes
      description: ""
      operationId: ApiClientCodesGet
      x-api-path-slug: apiclientcodes-get
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
      summary: Add API Client Codes
      description: ""
      operationId: ApiClientCodesPost
      x-api-path-slug: apiclientcodes-post
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
  /api/Client/keys/encodedmainkey:
    post:
      summary: Add API Client Keys Encodedmainkey
      description: ""
      operationId: ApiClientKeysEncodedmainkeyPost
      x-api-path-slug: apiclientkeysencodedmainkey-post
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
  /api/Client/balances/{baseAsset}:
    get:
      summary: Get API Client Balances Baseasset
      description: ""
      operationId: ApiClientBalancesByBaseAssetGet
      x-api-path-slug: apiclientbalancesbaseasset-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: baseAsset
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Client/pushTxDialogOk:
    post:
      summary: Add API Client Pushtxdialogok
      description: ""
      operationId: ApiClientPushTxDialogOkPost
      x-api-path-slug: apiclientpushtxdialogok-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Client/dictionary/{key}:
    get:
      summary: Get API Client Dictionary Key
      description: ""
      operationId: ApiClientDictionaryByKeyGet
      x-api-path-slug: apiclientdictionarykey-get
      parameters:
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
    delete:
      summary: Delete API Client Dictionary Key
      description: ""
      operationId: ApiClientDictionaryByKeyDelete
      x-api-path-slug: apiclientdictionarykey-delete
      parameters:
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
  /api/Client/dictionary:
    put:
      summary: Put API Client Dictionary
      description: ""
      operationId: ApiClientDictionaryPut
      x-api-path-slug: apiclientdictionary-put
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: keyValue
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
    post:
      summary: Add API Client Dictionary
      description: ""
      operationId: ApiClientDictionaryPost
      x-api-path-slug: apiclientdictionary-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: keyValue
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Client/properties/isUserFromUS:
    get:
      summary: Get API Client Properties Isuserfromus
      description: ""
      operationId: ApiClientPropertiesIsUserFromUSGet
      x-api-path-slug: apiclientpropertiesisuserfromus-get
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
      summary: Add API Client Properties Isuserfromus
      description: ""
      operationId: ApiClientPropertiesIsUserFromUSPost
      x-api-path-slug: apiclientpropertiesisuserfromus-post
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
  /api/Client/pendingActions:
    get:
      summary: Get API Client Pendingactions
      description: ""
      operationId: ApiClientPendingActionsGet
      x-api-path-slug: apiclientpendingactions-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ClientFirstNameLastName:
    post:
      summary: Add API Clientfirstnamelastname
      description: ""
      operationId: ApiClientFirstNameLastNamePost
      x-api-path-slug: apiclientfirstnamelastname-post
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
  /api/ClientFullName:
    post:
      summary: Add API Clientfullname
      description: ""
      operationId: ApiClientFullNamePost
      x-api-path-slug: apiclientfullname-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: fullNameModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ClientKeys:
    post:
      summary: Add API Clientkeys
      description: ""
      operationId: ApiClientKeysPost
      x-api-path-slug: apiclientkeys-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ClientLog:
    post:
      summary: Add API Clientlog
      description: ""
      operationId: ApiClientLogPost
      x-api-path-slug: apiclientlog-post
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
  /api/ClientPhone:
    post:
      summary: Add API Clientphone
      description: ""
      operationId: ApiClientPhonePost
      x-api-path-slug: apiclientphone-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: phoneModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ClientState:
    get:
      summary: Get API Clientstate
      description: ""
      operationId: ApiClientStateGet
      x-api-path-slug: apiclientstate-get
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
  /api/ClientTrading/termsOfUse:
    get:
      summary: Get API Clienttrading Termsofuse
      description: ""
      operationId: ApiClientTradingTermsOfUseGet
      x-api-path-slug: apiclienttradingtermsofuse-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ClientTrading/termsOfUse/margin/agree:
    post:
      summary: Add API Clienttrading Termsofuse Margin Agree
      description: ""
      operationId: ApiClientTradingTermsOfUseMarginAgreePost
      x-api-path-slug: apiclienttradingtermsofusemarginagree-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/CountryPhoneCodes:
    get:
      summary: Get API Countryphonecodes
      description: ""
      operationId: ApiCountryPhoneCodesGet
      x-api-path-slug: apicountryphonecodes-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/client/Dialogs:
    get:
      summary: Get API Client Dialogs
      description: ""
      operationId: ApiClientDialogsGet
      x-api-path-slug: apiclientdialogs-get
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
      summary: Add API Client Dialogs
      description: ""
      operationId: ApiClientDialogsPost
      x-api-path-slug: apiclientdialogs-post
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
  /api/Dictionary/{key}:
    get:
      summary: Get API Dictionary Key
      description: ""
      operationId: ApiDictionaryByKeyGet
      x-api-path-slug: apidictionarykey-get
      parameters:
      - in: path
        name: key
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Dictionary:
    get:
      summary: Get API Dictionary
      description: ""
      operationId: ApiDictionaryGet
      x-api-path-slug: apidictionary-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Dicts:
    get:
      summary: Get API Dicts
      description: ""
      operationId: ApiDictsGet
      x-api-path-slug: apidicts-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Dicts/assets:
    get:
      summary: Get API Dicts Assets
      description: ""
      operationId: ApiDictsAssetsGet
      x-api-path-slug: apidictsassets-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Dicts/updates:
    get:
      summary: Get API Dicts Updates
      description: ""
      operationId: ApiDictsUpdatesGet
      x-api-path-slug: apidictsupdates-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Email/PrivateWalletAddress:
    post:
      summary: Add API Email Privatewalletaddress
      description: ""
      operationId: ApiEmailPrivateWalletAddressPost
      x-api-path-slug: apiemailprivatewalletaddress-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/EmailMeWalletAddress:
    post:
      summary: Add API Emailmewalletaddress
      description: ""
      operationId: ApiEmailMeWalletAddressPost
      x-api-path-slug: apiemailmewalletaddress-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: reqModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/EmailVerification:
    get:
      summary: Get API Emailverification
      description: ""
      operationId: ApiEmailVerificationGet
      x-api-path-slug: apiemailverification-get
      parameters:
      - in: query
        name: code
      - in: query
        name: email
      - in: query
        name: partnerId
      responses:
        200:
          description: OK
      tags:
      - ""
    post:
      summary: Add API Emailverification
      description: ""
      operationId: ApiEmailVerificationPost
      x-api-path-slug: apiemailverification-post
      parameters:
      - in: body
        name: email
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/EncodedPrivateKey:
    post:
      summary: Add API Encodedprivatekey
      description: ""
      operationId: ApiEncodedPrivateKeyPost
      x-api-path-slug: apiencodedprivatekey-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/{operationId}/transfer:
    post:
      summary: Add API Ethereum Operation Transfer
      description: ""
      operationId: ApiEthereumByOperationIdTransferPost
      x-api-path-slug: apiethereumoperationidtransfer-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/trade:
    post:
      summary: Add API Ethereum Trade
      description: ""
      operationId: ApiEthereumTradePost
      x-api-path-slug: apiethereumtrade-post
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
  /api/Ethereum/cashout:
    post:
      summary: Add API Ethereum Cashout
      description: ""
      operationId: ApiEthereumCashoutPost
      x-api-path-slug: apiethereumcashout-post
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
  /api/Ethereum/{operationId}/hash:
    post:
      summary: Add API Ethereum Operation Hash
      description: ""
      operationId: ApiEthereumByOperationIdHashPost
      x-api-path-slug: apiethereumoperationidhash-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/transfers:
    get:
      summary: Get API Ethereum Transfers
      description: ""
      operationId: ApiEthereumTransfersGet
      x-api-path-slug: apiethereumtransfers-get
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
      summary: Add API Ethereum Transfers
      description: ""
      operationId: ApiEthereumTransfersPost
      x-api-path-slug: apiethereumtransfers-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: operations
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/hash:
    post:
      summary: Add API Ethereum Hash
      description: ""
      operationId: ApiEthereumHashPost
      x-api-path-slug: apiethereumhash-post
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
  /api/Ethereum/privateWallet/generateTransaction:
    post:
      summary: Add API Ethereum Privatewallet Generatetransaction
      description: ""
      operationId: ApiEthereumPrivateWalletGenerateTransactionPost
      x-api-path-slug: apiethereumprivatewalletgeneratetransaction-post
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
  /api/Ethereum/privateWallet/broadcastTransaction:
    post:
      summary: Add API Ethereum Privatewallet Broadcasttransaction
      description: ""
      operationId: ApiEthereumPrivateWalletBroadcastTransactionPost
      x-api-path-slug: apiethereumprivatewalletbroadcasttransaction-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: transaction
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/privateWallet/estimateTransaction:
    post:
      summary: Add API Ethereum Privatewallet Estimatetransaction
      description: ""
      operationId: ApiEthereumPrivateWalletEstimateTransactionPost
      x-api-path-slug: apiethereumprivatewalletestimatetransaction-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: transaction
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/getCurrentNetworkGas:
    get:
      summary: Get API Ethereum Getcurrentnetworkgas
      description: ""
      operationId: ApiEthereumGetCurrentNetworkGasGet
      x-api-path-slug: apiethereumgetcurrentnetworkgas-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/tx/{transactionHash}:
    get:
      summary: Get API Ethereum Tx Transactionhash
      description: ""
      operationId: ApiEthereumTxByTransactionHashGet
      x-api-path-slug: apiethereumtxtransactionhash-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: transactionHash
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/history/{address}:
    get:
      summary: Get API Ethereum History Address
      description: ""
      operationId: ApiEthereumHistoryByAddressGet
      x-api-path-slug: apiethereumhistoryaddress-get
      parameters:
      - in: path
        name: address
      - in: query
        name: assetId
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: count
      - in: query
        name: start
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Ethereum/settings:
    get:
      summary: Get API Ethereum Settings
      description: ""
      operationId: ApiEthereumSettingsGet
      x-api-path-slug: apiethereumsettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ExchangeInfo:
    get:
      summary: Get API Exchangeinfo
      description: ""
      operationId: ApiExchangeInfoGet
      x-api-path-slug: apiexchangeinfo-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: exchangeId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/FormatCreditVouchersContent:
    post:
      summary: Add API Formatcreditvoucherscontent
      description: ""
      operationId: ApiFormatCreditVouchersContentPost
      x-api-path-slug: apiformatcreditvoucherscontent-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/operations/ForwardWithdrawal:
    post:
      summary: Add API Operations Forwardwithdrawal
      description: ""
      operationId: ApiOperationsForwardWithdrawalPost
      x-api-path-slug: apioperationsforwardwithdrawal-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/GenerateTransferTransaction:
    post:
      summary: Add API Generatetransfertransaction
      description: ""
      operationId: ApiGenerateTransferTransactionPost
      x-api-path-slug: apigeneratetransfertransaction-post
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
  /api/GraphPeriods:
    get:
      summary: Get API Graphperiods
      description: ""
      operationId: ApiGraphPeriodsGet
      x-api-path-slug: apigraphperiods-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/HashedPwd:
    post:
      summary: Add API Hashedpwd
      description: ""
      operationId: ApiHashedPwdPost
      x-api-path-slug: apihashedpwd-post
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
  /api/History:
    get:
      summary: Get API History
      description: ""
      operationId: ApiHistoryGet
      x-api-path-slug: apihistory-get
      parameters:
      - in: query
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/History/limit/trades:
    get:
      summary: Get API History Limit Trades
      description: ""
      operationId: ApiHistoryLimitTradesGet
      x-api-path-slug: apihistorylimittrades-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/History/limit/order:
    get:
      summary: Get API History Limit Order
      description: ""
      operationId: ApiHistoryLimitOrderGet
      x-api-path-slug: apihistorylimitorder-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/History/limit/history:
    get:
      summary: Get API History Limit History
      description: ""
      operationId: ApiHistoryLimitHistoryGet
      x-api-path-slug: apihistorylimithistory-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/HotWallet/marketOrder:
    post:
      summary: Add API Hotwallet Marketorder
      description: ""
      operationId: MarketOrder
      x-api-path-slug: apihotwalletmarketorder-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SignatureVerificationToken
        description: signature verification token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/HotWallet/limitOrder:
    post:
      summary: Add API Hotwallet Limitorder
      description: ""
      operationId: LimitOrder
      x-api-path-slug: apihotwalletlimitorder-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SignatureVerificationToken
        description: signature verification token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/HotWallet/cashout:
    post:
      summary: Add API Hotwallet Cashout
      description: ""
      operationId: Cashout
      x-api-path-slug: apihotwalletcashout-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SignatureVerificationToken
        description: signature verification token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/HotWallet/addresses/{destinationAddress}/{assetId}/validity:
    get:
      summary: Get API Hotwallet Addresses Destinationaddress Asset Vality
      description: ""
      operationId: AddressValidity
      x-api-path-slug: apihotwalletaddressesdestinationaddressassetidvalidity-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: destinationAddress
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/IcoCoinsSold:
    get:
      summary: Get API Icocoinssold
      description: ""
      operationId: ApiIcoCoinsSoldGet
      x-api-path-slug: apiicocoinssold-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/InvertedAssetPairs:
    post:
      summary: Add API Invertedassetpairs
      description: ""
      operationId: ApiInvertedAssetPairsPost
      x-api-path-slug: apiinvertedassetpairs-post
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
  /api/IsAlive:
    get:
      summary: Get API Isalive
      description: ""
      operationId: ApiIsAliveGet
      x-api-path-slug: apiisalive-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/IsPinEntered:
    get:
      summary: Get API Ispinentered
      description: ""
      operationId: ApiIsPinEnteredGet
      x-api-path-slug: apiispinentered-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Issuers:
    get:
      summary: Get API Issuers
      description: ""
      operationId: ApiIssuersGet
      x-api-path-slug: apiissuers-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Issuers/{id}:
    get:
      summary: Get API Issuers
      description: ""
      operationId: ApiIssuersByIdGet
      x-api-path-slug: apiissuersid-get
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
  /api/KycDocuments:
    get:
      summary: Get API Kycdocuments
      description: ""
      operationId: ApiKycDocumentsGet
      x-api-path-slug: apikycdocuments-get
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
      summary: Add API Kycdocuments
      description: ""
      operationId: ApiKycDocumentsPost
      x-api-path-slug: apikycdocuments-post
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
  /api/KycDocumentsBin/{id}:
    get:
      summary: Get API Kycdocumentsbin
      description: ""
      operationId: ApiKycDocumentsBinByIdGet
      x-api-path-slug: apikycdocumentsbinid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: height
      - in: path
        name: id
      - in: query
        name: width
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/KycDocumentsBin:
    post:
      summary: Add API Kycdocumentsbin
      description: ""
      operationId: ApiKycDocumentsBinPost
      x-api-path-slug: apikycdocumentsbin-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: ext
      - in: query
        name: idType
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/KycDocumentUpload:
    post:
      summary: Add API Kycdocumentupload
      description: ""
      operationId: ApiKycDocumentUploadPost
      x-api-path-slug: apikycdocumentupload-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: idType
      - in: formfile
        name: photo
      - in: query
        name: type
      - in: formfile
        name: userFile
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/KycForAsset/{id}:
    get:
      summary: Get API Kycforasset
      description: ""
      operationId: ApiKycForAssetByIdGet
      x-api-path-slug: apikycforassetid-get
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
  /api/KycStatus:
    get:
      summary: Get API Kycstatus
      description: ""
      operationId: ApiKycStatusGet
      x-api-path-slug: apikycstatus-get
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
      summary: Add API Kycstatus
      description: ""
      operationId: ApiKycStatusPost
      x-api-path-slug: apikycstatus-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/LastBaseAssets:
    get:
      summary: Get API Lastbaseassets
      description: ""
      operationId: ApiLastBaseAssetsGet
      x-api-path-slug: apilastbaseassets-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: "n"
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/offchain/limit/list:
    get:
      summary: Get API Offchain Limit List
      description: ""
      operationId: ApiOffchainLimitListGet
      x-api-path-slug: apioffchainlimitlist-get
      parameters:
      - in: query
        name: assetPair
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/offchain/limit/count:
    get:
      summary: Get API Offchain Limit Count
      description: ""
      operationId: ApiOffchainLimitCountGet
      x-api-path-slug: apioffchainlimitcount-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/LykkeNews:
    get:
      summary: Get API Lykkenews
      description: ""
      operationId: ApiLykkeNewsGet
      x-api-path-slug: apilykkenews-get
      parameters:
      - in: query
        name: skip
      - in: query
        name: take
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/MarginTrading/account/balance:
    post:
      summary: Add API Margintrading Account Balance
      description: ""
      operationId: ApiMarginTradingAccountBalancePost
      x-api-path-slug: apimargintradingaccountbalance-post
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
  /api/MarginTrading/account/reset/{accountId}:
    delete:
      summary: Delete API Margintrading Account Reset Account
      description: ""
      operationId: ApiMarginTradingAccountResetByAccountIdDelete
      x-api-path-slug: apimargintradingaccountresetaccountid-delete
      parameters:
      - in: path
        name: accountId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/MarginTrading/cashOutSwift:
    post:
      summary: Add API Margintrading Cashoutswift
      description: ""
      operationId: ApiMarginTradingCashOutSwiftPost
      x-api-path-slug: apimargintradingcashoutswift-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Market/converter/tobase:
    post:
      summary: Add API Market Converter Tobase
      description: ""
      operationId: ApiMarketConverterTobasePost
      x-api-path-slug: apimarketconvertertobase-post
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
  /api/MyLykkeCashInEmail:
    post:
      summary: Add API Mylykkecashinemail
      description: ""
      operationId: ApiMyLykkeCashInEmailPost
      x-api-path-slug: apimylykkecashinemail-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: reqModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/MyLykkeInfo:
    get:
      summary: Get API Mylykkeinfo
      description: ""
      operationId: ApiMyLykkeInfoGet
      x-api-path-slug: apimylykkeinfo-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/MyLykkeSettings:
    get:
      summary: Get API Mylykkesettings
      description: ""
      operationId: ApiMyLykkeSettingsGet
      x-api-path-slug: apimylykkesettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/offchain/requests:
    get:
      summary: Get API Offchain Requests
      description: ""
      operationId: ApiOffchainRequestsGet
      x-api-path-slug: apioffchainrequests-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/offchain/trade:
    post:
      summary: Add API Offchain Trade
      description: ""
      operationId: ApiOffchainTradePost
      x-api-path-slug: apioffchaintrade-post
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
  /api/offchain/limit/trade:
    post:
      summary: Add API Offchain Limit Trade
      description: ""
      operationId: ApiOffchainLimitTradePost
      x-api-path-slug: apioffchainlimittrade-post
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
  /api/offchain/limit/cancel:
    post:
      summary: Add API Offchain Limit Cancel
      description: ""
      operationId: ApiOffchainLimitCancelPost
      x-api-path-slug: apioffchainlimitcancel-post
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
  /api/offchain/processchannel:
    post:
      summary: Add API Offchain Processchannel
      description: ""
      operationId: ApiOffchainProcesschannelPost
      x-api-path-slug: apioffchainprocesschannel-post
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
  /api/offchain/finalizetransfer:
    post:
      summary: Add API Offchain Finalizetransfer
      description: ""
      operationId: ApiOffchainFinalizetransferPost
      x-api-path-slug: apioffchainfinalizetransfer-post
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
  /api/offchain/requestTransfer:
    post:
      summary: Add API Offchain Requesttransfer
      description: ""
      operationId: ApiOffchainRequestTransferPost
      x-api-path-slug: apioffchainrequesttransfer-post
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
  /api/offchain/channelkey:
    get:
      summary: Get API Offchain Channelkey
      description: ""
      operationId: ApiOffchainChannelkeyGet
      x-api-path-slug: apioffchainchannelkey-get
      parameters:
      - in: query
        name: asset
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/offchain/transferToMargin:
    post:
      summary: Add API Offchain Transfertomargin
      description: ""
      operationId: ApiOffchainTransferToMarginPost
      x-api-path-slug: apioffchaintransfertomargin-post
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
  /api/offchain/{operationId}/transferToTrusted:
    post:
      summary: Add API Offchain Operation Transfertotrusted
      description: ""
      operationId: ApiOffchainByOperationIdTransferToTrustedPost
      x-api-path-slug: apioffchainoperationidtransfertotrusted-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/offchain/cashout:
    post:
      summary: Add API Offchain Cashout
      description: ""
      operationId: ApiOffchainCashoutPost
      x-api-path-slug: apioffchaincashout-post
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
  /api/offchain/cashout/swift:
    get:
      summary: Get API Offchain Cashout Swift
      description: ""
      operationId: ApiOffchainCashoutSwiftGet
      x-api-path-slug: apioffchaincashoutswift-get
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
      summary: Add API Offchain Cashout Swift
      description: ""
      operationId: ApiOffchainCashoutSwiftPost
      x-api-path-slug: apioffchaincashoutswift-post
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
  /api/offchain/cashout/forward:
    post:
      summary: Add API Offchain Cashout Forward
      description: ""
      operationId: ApiOffchainCashoutForwardPost
      x-api-path-slug: apioffchaincashoutforward-post
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
  /api/Operations/unsignedTransactions:
    get:
      summary: Get API Operations Unsignedtransactions
      description: ""
      operationId: ApiOperationsUnsignedTransactionsGet
      x-api-path-slug: apioperationsunsignedtransactions-get
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
      summary: Add API Operations Unsignedtransactions
      description: ""
      operationId: ApiOperationsUnsignedTransactionsPost
      x-api-path-slug: apioperationsunsignedtransactions-post
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
  /api/Operations/list/{status}:
    get:
      summary: Get API Operations List Status
      description: ""
      operationId: ApiOperationsListByStatusGet
      x-api-path-slug: apioperationsliststatus-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: status
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Operations/{id}:
    get:
      summary: Get API Operations
      description: ""
      operationId: ApiOperationsByIdGet
      x-api-path-slug: apioperationsid-get
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
  /api/Operations/{id}/cancel:
    post:
      summary: Add API Operations  Cancel
      description: ""
      operationId: ApiOperationsByIdCancelPost
      x-api-path-slug: apioperationsidcancel-post
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
  /api/Operations/cancel:
    post:
      summary: Add API Operations Cancel
      description: ""
      operationId: ApiOperationsCancelPost
      x-api-path-slug: apioperationscancel-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/OrderBook/{id}:
    get:
      summary: Get API Orderbook
      description: ""
      operationId: ApiOrderBookByIdGet
      x-api-path-slug: apiorderbookid-get
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
  /api/PersonalData:
    get:
      summary: Get API Personaldata
      description: ""
      operationId: ApiPersonalDataGet
      x-api-path-slug: apipersonaldata-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/PinSecurity:
    get:
      summary: Get API Pinsecurity
      description: ""
      operationId: ApiPinSecurityGet
      x-api-path-slug: apipinsecurity-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: pin
      responses:
        200:
          description: OK
      tags:
      - ""
    post:
      summary: Add API Pinsecurity
      description: ""
      operationId: ApiPinSecurityPost
      x-api-path-slug: apipinsecurity-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/PrivateKeyOwnershipMsg:
    get:
      summary: Get API Privatekeyownershipmsg
      description: ""
      operationId: ApiPrivateKeyOwnershipMsgGet
      x-api-path-slug: apiprivatekeyownershipmsg-get
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
    post:
      summary: Add API Privatekeyownershipmsg
      description: ""
      operationId: ApiPrivateKeyOwnershipMsgPost
      x-api-path-slug: apiprivatekeyownershipmsg-post
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
  /api/PrivateWallet:
    get:
      summary: Get API Privatewallet
      description: ""
      operationId: ApiPrivateWalletGet
      x-api-path-slug: apiprivatewallet-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
    put:
      summary: Put API Privatewallet
      description: ""
      operationId: ApiPrivateWalletPut
      x-api-path-slug: apiprivatewallet-put
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: editModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
    post:
      summary: Add API Privatewallet
      description: ""
      operationId: ApiPrivateWalletPost
      x-api-path-slug: apiprivatewallet-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: createWalletModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
    delete:
      summary: Delete API Privatewallet
      description: ""
      operationId: ApiPrivateWalletDelete
      x-api-path-slug: apiprivatewallet-delete
      parameters:
      - in: query
        name: address
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/PrivateWallet/{id}:
    get:
      summary: Get API Privatewallet
      description: ""
      operationId: ApiPrivateWalletByIdGet
      x-api-path-slug: apiprivatewalletid-get
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
  /api/PrivateWallet/key:
    post:
      summary: Add API Privatewallet Key
      description: ""
      operationId: ApiPrivateWalletKeyPost
      x-api-path-slug: apiprivatewalletkey-post
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
  /api/PrivateWalletBackup:
    post:
      summary: Add API Privatewalletbackup
      description: ""
      operationId: ApiPrivateWalletBackupPost
      x-api-path-slug: apiprivatewalletbackup-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: backupModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/PrivateWalletBalance:
    get:
      summary: Get API Privatewalletbalance
      description: ""
      operationId: ApiPrivateWalletBalanceGet
      x-api-path-slug: apiprivatewalletbalance-get
      parameters:
      - in: query
        name: address
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/PrivateWalletHistory:
    get:
      summary: Get API Privatewallethistory
      description: ""
      operationId: ApiPrivateWalletHistoryGet
      x-api-path-slug: apiprivatewallethistory-get
      parameters:
      - in: query
        name: address
      - in: query
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/PubkeyAddressValidation:
    get:
      summary: Get API Pubkeyaddressvalation
      description: ""
      operationId: ApiPubkeyAddressValidationGet
      x-api-path-slug: apipubkeyaddressvalidation-get
      parameters:
      - in: query
        name: pubkeyAddress
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/PurchaseAsset:
    post:
      summary: Add API Purchaseasset
      description: ""
      operationId: ApiPurchaseAssetPost
      x-api-path-slug: apipurchaseasset-post
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
  /api/PushSettings:
    get:
      summary: Get API Pushsettings
      description: ""
      operationId: ApiPushSettingsGet
      x-api-path-slug: apipushsettings-get
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
      summary: Add API Pushsettings
      description: ""
      operationId: ApiPushSettingsPost
      x-api-path-slug: apipushsettings-post
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
  /api/RecoverySmsConfirmation:
    post:
      summary: Add API Recoverysmsconfirmation
      description: ""
      operationId: ApiRecoverySmsConfirmationPost
      x-api-path-slug: apirecoverysmsconfirmation-post
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
  /api/RefundAddress:
    get:
      summary: Get API Refundaddress
      description: ""
      operationId: ApiRefundAddressGet
      x-api-path-slug: apirefundaddress-get
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
      summary: Add API Refundaddress
      description: ""
      operationId: ApiRefundAddressPost
      x-api-path-slug: apirefundaddress-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: refundAddressModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/RefundSettings:
    get:
      summary: Get API Refundsettings
      description: ""
      operationId: ApiRefundSettingsGet
      x-api-path-slug: apirefundsettings-get
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
      summary: Add API Refundsettings
      description: ""
      operationId: ApiRefundSettingsPost
      x-api-path-slug: apirefundsettings-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: refundAddressModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Registration:
    get:
      summary: Get API Registration
      description: ""
      operationId: ApiRegistrationGet
      x-api-path-slug: apiregistration-get
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
      summary: Add API Registration
      description: ""
      operationId: ApiRegistrationPost
      x-api-path-slug: apiregistration-post
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
  /api/RemindPasswordEmail:
    post:
      summary: Add API Remindpasswordemail
      description: ""
      operationId: ApiRemindPasswordEmailPost
      x-api-path-slug: apiremindpasswordemail-post
      parameters:
      - in: body
        name: reqModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/RequestVoiceCall:
    post:
      summary: Add API Requestvoicecall
      description: ""
      operationId: ApiRequestVoiceCallPost
      x-api-path-slug: apirequestvoicecall-post
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
  /api/RestrictedCountries:
    get:
      summary: Get API Restrictedcountries
      description: ""
      operationId: ApiRestrictedCountriesGet
      x-api-path-slug: apirestrictedcountries-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/SendBlockchainEmail:
    post:
      summary: Add API Sendblockchainemail
      description: ""
      operationId: ApiSendBlockchainEmailPost
      x-api-path-slug: apisendblockchainemail-post
      parameters:
      - in: query
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/ServerTime:
    get:
      summary: Get API Servertime
      description: ""
      operationId: ApiServerTimeGet
      x-api-path-slug: apiservertime-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/SettingSignOrder:
    post:
      summary: Add API Settingsignorder
      description: ""
      operationId: ApiSettingSignOrderPost
      x-api-path-slug: apisettingsignorder-post
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
  /api/signatureVerificationToken/KeyConfirmation:
    get:
      summary: Get API Signatureverificationtoken Keyconfirmation
      description: ""
      operationId: ApiSignatureVerificationTokenKeyConfirmationGet
      x-api-path-slug: apisignatureverificationtokenkeyconfirmation-get
      parameters:
      - in: query
        name: email
      responses:
        200:
          description: OK
      tags:
      - ""
    post:
      summary: Add API Signatureverificationtoken Keyconfirmation
      description: ""
      operationId: ApiSignatureVerificationTokenKeyConfirmationPost
      x-api-path-slug: apisignatureverificationtokenkeyconfirmation-post
      parameters:
      - in: body
        name: response
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/SignRequest:
    get:
      summary: Get API Signrequest
      description: ""
      operationId: ApiSignRequestGet
      x-api-path-slug: apisignrequest-get
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
      summary: Add API Signrequest
      description: ""
      operationId: ApiSignRequestPost
      x-api-path-slug: apisignrequest-post
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
  /api/SwiftCredentials/{assetId}:
    get:
      summary: Get API Swiftcredentials Asset
      description: ""
      operationId: ApiSwiftCredentialsByAssetIdGet
      x-api-path-slug: apiswiftcredentialsassetid-get
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
  /api/SwiftCredentials:
    get:
      summary: Get API Swiftcredentials
      description: ""
      operationId: ApiSwiftCredentialsGet
      x-api-path-slug: apiswiftcredentials-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Transactions:
    get:
      summary: Get API Transactions
      description: ""
      operationId: ApiTransactionsGet
      x-api-path-slug: apitransactions-get
      parameters:
      - in: query
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/TransferInfo:
    get:
      summary: Get API Transferinfo
      description: ""
      operationId: ApiTransferInfoGet
      x-api-path-slug: apitransferinfo-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: transferId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/TrustedWallets/{operationId}/transfer:
    post:
      summary: Add API Trustedwallets Operation Transfer
      description: ""
      operationId: Transfer
      x-api-path-slug: apitrustedwalletsoperationidtransfer-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Utils/isUSorCanadaNumber/{phoneNumber}:
    get:
      summary: Get API Utils Isusorcanadanumber Phonenumber
      description: ""
      operationId: ApiUtilsIsUSorCanadaNumberByPhoneNumberGet
      x-api-path-slug: apiutilsisusorcanadanumberphonenumber-get
      parameters:
      - in: path
        name: phoneNumber
      responses:
        200:
          description: OK
      tags:
      - ""
  /home/Version:
    get:
      summary: Get Home Version
      description: ""
      operationId: HomeVersionGet
      x-api-path-slug: homeversion-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/WalletMigration:
    post:
      summary: Add API Walletmigration
      description: ""
      operationId: ApiWalletMigrationPost
      x-api-path-slug: apiwalletmigration-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Wallets:
    get:
      summary: Get API Wallets
      description: ""
      operationId: ApiWalletsGet
      x-api-path-slug: apiwallets-get
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
      summary: Add API Wallets
      description: ""
      operationId: ApiWalletsPost
      x-api-path-slug: apiwallets-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/Wallets/{id}:
    get:
      summary: Get API Wallets
      description: ""
      operationId: ApiWalletsByIdGet
      x-api-path-slug: apiwalletsid-get
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
  /api/Wallets/depositaddress/{assetId}:
    post:
      summary: Add API Wallets Depositaddress Asset
      description: ""
      operationId: ApiWalletsDepositaddressByAssetIdPost
      x-api-path-slug: apiwalletsdepositaddressassetid-post
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
  /api/WatchLists:
    get:
      summary: Get API Watchlists
      description: ""
      operationId: ApiWatchListsGet
      x-api-path-slug: apiwatchlists-get
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
      summary: Add API Watchlists
      description: ""
      operationId: ApiWatchListsPost
      x-api-path-slug: apiwatchlists-post
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
  /api/WatchLists/{id}:
    get:
      summary: Get API Watchlists
      description: ""
      operationId: ApiWatchListsByIdGet
      x-api-path-slug: apiwatchlistsid-get
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
    put:
      summary: Put API Watchlists
      description: ""
      operationId: ApiWatchListsByIdPut
      x-api-path-slug: apiwatchlistsid-put
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""
    delete:
      summary: Delete API Watchlists
      description: ""
      operationId: ApiWatchListsByIdDelete
      x-api-path-slug: apiwatchlistsid-delete
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
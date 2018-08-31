---
swagger: "2.0"
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/PushSettings:
    get:
      summary: Get API Pushsettings
      description: ""
      operationId: ApiPushSettingsGet
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - ""
definitions:
  ResponseModel[AccountExistResultModel]:
    properties: []
  AccountExistResultModel:
    properties:
      IsEmailRegistered:
        description: This is a default description.
        type: delete
  ErrorModel:
    properties:
      Code:
        description: This is a default description.
        type: delete
      Field:
        description: This is a default description.
        type: delete
      Message:
        description: This is a default description.
        type: delete
      Details:
        description: This is a default description.
        type: delete
  ResponseModel[AssetDescriptionModel]:
    properties: []
  AssetDescriptionModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      AssetClass:
        description: This is a default description.
        type: delete
      PopIndex:
        description: This is a default description.
        type: delete
      Description:
        description: This is a default description.
        type: delete
      IssuerName:
        description: This is a default description.
        type: delete
      NumberOfCoins:
        description: This is a default description.
        type: delete
      MarketCapitalization:
        description: This is a default description.
        type: delete
      AssetDescriptionUrl:
        description: This is a default description.
        type: delete
      FullName:
        description: This is a default description.
        type: delete
  ResponseModel[GetAllAssetPairsRatesModel]:
    properties: []
  GetAllAssetPairsRatesModel:
    properties:
      Rates:
        description: This is a default description.
        type: delete
  ApiAssetPairRateBaseModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Bid:
        description: This is a default description.
        type: delete
      Ask:
        description: This is a default description.
        type: delete
  ResponseModel[GetSingleAssetPairRateModel]:
    properties: []
  GetSingleAssetPairRateModel:
    properties: []
  ResponseModel[GetAssetPairsResponseModel]:
    properties: []
  GetAssetPairsResponseModel:
    properties:
      AssetPairs:
        description: This is a default description.
        type: delete
  ApiAssetPairModel:
    properties:
      Group:
        description: This is a default description.
        type: delete
      Id:
        description: This is a default description.
        type: delete
      Name:
        description: This is a default description.
        type: delete
      Accuracy:
        description: This is a default description.
        type: delete
      InvertedAccuracy:
        description: This is a default description.
        type: delete
      BaseAssetId:
        description: This is a default description.
        type: delete
      QuotingAssetId:
        description: This is a default description.
        type: delete
      Inverted:
        description: This is a default description.
        type: delete
      MinVolume:
        description: This is a default description.
        type: delete
      MinInvertedVolume:
        description: This is a default description.
        type: delete
  ResponseModel[GetAssetPairResponseModel]:
    properties: []
  GetAssetPairResponseModel:
    properties: []
  ResponseModel[ApplicationInfoResponseModel]:
    properties: []
  ApplicationInfoResponseModel:
    properties:
      AppVersion:
        description: This is a default description.
        type: delete
      CountryPhoneCodesLastModified:
        description: This is a default description.
        type: delete
      TermsOfUseLink:
        description: This is a default description.
        type: delete
      InformationBrochureLink:
        description: This is a default description.
        type: delete
      RefundInfoLink:
        description: This is a default description.
        type: delete
      SupportPhoneNum:
        description: This is a default description.
        type: delete
      UserAgreementUrl:
        description: This is a default description.
        type: delete
  MarginSettings:
    properties:
      ApiUrl:
        description: This is a default description.
        type: delete
      WampHost:
        description: This is a default description.
        type: delete
  ResponseModel[ApiAppSettingsModel]:
    properties: []
  ApiAppSettingsModel:
    properties:
      RateRefreshPeriod:
        description: This is a default description.
        type: delete
      SignOrder:
        description: This is a default description.
        type: delete
      DepositUrl:
        description: This is a default description.
        type: delete
      DebugMode:
        description: This is a default description.
        type: delete
      MarketOrderPriceDeviation:
        description: This is a default description.
        type: delete
  ApiAssetModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Name:
        description: This is a default description.
        type: delete
      Accuracy:
        description: This is a default description.
        type: delete
      Symbol:
        description: This is a default description.
        type: delete
      HideWithdraw:
        description: This is a default description.
        type: delete
      HideDeposit:
        description: This is a default description.
        type: delete
      KycNeeded:
        description: This is a default description.
        type: delete
      BankCardsDepositEnabled:
        description: This is a default description.
        type: delete
      SwiftDepositEnabled:
        description: This is a default description.
        type: delete
      BlockchainDepositEnabled:
        description: This is a default description.
        type: delete
  ApiRefundSettings:
    properties:
      Address:
        description: This is a default description.
        type: delete
  ApiFeeSettings:
    properties:
      BankCardsFeeSizePercentage:
        description: This is a default description.
        type: delete
      CashOut:
        description: This is a default description.
        type: delete
  CashOutFee:
    properties:
      AssetId:
        description: This is a default description.
        type: delete
      Size:
        description: This is a default description.
        type: delete
      Type:
        description: This is a default description.
        type: delete
  ResponseModel[GetAssetCategoriesResponseModel]:
    properties: []
  GetAssetCategoriesResponseModel:
    properties:
      AssetCategories:
        description: This is a default description.
        type: delete
  ApiAssetCategoryModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Name:
        description: This is a default description.
        type: delete
      IosIconUrl:
        description: This is a default description.
        type: delete
      AndroidIconUrl:
        description: This is a default description.
        type: delete
  ResponseModel[AssetDisclaimerResponceModel]:
    properties: []
  AssetDisclaimerResponceModel:
    properties:
      Disclaimers:
        description: This is a default description.
        type: delete
  AssetDisclaimerModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Text:
        description: This is a default description.
        type: delete
  ResponseModel:
    properties: []
  ResponseModel[GetAssetPairDetailedRateModel]:
    properties: []
  GetAssetPairDetailedRateModel:
    properties:
      FixingTime:
        description: This is a default description.
        type: delete
      LastPrice:
        description: This is a default description.
        type: delete
      StartTime:
        description: This is a default description.
        type: delete
      EndTime:
        description: This is a default description.
        type: delete
  AssetPairDetailedRateModel:
    properties:
      PChange:
        description: This is a default description.
        type: delete
      PChangeBid:
        description: This is a default description.
        type: delete
      ChngGrph:
        description: This is a default description.
        type: delete
      AskBidGraph:
        description: This is a default description.
        type: delete
      Inverted:
        description: This is a default description.
        type: delete
  AskBid:
    properties:
      A:
        description: This is a default description.
        type: delete
      B:
        description: This is a default description.
        type: delete
  ResponseModel[GetAssetPairsRatesModel]:
    properties: []
  GetAssetPairsRatesModel:
    properties:
      Rates:
        description: This is a default description.
        type: delete
  ApiAssetPairRateModel:
    properties:
      PChng:
        description: This is a default description.
        type: delete
      ChngGrph:
        description: This is a default description.
        type: delete
      Inverted:
        description: This is a default description.
        type: delete
      Id:
        description: This is a default description.
        type: delete
      Bid:
        description: This is a default description.
        type: delete
      Ask:
        description: This is a default description.
        type: delete
  ResponseModel[GetAssetPairRateModel]:
    properties: []
  GetAssetPairRateModel:
    properties: []
  ResponseModel[GetBaseAssetsRespModel]:
    properties: []
  GetBaseAssetsRespModel:
    properties:
      Assets:
        description: This is a default description.
        type: delete
  ResponseModel[GetClientBaseAssetRespModel]:
    properties: []
  GetClientBaseAssetRespModel:
    properties: []
  GetAssetDescriptionsListModel:
    properties:
      Ids:
        description: This is a default description.
        type: delete
  ResponseModel[AssetDescriptionsListModel]:
    properties: []
  AssetDescriptionsListModel:
    properties:
      Descriptions:
        description: This is a default description.
        type: delete
  ResponseModel[AssetAttributesModel]:
    properties: []
  AssetAttributesModel:
    properties:
      Pairs:
        description: This is a default description.
        type: delete
  AssetAttribute:
    properties:
      Key:
        description: This is a default description.
        type: delete
      Value:
        description: This is a default description.
        type: delete
  ResponseModel[AssetAttribute]:
    properties: []
  AuthenticateModel:
    properties:
      Email:
        description: This is a default description.
        type: delete
      Password:
        description: This is a default description.
        type: delete
      ClientInfo:
        description: This is a default description.
        type: delete
      PartnerId:
        description: This is a default description.
        type: delete
  ResponseModel[AuthenticateResponseModel]:
    properties: []
  AuthenticateResponseModel:
    properties:
      KycStatus:
        description: This is a default description.
        type: delete
      PinIsEntered:
        description: This is a default description.
        type: delete
      Token:
        description: This is a default description.
        type: delete
      NotificationsId:
        description: This is a default description.
        type: delete
      CanCashInViaBankCard:
        description: This is a default description.
        type: delete
      SwiftDepositEnabled:
        description: This is a default description.
        type: delete
      IsUserFromUSA:
        description: This is a default description.
        type: delete
  ApiPersonalDataModel:
    properties:
      FullName:
        description: This is a default description.
        type: delete
      FirstName:
        description: This is a default description.
        type: delete
      LastName:
        description: This is a default description.
        type: delete
      Email:
        description: This is a default description.
        type: delete
      Phone:
        description: This is a default description.
        type: delete
      Country:
        description: This is a default description.
        type: delete
      Address:
        description: This is a default description.
        type: delete
      City:
        description: This is a default description.
        type: delete
      Zip:
        description: This is a default description.
        type: delete
  BankCardPaymentUrlInputModel:
    properties:
      Amount:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
      FirstName:
        description: This is a default description.
        type: delete
      LastName:
        description: This is a default description.
        type: delete
      City:
        description: This is a default description.
        type: delete
      Zip:
        description: This is a default description.
        type: delete
      Address:
        description: This is a default description.
        type: delete
      Country:
        description: This is a default description.
        type: delete
      Email:
        description: This is a default description.
        type: delete
      Phone:
        description: This is a default description.
        type: delete
  ResponseModel[BankCardPaymentUrlResponceModel]:
    properties: []
  BankCardPaymentUrlResponceModel:
    properties:
      Url:
        description: This is a default description.
        type: delete
      OkUrl:
        description: This is a default description.
        type: delete
      FailUrl:
        description: This is a default description.
        type: delete
      ReloadRegex:
        description: This is a default description.
        type: delete
      UrlsToFormatRegex:
        description: This is a default description.
        type: delete
  ResponseModel[BankCardPaymentUrlInputModel]:
    properties: []
  TransferReqModel:
    properties:
      AssetId:
        description: This is a default description.
        type: delete
      BalanceChange:
        description: This is a default description.
        type: delete
  PostClientBaseCurrencyModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
  ResponseModel[BlockchainTransactionRespModel]:
    properties: []
  BlockchainTransactionRespModel:
    properties: []
  ApiBlockchainTransaction:
    properties:
      Hash:
        description: This is a default description.
        type: delete
      Date:
        description: This is a default description.
        type: delete
      Confirmations:
        description: This is a default description.
        type: delete
      Block:
        description: This is a default description.
        type: delete
      Height:
        description: This is a default description.
        type: delete
      SenderId:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
      Quantity:
        description: This is a default description.
        type: delete
      Url:
        description: This is a default description.
        type: delete
  ResponseModel[BccMultisigTransactionResponseModel]:
    properties: []
  BccMultisigTransactionResponseModel:
    properties:
      ClientAmount:
        description: This is a default description.
        type: delete
      HubAmount:
        description: This is a default description.
        type: delete
      ClientFee:
        description: This is a default description.
        type: delete
      Transaction:
        description: This is a default description.
        type: delete
      Inputs:
        description: This is a default description.
        type: delete
  ResponseModel[BccTransactionResponseModel]:
    properties: []
  BccTransactionResponseModel:
    properties:
      Transaction:
        description: This is a default description.
        type: delete
      Inputs:
        description: This is a default description.
        type: delete
  ResponseModel[BccPrivateBalanceModel]:
    properties: []
  BccPrivateBalanceModel:
    properties:
      Balance:
        description: This is a default description.
        type: delete
      Fee:
        description: This is a default description.
        type: delete
  BccBroadcastRequest:
    properties:
      Transaction:
        description: This is a default description.
        type: delete
  ResponseModel[BccBroadcastResponseModel]:
    properties: []
  BccBroadcastResponseModel:
    properties:
      TransactionHash:
        description: This is a default description.
        type: delete
  ApiTransaction:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Hex:
        description: This is a default description.
        type: delete
  CashOutPostModel:
    properties:
      MultiSig:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
  SwiftCashOutReqModel:
    properties:
      AssetId:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
      Bic:
        description: This is a default description.
        type: delete
      AccNumber:
        description: This is a default description.
        type: delete
      AccName:
        description: This is a default description.
        type: delete
      AccHolderAddress:
        description: This is a default description.
        type: delete
      BankName:
        description: This is a default description.
        type: delete
      AccHolderCountry:
        description: This is a default description.
        type: delete
      AccHolderZipCode:
        description: This is a default description.
        type: delete
      AccHolderCity:
        description: This is a default description.
        type: delete
  PostChangePinAndPasswordModel:
    properties:
      PartnerId:
        description: This is a default description.
        type: delete
      Email:
        description: This is a default description.
        type: delete
      SignedOwnershipMsg:
        description: This is a default description.
        type: delete
      SmsCode:
        description: This is a default description.
        type: delete
      NewPin:
        description: This is a default description.
        type: delete
      NewPassword:
        description: This is a default description.
        type: delete
      NewHint:
        description: This is a default description.
        type: delete
      EncodedPrivateKey:
        description: This is a default description.
        type: delete
  ResponseModel[CheckDocumentsToUploadModel]:
    properties: []
  CheckDocumentsToUploadModel:
    properties:
      IdCard:
        description: This is a default description.
        type: delete
      ProofOfAddress:
        description: This is a default description.
        type: delete
      Selfie:
        description: This is a default description.
        type: delete
  ResponseModel[CheckMobilePhoneResultModel]:
    properties: []
  CheckMobilePhoneResultModel:
    properties:
      Passed:
        description: This is a default description.
        type: delete
  PostClientPhoneModel:
    properties:
      PhoneNumber:
        description: This is a default description.
        type: delete
  SubmitCodeModel:
    properties:
      Code:
        description: This is a default description.
        type: delete
  ResponseModel[AccessTokenModel]:
    properties: []
  AccessTokenModel:
    properties:
      AccessToken:
        description: This is a default description.
        type: delete
  ResponseModel[EncodedKeyModel]:
    properties: []
  EncodedKeyModel:
    properties:
      EncodedPrivateKey:
        description: This is a default description.
        type: delete
  ResponseModel[ClientBalancesModel]:
    properties: []
  ClientBalancesModel:
    properties:
      TradingWallet:
        description: This is a default description.
        type: delete
      PrivateWallets:
        description: This is a default description.
        type: delete
      MarginWallets:
        description: This is a default description.
        type: delete
  ResponseModel[IKeyValue]:
    properties: []
  IKeyValue:
    properties:
      Key:
        description: This is a default description.
        type: delete
      Value:
        description: This is a default description.
        type: delete
  KeyValue:
    properties:
      Key:
        description: This is a default description.
        type: delete
      Value:
        description: This is a default description.
        type: delete
  ResponseModel[IsUserFromUSModel]:
    properties: []
  IsUserFromUSModel:
    properties:
      IsUserFromUS:
        description: This is a default description.
        type: delete
  SetIsUserFromUSModel:
    properties:
      IsUserFromUS:
        description: This is a default description.
        type: delete
  ResponseModel[PendingActionsModel]:
    properties: []
  PendingActionsModel:
    properties:
      UnsignedTxs:
        description: This is a default description.
        type: delete
      OffchainRequests:
        description: This is a default description.
        type: delete
      NeedReinit:
        description: This is a default description.
        type: delete
      DialogPending:
        description: This is a default description.
        type: delete
      PendingOperations:
        description: This is a default description.
        type: delete
      EthereumPendingActions:
        description: This is a default description.
        type: delete
  PostClientFirstNameLastNameModel:
    properties:
      FirstName:
        description: This is a default description.
        type: delete
      LastName:
        description: This is a default description.
        type: delete
  PostClientFullNameModel:
    properties:
      FullName:
        description: This is a default description.
        type: delete
  ClientKeysModel:
    properties:
      PubKey:
        description: This is a default description.
        type: delete
      EncodedPrivateKey:
        description: This is a default description.
        type: delete
      PrivateKey:
        description: This is a default description.
        type: delete
      TempKey:
        description: This is a default description.
        type: delete
  WriteClientLogModel:
    properties:
      Data:
        description: This is a default description.
        type: delete
  ResponseModel[ClientStateModel]:
    properties: []
  ClientStateModel:
    properties:
      IsRegistered:
        description: This is a default description.
        type: delete
      HasPwdHint:
        description: This is a default description.
        type: delete
      HasBackup:
        description: This is a default description.
        type: delete
      IsPwdHashed:
        description: This is a default description.
        type: delete
      KycStatus:
        description: This is a default description.
        type: delete
      CanCashInViaBankCard:
        description: This is a default description.
        type: delete
      SwiftDepositEnabled:
        description: This is a default description.
        type: delete
      MarginTrading:
        description: This is a default description.
        type: delete
      IsOffchain:
        description: This is a default description.
        type: delete
      MarginTradingLive:
        description: This is a default description.
        type: delete
  IcoSettings:
    properties:
      IsEnabled:
        description: This is a default description.
        type: delete
      ShowBanner:
        description: This is a default description.
        type: delete
  ResponseModel[TermsOfUseModel]:
    properties: []
  TermsOfUseModel:
    properties:
      SpotTermsOfUseLink:
        description: This is a default description.
        type: delete
      MarginTermsOfUseLink:
        description: This is a default description.
        type: delete
      MarginRiskDescriptionLink:
        description: This is a default description.
        type: delete
  ResponseModel[CountriesResponseModel]:
    properties: []
  CountriesResponseModel:
    properties:
      Current:
        description: This is a default description.
        type: delete
      CountriesList:
        description: This is a default description.
        type: delete
  CountryItem:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Iso2:
        description: This is a default description.
        type: delete
      Name:
        description: This is a default description.
        type: delete
      Prefix:
        description: This is a default description.
        type: delete
  ResponseModel[ClientDialogsModel]:
    properties: []
  ClientDialogsModel:
    properties:
      Dialogs:
        description: This is a default description.
        type: delete
  ClientDialog:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Type:
        description: This is a default description.
        type: delete
      Caption:
        description: This is a default description.
        type: delete
      Text:
        description: This is a default description.
        type: delete
      Buttons:
        description: This is a default description.
        type: delete
  ClientDialogButtonModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      PinRequired:
        description: This is a default description.
        type: delete
      Text:
        description: This is a default description.
        type: delete
  ClientDialogSubmitModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      ButtonId:
        description: This is a default description.
        type: delete
  ResponseModel[IKeyValue[]]:
    properties:
      Result:
        description: This is a default description.
        type: delete
  ResponseModel[ObsoletteDictsRespModel]:
    properties: []
  ObsoletteDictsRespModel:
    properties:
      Assets:
        description: This is a default description.
        type: delete
  ObsoleteApiDictAsset:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Name:
        description: This is a default description.
        type: delete
      Accuracy:
        description: This is a default description.
        type: delete
      IssuerId:
        description: This is a default description.
        type: delete
  ResponseModel[AssetDictRespModel]:
    properties: []
  AssetDictRespModel:
    properties:
      Assets:
        description: This is a default description.
        type: delete
  ApiDictAsset:
    properties:
      Id:
        description: This is a default description.
        type: delete
      BlockchainId:
        description: This is a default description.
        type: delete
      Name:
        description: This is a default description.
        type: delete
      Symbol:
        description: This is a default description.
        type: delete
      IdIssuer:
        description: This is a default description.
        type: delete
      Accuracy:
        description: This is a default description.
        type: delete
      HideWithdraw:
        description: This is a default description.
        type: delete
      HideDeposit:
        description: This is a default description.
        type: delete
      DefaultOrder:
        description: This is a default description.
        type: delete
      KycNeeded:
        description: This is a default description.
        type: delete
  ResponseModel[DictionariesUpdatesRespModel]:
    properties: []
  DictionariesUpdatesRespModel:
    properties:
      AssetsUpd:
        description: This is a default description.
        type: delete
  WalletAddressModel:
    properties:
      Address:
        description: This is a default description.
        type: delete
      WalletName:
        description: This is a default description.
        type: delete
  PostEmailMeRequestModel:
    properties:
      AssetId:
        description: This is a default description.
        type: delete
      BcnAddress:
        description: This is a default description.
        type: delete
  ResponseModel[EmailVerificationModel]:
    properties: []
  EmailVerificationModel:
    properties:
      Passed:
        description: This is a default description.
        type: delete
  PostEmailModel:
    properties:
      Email:
        description: This is a default description.
        type: delete
      PartnerId:
        description: This is a default description.
        type: delete
  EncodedPrivateKeysModel:
    properties:
      Password:
        description: This is a default description.
        type: delete
  ResponseModel[PostEncodedPrivateKeyResponseModel]:
    properties: []
  PostEncodedPrivateKeyResponseModel:
    properties:
      EncodedPrivateKey:
        description: This is a default description.
        type: delete
  EthereumTransferModel:
    properties:
      Sign:
        description: This is a default description.
        type: delete
  ResponseModel[EthereumSuccessTradeRespModel]:
    properties: []
  EthereumSuccessTradeRespModel:
    properties: []
  ApiEthereumOrder:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      OrderType:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      TotalCost:
        description: This is a default description.
        type: delete
  EthereumTradeModel:
    properties: []
  EthereumTransactionModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Sign:
        description: This is a default description.
        type: delete
  EthereumCashOutModel:
    properties:
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
  ResponseModel[EthereumEmptyTransactionModel]:
    properties: []
  EthereumEmptyTransactionModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Hash:
        description: This is a default description.
        type: delete
  ResponseModel[EthereumEmptyTransactionModelContainer]:
    properties: []
  EthereumEmptyTransactionModelContainer:
    properties:
      Transfers:
        description: This is a default description.
        type: delete
  EthereumTransactionModelContainer:
    properties:
      Transfers:
        description: This is a default description.
        type: delete
  EthOperationModel:
    properties:
      AssetPair:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      AddressTo:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      IsLimit:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
  GenerateTransferTransactionForEthereumModel:
    properties:
      GasPrice:
        description: This is a default description.
        type: delete
      GasAmount:
        description: This is a default description.
        type: delete
      SourceAddress:
        description: This is a default description.
        type: delete
      DestinationAddress:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
  ResponseModel[EthTransaction]:
    properties: []
  EthTransaction:
    properties:
      From:
        description: This is a default description.
        type: delete
      Hex:
        description: This is a default description.
        type: delete
  ResponseModel[TransactionHashModel]:
    properties: []
  TransactionHashModel:
    properties:
      TransactionHash:
        description: This is a default description.
        type: delete
  ResponseModel[ExecutionEstimationResponse]:
    properties: []
  ExecutionEstimationResponse:
    properties:
      GasAmount:
        description: This is a default description.
        type: delete
      WouldFail:
        description: This is a default description.
        type: delete
  ResponseModel[EthBalance]:
    properties: []
  EthBalance:
    properties:
      Amount:
        description: This is a default description.
        type: delete
  ResponseModel[EthereumTransactionResponseContainer]:
    properties: []
  EthereumTransactionResponseContainer:
    properties:
      Messages:
        description: This is a default description.
        type: delete
      ErcTransfers:
        description: This is a default description.
        type: delete
  EthereumTransactionHistoricalResponse:
    properties:
      TransactionIndex:
        description: This is a default description.
        type: delete
      BlockNumber:
        description: This is a default description.
        type: delete
      Gas:
        description: This is a default description.
        type: delete
      GasPrice:
        description: This is a default description.
        type: delete
      Value:
        description: This is a default description.
        type: delete
      Nonce:
        description: This is a default description.
        type: delete
      TransactionHash:
        description: This is a default description.
        type: delete
      BlockHash:
        description: This is a default description.
        type: delete
      From:
        description: This is a default description.
        type: delete
      To:
        description: This is a default description.
        type: delete
  EthereumInternalMessageHistoricalResponse:
    properties:
      TransactionHash:
        description: This is a default description.
        type: delete
      BlockNumber:
        description: This is a default description.
        type: delete
      FromAddress:
        description: This is a default description.
        type: delete
      ToAddress:
        description: This is a default description.
        type: delete
      Depth:
        description: This is a default description.
        type: delete
      Value:
        description: This is a default description.
        type: delete
      MessageIndex:
        description: This is a default description.
        type: delete
      Type:
        description: This is a default description.
        type: delete
      BlockTimeUtc:
        description: This is a default description.
        type: delete
      BlockTimestamp:
        description: This is a default description.
        type: delete
  ErcEthPrivateWalletHistoryRecord:
    properties: []
  EthPrivateWalletHistoryRecord:
    properties:
      FromAddress:
        description: This is a default description.
        type: delete
      ToAddress:
        description: This is a default description.
        type: delete
      ContractAddress:
        description: This is a default description.
        type: delete
      TransactionStatus:
        description: This is a default description.
        type: delete
      Fee:
        description: This is a default description.
        type: delete
      Value:
        description: This is a default description.
        type: delete
      TransactionHash:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
  ResponseModel[EthereumPrivateWalletHistory]:
    properties: []
  EthereumPrivateWalletHistory:
    properties:
      History:
        description: This is a default description.
        type: delete
  ResponseModel[EthereumAssetResponse]:
    properties: []
  EthereumAssetResponse:
    properties:
      StepsCount:
        description: This is a default description.
        type: delete
      EthAssetId:
        description: This is a default description.
        type: delete
      StepGas:
        description: This is a default description.
        type: delete
  ResponseModel[ApiMarketOrder]:
    properties: []
  ApiMarketOrder:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      OrderType:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
      BaseAsset:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      TotalCost:
        description: This is a default description.
        type: delete
      Comission:
        description: This is a default description.
        type: delete
      Position:
        description: This is a default description.
        type: delete
  CreditVoucherContent:
    properties:
      ContentBase64:
        description: This is a default description.
        type: delete
      Url:
        description: This is a default description.
        type: delete
  ResponseModel[CreditVoucherFormattedContent]:
    properties: []
  CreditVoucherFormattedContent:
    properties:
      FormattedContentBase64:
        description: This is a default description.
        type: delete
  ForwardWithdrawalModel:
    properties:
      AssetId:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
  GenerateTransferTransactionModel:
    properties:
      SourceAddress:
        description: This is a default description.
        type: delete
      DestinationAddress:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
  ResponseModel[ApiTransaction]:
    properties: []
  ResponseModel[GetGraphPeriodsRespModel]:
    properties: []
  GetGraphPeriodsRespModel:
    properties:
      AvailablePeriods:
        description: This is a default description.
        type: delete
  GraphPeriod:
    properties:
      Name:
        description: This is a default description.
        type: delete
      Value:
        description: This is a default description.
        type: delete
  PasswordHashModel:
    properties:
      PwdHash:
        description: This is a default description.
        type: delete
  ResponseModel[IEnumerable[HistoryRecordModel]]:
    properties:
      Result:
        description: This is a default description.
        type: delete
  HistoryRecordModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
  ApiBalanceChangeModel:
    properties:
      Id:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      IconId:
        description: This is a default description.
        type: delete
      BlockChainHash:
        description: This is a default description.
        type: delete
      IsRefund:
        description: This is a default description.
        type: delete
      AddressFrom:
        description: This is a default description.
        type: delete
      AddressTo:
        description: This is a default description.
        type: delete
      IsSettled:
        description: This is a default description.
        type: delete
  ApiTradeOperation:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      IconId:
        description: This is a default description.
        type: delete
      BlockChainHash:
        description: This is a default description.
        type: delete
      AddressFrom:
        description: This is a default description.
        type: delete
      AddressTo:
        description: This is a default description.
        type: delete
      IsSettled:
        description: This is a default description.
        type: delete
      State:
        description: This is a default description.
        type: delete
  ApiTransfer:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      IconId:
        description: This is a default description.
        type: delete
      BlockChainHash:
        description: This is a default description.
        type: delete
      AddressFrom:
        description: This is a default description.
        type: delete
      AddressTo:
        description: This is a default description.
        type: delete
      IsSettled:
        description: This is a default description.
        type: delete
      State:
        description: This is a default description.
        type: delete
  ApiCashOutAttempt:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      IconId:
        description: This is a default description.
        type: delete
  ApiCashOutCancelled:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      IconId:
        description: This is a default description.
        type: delete
  ApiCashOutDone:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      IconId:
        description: This is a default description.
        type: delete
  ApiLimitTradeEvent:
    properties:
      Id:
        description: This is a default description.
        type: delete
      OrderId:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
      Status:
        description: This is a default description.
        type: delete
      Type:
        description: This is a default description.
        type: delete
      TotalCost:
        description: This is a default description.
        type: delete
  Fee:
    properties:
      Amount:
        description: This is a default description.
        type: delete
      Type:
        description: This is a default description.
        type: delete
  ResponseModel[ApiLimitOrder]:
    properties: []
  ApiLimitOrder:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      OrderType:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      RemainingVolume:
        description: This is a default description.
        type: delete
      RemainingOtherVolume:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
      BaseAsset:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      TotalCost:
        description: This is a default description.
        type: delete
  HotWalletOperation:
    properties:
      AssetPair:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
  ResponseModel[HotWalletSuccessTradeRespModel]:
    properties: []
  HotWalletSuccessTradeRespModel:
    properties: []
  ApiHotWalletOrder:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      OrderType:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      TotalCost:
        description: This is a default description.
        type: delete
  HotWalletLimitOperation:
    properties:
      Price:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
  HotWalletCashoutOperation:
    properties:
      DestinationAddress:
        description: This is a default description.
        type: delete
      AssetId:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
  ResponseModel[BlockchainAddressValidityResponseModel]:
    properties: []
  BlockchainAddressValidityResponseModel:
    properties:
      IsValid:
        description: This is a default description.
        type: delete
  ResponseModel[GetIcoCounsSoldResponseModel]:
    properties: []
  GetIcoCounsSoldResponseModel:
    properties:
      Amount:
        description: This is a default description.
        type: delete
  PostRevertAssetPairModel:
    properties:
      AssetPairId:
        description: This is a default description.
        type: delete
      Inverted:
        description: This is a default description.
        type: delete
  IsAliveResponse:
    properties:
      Version:
        description: This is a default description.
        type: delete
      Env:
        description: This is a default description.
        type: delete
      OtherInfo:
        description: This is a default description.
        type: delete
  ResponseModel[IsPinSecurityEnabledResultModel]:
    properties: []
  IsPinSecurityEnabledResultModel:
    properties:
      IsEnabled:
        description: This is a default description.
        type: delete
  ResponseModel[IEnumerable[ApiIssuer]]:
    properties:
      Result:
        description: This is a default description.
        type: delete
  ApiIssuer:
    properties:
      Name:
        description: This is a default description.
        type: delete
      IconUrl:
        description: This is a default description.
        type: delete
      Id:
        description: This is a default description.
        type: delete
  ResponseModel[ApiIssuer]:
    properties: []
  ResponseModel[KycDocumentsModel]:
    properties: []
  KycDocumentsModel:
    properties:
      Docs:
        description: This is a default description.
        type: delete
  KycDocumentModel:
    properties:
      Type:
        description: This is a default description.
        type: delete
      IdType:
        description: This is a default description.
        type: delete
      DocumentId:
        description: This is a default description.
        type: delete
      DocumentState:
        description: This is a default description.
        type: delete
      KycComment:
        description: This is a default description.
        type: delete
  KycDocumentsModelDeprecated:
    properties:
      Type:
        description: This is a default description.
        type: delete
      Ext:
        description: This is a default description.
        type: delete
      Data:
        description: This is a default description.
        type: delete
      IdType:
        description: This is a default description.
        type: delete
  ResponseModel[PostKycDocumentRespModel]:
    properties: []
  PostKycDocumentRespModel:
    properties: []
  IFormFile:
    properties:
      ContentType:
        description: This is a default description.
        type: delete
      ContentDisposition:
        description: This is a default description.
        type: delete
      Headers:
        description: This is a default description.
        type: delete
      Length:
        description: This is a default description.
        type: delete
      Name:
        description: This is a default description.
        type: delete
      FileName:
        description: This is a default description.
        type: delete
  ResponseModel[KycForAssetResponseModel]:
    properties: []
  KycForAssetResponseModel:
    properties:
      UserKycStatus:
        description: This is a default description.
        type: delete
      KycNeeded:
        description: This is a default description.
        type: delete
  ResponseModel[GetKycStatusRespModel]:
    properties: []
  GetKycStatusRespModel:
    properties:
      KycStatus:
        description: This is a default description.
        type: delete
  ResponseModel[PostKycStatusRespModel]:
    properties: []
  PostKycStatusRespModel:
    properties: []
  ResponseModel[GetLastBaseAssetsRespModel]:
    properties: []
  GetLastBaseAssetsRespModel:
    properties:
      Assets:
        description: This is a default description.
        type: delete
  ResponseModel[OffchainLimitOrdersRespModel]:
    properties: []
  OffchainLimitOrdersRespModel:
    properties:
      Orders:
        description: This is a default description.
        type: delete
  ApiOffchainOrder:
    properties:
      Id:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      OrderType:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      TotalCost:
        description: This is a default description.
        type: delete
      RemainingVolume:
        description: This is a default description.
        type: delete
      RemainingOtherVolume:
        description: This is a default description.
        type: delete
  ResponseModel[OffchainLimitOrdersCountRespModel]:
    properties: []
  OffchainLimitOrdersCountRespModel:
    properties:
      Count:
        description: This is a default description.
        type: delete
  ResponseModel[IEnumerable[ILykkeNewsRecord]]:
    properties:
      Result:
        description: This is a default description.
        type: delete
  ILykkeNewsRecord:
    properties:
      Author:
        description: This is a default description.
        type: delete
      Title:
        description: This is a default description.
        type: delete
      DateTime:
        description: This is a default description.
        type: delete
      ImgUrl:
        description: This is a default description.
        type: delete
      Url:
        description: This is a default description.
        type: delete
      Text:
        description: This is a default description.
        type: delete
  ChangeMarginAccountBalanceModel:
    properties:
      AccountId:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
  MarginSwiftCashOutReqModel:
    properties:
      MarginAccountId:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
      Bic:
        description: This is a default description.
        type: delete
      AccNumber:
        description: This is a default description.
        type: delete
      AccName:
        description: This is a default description.
        type: delete
      AccHolderAddress:
        description: This is a default description.
        type: delete
      BankName:
        description: This is a default description.
        type: delete
      AccHolderCountry:
        description: This is a default description.
        type: delete
      AccHolderZipCode:
        description: This is a default description.
        type: delete
      AccHolderCity:
        description: This is a default description.
        type: delete
  ToBaseConvertionRequest:
    properties:
      BaseAssetId:
        description: This is a default description.
        type: delete
      AssetsFrom:
        description: This is a default description.
        type: delete
      OrderAction:
        description: This is a default description.
        type: delete
  AssetWithAmount:
    properties:
      AssetId:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
  ResponseModel[ToBaseConvertionResponse]:
    properties: []
  ToBaseConvertionResponse:
    properties:
      Converted:
        description: This is a default description.
        type: delete
  ConversionResult:
    properties:
      Price:
        description: This is a default description.
        type: delete
      VolumePrice:
        description: This is a default description.
        type: delete
      Result:
        description: This is a default description.
        type: delete
  PostMyLykkeCashInEmailModel:
    properties:
      AssetId:
        description: This is a default description.
        type: delete
      Amount:
        description: This is a default description.
        type: delete
      LkkAmount:
        description: This is a default description.
        type: delete
      Price:
        description: This is a default description.
        type: delete
  ResponseModel[GetMyLykkeInfoRespModel]:
    properties: []
  GetMyLykkeInfoRespModel:
    properties:
      LkkTotalAmount:
        description: This is a default description.
        type: delete
      LkkBalance:
        description: This is a default description.
        type: delete
      BtcConversionWalletAddress:
        description: This is a default description.
        type: delete
      NumberOfShares:
        description: This is a default description.
        type: delete
      MarketValueUSD:
        description: This is a default description.
        type: delete
      MyEquityPercent:
        description: This is a default description.
        type: delete
  ResponseModel[MyLykkeSettingsModel]:
    properties: []
  MyLykkeSettingsModel:
    properties:
      MyLykkeEnabled:
        description: This is a default description.
        type: delete
  ResponseModel[OffchainRequestResponsesModel]:
    properties: []
  OffchainRequestResponsesModel:
    properties:
      Requests:
        description: This is a default description.
        type: delete
  OffchainRequestResponseModel:
    properties:
      Asset:
        description: This is a default description.
        type: delete
      RequestId:
        description: This is a default description.
        type: delete
      Type:
        description: This is a default description.
        type: delete
  OffchainTradeModel:
    properties:
      AssetPair:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      PrevTempPrivateKey:
        description: This is a default description.
        type: delete
  ResponseModel[OffchainTradeRespModel]:
    properties: []
  OffchainTradeRespModel:
    properties:
      TransferId:
        description: This is a default description.
        type: delete
      TransactionHex:
        description: This is a default description.
        type: delete
      OperationResult:
        description: This is a default description.
        type: delete
  OffchainLimitTradeModel:
    properties:
      Price:
        description: This is a default description.
        type: delete
      AssetPair:
        description: This is a default description.
        type: delete
      Asset:
        description: This is a default description.
        type: delete
      Volume:
        description: This is a default description.
        type: delete
      PrevTempPrivateKey:
        description: This is a default description.
        type: delete
  OffchainLimitCancelModel:
    properties:
      OrderId:
        description: This is a default description.
        type: delete
  OffchainChannelProcessModel:
    properties:
      TransferId:
        description: This is a default description.
        type: delete
      SignedChannelTransaction:
        description: This is a default description.
        type: delete
  OffchainFinalizeModel:
    properties:
      TransferId:
        description: This is a default description.
        type: delete
      ClientRevokePubKey:
        description: This is a default description.
        type: delete
      ClientRevokeEncryptedPrivateKey:
        description: This is a default description.
        type: delete
      SignedTransferTransaction:
        description: This is a default description.
        type: delete
  ResponseModel[OffchainSuccessTradeRespModel]:
    properties: []
  OffchainSuccessTradeRespModel:
    properties:
      TransferId:
        description: This is a default description.
        type: delete
      TransactionHex:
        description: This is a default description.
        type: delete
      OperationResult:
        description: This is a default description.
        type: delete
x-collection-name: Lykke
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
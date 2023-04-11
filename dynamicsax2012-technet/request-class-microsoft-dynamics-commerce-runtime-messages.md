---
title: Request Class (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Request Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Messages.Request
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request(v=AX.60)
ms:contentKeyID: 49822665
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request
dev_langs:
- CSharp
- C++
- VB
---

# Request Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the base request used by all request messages.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class Request
'Usage
Dim instance As Request
```

``` csharp
[DataContractAttribute]
public abstract class Request
```

``` c++
[DataContractAttribute]
public ref class Request abstract
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Messages.Request  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataRequest](getproductcatalogassociationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCartDataRequest](savecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveSalesTransactionDataRequest](savesalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest](addorremovediscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.AuthenticateDevicePartialRequest](authenticatedevicepartialrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsRequest](beginreadchangedproductsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CalculateChargesRequest](calculatechargesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CancelOrderRequest](cancelorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeDatabaseConnectionRequest](changedatabaseconnectionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ChangedProductsSearchRequest](changedproductssearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusRequest](changeshiftstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CompleteAccountActivationRequest](completeaccountactivationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CreateCustomerRequest](createcustomerrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CreateHardwareStationTokenRequest](createhardwarestationtokenrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartRequest](createorderfromcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest](createshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CreateStockCountRequest](createstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.CustomersSearchRequest](customerssearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.DeactivateDeviceRequest](deactivatedevicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteCartRequest](deletecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteShiftRequest](deleteshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest](deletestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.DeviceActivationRequest](deviceactivationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.DownloadDataSetRequest](downloaddatasetrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest](employeetimeregistrationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.EndReadChangedProductsRequest](endreadchangedproductsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceRequest](getactiveproductpricerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAffiliationsRequest](getaffiliationsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllDeliveryOptionsRequest](getalldeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllStoreEmployeesRequest](getallstoreemployeesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableShiftsRequest](getavailableshiftsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableStoresRequest](getavailablestoresrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeRequest](getbarcoderequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridByIdRequest](getbuttongridbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsRequest](getbuttongridsbyidsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsRequest](getbuttongridsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesRequest](getcardtypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest](getcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelAttributesRequest](getchannelattributesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCashDeclarationRequest](getchannelcashdeclarationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryAttributesRequest](getchannelcategoryattributesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyRequest](getchannelcategoryhierarchyrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelConfigurationRequest](getchannelconfigurationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountRequest](getchannelcurrencyamountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributeRequest](getchannelproductattributerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributesRequest](getchannelproductattributesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProfileByChannelIdRequest](getchannelprofilebychannelidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelTenderTypesRequest](getchanneltendertypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCommerceListRequest](getcommercelistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCreditMemoRequest](getcreditmemorequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrenciesRequest](getcurrenciesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrentChannelRequest](getcurrentchannelrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerBalanceRequest](getcustomerbalancerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerGroupsRequest](getcustomergroupsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerLoyaltyCardsRequest](getcustomerloyaltycardsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersRequest](getcustomersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetDefaultChannelRequest](getdefaultchannelrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryPreferencesRequest](getdeliverypreferencesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeviceConfigurationRequest](getdeviceconfigurationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest](getdiscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetEmployeePermissionsRequest](getemployeepermissionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetGiftCardRequest](getgiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetHardwareProfileRequest](gethardwareprofilerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsRequest](getincomeexpenseaccountsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountRequest](getindependentproductpricediscountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceRequest](getinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesRequest](getitemavailabilitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesRequest](getitemavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdRequest](getitembarcodesbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdRequest](getitembyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemDimensionsRequest](getitemdimensionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetLatestOfflineDatabaseChunksRequest](getlatestofflinedatabasechunksrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetLineDeliveryOptionsRequest](getlinedeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingAvailableQuantitiesRequest](getlistingavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingPublishStatusesRequest](getlistingpublishstatusesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsRequest](getlocalizedstringsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardStatusRequest](getloyaltycardstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardTransactionsRequest](getloyaltycardtransactionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetNextBatchListingPublishStatusesRequest](getnextbatchlistingpublishstatusesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetNumberSequenceRequest](getnumbersequencerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineDatabaseChunkRequest](getofflinedatabasechunkrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineSyncStatsRequest](getofflinesyncstatsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionCountRequest](getofflinetransactioncountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionIdsRequest](getofflinetransactionidsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineTransactionsRequest](getofflinetransactionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOnlineChannelRequest](getonlinechannelrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOperationPermissionsRequest](getoperationpermissionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersRequest](getordersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetPickingListRequest](getpickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductCatalogsRequest](getproductcatalogsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductDeliveryOptionsRequest](getproductdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductRefinersRequest](getproductrefinersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductsInCartRequest](getproductsincartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetPromotionsRequest](getpromotionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetPurchaseOrderRequest](getpurchaseorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetReasonCodesRequest](getreasoncodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataRequest](getreportdatarequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetReturnOrderReasonCodesRequest](getreturnorderreasoncodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSalesTaxGroupsRequest](getsalestaxgroupsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetShiftRequest](getshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentLineMappingRequest](getshipmentlinemappingrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentPublishingStatusRequest](getshipmentpublishingstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsBatchRequest](getshipmentsbatchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsRequest](getshipmentsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStockCountRequest](getstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsRequest](getstorelocationsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationRequest](getstoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresByEmployeeRequest](getstoresbyemployeerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresRequest](getstoresrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedCardTypesRequest](getsupportedcardtypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedLanguagesRequest](getsupportedlanguagesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedReportsRequest](getsupportedreportsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetTaxOverridesRequest](gettaxoverridesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetTillLayoutRequest](gettilllayoutrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderRequest](gettransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureRequest](getunitsofmeasurerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsRequest](getwarehousedetailsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.GetXAndZReportReceiptRequest](getxandzreportreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.IssueLoyaltyCardRequest](issueloyaltycardrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest](issueoraddtogiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest](pickandpackorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.PickupAtStoreRequest](pickupatstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest](pricecheckrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeRequest](processbarcodetyperequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ProductSearchRequest](productsearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.PurgeOfflineTransactionsRequest](purgeofflinetransactionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.RecalculateOrderRequest](recalculateorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.RecallCustomerOrderRequest](recallcustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.RecallSalesInvoiceRequest](recallsalesinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ResumeCartRequest](resumecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCommerceListRequest](savecommercelistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCustomerOrderRequest](savecustomerorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveKitTransactionRequest](savekittransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveOfflineTransactionsRequest](saveofflinetransactionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SavePickingListRequest](savepickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SavePurchaseOrderRequest](savepurchaseorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest](savereasoncodelinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveShipmentPublishingStatusRequest](saveshipmentpublishingstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest](savestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationRequest](savestoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest](savetenderlinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTransferOrderRequest](savetransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveVoidTransactionRequest](savevoidtransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreRequest](searchstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerAccountActivationEmailRequest](sendcustomeraccountactivationemailrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerEmailRequest](sendcustomeremailrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest](shiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SubmitSalesTransactionRequest](submitsalestransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SuspendCartRequest](suspendcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountRequest](syncstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.TransferCartRequest](transfercartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.TransferShiftRequest](transfershiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPropertiesRequest](updatechannelpropertiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateChannelPublishingStatusRealtimeRequest](updatechannelpublishingstatusrealtimerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateCustomerRequest](updatecustomerrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateListingPublishingStatusRequest](updatelistingpublishingstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateOnlineChannelPublishStatusRequest](updateonlinechannelpublishstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UploadOrderRequest](uploadorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRenewalRequest](userauthenticationrenewalrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UserChangePasswordRequest](userchangepasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest](userlogoffrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest](userresetpasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateAccountActivationRequestRequest](validateaccountactivationrequestrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateHardwareStationTokenRequest](validatehardwarestationtokenrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateTenderLineForAddRequest](validatetenderlineforaddrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceRequest](verifyproductexistencerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest](makepaymentrequest-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitStockCountJournalRealtimeRequest](commitstockcountjournalrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalRealtimeRequest](createstockcountjournalrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase](creditmemorealtimerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountJournalRealtimeRequest](deletestockcountjournalrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCreditMemoRealtimeRequest](getcreditmemorealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDeliveryPreferencesServiceRequest](getdeliverypreferencesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetGiftCardRealtimeRequest](getgiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNumberSequenceSeedDataTransactionServiceRequest](getnumbersequenceseeddatatransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsRealtimeRequest](getshipmentsrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalsRealtimeRequest](getstockcountjournalsrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionsRealtimeRequest](getstockcountjournaltransactionsrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityRealtimeRequest](getstoreavailabilityrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GiftCardRealtimeRequestBase](giftcardrealtimerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IndiaGetInterStateTaxRegimeServiceRequest](indiagetinterstatetaxregimeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProductSearchServiceRequest](productsearchservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest](sendemailservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UnlockGiftCardRealtimeRequest](unlockgiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCustomerAccountPaymentRealtimeRequest](validatecustomeraccountpaymentrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidGiftCardRealtimeRequest](voidgiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


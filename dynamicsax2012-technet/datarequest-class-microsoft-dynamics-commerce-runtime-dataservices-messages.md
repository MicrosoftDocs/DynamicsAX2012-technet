---
title: DataRequest Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: DataRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.datarequest(v=AX.60)
ms:contentKeyID: 65320914
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest
dev_langs:
- CSharp
- C++
- VB
---

# DataRequest Class

Base class for data request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class DataRequest _
    Inherits Request
'Usage
Dim instance As DataRequest
```

``` csharp
[DataContractAttribute]
public abstract class DataRequest : Request
```

``` c++
[DataContractAttribute]
public ref class DataRequest abstract : public Request
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CompleteCustomerAccountActivationDataRequest](completecustomeraccountactivationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateCustomerDataRequest](createorupdatecustomerdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateShipmentStatusDataRequest](createorupdateshipmentstatusdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalDataRequest](createupdatestockcountjournaldatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalTransactionDataRequest](createupdatestockcountjournaltransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteCartDataRequest](deletecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeletePickingListLinesDataRequest](deletepickinglistlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeletePurchaseOrderLinesDataRequest](deletepurchaseorderlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteStockCountJournalsDataRequest](deletestockcountjournalsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteStockCountTransactionDataRequest](deletestockcounttransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteTransferOrderLinesDataRequest](deletetransferorderlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest](employeelogonstoredatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceRequest\<TResponseEntity\>](entitydataservicerequest-tresponseentity-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceRequest\<TRequestEntity, TResponseEntity\>](entitydataservicerequest-trequestentity-tresponseentity-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest](getaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressesDataRequest](getaddressesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest](getaddressinfodatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationByAffilationIdDataRequest](getaffiliationbyaffilationiddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsDataRequest](getaffiliationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAllDeliveryOptionsDataRequest](getalldeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCardTypeDataRequest](getcardtypedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCategoryAttributesDataRequest](getchannelcategoryattributesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelConfigurationDataServiceRequest](getchannelconfigurationdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCurrenciesDataRequest](getchannelcurrenciesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelTenderTypesDataRequest](getchanneltendertypesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCurrencyByCodeDataRequest](getcurrencybycodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCurrentTerminalIdDataRequest](getcurrentterminaliddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerDataRequest](getcustomerdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerGroupsDataRequest](getcustomergroupsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerLoyaltyCardsDataRequest](getcustomerloyaltycardsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomersDataRequest](getcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerWithPartyNumberDataRequest](getcustomerwithpartynumberdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDefaultLanguageIdDataRequest](getdefaultlanguageiddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeliveryOptionDataRequest](getdeliveryoptiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeliveryPreferencesDataRequest](getdeliverypreferencesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceConfigurationDataServiceRequest](getdeviceconfigurationdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceDataServiceRequest](getdevicedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountLinesDataRequest](getdiscountlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByActivityDataRequest](getemployeebreakcategoriesbyactivitydatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByJobDataRequest](getemployeebreakcategoriesbyjobdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase](getemployeedatarequestbase-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeIdFromLogOnKeyDataRequest](getemployeeidfromlogonkeydatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeePermissionsDataRequest](getemployeepermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest](getexchangeratesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemAvailabilitiesDataRequest](getitemavailabilitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest](getitemdeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDimensionsDataRequest](getitemdimensionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsDataRequest](getitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceRequest](getlatestnumbersequencedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLineDeliveryOptionsDataRequest](getlinedeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLinkedProductsDataRequest](getlinkedproductsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyCardAffiliationsDataRequest](getloyaltycardaffiliationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyCardDataRequest](getloyaltycarddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyGroupsAndTiersDataRequest](getloyaltygroupsandtiersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyRewardPointLinesDataRequest](getloyaltyrewardpointlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineEarnDataRequest](getloyaltyschemelineearndatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineRedeemDataRequest](getloyaltyschemelineredeemdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineSyncStatsDataServiceRequest](getofflinesyncstatsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionCountDataServiceRequest](getofflinetransactioncountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionIdsDataServiceRequest](getofflinetransactionidsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineTransactionsDataServiceRequest](getofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOLTPReportDataRequest](getoltpreportdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest](getoperationpermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataRequest](getparentkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPaymentConnectorConfigurationDataRequest](getpaymentconnectorconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPaymentConnectorDataRequest](getpaymentconnectordatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPickingListDataRequest](getpickinglistdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductBarcodeDataRequest](getproductbarcodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataRequest](getproductkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataRequest](getproductrefinersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataRequest](getproductunitofmeasureoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductVariantsDataRequest](getproductvariantsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPurchaseOrderDataRequest](getpurchaseorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetQuantityDiscountDataServiceRequest](getquantitydiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReasonCodesDataRequest](getreasoncodesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest](getreceiptmaskdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReportConfigurationDataRequest](getreportconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesLinesDataRequest](getsaleslinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTaxGroupDataRequest](getsalestaxgroupdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTaxGroupsDataRequest](getsalestaxgroupsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTransactionDataRequest](getsalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftDataDataRequest](getshiftdatadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftRequiredAmountsPerTenderDataRequest](getshiftrequiredamountspertenderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentLineMappingDataRequest](getshipmentlinemappingdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentsDataRequest](getshipmentsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShippingAdapterConfigurationDataRequest](getshippingadapterconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStockCountDataRequest](getstockcountdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStoreDataServiceRequest](getstoredataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSupportedReportsDataRequest](getsupportedreportsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeFormulaIndiaDataRequest](gettaxcodeformulaindiadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsDataRequest](gettaxcodeintervalsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxCodeIntervalsIndiaDataRequest](gettaxcodeintervalsindiadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverrideDetailsDataRequest](gettaxoverridedetailsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverridesDataRequest](gettaxoverridesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxParameterDataRequest](gettaxparameterdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTerminalByRecordIdDataRequest](getterminalbyrecordiddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest](gettilllayoutdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTransferOrderDataRequest](gettransferorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataRequest](getunitofmeasureconversiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseDetailsDataRequest](getwarehousedetailsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAuditLogDataRequest](insertauditlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertLoyaltyCardDataRequest](insertloyaltycarddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest](insertsalestransactiontablesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTransactionLogDataRequest](inserttransactionlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceRequest](numbersequencedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProcessCustomerImagesDataRequest](processcustomerimagesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProductSearchDataRequest](productsearchdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeOfflineTransactionsDataServiceRequest](purgeofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeSalesTransactionsDataRequest](purgesalestransactionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseConnection.ReleaseConnectionServiceRequest](releaseconnectionservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages-releaseconnection.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseItemsDataRequest](releaseitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReserveItemsDataRequest](reserveitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCustomerAccountActivationDataRequest](savecustomeraccountactivationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveOfflineTransactionsDataServiceRequest](saveofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SavePickingListDataRequest](savepickinglistdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SavePurchaseOrderLinesDataRequest](savepurchaseorderlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTransactionLogDataServiceRequest](savetransactionlogdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTransferOrderDataRequest](savetransferorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchCustomersDataRequest](searchcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesTransactionDataRequest](searchsalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ShiftDataServiceRequest](shiftdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest](unlockuseratlogoffdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateReturnQuantitiesDataRequest](updatereturnquantitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAccountActivationDataRequest](validateaccountactivationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateEmployeePasswordDataRequest](validateemployeepassworddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: ServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.servicerequest(v=AX.60)
ms:contentKeyID: 65318419
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# ServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class ServiceRequest _
    Inherits Request
'Usage
Dim instance As ServiceRequest
```

``` csharp
[DataContractAttribute]
public abstract class ServiceRequest : Request
```

``` c++
[DataContractAttribute]
public ref class ServiceRequest abstract : public Request
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest  
      [Microsoft.Dynamics.Commerce.Runtime.Messages.AuthenticateDeviceTransactionServiceRequest](authenticatedevicetransactionservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase](dataprotectionservicerequestbase-class-microsoft-dynamics-commerce-runtime-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateStaffPasswordTransactionServiceRequest](validatestaffpasswordtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ActivateDeviceServiceRequest](activatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardServiceRequest](addtogiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest](authenticatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateAmountPaidAndDueServiceRequest](calculateamountpaidanddueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateDepositServiceRequest](calculatedepositservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateDiscountsServiceRequest](calculatediscountsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateLoyaltyRewardPointsServiceRequest](calculateloyaltyrewardpointsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceRequest](calculatequantityfrompriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest](calculaterequiredreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTaxServiceRequest](calculatetaxservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalAmountServiceRequest](calculatetotalamountservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalsServiceRequest](calculatetotalsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitStockCountTransactionsServiceRequest](commitstockcounttransactionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateAddressServiceRequest](createaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateHardwareStationTokenServiceRequest](createhardwarestationtokenservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateSalesOrderServiceRequest](createsalesorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalServiceRequest](createstockcountjournalservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CustomersSearchServiceRequest](customerssearchservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateAddressServiceRequest](deactivateaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateDeviceServiceRequest](deactivatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountJournalServiceRequest](deletestockcountjournalservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountTransactionServiceRequest](deletestockcounttransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.EmployeeClockInOutServiceRequest](employeeclockinoutservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceRequest](getaddressinfoservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAllPeriodicDiscountsServiceRequest](getallperiodicdiscountsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetBarcodeTypeServiceRequest](getbarcodetypeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridByIdServiceRequest](getbuttongridbyidservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsByIdsServiceRequest](getbuttongridsbyidsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsServiceRequest](getbuttongridsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest](getchangepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceRequest](getchannelcurrencyservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChargesServiceRequest](getchargesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceRequest](getcommercelistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCreditMemoServiceRequest](getcreditmemoservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceRequest](getcurrencyvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest](getcustomerbalanceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerGroupsServiceRequest](getcustomergroupsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerOrderCalculationModesServiceRequest](getcustomerordercalculationmodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest](getcustomersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest](getdiscountcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest](getemailreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest](getemployeeactivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeCurrentRegistrationStateServiceRequest](getemployeecurrentregistrationstateservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExchangeRateServiceRequest](getexchangerateservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceRequest](getexternalshippingrateservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetGiftCardServiceRequest](getgiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetIndependentPriceDiscountServiceRequest](getindependentpricediscountservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceRequest](getinvoiceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest](getitemavailabilitiesbyitemquantitiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceRequest](getitemavailabilitiesbyitemsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceRequest](getitemavailabilitiesbyitemwarehousesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailableQuantitiesByItemsServiceRequest](getitemavailablequantitiesbyitemsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest](getlinedeliveryoptionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceRequest](getloyaltycardrewardpointsstatustransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceRequest](getloyaltycardstatusservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardTransactionsServiceRequest](getloyaltycardtransactionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest](getmanageractivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest](getnextreceiptidservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderDeliveryOptionsServiceRequest](getorderdeliveryoptionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceRequest](getordersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest](getpaymentroundedvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPickingListServiceRequest](getpickinglistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPriceServiceRequest](getpriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest](getpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDataServiceRequest](getproductdataservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDeliveryOptionsServiceRequest](getproductdeliveryoptionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceRequest](getproductpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductsServiceRequest](getproductsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceRequest](getpurchaseorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReasonCodesServiceRequest](getreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRemoteProductsByCategoryServiceRequest](getremoteproductsbycategoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRemoteProductsByKeywordServiceRequest](getremoteproductsbykeywordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceRequest](getreportdataservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest](getreturnlocationtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnOrderReasonCodesServiceRequest](getreturnorderreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest](getroundedstringservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedValueServiceRequest](getroundedvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundQuantityServiceRequest](getroundquantityservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceRequest](getshipmentsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceRequest](getshippingratefromcarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalServiceRequest](getstockcountjournalservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionServiceRequest](getstockcountjournaltransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityServiceRequest](getstoreavailabilityservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceRequest](getstoresservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxRegimeServiceRequest](gettaxregimeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceRequest](gettrackinginformationfromcarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceRequest](gettransferorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest](insertauditlogservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardServiceRequest](issuegiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest](issueloyaltycardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardTransactionServiceRequest](issueloyaltycardtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.MarkReturnedItemsServiceRequest](markreturneditemsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NewCustomerFromDirectoryPartyServiceRequest](newcustomerfromdirectorypartyservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NewCustomerServiceRequest](newcustomerservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NonSaleTenderServiceRequest](nonsaletenderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase](paymentservicerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest](pickandpackorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PostLoyaltyCardRewardPointServiceRequest](postloyaltycardrewardpointservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PostLoyaltyCardRewardPointTransactionServiceRequest](postloyaltycardrewardpointtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceRequest](processmasksegmentsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RecallCustomerOrderServiceRequest](recallcustomerorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RegisterEmployeeBreakServiceRequest](registeremployeebreakservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCommerceListServiceRequest](savecommercelistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerAccountActivationServiceRequest](savecustomeraccountactivationservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest](savecustomerorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerServiceRequest](savecustomerservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest](savedropanddeclareservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePickingListServiceRequest](savepickinglistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePurchaseOrderServiceRequest](savepurchaseorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceRequest](savestockcountjournaltransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransactionLogRequest](savetransactionlogrequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransferOrderServiceRequest](savetransferorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SettleInvoiceServiceRequest](settleinvoiceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountJournalsFromAxServiceRequest](syncstockcountjournalsfromaxservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceRequest](syncstockcounttransactionsfromaxservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UnlockGiftCardServiceRequest](unlockgiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateAddressServiceRequest](updateaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateChannelPublishStatusServiceRequest](updatechannelpublishstatusservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdatePriceServiceRequest](updatepriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest](userchangepasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOffServiceRequest](userlogoffservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnRenewalServiceRequest](userlogonrenewalservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest](userresetpasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateAccountActivationRequestServiceRequest](validateaccountactivationrequestservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceRequest](validatehardwarestationtokenservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceRequest](validateshippingaddresscarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest](validateshippingaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateTenderLineForAddServiceRequest](validatetenderlineforaddservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidGiftCardServiceRequest](voidgiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


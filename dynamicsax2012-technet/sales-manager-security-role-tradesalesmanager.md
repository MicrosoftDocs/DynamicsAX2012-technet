---
title: Sales manager security role (TradeSalesManager)
TOCTitle: Sales manager security role (TradeSalesManager)
ms:assetid: 508f38b3-936b-491b-8059-0dcd22a677da
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527088(v=AX.60)
ms:contentKeyID: 37823140
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Sales manager security role (TradeSalesManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Sales manager security role represents a user who reviews sales process performance and enables the sales process.

## Duties

By default, this security role is assigned the following duties in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty name</p></th>
<th><p>Duty AOT name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Inquire into sales agreement master</p></td>
<td><p>AgreementSalesAgreementMasterInquire</p></td>
<td><p>Respond to inquiries about sales agreement master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain sales agreement master</p></td>
<td><p>AgreementSalesAgreementMasterMaintain</p></td>
<td><p>Maintain sales agreement master</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into export letter of credit</p></td>
<td><p>BankExportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of export letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Enable case management</p></td>
<td><p>CaseCaseManagementEnable</p></td>
<td><p>Set up policies and reference data to enable the case management process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cases</p></td>
<td><p>CaseCasesMaintain</p></td>
<td><p>Maintain cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales case progress</p></td>
<td><p>CaseSalesCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of sales cases</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service case progress</p></td>
<td><p>CaseServiceCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of service cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="odd">
<td><p>Review customer master</p></td>
<td><p>CustCustomerMasterReview</p></td>
<td><p>Review customer master</p></td>
</tr>
<tr class="even">
<td><p>Enable customer process</p></td>
<td><p>CustCustomerProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the customer process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain customer master</p></td>
<td><p>CustCustomersMaintain</p></td>
<td><p>Document and record customer master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire about payment status for customer invoices</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CustInvoice4PaymInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsMaintain</p></td>
<td><p>Document and record sales commissions master information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into external items descriptions master</p></td>
<td><p>CustVendExternalItemMasterInquire</p></td>
<td><p>Respond to inquiries about customers and vendors external item descriptions</p></td>
</tr>
<tr class="even">
<td><p>Maintain external items descriptions master</p></td>
<td><p>CustVendExternalItemMasterMaintain</p></td>
<td><p>Maintain customers and vendors external item descriptions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain online commerce batch jobs</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DOCommerceBatchJobsMaintain</p></td>
<td><p>Run online commerce batch jobs</p></td>
</tr>
<tr class="even">
<td><p>Maintain online product item list</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DOCommerceOnlineProductsMaintain</p></td>
<td><p>Adds, updates, and deletes the Commerce Service account and configuration</p></td>
</tr>
<tr class="odd">
<td><p>Maintains the online sales orders</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in versions prior to Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DOCommerceOnlineSalesOrdersMaintain</p></td>
<td><p>Maintains the online sales orders</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document source texts</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain demand forecasts</p></td>
<td><p>ForecastDemandForecastMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="even">
<td><p>Maintain tracking dimensions master</p></td>
<td><p>InventTrackingDimensionsMasterMaintain</p></td>
<td><p>Maintain serial and batch numbers</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales events kanban progress</p></td>
<td><p>KanbanExecutionSalesEvtsProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into kanban schedule status</p></td>
<td><p>KanbanScheduleStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain broker claims</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRBrokerClaimMaintain</p></td>
<td><p>Make changes to broker claims</p></td>
</tr>
<tr class="even">
<td><p>Maintain broker information</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRBrokerMaintain</p></td>
<td><p>Make changes to broker information</p></td>
</tr>
<tr class="odd">
<td><p>Process catalog requests</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRCatalogRequestMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain continuity</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRContinuityMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View customer payment schedules</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRContinuityPaymSchedInquire</p></td>
<td><p>Display customer payment schedules</p></td>
</tr>
<tr class="even">
<td><p>Maintain coupons</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRCouponMaintain</p></td>
<td><p>Make changes to coupons</p></td>
</tr>
<tr class="odd">
<td><p>Maintain direct delivery</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRDirectDeliveryMaintain</p></td>
<td><p>Make changes to direct delivery information</p></td>
</tr>
<tr class="even">
<td><p>Enable call center events and letters</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCREventEnable</p></td>
<td><p>Enable events and letters</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into order events</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCREventInquire</p></td>
<td><p>Respond to inquiries about order events</p></td>
</tr>
<tr class="even">
<td><p>Maintain fraud setup</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRFraudMaintain</p></td>
<td><p>Make changes to fraud setup</p></td>
</tr>
<tr class="odd">
<td><p>Enable installment billing process</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRInstallmentBillEnable</p></td>
<td><p>Enable the processing of installment billing payments</p></td>
</tr>
<tr class="even">
<td><p>Maintain scripts</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRMessageMaintain</p></td>
<td><p>Maintain scripts that are displayed in sales orders</p></td>
</tr>
<tr class="odd">
<td><p>Maintain support for change-of-address files</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRNCOAMaintain</p></td>
<td><p>Maintain the ability to import and process a change-of-address file</p></td>
</tr>
<tr class="even">
<td><p>Maintain gift card payments</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPaymGiftCardMaintain</p></td>
<td><p>Maintain the ability to use gift card payments in sales orders for call centers</p></td>
</tr>
<tr class="odd">
<td><p>Maintain gift certificate payments</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPaymGiftCertificateMaintain</p></td>
<td><p>Maintain the ability to use gift certificate payments in sales orders for call centers</p></td>
</tr>
<tr class="even">
<td><p>Maintain refund check processing</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPaymRefundCheckMaintain</p></td>
<td><p>Maintain approval and processing for refund checks</p></td>
</tr>
<tr class="odd">
<td><p>Maintain price details</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPriceMaintain</p></td>
<td><p>Maintain the ability to view price details in sales orders</p></td>
</tr>
<tr class="even">
<td><p>Maintain price overrides</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPriceOverrideMaintain</p></td>
<td><p>Maintain price overrides for sales orders in call centers</p></td>
</tr>
<tr class="odd">
<td><p>Enable the price override process</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPriceOverrideProcessEnable</p></td>
<td><p>Set up price override permissions and reference data to enable the price override process</p></td>
</tr>
<tr class="even">
<td><p>Maintain retail sales order recalculation process</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRRetailRecalculatorMaintain</p></td>
<td><p>Maintain retail sales order recalculation process</p></td>
</tr>
<tr class="odd">
<td><p>View royalty definitions</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRRoyaltyTableInquire</p></td>
<td><p>View information about royalty definitions</p></td>
</tr>
<tr class="even">
<td><p>Maintain royalty information</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRRoyaltyVendTableMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable sales</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesEnable</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain sales order holds</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesHoldMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable sales order hold process</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesHoldProcessEnable</p></td>
<td><p>Set up hold codes and reference data to enable the order hold process</p></td>
</tr>
<tr class="even">
<td><p>Maintain sales order</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesOrderMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Purge sales orders</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesPurgeBatchProcess</p></td>
<td><p>Maintain the sales order purge processes</p></td>
</tr>
<tr class="even">
<td><p>Maintain sales order completion</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesTableCompleteMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Update gift card information</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSalesTableUpdateGiftCardMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain full text search</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRSearchMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain up and cross-selling</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRUpSellCrossMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into product builder configuration data</p></td>
<td><p>PBAProductBuilderConfigStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into product configuration</p></td>
<td><p>PCProductConfigConfigurationStatInquir</p></td>
<td><p>Respond to inquiries about constraint-based product configuration model configuration master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain activation of product configuration model versions</p></td>
<td><p>PCProductConfigModelVersionActivate</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Commodity pricing</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsComdPricingMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approves customer rebate agreement</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsRebateAgreementApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintains customer rebate agreements</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsRebateAgreementMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain rebate payments</p></td>
<td><p>PdsRebatePaymentMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain customer rebates</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsRebateTableMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into product sales prices and discount master</p></td>
<td><p>PriceDiscProdSalesPriceDiscMasterInquir</p></td>
<td><p>Respond to inquiries about product sales prices and discount master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain product prices and discount master</p></td>
<td><p>PriceDiscProductPriceDiscMasterMaintain</p></td>
<td><p>Maintain product prices and discount master</p></td>
</tr>
<tr class="even">
<td><p>Approve product prices and discounts</p></td>
<td><p>PriceDiscProductPricesDiscountsApprove</p></td>
<td><p>Approve and authorize product prices and discounts</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales document print management settings</p></td>
<td><p>PrintMgmtSalesDocumentSettingsMaintain</p></td>
<td><p>Maintain sales document print management settings.</p></td>
</tr>
<tr class="even">
<td><p>Maintain project master</p></td>
<td><p>ProjProjectMasterMaintain</p></td>
<td><p>Maintain project master</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into CTP</p></td>
<td><p>ReqCtpStatusInquire</p></td>
<td><p>Respond to inquiries about capable to promise (CTP) requests</p></td>
</tr>
<tr class="even">
<td><p>Approve return acknowledgement</p></td>
<td><p>ReturnAcknowledgementApprove</p></td>
<td><p>Approve and authorize return acknowledgement</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales return order progress</p></td>
<td><p>ReturnSalesReturnOrderProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the sales return order process</p></td>
</tr>
<tr class="even">
<td><p>Maintain sales fiscal document</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>SalesFiscalDocumentMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales order entry deadlines</p></td>
<td><p>SalesOrderEntryDeadlineMaintain</p></td>
<td><p>Maintain sales order entry deadlines</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales order progress</p></td>
<td><p>SalesOrderProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the sales order process</p></td>
</tr>
<tr class="odd">
<td><p>Review sales orders process performance</p></td>
<td><p>SalesOrdersProcessPerformanceReview</p></td>
<td><p>Monitor sales orders</p></td>
</tr>
<tr class="even">
<td><p>Inquire into quotation progress</p></td>
<td><p>SalesQuotationProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the quotation process</p></td>
</tr>
<tr class="odd">
<td><p>Enable quotation to sales order process</p></td>
<td><p>SalesQuotationToSalesOrderProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the quotation to sales order process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into service agreement master</p></td>
<td><p>SMAServiceAgreementMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into service orders</p></td>
<td><p>SMAServiceOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain service subscriptions</p></td>
<td><p>SMAServiceSubscriptionSMAintain</p></td>
<td><p>Document and record service subscriptions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain activities</p></td>
<td><p>smmActivitiesMaintain</p></td>
<td><p>Maintain activities</p></td>
</tr>
<tr class="even">
<td><p>Inquire into activities</p></td>
<td><p>smmActivityInquire</p></td>
<td><p>Respond to inquiries about activity data</p></td>
</tr>
<tr class="odd">
<td><p>Enable activity process</p></td>
<td><p>smmActivityProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the activity process</p></td>
</tr>
<tr class="even">
<td><p>Review activity process</p></td>
<td><p>smmActivityProcessReview</p></td>
<td><p>Monitor, analyze, and improve the activity process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into activity reference data</p></td>
<td><p>smmActivityReferenceDataInquire</p></td>
<td><p>Respond to inquiries about activity reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into prospect master</p></td>
<td><p>smmBusinessRelationMasterInquire</p></td>
<td><p>Respond to inquiries about prospects master data</p></td>
</tr>
<tr class="odd">
<td><p>Review prospects</p></td>
<td><p>smmBusinessRelationMasterReview</p></td>
<td><p>Monitor, analyze, and improve the prospects</p></td>
</tr>
<tr class="even">
<td><p>Enable prospect process</p></td>
<td><p>smmBusinessRelationProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the prospect process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into prospect reference data</p></td>
<td><p>smmBusinessRelationReferenceDataInquire</p></td>
<td><p>Respond to inquiries about prospect master reference data</p></td>
</tr>
<tr class="even">
<td><p>Review campaign process</p></td>
<td><p>smmCampaginProcessReview</p></td>
<td><p>Monitor, analyze, and improve the campaign process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into campaign progress</p></td>
<td><p>smmCampaignProgressInquire</p></td>
<td><p>Respond to inquiries about the status of campaigns</p></td>
</tr>
<tr class="even">
<td><p>Maintain campaigns</p></td>
<td><p>smmCampaignsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain competitors</p></td>
<td><p>smmCompetitorsMaintain</p></td>
<td><p>Maintain competitors</p></td>
</tr>
<tr class="even">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="odd">
<td><p>Enable contact process</p></td>
<td><p>smmContactProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the contact process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into contact reference data</p></td>
<td><p>smmContactReferenceDataInquire</p></td>
<td><p>Respond to inquiries about contact master reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Sales and marketing policies</p></td>
<td><p>smmCRMPolicyInquire</p></td>
<td><p>Respond to inquiries about policies governing the Sales and marketing process</p></td>
</tr>
<tr class="even">
<td><p>Enable the Sales and marketing process</p></td>
<td><p>smmCRMProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the Sales and marketing process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Sales and marketing reference data</p></td>
<td><p>smmCRMReferenceDataInquire</p></td>
<td><p>Respond to inquiries about Sales and marketing reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into knowledge articles</p></td>
<td><p>smmKnowledgeArticlesInquire</p></td>
<td><p>Respond to inquiries about knowledge article data</p></td>
</tr>
<tr class="odd">
<td><p>Review leads and opportunities</p></td>
<td><p>smmLeadsAndOppoortunitiesReview</p></td>
<td><p>Monitor, analyze, and improve leads and opportunities</p></td>
</tr>
<tr class="even">
<td><p>Inquire into leads and opportunities</p></td>
<td><p>smmLeadsAndOpportunitiesInquire</p></td>
<td><p>Respond to inquiries about lead and opportunity data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain leads and opportunities</p></td>
<td><p>smmLeadsAndOpportunititiesMaintain</p></td>
<td><p>Configure and maintain leads and opportunities</p></td>
</tr>
<tr class="even">
<td><p>Inquire into marketing policies</p></td>
<td><p>smmMarketingPolicyInquire</p></td>
<td><p>Respond to inquiries about policies governing the marketing and telemarketing process</p></td>
</tr>
<tr class="odd">
<td><p>Enable marketing process</p></td>
<td><p>smmMarketingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the marketing and telemarketing process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into marketing reference data</p></td>
<td><p>smmMarketingReferenceData</p></td>
<td><p>Respond to inquiries about marketing and telemarketing reference data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain Microsoft Outlook synchronization</p></td>
<td><p>smmOutlookSynchronizationMaintain</p></td>
<td><p>Configure and maintain Microsoft Outlook synchronization</p></td>
</tr>
<tr class="even">
<td><p>Prospect turnover</p></td>
<td><p>smmProspectsTurnoverGenerate</p></td>
<td><p>Create turnover report for prospects</p></td>
</tr>
<tr class="odd">
<td><p>Review sales target process</p></td>
<td><p>smmSalesTargetProcessReview</p></td>
<td><p>Monitor, analyze, and improve the sales target process</p></td>
</tr>
<tr class="even">
<td><p>Maintain sites service solution in sales and marketing module</p></td>
<td><p>smmSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into telemarketing</p></td>
<td><p>smmTelemarketingInquire</p></td>
<td><p>Respond to inquiries about telemarketing</p></td>
</tr>
<tr class="even">
<td><p>Maintain telemarketing</p></td>
<td><p>smmTelemarketingMaintain</p></td>
<td><p>Respond to inquiries about telemarketing</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into telemarketing progress</p></td>
<td><p>smmTelemarketingProgressInquire</p></td>
<td><p>Respond to inquiries about the status of telemarketing cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales supplementary items master</p></td>
<td><p>SupSalesSupplementaryItemsMasterInquire</p></td>
<td><p>Respond to inquiries about sales supplementary items master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales supplementary items master</p></td>
<td><p>SupSalesSupplementaryItemsMasterMaintai</p></td>
<td><p>Maintain sales supplementary items master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain trade allowance inquiries</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TAMAllowanceInquiryMaintain</p></td>
<td><p>Process and review trade allowances</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bill back rebates</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TAMBillBackInquire</p></td>
<td><p>View bill back rebates</p></td>
</tr>
<tr class="even">
<td><p>Maintain trade allowances</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TAMMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales tax transaction status</p></td>
<td><p>TaxSalesTaxTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of sales tax transactions</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


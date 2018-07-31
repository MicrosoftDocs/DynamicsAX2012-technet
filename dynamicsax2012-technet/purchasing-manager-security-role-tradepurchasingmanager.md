---
title: Purchasing manager security role (TradePurchasingManager)
TOCTitle: Purchasing manager security role (TradePurchasingManager)
ms:assetid: 39b5742f-e483-4091-bfe9-505802669119
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527081(v=AX.60)
ms:contentKeyID: 37823133
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Purchasing manager security role (TradePurchasingManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Purchasing manager security role represents a user who reviews purchasing process performance and enables the purchasing process.

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
<td><p>Maintain purchase agreement master</p></td>
<td><p>AgreementPurchaseAgreementMasterMaintai</p></td>
<td><p>Maintain purchase agreement master</p></td>
</tr>
<tr class="even">
<td><p>Configure AIF synchronization</p></td>
<td><p>AifSyncConfigure</p></td>
<td><p>Allows specifying filters on ports</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Enable case management</p></td>
<td><p>CaseCaseManagementEnable</p></td>
<td><p>Set up policies and reference data to enable the case management process</p></td>
</tr>
<tr class="odd">
<td><p>Review case process</p></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
</tr>
<tr class="even">
<td><p>Maintain cases</p></td>
<td><p>CaseCasesMaintain</p></td>
<td><p>Maintain cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchasing cases</p></td>
<td><p>CasePurchasingCasesMaintain</p></td>
<td><p>Maintain purchasing cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into catalogs</p></td>
<td><p>CatProcurementCatalogMasterInquire</p></td>
<td><p>View all types of catalogs</p></td>
</tr>
<tr class="odd">
<td><p>Enable accounting for customs duty process</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CustomsDutyProcessEnable_RU</p></td>
<td><p>Set up required customs duty information to enable accounting for customs duty process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into external items descriptions master</p></td>
<td><p>CustVendExternalItemMasterInquire</p></td>
<td><p>Respond to inquiries about customers and vendors external item descriptions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain external items descriptions master</p></td>
<td><p>CustVendExternalItemMasterMaintain</p></td>
<td><p>Maintain customers and vendors external item descriptions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into category hierarchy details</p></td>
<td><p>EcoResCategoryMasterInquire</p></td>
<td><p>Respond to inquiries about category hierarchy master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain all category hierarchy details</p></td>
<td><p>EcoResCategoryMasterMaintain</p></td>
<td><p>Category maintenance</p></td>
</tr>
<tr class="even">
<td><p>Inquire into products definition master</p></td>
<td><p>EcoResProductDefinitionMasterInquire</p></td>
<td><p>Respond to inquiries about products definition master data</p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic Role center URL</p></td>
</tr>
<tr class="even">
<td><p>Maintain supply forecasts</p></td>
<td><p>ForecastSupplyForecastMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain intercompany master scheduling</p></td>
<td><p>InterCompanyMasterSchedulingMaintain</p></td>
<td><p>Document and record intercompany master scheduling</p></td>
</tr>
<tr class="even">
<td><p>Enable intercompany planning process</p></td>
<td><p>IntercompanyPlanningProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the intercompany master scheduling process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into quality control progress</p></td>
<td><p>InventQualityControlProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the quality control process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="odd">
<td><p>Maintain tracking dimensions master</p></td>
<td><p>InventTrackingDimensionsMasterMaintain</p></td>
<td><p>Maintain serial and batch numbers</p></td>
</tr>
<tr class="even">
<td><p>Inquire into product builder configuration data</p></td>
<td><p>PBAProductBuilderConfigStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Commodity pricing</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsComdPricingMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into product purchase prices and discount master</p></td>
<td><p>PriceDiscProdPurchPriceDiscMasterInquir</p></td>
<td><p>Respond to inquiries about product purchase prices and discount master data</p></td>
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
<td><p>Maintain purchase setup print management settings</p></td>
<td><p>PrintMgmtPurchaseSettingsMaintain</p></td>
<td><p>Maintain purchase setup print management settings</p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase document print management settings</p></td>
<td><p>PrintMgmtPurchDocumentSettingsMaintain</p></td>
<td><p>Maintain purchase document print management settings.</p></td>
</tr>
<tr class="odd">
<td><p>Review all purchasing reports</p></td>
<td><p>ProcPurchaseProcessReview</p></td>
<td><p>View all reports related to the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Enable purchasing process</p></td>
<td><p>ProcPurchasingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchasing process for public sector</p></td>
<td><p>ProcPurchasingProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase agreement activity summary</p></td>
<td><p>PurchAgreementActivitiesSummaryMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View purchase agreement certification compliance report</p></td>
<td><p>PurchAgreementCertComplianceMaintain</p></td>
<td><p>View purchase agreement certification compliance report</p></td>
</tr>
<tr class="even">
<td><p>Maintain child purchase agreements</p></td>
<td><p>PurchAgreementChildMaintain_PSN</p></td>
<td><p>Maintain child purchase agreements</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase agreement department authorization</p></td>
<td><p>PurchAgreementFinDimAccessMaintain_PSN</p></td>
<td><p>Document and record information about the departments authorized to use a purchase agreement</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase agreement tree</p></td>
<td><p>PurchAgreementTreeInquire_PSN</p></td>
<td><p>Respond to inquiries about the hierarchical list of purchase agreements</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase agreement tree</p></td>
<td><p>PurchAgreementTreeMaintain_PSN</p></td>
<td><p>Maintain the hierarchical list of purchase agreements</p></td>
</tr>
<tr class="even">
<td><p>Approve purchase agreement</p></td>
<td><p>PurchaseAgreementWFMaintain</p></td>
<td><p>Approve purchase agreement</p></td>
</tr>
<tr class="odd">
<td><p>Approve purchase order</p></td>
<td><p>PurchOrderApprove</p></td>
<td><p>Approve and authorize purchase order document</p></td>
</tr>
<tr class="even">
<td><p>Review purchase order process performance</p></td>
<td><p>PurchOrderProcessPerformanceReview</p></td>
<td><p>Monitor purchase orders</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchase order to invoice process</p></td>
<td><p>PurchOrderToInvoiceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Enable purchase order to invoice process for public sector</p></td>
<td><p>PurchOrderToInvoiceProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase order to invoice progress</p></td>
<td><p>PurchOrderToInvoiceProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice progress for public sector</p></td>
<td><p>PurchOrderToInvoiceProgressInquire_PSN</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase order to invoice reference data</p></td>
<td><p>PurchOrderToInvoiceReferenceDataInquire</p></td>
<td><p>Respond to inquiries about purchase order to invoice reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase requisition consolidation</p></td>
<td><p>PurchReqConsolidationReview</p></td>
<td><p>Monitor, analyze and improve the purchase requisition consolidation process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain creation of purchase orders from purchase requisitions</p></td>
<td><p>PurchReqOrderFromRequisitionMaintain</p></td>
<td><p>Release purchase orders from purchase requisitions</p></td>
</tr>
<tr class="even">
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
</tr>
<tr class="even">
<td><p>Maintain all purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionMaintainAll</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain document services operation</p></td>
<td><p>PurchRFQFormLetterSendProcessMaintain</p></td>
<td><p>Send/receive RFQ</p></td>
</tr>
<tr class="even">
<td><p>Maintain request for quotations questionnaire</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchRFQQuestionnaireMaintain</p></td>
<td><p>Maintain request for quotations questionnaire</p></td>
</tr>
<tr class="odd">
<td><p>Approve request for quotations</p></td>
<td><p>PurchRFQRequestForQuoteApprove</p></td>
<td><p>Approve request for quotations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into request for quotation reply status</p></td>
<td><p>PurchRFQRequestForQuoteReplyInquire</p></td>
<td><p>Respond to inquiries about the status of request for quotation replies</p></td>
</tr>
<tr class="odd">
<td><p>Maintain request for quotation replies</p></td>
<td><p>PurchRFQRequestForQuoteReplyMaintain</p></td>
<td><p>Maintain request for quotation replies</p></td>
</tr>
<tr class="even">
<td><p>Review request for quotation performance</p></td>
<td><p>PurchRFQRequestForQuoteReview</p></td>
<td><p>Monitor request for quotation performance</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sealed bids</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchRFQSealedBids</p></td>
<td><p>Maintain sealed bids</p></td>
</tr>
<tr class="even">
<td><p>PurchSolicitationTypeMaintain</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchRFQSolicitationTypeMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites service solution and online pages available in procurement and sourcing area</p></td>
<td><p>PurchRFQSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into CTP</p></td>
<td><p>ReqCtpStatusInquire</p></td>
<td><p>Respond to inquiries about capable to promise (CTP) requests</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into planned orders</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqPlannedOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into planned purchase orders</p></td>
<td><p>ReqPlannedPurchaseOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase supplementary items master</p></td>
<td><p>SupPurchSupplementaryItemsMasterInquire</p></td>
<td><p>Respond to inquiries about purchase supplementary items master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase supplementary items master</p></td>
<td><p>SupPurchSupplementaryItemsMasterMaintai</p></td>
<td><p>Maintain purchase supplementary items master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor rebate agreements</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TAMVendRebateAgreementMaintain</p></td>
<td><p>Create and manage vendor rebate agreements</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor rebates</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TAMVendRebateInquire</p></td>
<td><p>View vendor rebates</p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase agreement type</p></td>
<td><p>VendCertificationTypeMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View purchase agreement type</p></td>
<td><p>VendCertificationTypeView</p></td>
<td><p>View purchase agreement type</p></td>
</tr>
<tr class="even">
<td><p>Inquire about payment status for vendor invoices</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>VendInvoice4paymentStatusInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for vendor invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into prospective vendor master</p></td>
<td><p>VendProspectiveVendorMasterInquire</p></td>
<td><p>Respond to inquiries about prospective vendor master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into employee-initiated vendor request status</p></td>
<td><p>VendRequestEmployeeVendorRequestInquire</p></td>
<td><p>Respond to inquiries about status on employee-initiated vendor requests</p></td>
</tr>
<tr class="odd">
<td><p>Maintain document services operation</p></td>
<td><p>VendRequestSignupServiceMaintain</p></td>
<td><p>Read/create unsolicited vendors and inquire about category information</p></td>
</tr>
<tr class="even">
<td><p>Activate, deactivate, update and synchronize unsolicited vendor sites solution</p></td>
<td><p>VendRequestSignupSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor-initiated request status</p></td>
<td><p>VendRequestVendorInitiateRequestInquire</p></td>
<td><p>Respond to inquiries about status on vendor-initiated requests</p></td>
</tr>
<tr class="even">
<td><p>Inquire into unsolicited vendor master</p></td>
<td><p>VendUnsolicitedVendorMasterInquire</p></td>
<td><p>Respond to inquiries about unsolicited vendor master data</p></td>
</tr>
<tr class="odd">
<td><p>Approve vendor user requests</p></td>
<td><p>VendUserRequestApprove</p></td>
<td><p>View and approve vendor user requests</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor master</p></td>
<td><p>VendVendorMasterInquire</p></td>
<td><p>Respond to inquiries about vendor master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor master</p></td>
<td><p>VendVendorMasterMaintain</p></td>
<td><p>Maintain vendor master</p></td>
</tr>
<tr class="even">
<td><p>Enable vendor process</p></td>
<td><p>VendVendorProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the vendor process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor questionnaire progress</p></td>
<td><p>VendVendorQuestionnaireInquire</p></td>
<td><p>Respond to inquiries about vendor questionnaires</p></td>
</tr>
<tr class="even">
<td><p>Inquire into performance of workflow participants</p></td>
<td><p>WorkflowViewWorkflowParticipantsPerf</p></td>
<td><p>Respond to inquiries about status on performance of workflow participants</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workflow performance</p></td>
<td><p>WorkflowViewWorkflowPerf</p></td>
<td><p>View reports about the performance of workflows</p></td>
</tr>
</tbody>
</table>

  



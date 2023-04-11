---
title: Purchasing agent - Public Sector security role (VendPurchasingAgent_PSN)
TOCTitle: Purchasing agent - Public Sector security role (VendPurchasingAgent_PSN)
ms:assetid: 15108371-3071-48fb-8002-92b4c9f1c5e0
ms:mtpsurl: https://technet.microsoft.com/library/JJ900461(v=AX.60)
ms:contentKeyID: 50557236
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Purchasing agent - Public Sector security role (VendPurchasingAgent\_PSN) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Purchasing agent – Public Sector security role supports the public sector extensions for the Project management module. Assign this role in addition to the Purchasing agent role to give purchasing agents access to purchasing functionality for the public sector.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Ee355075.alert_security(AX.60).gif" title="Security note" alt="Security note" /><strong>Security Note</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>This role is available only if Microsoft Dynamics AX 2012 R2 is installed.</p></td>
</tr>
</tbody>
</table>


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
<td><p>Inquire into purchasing case progress</p></td>
<td><p>CasePurchasingCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of purchasing cases</p></td>
</tr>
<tr class="even">
<td><p>Maintain catalogs</p></td>
<td><p>CatProcurementCatalogMasterMaintain</p></td>
<td><p>Maintain all types of catalogs</p></td>
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
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>Inquire into product builder configuration data</p></td>
<td><p>PBAProductBuilderConfigStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain product builder configuration</p></td>
<td><p>PBAProductBuilderConfigurationMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain product configuration</p></td>
<td><p>PCProductConfigConfigurationMaintain</p></td>
<td><p>Maintain a constraint-based product configuration model configuration</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into product configuration</p></td>
<td><p>PCProductConfigConfigurationStatInquir</p></td>
<td><p>Respond to inquiries about constraint-based product configuration model configuration master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase setup print management settings</p></td>
<td><p>PrintMgmtPurchaseSettingsMaintain</p></td>
<td><p>Maintain purchase setup print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase document print management settings</p></td>
<td><p>PrintMgmtPurchDocumentSettingsMaintain</p></td>
<td><p>Maintain purchase document print management settings.</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchasing policies</p></td>
<td><p>ProcPurchasingProcessInquire</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchasing policies for public sector</p></td>
<td><p>ProcPurchasingProcessInquire_PSN</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Approve purchase agreement</p></td>
<td><p>PurchaseAgreementWFMaintain</p></td>
<td><p>Approve purchase agreement</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase orders</p></td>
<td><p>PurchOrderMaintain</p></td>
<td><p>Document and record purchase order</p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase requisition consolidation</p></td>
<td><p>PurchReqConsolidationMaintain</p></td>
<td><p>Maintain the purchase requisition consolidation process</p></td>
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
<td><p>Maintain all purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionMaintainAll</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View purchase requisitions on hold</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchReqTableView</p></td>
<td><p>View purchase requisitions on hold</p></td>
</tr>
<tr class="odd">
<td><p>Maintain request for quotations questionnaire</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchRFQQuestionnaireMaintain</p></td>
<td><p>Maintain request for quotations questionnaire</p></td>
</tr>
<tr class="even">
<td><p>Maintain request for quotations</p></td>
<td><p>PurchRFQRequestForQuoteMaintain</p></td>
<td><p>Maintain request for quotations</p></td>
</tr>
<tr class="odd">
<td><p>Maintain request for quotation replies</p></td>
<td><p>PurchRFQRequestForQuoteReplyMaintain</p></td>
<td><p>Maintain request for quotation replies</p></td>
</tr>
<tr class="even">
<td><p>Maintain sealed bids</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchRFQSealedBids</p></td>
<td><p>Maintain sealed bids</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about payment status for vendor invoices</p></td>
<td><p>VendInvoice4paymentStatusInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor invoices for payment</p></td>
<td><p>VendInvoice4PaymMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain prospective vendor master</p></td>
<td><p>VendProspectiveVendorMasterMaintain</p></td>
<td><p>Maintain prospective vendor master</p></td>
</tr>
<tr class="even">
<td><p>Maintain employee-initiated vendor requests</p></td>
<td><p>VendRequestEmployeeVendorRequestMaintain</p></td>
<td><p>Document and record employee initiated vendor requests</p></td>
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
<td><p>Maintain vendor user requests</p></td>
<td><p>VendUserRequestMaintain</p></td>
<td><p>Maintain and submit vendor user requests</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor master</p></td>
<td><p>VendVendorMasterMaintain</p></td>
<td><p>Maintain vendor master</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor questionnaires</p></td>
<td><p>VendVendorQuestionnaireMaintain</p></td>
<td><p>Create and update vendor questionnaire information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into workflow performance</p></td>
<td><p>WorkflowViewWorkflowPerf</p></td>
<td><p>View reports about the performance of workflows</p></td>
</tr>
</tbody>
</table>

  



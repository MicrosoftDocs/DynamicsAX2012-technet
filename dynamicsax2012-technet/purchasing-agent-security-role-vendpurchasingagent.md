---
title: Purchasing agent security role (VendPurchasingAgent)
TOCTitle: Purchasing agent security role (VendPurchasingAgent)
ms:assetid: 517ab538-045f-44ed-bec2-8e96ec5f25db
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527091(v=AX.60)
ms:contentKeyID: 37823143
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Purchasing agent security role (VendPurchasingAgent) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Purchasing agent security role represents a user who documents purchasing events and responds to purchasing inquiries.

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
<td><p>Configure AIF synchronization</p></td>
<td><p>AifSyncConfigure</p></td>
<td><p>Allows specifying filters on ports</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchasing case progress</p></td>
<td><p>CasePurchasingCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of purchasing cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain catalogs</p></td>
<td><p>CatProcurementCatalogMasterMaintain</p></td>
<td><p>Maintain all types of catalogs</p></td>
</tr>
<tr class="even">
<td><p>Maintain all category hierarchy details</p></td>
<td><p>EcoResCategoryMasterMaintain</p></td>
<td><p>Category maintenance</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into products definition master</p></td>
<td><p>EcoResProductDefinitionMasterInquire</p></td>
<td><p>Respond to inquiries about products definition master data</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
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
<td><p>Maintain price details</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPriceHistoryMaintain</p></td>
<td><p>Maintain the ability to view price details in sales orders</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase order details</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRPurchMaintain</p></td>
<td><p>Maintain purchase order details</p></td>
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
<td><p>Maintain purchase orders</p></td>
<td><p>PurchOrderMaintain</p></td>
<td><p>Document and record purchase order</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase requisition consolidation</p></td>
<td><p>PurchReqConsolidationMaintain</p></td>
<td><p>Maintain the purchase requisition consolidation process</p></td>
</tr>
<tr class="even">
<td><p>Maintain creation of purchase orders from purchase requisitions</p></td>
<td><p>PurchReqOrderFromRequisitionMaintain</p></td>
<td><p>Release purchase orders from purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="even">
<td><p>Maintain all purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionMaintainAll</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View purchase requisitions on hold</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchReqTableView</p></td>
<td><p>View purchase requisitions on hold</p></td>
</tr>
<tr class="even">
<td><p>Maintain request for quotations questionnaire</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchRFQQuestionnaireMaintain</p></td>
<td><p>Maintain request for quotations questionnaire</p></td>
</tr>
<tr class="odd">
<td><p>Maintain request for quotations</p></td>
<td><p>PurchRFQRequestForQuoteMaintain</p></td>
<td><p>Maintain request for quotations</p></td>
</tr>
<tr class="even">
<td><p>Maintain request for quotation replies</p></td>
<td><p>PurchRFQRequestForQuoteReplyMaintain</p></td>
<td><p>Maintain request for quotation replies</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sealed bids</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PurchRFQSealedBids</p></td>
<td><p>Maintain sealed bids</p></td>
</tr>
<tr class="even">
<td><p>Review average VAT</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxAverageVATReview</p></td>
<td><p>Review average VAT details via the average VAT report</p></td>
</tr>
<tr class="odd">
<td><p>View tax branches</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxBranchView</p></td>
<td><p>Set up tax branch details</p></td>
</tr>
<tr class="even">
<td><p>Review unrealized VAT</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxUnrealizdVATRemainingReview</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire about payment status for vendor invoices</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>VendInvoice4paymentStatusInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor invoices for payment</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>VendInvoice4PaymMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor hold status</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>VendOnHoldUpdate</p></td>
<td><p>Maintain vendor hold status</p></td>
</tr>
<tr class="even">
<td><p>Maintain prospective vendor master</p></td>
<td><p>VendProspectiveVendorMasterMaintain</p></td>
<td><p>Maintain prospective vendor master</p></td>
</tr>
<tr class="odd">
<td><p>Maintain employee-initiated vendor requests</p></td>
<td><p>VendRequestEmployeeVendorRequestMaintain</p></td>
<td><p>Document and record employee initiated vendor requests</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor-initiated request status</p></td>
<td><p>VendRequestVendorInitiateRequestInquire</p></td>
<td><p>Respond to inquiries about status on vendor-initiated requests</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into unsolicited vendor master</p></td>
<td><p>VendUnsolicitedVendorMasterInquire</p></td>
<td><p>Respond to inquiries about unsolicited vendor master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor user requests</p></td>
<td><p>VendUserRequestMaintain</p></td>
<td><p>Maintain and submit vendor user requests</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor master</p></td>
<td><p>VendVendorMasterMaintain</p></td>
<td><p>Maintain vendor master</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor questionnaires</p></td>
<td><p>VendVendorQuestionnaireMaintain</p></td>
<td><p>Create and update vendor questionnaire information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workflow performance</p></td>
<td><p>WorkflowViewWorkflowPerf</p></td>
<td><p>View reports about the performance of workflows</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Employee security role (HCMEmployee)
TOCTitle: Employee security role (HCMEmployee)
ms:assetid: 65f140fb-ed4e-44e9-bba3-31a4a8c1be56
ms:mtpsurl: https://technet.microsoft.com/library/Hh527099(v=AX.60)
ms:contentKeyID: 37823151
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Employee security role (HCMEmployee) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Employee security role represents a worker who is employed by a legal entity.

By default, the [Time registration worker security role (JmgAdvTimeWorker)](time-registration-worker-security-role-jmgadvtimeworker.md) is a subordinate role of this security role. This means that when a user is assigned to this security role, they automatically gain access to the duties in the subordinate role, as well.

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
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="even">
<td><p>Maintain shopping carts</p></td>
<td><p>CatShoppingCartMaintain</p></td>
<td><p>Maintain shopping cart line items</p></td>
</tr>
<tr class="odd">
<td><p>Maintain confirmation of product receipts</p></td>
<td><p>EPPurchCORConfOfReceiptsMaintain</p></td>
<td><p>Document and record confirmation of product receipts</p></td>
</tr>
<tr class="even">
<td><p>Maintain rejected confirmation of product receipts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EPPurchCORConfOfReceiptsRejectMaintain</p></td>
<td><p>Document and record rejected confirmation of product receipts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into employee information (Enterprise Portal)</p></td>
<td><p>HcmEPEmployeeInquire</p></td>
<td><p>Respond to inquiries about employee information using Enterprise Portal</p></td>
</tr>
<tr class="even">
<td><p>Maintain employee information (Enterprise Portal)</p></td>
<td><p>HcmEPemployeemaintenance</p></td>
<td><p>Maintain employee information using Enterprise Portal</p></td>
</tr>
<tr class="odd">
<td><p>Maintain organizational access (Enterprise Portal)</p></td>
<td><p>HcmEPOrganizationalMaintain</p></td>
<td><p>Maintain access to organizational information using Enterprise Portal</p></td>
</tr>
<tr class="even">
<td><p>Maintain access to questionnaires (Enterprise Portal)</p></td>
<td><p>HcmEPQuestionnaireMaintain</p></td>
<td><p>Maintain access to questionnaires using Enterprise Portal</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into signing limit status</p></td>
<td><p>HRPSigningLimitInquire</p></td>
<td><p>Respond to inquiries about status of signing limits</p></td>
</tr>
<tr class="even">
<td><p>Maintain signing limits</p></td>
<td><p>HRPSigningLimitMaintain</p></td>
<td><p>Respond to inquiries about signing limits</p></td>
</tr>
<tr class="odd">
<td><p>Service operations for purchase requisitions</p></td>
<td><p>PurchReqPurchaseReqServiceOperations</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionMaintain</p></td>
<td><p>Maintain the purchase requisition process</p></td>
</tr>
<tr class="odd">
<td><p>Service operations for expense management</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TrvTravelAndExpenseServiceOperations</p></td>
<td><p>Utilize service operations for expense management</p></td>
</tr>
<tr class="even">
<td><p>Approve travel requisitions and expenses</p></td>
<td><p>TrvTravelRequestsAndExpensesApprove</p></td>
<td><p>Approve and authorize travel requisitions and expenses</p></td>
</tr>
<tr class="odd">
<td><p>Maintain travel requisitions and expenses</p></td>
<td><p>TrvTravelRequestsAndExpensesMaintain</p></td>
<td><p>Document and record travel requisitions and expenses</p></td>
</tr>
<tr class="even">
<td><p>Approve vendor invoices as employee</p></td>
<td><p>VendInvoiceVendInvEmployeeApprove</p></td>
<td><p>Approve vendor invoices from employee portal</p></td>
</tr>
<tr class="odd">
<td><p>Maintain employee-initiated vendor requests</p></td>
<td><p>VendRequestEmployeeVendorRequestMaintain</p></td>
<td><p>Document and record employee initiated vendor requests</p></td>
</tr>
<tr class="even">
<td><p>Maintain automatic workflow delegation</p></td>
<td><p>WorkflowDelegationSettingsMaintain</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  



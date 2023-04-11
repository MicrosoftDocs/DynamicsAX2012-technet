---
title: Approve check and credit card refunds
TOCTitle: Approve check and credit card refunds
ms:assetid: 7e68104c-210f-4171-831a-10d94d5ffaa1
ms:mtpsurl: https://technet.microsoft.com/library/Dn497794(v=AX.60)
ms:contentKeyID: 62200107
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- refunds
- Forms.MCRCCRefundApproval
- MsDynAx060.Forms.MCRRefundCheckApproval
- Forms.MCRRefundCheckProcessing
- Forms.MCRRefundCheckApproval
- MsDynAx060.Forms.MCRCCRefundApproval
- MsDynAx060.Forms.MCRRefundCheckProcessing
- check refund
- credit card refund
audience: Application User
ms.search.region: Global
---

# Approve check and credit card refunds 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to approve and process refunds for call center customers.

In the **Call center parameters** form, you can set thresholds above which refunds that are issued via check and credit card must be manually approved. For more information, see [Configuring parameters and initial settings (Call center)](configuring-parameters-and-initial-settings-call-center.md). Any refund that exceeds the threshold amount is added to the approval queue. After you approve the refund, the return sales order can be invoiced.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required setup steps</p></td>
<td><p>Create a call center, and add the user who approves refunds to the list of users for the call center:</p>
<p><a href="set-up-a-call-center.md">Set up a call center</a></p>
<p>Set call center parameters:</p>
<p><a href="configuring-parameters-and-initial-settings-call-center.md">Configuring parameters and initial settings (Call center)</a></p></td>
</tr>
<tr class="even">
<td><p>Related process</p></td>
<td><p>Create a return sales order and a refund for a product that was returned.</p></td>
</tr>
</tbody>
</table>


## 1\. Approve a credit card refund

Credit card refunds that require approval are added to the queue in the **Credit card refund approval** form.

To approve a credit card refund, follow these steps.

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Credit cards** \> **Refund approval**.

2.  The **Sales order** field displays the ID for a return sales order. Review the details of the refund that is associated with the order.

3.  Select the refund, and then click **Approve** to approve the refund or **Decline** to decline the refund.

## 2\. Approve and process a check refund

Check refunds that require approval are added to the queue in the **Refund check approval** form. After you approve check refunds, you must create a batch job to print the refund checks.

To approve and process a check refund, follow these steps.

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Refund check** \> **Refund approval**.

2.  On the **Pending approval** tab, review the details of a refund for a return sales order.

3.  Select the refund, and then click **Approve** to approve the refund.

4.  Click **Call center** \> **Journals** \> **Payment management** \> **Refund check** \> **Refund check processing**.

5.  On the **Action Pane**, click **New**.

6.  In the **Show** field, select whether to view all transactions, open transactions, or posted transactions.

7.  The **Transactions** FastTab displays the refunds that have been approved. Select the refunds to include in the batch.
    
    The **Amount** field displays the total amount of the refunds that are included in the batch.

8.  Click **Post** to post the batch, and then click **Print** to print refund checks for the batch.

## Next step

Invoice the sales order for the return.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p>
<p><strong>Payment</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales clerk</p></td>
</tr>
</tbody>
</table>

  



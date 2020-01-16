---
title: Reimburse customers
TOCTitle: Reimburse customers
ms:assetid: c05a5881-84f4-4227-8a41-7c6b9bbd4206
ms:mtpsurl: https://technet.microsoft.com/library/Aa498997(v=AX.60)
ms:contentKeyID: 36059262
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Reimburse customers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to create reimbursement transactions for a group of customers. If a customer has a credit balance, you can reimburse the customer for the amount of the balance. The customer must have an associated vendor account, and the balance amount must exceed the minimum reimbursement amount that is specified for your legal entity.

To reimburse one customer at a time, you can use the **Collections** form. For more information, see [Key tasks: Collections](key-tasks-collections.md).

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Prerequisite</p></th>
<th><p>Instructions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Specify the minimum reimbursement amount for the legal entity</p></td>
<td><ol>
<li><p>Click <strong>Accounts receivable</strong> &gt; <strong>Setup</strong> &gt; <strong>Accounts receivable parameters</strong>.</p></li>
<li><p>In the <strong>General</strong> area, in the <strong>Minimum reimbursement</strong> field, enter the minimum amount for the reimbursement of customer overpayments.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Optional: Add a vendor account to each customer who can be reimbursed</p></td>
<td><ol>
<li><p>Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Customers</strong> &gt; <strong>All customers</strong>.</p></li>
<li><p>Double-click a customer account.</p></li>
<li><p>In the <strong>Customers</strong> form, on the <strong>Action Pane</strong>, click <strong>Edit</strong>.</p></li>
<li><p>Click the <strong>Miscellaneous details</strong> FastTab.</p></li>
<li><p>In the <strong>Vendor account</strong> field, select the vendor account for the customer.</p></li>
<li><p>In the <strong>Vendor account</strong> field, right-click and then select <strong>View details</strong>.</p></li>
<li><p>In the <strong>Vendors</strong> form, on the <strong>Action Pane</strong>, click <strong>Bank accounts</strong> and set up the bank account to use for reimbursement payments to this vendor (who is also your customer).</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Create reimbursement transactions

When you create reimbursement transactions, a vendor invoice is created for the amount of the credit balance. This removes the credit balance for the customer account and creates a balance due for the vendor account that corresponds to the customer.

1.  Click **Accounts receivable** \> **Periodic** \> **Reimbursement**.

2.  To reimburse specific customer accounts, click **Select** and specify the customer accounts in the query. To reimburse all customer accounts, click **OK**.
    
    The credit amounts are transferred to the vendor accounts of the customers and are processed as ordinary payments. If a customer does not have a vendor account, a one-time vendor account is automatically created for the customer.

3.  To view the reimbursement transactions that were created, use the **Reimbursement** form. (Click **Accounts receivable** \> **Reports** \> **Transactions** \> **Payments** \> **Reimbursement**.)

## Next step

In Accounts payable, create a payment for the vendor invoices that were created as a result of the reimbursement process. For more information, see [Select vendor invoices to pay and settle](select-vendor-invoices-to-pay-and-settle.md).

## See also

[Collections (form)](https://technet.microsoft.com/library/hh209726\(v=ax.60\))

[Reimbursement (class form)](https://technet.microsoft.com/library/aa553712\(v=ax.60\))

[Vendor bank accounts (form)](https://technet.microsoft.com/library/aa589805\(v=ax.60\))

  



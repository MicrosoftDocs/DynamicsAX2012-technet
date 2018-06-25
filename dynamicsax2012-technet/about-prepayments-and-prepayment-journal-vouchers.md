---
title: About prepayments and prepayment journal vouchers
TOCTitle: About prepayments and prepayment journal vouchers
ms:assetid: 41c8dacb-6759-4782-a145-222dea1d8a53
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242262(v=AX.60)
ms:contentKeyID: 36056731
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advance
- prepayment
- vendor advance
- prepay
- prepay vendors
- pre-payment
---

# About prepayments and prepayment journal vouchers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Organizations might issue prepayments to vendors for goods or services before those goods or services are fulfilled. To minimize risk, you can track prepayments by defining the prepayment on a purchase order. Vendors can also create a prepayment invoice that is associated with a purchase order.

Organizations that do not want to track prepayments as closely can use prepayment journal vouchers instead of the prepayment feature. You can create prepayment journal vouchers by creating journal entries and marking them as prepayment journal vouchers. However, you cannot track which prepayments are made to a vendor against which purchase orders.

## When to use prepayments or prepayment journal vouchers

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of prepayment</p></th>
<th><p>Modules</p></th>
<th><p>Uses</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Prepayment</p></td>
<td><p>Accounts payable</p></td>
<td><p>You can do the following with prepayments:</p>
<ul>
<li><p>Define prepayments for a purchase order. This includes prepayment limits and purchase categories.</p></li>
<li><p>Record and settle payments against prepayment requests from vendors.</p></li>
<li><p>Apply prepayments against vendor invoices to reduce vendor liability.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Prepayment journal vouchers</p></td>
<td><p>Accounts payable</p>
<p>Accounts receivable</p></td>
<td><p>You can do the following with prepayment journal vouchers:</p>
<ul>
<li><p>Create accounting entries for customer or vendor prepayments.</p></li>
<li><p>Make and settle prepayments that were made to a customer or vendor, and that do not reference a sales order or purchase order.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Overview of the prepayment journal voucher process

Accounting practices in many countries/regions require that prepayments (payments in advance) from a customer or to a vendor are not posted to the usual summary accounts for the customer or vendor. Instead, these prepayments are posted to special ledger accounts for prepayments. When a sales order or purchase order is made, an invoice is issued to the customer or vendor. When the invoice is paid, the prepayment journal voucher and sales tax prepayment voucher on the prepayment ledger accounts are reversed, and the invoice amounts are automatically posted to the usual summary accounts. For more information, see [Post prepayment journal vouchers to prepayment accounts](post-prepayment-journal-vouchers-to-prepayment-accounts.md).

Follow these steps to create a prepayment journal voucher:

1.  Set up prepayment journal vouchers by using posting profiles for prepayment journal vouchers.

2.  Create a journal voucher entry and mark it as a prepayment journal voucher.

3.  Settle the prepayment.

4.  After the vendor delivers the goods or services, the transaction for the prepayment journal voucher is automatically reversed.

5.  Post the payment to the customer or vendor account.

## Overview of the prepayment process

Prepayments are a common business practice, and are advance invoice payments that are made to a vendor before the purchase order is fulfilled. For example, a vendor might require a prepayment for specific goods or services. After the prepayment is paid, your legal entity can later apply the prepayment to one or more invoices from the vendor to offset the amount that was already paid.

Follow these steps to create a prepayment:

1.  The purchasing agent creates, confirms, and then submits a purchase order that has a prepayment associated with it.

2.  The vendor submits a prepayment invoice.

3.  The accounts payable coordinator records the prepayment invoice against the purchase order, and then settles the payment.

4.  After the vendor delivers the goods or services, and the related vendor invoices have been received, the accounts payable coordinator applies the prepayment amount that was already paid against the invoice.

5.  The accounts payable coordinator pays and settles the remaining amount of the invoice.

For more information about the prepayment process, see [Key tasks: Prepayments](key-tasks-prepayments.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


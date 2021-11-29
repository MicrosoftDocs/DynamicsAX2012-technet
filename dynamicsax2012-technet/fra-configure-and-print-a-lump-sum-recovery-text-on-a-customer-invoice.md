---
title: (FRA) Configure and print a lump sum recovery text on a customer invoice
TOCTitle: (FRA) Configure and print a lump sum recovery text on a customer invoice
ms:assetid: 640087d4-b724-4a79-aeb1-b345c70fc15b
ms:mtpsurl: https://technet.microsoft.com/library/Dn304975(v=AX.60)
ms:contentKeyID: 54899957
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTable
- Forms.CustInvoiceJournal
- Forms.SalesEditLines
- FR – 00018
- Forms.CustFormletterParameters
audience: Application User
ms.search.region: France
---

# (FRA) Configure and print a lump sum recovery text on a customer invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Follow the steps in this topic to set up and print the lump sum recovery text that displays the penalty amount on customer invoices.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 5 for AX 2012.</P>



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
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Set up interest calculations. For more information, see <a href="set-up-interest-calculations.md">Set up interest calculations</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Create collection letter sequences. For more information, see <a href="set-up-a-collection-letter-sequence.md">Set up a collection letter sequence</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related tasks</strong></p></td>
<td><p>Create a sales order. For more information, go to <a href="create-or-edit-a-sales-order.md">Create or edit a sales order</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Create a free text invoice. For more information, see <a href="create-free-text-invoices.md">Create free text invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Create a collection letter. For more information, see <a href="create-collection-letters.md">Create collection letters</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. (FRA) Set up the parameters to print a lump sum recovery text on customer invoices

Use the **Form setup** form to set up the parameters to print a lump sum recovery text on customer invoices. The lump sum recovery text contains a penalty amount and the due date of the payment.

To set up the parameters to print a penalty amount on customer invoices, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**.

2.  Click **Invoice**, and then in the **Invoice** area, in the **Lump sum recovery text** field, enter the lump sum recovery text, along with the penalty amount, to print on customer invoices.

3.  In the **Days in grace period for lump sum recovery** field, enter the number of days in the grace period before a penalty is applied. The penalty is applied after the specified number of days from the document date or the invoice date have elapsed.

## 2\. (FRA) Print the lump sum recovery text on a customer invoice

Use the **Posting invoice** form to print the lump sum recovery text that displays the penalty amount on the customer invoices.

To print the lump sum recovery text on a customer invoice, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order to post.

3.  On the **Action Pane**, on the **Invoice** tab, click **Invoice**.

4.  In the **Posting invoice** form, specify the required details. For more information, see [Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\)).

5.  In the lower pane, on the **Overview** tab, the **Print lump sum recovery text** check box is selected for each line. A selected check box indicates that the lump sum recovery text is printed on the customer invoices.

6.  Click **OK** to post the sales order. The lump sum recovery text is printed on the customer invoice.

You can also print the lump sum recovery text on a customer invoice that you print from the **Invoice journal** form. For more information, see [Customer invoice journal (form)](https://technet.microsoft.com/library/aa618201\(v=ax.60\)).

## Related tasks

[Key tasks: Customer invoices](key-tasks-customer-invoices.md)

[Key tasks: Free text invoices](key-tasks-free-text-invoices.md)

[Enter and settle customer payments in a payment journal](enter-and-settle-customer-payments-in-a-payment-journal.md)

[Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md)

[Receive and enter customer payments](receive-and-enter-customer-payments.md)

[(FRA) Apply a penalty when a customer payment is past due](fra-apply-a-penalty-when-a-customer-payment-is-past-due.md)

  



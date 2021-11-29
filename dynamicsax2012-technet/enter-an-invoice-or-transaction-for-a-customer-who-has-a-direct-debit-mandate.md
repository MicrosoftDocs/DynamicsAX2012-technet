---
title: Enter an invoice or transaction for a customer who has a direct debit mandate
TOCTitle: Enter an invoice or transaction for a customer who has a direct debit mandate
ms:assetid: 415961d0-df34-47a5-8292-4e1fb798b699
ms:mtpsurl: https://technet.microsoft.com/library/Dn268414(v=AX.60)
ms:contentKeyID: 54916953
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Enter an invoice or transaction for a customer who has a direct debit mandate 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to create a free text invoice for a customer who has a direct debit mandate. The process is similar for customer invoices for sales orders.

When you enter a customer invoice for a sales order or a free text invoice for a customer who has more than one direct debit mandate, you can select which mandate to use. When you print the invoice, a SEPA direct debit notification section is printed at the bottom of the invoice.

When you enter or generate interest notes, collection letters, project invoices, or journal entries, the default mandate reference that is specified for the customer is used. If necessary, you can use the **Customer transactions** form to change the mandate reference for a transaction after it has been posted.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



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
<td><p>Set up</p></td>
<td><p><a href="set-up-sepa-direct-debit-mandate.md">Set up SEPA direct debit mandate</a></p></td>
</tr>
<tr class="even">
<td><p>Master records</p></td>
<td><p><a href="add-direct-debit-mandate-information-to-a-customer-account.md">Add direct debit mandate information to a customer account</a></p></td>
</tr>
</tbody>
</table>


## Enter a free text invoice for a customer who has a direct debit mandate

To enter a free text invoice for a customer who has a direct debit mandate, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, click **Free text invoice**.

3.  Select a customer who has a direct debit mandate, and enter invoice header and line information. For basic information about how to work with free text invoices, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

4.  Select a method of payment that has the **Require mandate** check box selected.

5.  In the **Direct debit mandate ID** field, select a mandate reference.

6.  On the **Action Pane**, click **Post**.

7.  In the **Post free text invoice** form, select the **Print invoice** check box, and then click **OK**.
    
    The invoice is posted and printed. The SEPA direct debit notification section is printed at the bottom of the invoice.

## Optional: Print a direct debit mandate notification report

You can print a report that shows all invoices that have been posted for a mandate, and that have not yet been paid. You can send this report to a customer to let them know which invoices are scheduled to be paid through the mandate.

To print a direct debit mandate notification report, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer.

3.  On the **Direct debit mandates** FastTab, select a mandate, and then click **Print** \> **Notification report**.

## Next step

You have finished entering an invoice for a customer who has a direct debit mandate. Next, enter a payment. For more information, see [Create payments for customers who have direct debit mandates](create-payments-for-customers-who-have-direct-debit-mandates.md).

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
<td><p>Not applicable</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To enter an invoice or transaction for a customer who has a direct debit mandate, you must be a member of a security role that includes the following duty:</p>
<ul>
<li><p>Maintain customer invoice transactions (CustInvoiceCustomerInvoiceTransMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[SEPA direct debit overview](sepa-direct-debit-overview.md)

  



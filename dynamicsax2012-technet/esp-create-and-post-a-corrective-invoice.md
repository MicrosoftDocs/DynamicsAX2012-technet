---
title: (ESP) Create and post a corrective invoice
TOCTitle: (ESP) Create and post a corrective invoice
ms:assetid: 8279f8cf-63d8-487d-8cae-7ea1c3dea85e
ms:mtpsurl: https://technet.microsoft.com/library/Dn783116(v=AX.60)
ms:contentKeyID: 62830460
author: Khairunj
ms.date: 08/25/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- sales order
- Forms.VendTrans
- project invoice
- free text invoice
- Forms.SalesTable
- credit note
- Forms.ProjInvoiceJournal
- Forms.PurchTable
- Forms.CustFreeInvoice
- Forms.LedgerJournalTable
- Forms.CustTrans
- invoice journal
- corrective invoice
audience: Application User
ms.search.region: Spain
---

# (ESP) Create and post a corrective invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic explains how to create and post a corrective invoice for a posted sales order, purchase order, invoice journal, free text invoice, or project invoice. After creating the corrective invoice, you can link it to the posted original invoice and specify the reason to correct the original invoice.

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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Spain</p></td>
</tr>
<tr class="odd">
<td><p>Related set up</p></td>
<td><ul>
<li><p>Select a number sequence code for the corrective invoice reference in the <strong>Accounts receivable parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/library/aa576993(v=ax.60)">Accounts receivable parameters (form)</a>.</p></li>
<li><p>Create and post a sales order invoice. For more information, see <a href="https://technet.microsoft.com/library/aa585863(v=ax.60)">Sales orders (form)</a>.</p></li>
<li><p>Create and post a purchase order invoice. For more information, see <a href="create-a-purchase-order.md">Create a purchase order</a>.</p></li>
<li><p>Create and post a free text invoice. For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a>.</p></li>
<li><p>Create and post a project invoice proposal. For more information, see <a href="create-and-post-invoice-proposals.md">Create and post invoice proposals</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create and post a corrective invoice for a sales order

Use the **All sales orders** form to create and post a corrective invoice for a posted sales order.

To create and post a corrective invoice for a posted sales order, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the posted sales order, and then click **Edit** to add a sales order line for the returned items.

3.  Specify the item number, the quantity with a negative sign, and the unit price of the item.

4.  Confirm the updated sales order. On the **Invoice** tab, click **Credit invoicing**.

5.  Specify the original invoice number and reason to create the corrective invoice. Click **OK** to close the form.

6.  Click **Invoice** to post a corrective invoice for the updated sales order.

## Create and post a corrective invoice for a purchase order

Use the **All purchase orders** form to create and post a corrective invoice for a posted purchase order.

To create and post a corrective invoice for a purchase order, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  In the **All purchase orders** form, select the posted purchase order, and then click **Edit** to add a purchase order line for the returned items.

3.  Specify the item number, the quantity with a negative sign, and the unit price of the item.

4.  On the **Purchase** tab, on the **Generate** field group, click **Confirmation** to open the **Confirm purchase order** form. Click **OK** to confirm the purchase order.

5.  On the **Invoice** tab, click **Credit invoicing** and specify the original invoice and reason to create the corrective invoice. Click **OK** to close the form.

6.  Click **Invoice** to post a corrective invoice for the updated purchase order.

## Create and post a corrective invoice in a journal

To create and post a corrective invoice in a journal, follow these steps:

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.
    
    –or–
    
    Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New** to create a journal. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Lines** to add a journal line, and then specify an account number, an account type, and an invoice amount.
    

    > [!NOTE]
    > <P>For a vendor account type, enter the invoice amount in the <STRONG>Debit</STRONG> field. For a customer account type, enter the invoice amount in the <STRONG>Credit</STRONG> field.</P>



4.  On the **Invoice** tab, enter the invoice details.

5.  On the **Action Pane**, click **Functions** \> **Credit invoicing**, and specify the original invoice number and the reason to create the corrective invoice.

6.  Click **Post**, and then click **OK** to post the corrective invoice.

## Create and post a corrective invoice for a free text invoice

Use the **Free text invoice** form to create and post a corrective invoice for a posted free text invoice.

To create and post a corrective invoice for a posted free text invoice, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Click **Free text invoice** to create a corrective invoice for the posted free text invoice.

3.  Specify the customer account, main account, quantity of the returned items, and a unit price for the returned items.

4.  On the **Action Pane**, click **Set up** \> **Credit invoicing**, and specify the original invoice number and reason to correct the original invoice.

5.  Click **Post** to post the corrective free text invoice.

## Create and post a corrective invoice for a project invoice

Use the **Invoice proposals** form to create and post a corrective invoice for a posted project invoice.

To create and post a corrective invoice for a project invoice, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoices**.

2.  Select a posted project invoice, and then click **Select for credit note**.

3.  Select the invoice lines to be corrective, and on the **Action Pane**, click **Credit invoicing**.

4.  In the **Credit invoicing** form, enter the reason to correct the project invoice. Click **OK** to close the form.

5.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**.

6.  On the **Action Pane**, click **Invoice proposal** to create a corrective project invoice proposal.

7.  Select the project contract and project to list the transactions for. Select and approve the invoice line that is specified with a corrective reason. For more information, see the [Create and post invoice proposals](create-and-post-invoice-proposals.md).
    

    > [!NOTE]
    > <P>The invoice line amount is displayed with a negative sign in the <STRONG>Create invoice proposal</STRONG> form.</P>



## Verify the list of corrective invoices

Use the **Customer transactions** form or **Vendor transactions** form to verify the corrective invoice that is created for a customer or a vendor.

To verify the corrective invoices for a customer, follow the steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer for which the corrective invoices are to be verified. On the **Action Pane**, click **Transactions**.

3.  Select a transaction from the list and click **View the customer transactions related to credit invoicing** to list the corrective invoices.

To verify the corrective invoices for a vendor, follow the steps:

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor for which the corrective invoices are to be verified. On the **Action Pane**, click **Transactions**.

3.  Select a transaction from the list and click **View the vendor transactions related to credit invoicing** to list the corrective invoices.

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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To create and post a corrective invoice, you must have the following roles:</p>
<ul>
<li><p>Accountant</p></li>
<li><p>Accounts receivable clerk</p></li>
<li><p>Accounts payable clerk</p></li>
<li><p>Accounting supervisor</p></li>
<li><p>Buying agent</p></li>
<li><p>Collections agent</p></li>
<li><p>Collections manager</p></li>
<li><p>Purchasing agent</p></li>
<li><p>Purchasing Agent - Public Sector</p></li>
<li><p>Sales clerk</p></li>
</ul>
<p>To perform this task, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p>CollectionLetterCollectionsTransMaintai</p></li>
<li><p>CustInvoiceCustomerInvoiceTransMaintain</p></li>
<li><p>LedgerJournalsAndTransactionsMaintain</p></li>
<li><p>PurchOrderMaintain</p></li>
<li><p>SalesOrderMaintain</p></li>
<li><p>VendInvoiceVendorInvRegisterMaintain</p></li>
<li><p>VendInvoiceVendorInvoicesMaintain</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create and post a corrective invoice, you must be a member of a security role that includes the following privileges:</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain sales order details</strong></p></td>
<td><p>SalesTableDetailsMaintain</p></td>
<td><p>Create and post a corrective invoice for a sales order</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain purchase order details</strong></p></td>
<td><p>PurchTableDetailsMaintain</p></td>
<td><p>Create and post a corrective invoice for a purchase order</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain general journal transactions</strong></p></td>
<td><p>LedgerJournalTableMaintain</p></td>
<td><p>Create and post a corrective invoice in a journal</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain invoice register journal transactions</strong></p></td>
<td><p>LedgerJournalTable6Maintain</p></td>
<td><p>Create and post a corrective invoice in a journal</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain vendor invoice journal transactions</strong></p></td>
<td><p>LedgerJournalTable9Maintain</p></td>
<td><p>Create and post a corrective invoice in a journal</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain free text invoices</strong></p></td>
<td><p>CustFreeInvoiceMaintain</p></td>
<td><p>Create and post a corrective invoice for a free text invoice</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  



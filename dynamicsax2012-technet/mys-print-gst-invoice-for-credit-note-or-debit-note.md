---
title: (MYS) Print GST invoice for credit note or debit note
TOCTitle: (MYS) Print GST invoice for credit note or debit note
ms:assetid: d75a1a11-dff9-4a43-bd51-aba697a77d39
ms:mtpsurl: https://technet.microsoft.com/library/Dn858083(v=AX.60)
ms:contentKeyID: 63400915
author: tonyafehr
ms.date: 11/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Malaysia
---

# (MYS) Print GST invoice for credit note or debit note 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to print a Malaysian goods and services tax (GST) invoice for a credit note or a debit note. You can print a GST invoice for a credit note or debit note from a sales order, free text invoice, purchase order, or project proposal. The invoice is printed in either full or simplified format, depending on the selection that you make in the **General ledger parameters** form.

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
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 Cumulative Update 8</p></td>
</tr>
<tr class="even">
<td><p>Related setup tasks</p></td>
<td><ol>
<li><p>Create a new tax registration type for Malaysia, and select the <strong>Primary for country</strong> check box in the <strong>Tax registration types</strong> form. For more information, see <a href="https://technet.microsoft.com/library/jj677414(v=ax.60)">Tax registration types (form)</a>.</p></li>
<li><p>Specify a registration type, authority, registration number, effective date, and expiration date for the primary address of the legal entity in the <strong>Edit address</strong> form. For more information, see <a href="https://technet.microsoft.com/library/hh370713(v=ax.60)">Manage addresses (form)</a>.</p></li>
<li><p>Set up print management for Accounts receivable and Accounts payable in the <strong>Print management setup</strong> form. For more information, see <a href="set-up-print-management-for-a-module.md">Set up print management for a module</a>.</p></li>
<li><p>Specify the printing format for the GST invoice by selecting either <strong>Full invoice</strong> or <strong>Simplified invoice</strong> in the <strong>Sales tax</strong> area of the <strong>General ledger parameters</strong> form.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Print a GST invoice for the credit note or debit note of a sales order

To print a GST invoice for the credit note or debit note of a sales order, follow these steps.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Select an invoiced sales order.

2.  On the **Sell** tab, click **Credit note**.

3.  Select the **Select all** check box to select all sales invoice transactions.
    
    –or–
    
    In the lower pane, select the **Mark** check box next to the sales order line to correct the quantity of returned items for.

4.  Specify the reason code, original invoice number, and original invoice date. Then print the credit note or debit note with the GST invoice. For more information, see [Create and print a credit note for customer invoices](create-and-print-a-credit-note-for-customer-invoices.md).
    

    > [!NOTE]
    > <P>If the quantity of the item displays a negative sign, the invoice is a credit note. Otherwise, the adjusted invoice is a debit note.</P>



## Print a GST invoice for the credit note or debit note of a free text invoice

To print a GST invoice for the credit note or debit note of a free text invoice, follow these steps.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**. Select a posted free text invoice.

2.  Adjust the quantity and price of the item for the selected free text invoice.

3.  Specify the reason code, original invoice number, and original invoice date. Then print the free text invoice with the GST invoice. For more information, see [Correct a posted free text invoice](correct-a-posted-free-text-invoice.md).
    

    > [!NOTE]
    > <P>If the quantity of the item displays a negative sign, the invoice is a credit note. Otherwise, else the adjusted invoice is a debit note.</P>



## Print a GST invoice for the credit note or debit note of a purchase invoice

To print a GST invoice for the credit note or debit note of a purchase invoice, follow these steps.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a posted purchase order.

2.  On the **Purchase** tab, on the **Action Pane**, click **Credit note**.

3.  Select the **Select all** check box to create credit notes for all purchase order transactions.
    
    –or–
    
    Select the **Mark** check box next to the corresponding purchase order transaction lines to create credit notes for those lines only.

4.  Specify the reason code, original invoice number, and original invoice date. Then print the credit or debit note with the GST invoice. For more information, see Create and print a credit note for vendor invoices.
    

    > [!NOTE]
    > <P>If the quantity of the item displays a negative sign, the invoice is a credit note. Otherwise, the adjusted invoice is a debit note.</P>



## Print a GST invoice for the credit note of a project invoice

To print a GST invoice for the credit note of a project invoice, follow these steps.

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**.

2.  Create a new project invoice for a sales order, and then post the project invoice. For more information, see [Create and post invoice proposals](create-and-post-invoice-proposals.md).

3.  Create a new invoice proposal, and adjust the quantity and price of the item.

4.  Specify the reason code, original invoice number, and original invoice date. For more information, see [Credit invoiced amounts in projects](credit-invoiced-amounts-in-projects.md).
    

    > [!NOTE]
    > <P>If the quantity of the item displays a negative sign, the invoice is a credit note. Otherwise, the adjusted invoice is a debit note.</P>



5.  Click **Print** to print the posted project invoice with the GST invoice.

  



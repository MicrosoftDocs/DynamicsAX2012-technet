---
title: (MYS) Print self-billed GST invoices
TOCTitle: (MYS) Print self-billed GST invoices
ms:assetid: 74839207-2f46-41d7-aa00-1d5b6465903f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn858081(v=AX.60)
ms:contentKeyID: 63400913
ms.date: 11/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Malaysia
---

# (MYS) Print self-billed GST invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to print a self-billed Malaysian Goods and Services Tax (GST) invoice for goods and services that you have purchased from a vendor. Before you can invoice yourself for a purchase transaction, you must acquire an approval number to print a self-billed invoice from the Malaysian tax authorities. It is mandatory to enter a reference number for the approval in the **Purchase order** form. A self-billed invoice also includes a tax summary with GST details. You can either use a detailed or a simple printing format for the invoice depending on the selection that you make in the **General ledger parameters** form.

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
<td><p>Microsoft Dynamics AX 2012 R3 with cumulative update 8 (CU8)</p></td>
</tr>
<tr class="even">
<td><p>Related setup tasks</p></td>
<td><p></p>
<ol>
<li><p>Create a new tax registration type for Malaysia, and select the <strong>Primary for country</strong> check box in the <strong>Tax registration types</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677414(v=ax.60)">Tax registration types (form)</a>.</p></li>
<li><p>Select a registration type, and specify the authority, registration number, effective and expiration dates for the primary address of the legal entity in the <strong>Edit address</strong> form. For more information see, <a href="https://technet.microsoft.com/en-us/library/hh370713(v=ax.60)">Manage addresses (form)</a>.</p></li>
<li><p>Set up print management for the <strong>Accounts payable</strong>, <strong>Accounts receivable</strong>, and <strong>Project management and accounting</strong> modules in the <strong>Print management setup</strong> form. For more information see, <a href="set-up-print-management-for-a-module.md">Set up print management for a module</a>.</p></li>
<li><p>Select the printing format for the GST invoice as <strong>Full invoice</strong> or <strong>Simplified invoice</strong> in the <strong>GST invoice format</strong> field in the <strong>Sales tax</strong> area of the <strong>General ledger parameters</strong> form.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## 1\. Set up parameters to generate a self-billed invoice

Use the **General ledger parameters** form to make the self-billed invoicing option available in the **Purchase order** form. You must also specify parameters for printing the GST summary details here.

To set up parameters to generate a self-billed invoice, follow these steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Sales tax** link, and then on the **GST options** FastTab, in the **GST invoice** area, select the **Use self-billed invoice** check box.

3.  In the **Exempt GST print code** field, enter the print code to be used for GST exempt tax lines.

4.  Select the **Include delimiter in summary text** check box to use delimiters to print the summary text in the GST invoice.

5.  In the **Delimiter** field, enter the delimiter that should be used to print the summary text.
    

    > [!NOTE]
    > <P>This field is available only if you select the <STRONG>Include delimiter in summary text</STRONG> check box.</P>



6.  Select the **Include tax code in summary text** check box to include the tax code for the purchased items in the GST summary.

7.  Select the **Include tax value in summary text** check box to include the tax valuation for the purchased items in the GST summary.

## 2\. Assign an approval number to a self-billed invoice

Use the **Purchase order** form to indicate that you are issuing a self-invoice, and to enter the mandatory approval number for self-billing.

To assign an approval number to a self-billed invoice, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Create or select a purchase order, and then click **Edit**. For more information, see [Create a purchase order](create-a-purchase-order.md).

2.  In the **Purchase order** form, click **Header view** and then on the **General** FastTab, in the **Invoice type** field, select **Self-billed invoice** to indicate that you are invoicing yourself for goods and services that you have purchased from a vendor.

3.  In the **Approval number** field, enter the approval number that you acquired from the Malaysian tax authorities to print a self-billed invoice.
    

    > [!NOTE]
    > <P>This field is available only if you have selected the <STRONG>Self-billed invoice</STRONG> option in the <STRONG>Invoice type</STRONG> field.</P>



4.  Post the purchase order and print a self-billed invoice with a GST summary. For more information, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

## Related tasks

[(MYS) Print GST customer invoices with a relief clause](mys-print-gst-customer-invoices-with-a-relief-clause.md)

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
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To print self-billed GST invoices, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p>View GST relief category</p></li>
<li><p>Maintain GST relief category</p></li>
<li><p>View GST relief group</p></li>
<li><p>Maintain GST relief group</p></li>
<li><p>View GST report configuration</p></li>
<li><p>Maintain GST report configuration</p></li>
<li><p>Generate GST reports</p></li>
<li><p>Generate purchase list by tax codes report</p></li>
<li><p>Generate supply list by tax codes report</p></li>
<li><p>Generate GAF file for sales tax due</p></li>
<li><p>Generate vendor debit note and credit note list</p></li>
<li><p>Generate customer debit note and credit note list</p></li>
</ul></td>
</tr>
</tbody>
</table>

  



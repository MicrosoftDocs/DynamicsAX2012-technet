---
title: (MYS) Print GST customer invoices with a relief clause
TOCTitle: (MYS) Print GST customer invoices with a relief clause
ms:assetid: ceb8c657-37c6-437c-9a3a-311e87665cfc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn858082(v=AX.60)
ms:contentKeyID: 63400914
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- Menu_Items.Display.TaxGSTReliefCategory_MY
audience: Application User
ms.search.region: Malaysia
---

# (MYS) Print GST customer invoices with a relief clause 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to include and print a Malaysian Goods and Services Tax (GST) relief clause in a tax invoice for goods or services that are eligible for GST relief. You can print a GST invoice from a sales order, a free text invoice, or a project proposal. When you generate a tax invoice for a customer who has bought a GST relieved item or service, the relief clause is automatically included in the final printed invoice. You can either use a detailed or a simple printing format for the invoice depending on the selection that you make in the **General ledger parameters** form.

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
<td><ol>
<li><p>Create a new tax registration type for Malaysia, and select the <strong>Primary for country</strong> check box in the <strong>Tax registration types</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677414(v=ax.60)">Tax registration types (form)</a>.</p></li>
<li><p>Select a registration type, and specify the authority, registration number, effective and expiration dates for the primary address of the legal entity in the <strong>Edit address</strong> form. For more information see, <a href="https://technet.microsoft.com/en-us/library/hh370713(v=ax.60)">Manage addresses (form)</a>.</p></li>
<li><p>Set up print management for the <strong>Accounts payable</strong>, <strong>Accounts receivable</strong>, and <strong>Project management and accounting</strong> modules in the <strong>Print management setup</strong> form. For more information see, <a href="set-up-print-management-for-a-module.md">Set up print management for a module</a>.</p></li>
<li><p>Select the printing format for the GST invoice as <strong>Full invoice</strong> or <strong>Simplified invoice</strong> in the <strong>GST invoice format</strong> field in the <strong>Sales tax</strong> area of the <strong>General ledger parameters</strong> form.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## 1\. Create a GST relief category

Use the **GST relief category** form to specify a reference number for the item that has been granted GST relief by the Malaysian tax authorities. You must also provide the schedule number of the GST Act under which the relief has been granted. The relief item number and the schedule number are both included in the final GST invoice.

To create a GST relief category, follow these steps:

1.  **General ledger** \> **Setup** \> **Sales tax** \> **GST relief category**.

2.  Click **New** to create a record.

3.  In the **Relief item number** field, enter the item number for which you are seeking GST relief.

4.  In the **Relief schedule** field, enter the relief schedule for the GST relief category.

## 2\. Create a GST relief group

After you create a GST relief category, you must attach the category to a GST relief group. You can attach a GST relief group to multiple GST relief categories.

To create a GST relief group, follow these steps:

1.  **General ledger** \> **Setup** \> **Sales tax** \> **GST relief group**.

2.  Click **New** to create a group, and then add a name and a description for the group.

3.  On the **GST relief category** FastTab, click **Add** to add a GST relief category to a GST relief group.

4.  In the **GST relief category**, select a category.

## 3\. Assign a GST relief group to a customer

Use the **Customers** form to associate a customer with a GST relief group.

To assign a GST relief group to a customer, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Create or select a customer account, and then click **Edit**. For more information, see [Create a customer record](create-a-customer-record.md).

3.  On the **Invoice and delivery** FastTab, in the **GST relief group** field, select a relief group to which the customer belongs.

## 4\. Assign a GST relief category to a product

You must assign the relief category to a product to indicate that the product is eligible for GST relief.

To assign a GST relief category to a product, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Create or select a released product, and then click **Edit**. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

3.  On the **Sell** FastTab, in the **GST relief category** field, select a GST relief category for the product.

## 5\. Print the relief clause on a GST invoice

You can either use a **Sales order** form, or **Free text invoice** form, or the **Invoice proposals** form to generate and print a tax invoice with a GST relief clause for a customer.

To print the relief clause on a GST invoice, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Create or select a sales order, and then click **Edit**. For more information, see [Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\)).
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**. Create or select a free text invoice, and then click **Edit**. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**. Create or select a project invoice proposal, and then click **Edit**. For more information, see [Create and post invoice proposals](create-and-post-invoice-proposals.md).

2.  In the **Sales order** form, click **Header view**, and then on the **General** FastTab, in the **Invoice type** field, select **GST invoice**.
    
    –or–
    
    In the **Free text invoice** form, click **Header view**, and then on the **General** FastTab, in the **Invoice type** field, select **GST invoice**.
    
    –or–
    
    In the **Invoice proposals** form, on the **Invoice proposal header** FastTab, in the **GST invoice type** field, select **GST invoice**.

3.  Post and print a tax invoice with the GST relief clause from a sales order, free text invoice, or invoice proposal. For more information, see [Key tasks: Customer invoices](key-tasks-customer-invoices.md), [Key tasks: Free text invoices](key-tasks-free-text-invoices.md), or Post invoice proposals (form).

## Related tasks

[(MYS) Print self-billed GST invoices](mys-print-self-billed-gst-invoices.md)

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
<td><p>To print GST customer invoices with a relief clause, you must be a member of a security role that includes the following privileges.</p>
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

  



---
title: (IND) Generate annexure 58 for returned items
TOCTitle: (IND) Generate annexure 58 for returned items
ms:assetid: f848a56d-09ad-4880-baea-2de0f4b592f5
ms:mtpsurl: https://technet.microsoft.com/library/Dn876579(v=AX.60)
ms:contentKeyID: 63378995
author: Khairunj
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTableListPage
- Forms.ReturnTableListPage
- Annexure 58
- Forms.ExciseAnnexure58Inquiry_IN
- goods return
audience: Application User
ms.search.region: India
---

# (IND) Generate annexure 58 for returned items 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can generate and print annexure 58 for items that are returned from customers for repair or reconditioning, and then dispatched back to the customers after repair.

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
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: India</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ol>
<li><p>In the <strong>General ledger parameters</strong> form, in the <strong>Sales tax</strong> area, in the <strong>Apply India taxes</strong> field group, select the <strong>Excise</strong> check box and <strong>Customs</strong> check box. For more information, see <a href="https://technet.microsoft.com/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p></li>
<li><p>In the <strong>Exchange rate types</strong> form, set up the exchange rate types to be used for the tax calculation. For more information, see <a href="https://technet.microsoft.com/library/hh242857(v=ax.60)">Exchange rate types (form)</a>.</p></li>
<li><p>In the <strong>Released product details</strong> form, on the <strong>General</strong> FastTab in the <strong>Excise</strong> field group, select the <strong>Excise record type</strong> for the product. For more information, see <a href="https://technet.microsoft.com/library/aa615563(v=ax.60)">Released product details (form)</a>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Generate Annexure 58 for returned items

You can record the details of all items that are returned from a customer for repair or maintenance and then dispatched back to the customers after repair. Annexure 58 includes the manufacturer details, customer details, warehouse from which the item was returned, the excise amount of the returned items, the quantity of items, and the purpose of the return of the items.

To generate Annexure 58 for returned items using a return order, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Return orders** \> **All return orders**.

2.  Create a new return sales order, and then specify a customer account number and reason code for returning the items. For more information, see [Return orders (form)](https://technet.microsoft.com/library/hh803010\(v=ax.60\)).

3.  Click **OK**, and then on the **Action Pane**, click **Return** \> **Find sales order**.

4.  Select the **Select all** check box to select all sales invoice transactions, or in the lower pane, select the **Mark** check box next to the sales order line that you want to correct the quantity of the returned items for.

5.  Click **OK**. On the **Line details** FastTab, select the **Disposition code** field to specify what action is required to handle the returned item. The **Disposition code** must be of the type **Replace and credit** or **Replace and scrap** to generate Annexure 58 for returned items.

6.  Post the return order. Generate a packing slip and an invoice for the return order. The details of the invoiced return order are recorded in Annexure 58. For more information, see [Create and print a credit note for customer invoices](create-and-print-a-credit-note-for-customer-invoices.md).

7.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Annexure 58**.

8.  Click **Provide values for filtration**.

9.  Select the **ECC number**, **Customer**, **From date**, and **To date** fields. The details of all return orders are displayed.

To generate Annexure 58 for returned items using a replacement order, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a new replacement order to re-dispatch the items back to the customer. For more information, see [Create an item replacement order](create-an-item-replacement-order.md).

3.  On the **Line details** FastTab, enter the **Return action** that was taken for the items that were returned by the customer for repair.

4.  Post the replacement order. Generate a packing slip and an invoice for the replacement order. The details of the invoiced replacement order are recorded in Annexure 58. For more information, see [Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\)).

5.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Annexure 58**.

6.  Click **Provide values for filtration**.

7.  Select the **ECC number**, **Customer**, **From date**, and **To date** fields. The details of all replacement sales orders are displayed.

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
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p>Sales agent</p></li>
<li><p>Sales manager</p></li>
<li><p>Accountant</p></li>
<li><p>Accounts receivable administrator</p></li>
<li><p>Accounting manager</p></li>
<li><p>Accounting supervisor</p></li>
</ul></td>
</tr>
</tbody>
</table>

  



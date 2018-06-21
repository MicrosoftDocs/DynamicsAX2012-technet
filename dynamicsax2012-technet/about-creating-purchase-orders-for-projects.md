---
title: About creating purchase orders for projects
TOCTitle: About creating purchase orders for projects
ms:assetid: 663ccbbb-1739-4113-9a58-2449ae66d813
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571150(v=AX.60)
ms:contentKeyID: 36057751
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- sales order
- item requirement
---

# About creating purchase orders for projects [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use one of three methods to create a purchase order in Project management and accounting.

## Methods for creating a purchase order

The purpose of the purchase order determines when the purchase order is consumed and therefore, when items are charged on a project.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Purpose</p></th>
<th><p>Consumption of items</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a purchase order directly</p></td>
<td><p>Use this method to purchase items from an external vendor for consumption on a project. You can create the purchase order in the following ways:</p>
<ul>
<li><p>From the project itself. In this case the project is already defined for the purchase order.</p></li>
<li><p>By navigating to the project purchase order. (Click <strong>Project management and accounting</strong> &gt; <strong>Common</strong> &gt; <strong>Item tasks</strong> &gt; <strong>Project purchase orders</strong>.) You must select both the vendor and the project for which the purchase order is to be created.</p></li>
</ul></td>
<td><p>Items are consumed when the vendor invoice is updated.</p></td>
</tr>
<tr class="even">
<td><p>Create a purchase order from a sales order</p></td>
<td><p>Use this method if you want to purchase items when you create a sales order from a project.</p></td>
<td><p>Items are consumed when the sales order is invoiced to the customer.</p></td>
</tr>
<tr class="odd">
<td><p>Create a purchase order from an item requirement</p></td>
<td><p>Use this method if you want to purchase items when you create an item requirement from a project.</p></td>
<td><p>Items are consumed when the item-requirement packing slip is updated.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>When you update the vendor invoice or packing slip, you are prompted to update the packing slip on the item requirement.</P>



## Invoicing purchase orders in Project management and accounting

The line property that is attached to a purchase order line for an item determines whether the purchased item is invoiced to a customer. There are two invoicing options:

  - If you do not want to invoice the customer, and a non-chargeable line property is attached to the purchase order line, the purchase order is invoiced and no further action is necessary.

  - If you want to invoice the customer, and a chargeable line property is attached to the purchase order line, you must update the vendor invoice and invoice the customer by using the invoicing system in the **Project management and accounting** module.

## See also

[Create a purchase order for a project](create-a-purchase-order-for-a-project.md)

[Create a purchase order from a sales order](create-a-purchase-order-from-a-sales-order.md)

[Create a purchase order](create-a-purchase-order.md)

[Create an invoice for a time and material project](create-an-invoice-for-a-time-and-material-project.md)

[Create purchase order (form)](https://technet.microsoft.com/en-us/library/aa570189\(v=ax.60\))

[Create purchase order or direct delivery from sales (form)](https://technet.microsoft.com/en-us/library/aa557923\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


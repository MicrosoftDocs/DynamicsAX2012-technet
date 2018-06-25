---
title: About registering item consumption
TOCTitle: About registering item consumption
ms:assetid: 69d6d58e-e0bd-4ff6-9785-d2c64294b30c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571173(v=AX.60)
ms:contentKeyID: 36057974
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- item consumption
- consumption items
- item handling
- item requirements
---

# About registering item consumption [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can register consumption of items in **Project management and accounting** in several ways. You can either sell or purchase from a project or reserve items for a project.

## Sales order items

To sell items from a project, you can create a sales order from the project itself. You can only create sales orders from time and material projects.

## Consumption items

You can order items for consumption on a project from the company's inventory, or you can purchase them from an external vendor. Items can be consumed on all types of projects except time projects.

The way in which you order items depends on where you are ordering them from:

  - To order items from the company's inventory, you must enter the order as an item requirement. If you use the **Item requirements** form, you can set it up so that you receive items as partial deliveries. This means that you can postpone consumption of a quantity of the items until the items are required.

  - To order items from an external vendor, you must create the order as a purchase order in the **Purchase order** form.


> [!NOTE]
> <P>The packing slip for a project-related sales order cannot be canceled if the items have already been marked for packing.</P>



## Item handling methods

The following table lists methods for ordering items and describes how the items are consumed.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Purpose</p></th>
<th><p>Path or method</p></th>
<th><p>Consumption</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Sales order</strong></p></td>
<td><p>Enter a sales transaction directly on a time and material project.</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Common</strong> &gt; <strong>Projects</strong> &gt; <strong>All projects</strong>. On the <strong>Action Pane</strong>, on <strong>Manage</strong> tab, in the <strong>New</strong> group, click <strong>Item task</strong>, and then select <strong>Sales order</strong>.</p></td>
<td><p>Item transactions are consumed when the customer invoice is posted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Inventory journal</strong></p></td>
<td><p>Enter and maintain item records quickly. If, for example, you want to enter an item requirement based on a printed list, the inventory journal can be applied.</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Journals</strong> &gt; <strong>Item</strong>.</p></td>
<td><p>Item transactions are consumed when the journal is posted.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item requirement</strong></p></td>
<td><p>Enter items that will not be consumed immediately. This method lets users track the number of items that have been consumed in a single item requirement record.</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Common</strong> &gt; <strong>Projects</strong> &gt; <strong>All projects</strong>. On the <strong>Action Pane</strong>, on the <strong>Manage</strong> tab, in the <strong>New</strong> group, click <strong>Item task</strong>, and then select <strong>Item requirement</strong>.</p></td>
<td><p>Item transactions are consumed when the packing slip is updated. That is, the item requirement is created when the packing slip is posted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Purchase order</strong></p></td>
<td><p>Enter transactions in one of three locations, depending on the purchasing method.</p></td>
<td><p>Purchase orders can be entered as follows:</p>
<ul>
<li><p>The item record is entered as an ordinary project purchase order.</p></li>
<li><p>The purchase order is created from a sales order.</p></li>
<li><p>The purchase order is created from an item requirement.</p></li>
</ul></td>
<td><p>Item transactions are consumed on a packing slip update or when the customer or vendor is invoiced.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>When handling items in <STRONG>Project</STRONG>, you must define a project category on the <STRONG>Manage projects</STRONG> tab in the <STRONG>Released product details</STRONG> form.</P>



## See also

[Create a purchase order](create-a-purchase-order.md)

[Consume item requirements in a project](consume-item-requirements-in-a-project.md)

[Released product details (form)](https://technet.microsoft.com/en-us/library/aa615563\(v=ax.60\))

[Item requirements (form)](https://technet.microsoft.com/en-us/library/aa552021\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Create and print labels overview
TOCTitle: Create and print labels overview
ms:assetid: 51cf2c21-b8b1-4311-bd5d-11d4a0231976
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580643(v=AX.60)
ms:contentKeyID: 39519137
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- label
- overview
- labels
---

# Create and print labels overview 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

In Retail, you can generate and print labels to use in stores. A label is a piece of paper, polymer, cloth, metal, or other material that is attached to a product, a container, or a shelf. A label can also be printed directly on a container or an item. Retail offers two types of labels: product labels and shelf labels. Product labels are always specific to a particular variant, but shelf labels don’t have to be.

You can use labels for a variety of purposes, such as the following:

  - Product identification

  - Name tags

  - Bar codes

  - Pricing

  - Warnings

  - Batch numbers

  - Expiration dates


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for <STRONG>Retail</STRONG> in Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



The topics in this section provide information about how to create and print labels.

[Generate and print shelf labels](generate-and-print-shelf-labels.md)

[Generate and print product labels](generate-and-print-product-labels.md)

## Labels business process component forms

The following table lists the forms that support the labels business process component. The table entries are organized by business process component task and then alphabetically by form name.


> [!NOTE]
> <P>Some forms in the following table are available only if information has been entered in other forms in the program.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Business process component task</p></th>
<th><p>Form name</p></th>
<th><p>Usage</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Print shelf labels</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597343(v=ax.60)">Shelf label printing (form)</a></p></td>
<td><p>Place shelf labels on a store rack or shelf where products are displayed or stored. A shelf label contains core information about the product.</p></td>
</tr>
<tr class="even">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Print product labels</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/jj851124(v=ax.60)">Product label printing (form)</a></p></td>
<td><p>Place product labels on a product or article. A product label contains all information about the product, including its batch number, serial number, and expiration date.</p></td>
</tr>
</tbody>
</table>


## New or changed for Retail in Microsoft Dynamics AX 2012 R3

In addition to being able to generate labels for one product at a time, you can now generate product and shelf labels for multiple products at one time. You can also generate labels for products that are included in transfer orders or purchase orders. After the labels are generated, you can print them.

Generate product and shelf labels for products in the following scenarios:

  - From purchase orders, regardless of the purchase order status

  - From transfer orders when the products are shipped or when transfer orders are received

  - From the **Released products** list page or the **Released product details** form

When you generate labels in these scenarios, you can use the **Print shelf labels** form and the **Print product labels** form to specify the number of labels that you want to print. You can also add products to the list and generate labels for those products at the same time.

The following table lists the additional forms that support the labels business process component in AX 2012 R3. The table entries are organized by business process component task and then alphabetically by form name.


> [!NOTE]
> <P>Some forms in the following table are available only if information has been entered in other forms in the program.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Business process component task</p></th>
<th><p>Form name</p></th>
<th><p>Usage</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Print shelf and product labels from purchase orders</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa587152(v=ax.60)">Purchase posting (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/aa557983(v=ax.60)">Purchase order (form)</a></p></td>
<td><ul>
<li><p>In the <strong>Purchase posting</strong> form, generate labels for products that are included in a purchase order when the product shipment is received, and print them when the receipt is posted.</p></li>
<li><p>In the <strong>Purchase order</strong> form, generate labels at any time for products that are included in a purchase order for products that were received.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Print shelf and product labels from transfer orders</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa577094(v=ax.60)">Transfer order shipment (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/aa552649(v=ax.60)">Receive (form)</a></p></td>
<td><ul>
<li><p>In the <strong>Transfer order shipment</strong> form, generate labels for products that are included in a transfer order and send them with the products when they are shipped.</p></li>
<li><p>In the <strong>Receive</strong> form, generate labels for products that are included in a transfer order and print them for the received products</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Print shelf and product labels for released products</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580615(v=ax.60)">Released product details (form) (Retail)</a></p></td>
<td><p>Generate labels for one or more released products at any time, from either the <strong>Released products</strong> list page or the <strong>Released product details</strong> form.</p></td>
</tr>
</tbody>
</table>


## See also

[Generate and print shelf labels](generate-and-print-shelf-labels.md)

[Generate and print product labels](generate-and-print-product-labels.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


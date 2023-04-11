---
title: Create and print labels overview (Retail essentials)
TOCTitle: Create and print labels overview (Retail essentials)
ms:assetid: 211c46a0-8572-46c5-8cb0-d9f29ecc406e
ms:mtpsurl: https://technet.microsoft.com/library/Dn716058(v=AX.60)
ms:contentKeyID: 62200330
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Create and print labels overview (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In Retail essentials, you can generate and print labels to use in stores. A label is a piece of paper, polymer, cloth, metal, or other material that is attached to a product, a container, or a shelf. A label can also be printed directly on a container or an item. Retail essentials offers two types of labels: product labels and shelf labels. Product labels are always specific to a particular variant, but shelf labels don’t have to be.

You can use labels for a variety of purposes, such as the following:

  - Product identification

  - Name tags

  - Bar codes

  - Pricing

  - Warnings

  - Batch numbers

  - Expiration dates

You can generate product and shelf labels for individual products or for multiple products at one time. After the labels are generated you can print them. Generate product and shelf labels for products in the following scenarios:

  - From purchase orders regardless of the purchase order status

  - From transfer orders when the products are shipped or when transfer orders are received

  - From the **Released product details** form

When you generate labels in the scenarios listed above, you can specify the number of labels that you want to print. You can also add products to the list and generate labels for those products at the same time.

The following table lists the forms that support the labels business process component. The table entries are organized by business process component task and then alphabetically by form name.


> [!NOTE]
> <P>Some forms in the following table require information or parameter settings before you can navigate to them.</P>



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
<th><p>Use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Print shelf labels</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh597343(v=ax.60)">Shelf label printing (form)</a></p></td>
<td><p>Place shelf labels on a store rack or shelf where products are displayed or stored. A shelf label contains core information about the product.</p></td>
</tr>
<tr class="even">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Print product labels</p></td>
<td><p><a href="https://technet.microsoft.com/library/jj851124(v=ax.60)">Product label printing (form)</a></p></td>
<td><p>Place product labels on a product or article. A product label contains all information about the product, including its batch number, serial number, and expiration date.</p></td>
</tr>
<tr class="even">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Print shelf and product labels from purchase orders</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa587152(v=ax.60)">Purchase posting (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa557983(v=ax.60)">Purchase order (form)</a></p></td>
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
<td><p><a href="https://technet.microsoft.com/library/aa577094(v=ax.60)">Transfer order shipment (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa552649(v=ax.60)">Receive (form)</a></p></td>
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
<td><p><a href="https://technet.microsoft.com/library/hh580615(v=ax.60)">Released product details (form) (Retail)</a></p></td>
<td><p>Generate labels for one or more released products at any time, from either the <strong>Released products</strong> list page or the <strong>Released product details</strong> form.</p></td>
</tr>
</tbody>
</table>


The topics in this section provide information about creating and printing labels.

Enable label printing (Retail essentials)

[Print shelf labels (Retail essentials)](print-shelf-labels-retail-essentials.md)

[Print product labels (Retail essentials)](print-product-labels-retail-essentials.md)

## See also

[Print shelf labels (Retail essentials)](print-shelf-labels-retail-essentials.md)

[Print product labels (Retail essentials)](print-product-labels-retail-essentials.md)

  



---
title: About inventory blocking
TOCTitle: About inventory blocking
ms:assetid: 5be5811c-d90b-475c-a733-61f53b826ab9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209122(v=AX.60)
ms:contentKeyID: 36057564
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- automatically blocked
- block item
- inventory blocking
- unblock items
audience: Application User
ms.search.region: Global
---

# About inventory blocking 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Inventory blocking is part of the quality inspection process. During the quality inspection, items are automatically blocked from consumption or issue. Also, you can manually block items that you want to prevent from being issued or consumed.

## Inventory blocking methods

You can block inventory items in one of three ways.

  - Manually

  - By creating a quality order

  - By using a process that generates a quality order

## Block items manually

You can block a quantity of an item by creating a transaction in the **Inventory blocking** form. Only items that are available as on-hand inventory can be blocked.

For manually blocked quantities, you must consider if expected receipts should be included in planning activities as an expected on-hand quantity. Expected receipts are blocked items that are expected to be available as on-hand inventory after inspection. For items blocked through a quality order, the **Expected receipts** check box is by default selected.

You can cancel blocking of a manually blocked quantity by deleting the transaction in the **Inventory blocking** form.

## Block items by creating a quality order

You can specify items for inspection by creating a quality order in the **Quality orders** form. When you create a quality order, the quantity of an item that you specify is blocked.


> [!NOTE]
> <P>The sampling plan associated with a quality order controls the quantity of an item that should be inspected. The quantity of blocked items, on the other hand, is not controlled by the sampling plan. Regardless of the quantity that is sent for inspection, as specified by the sampling plan, the quantity of the item that is entered on the quality order is the quantity that is blocked.</P>



## Block items by a process that generates a quality order

A quantity of an item that is specified for inspection through a quality process is automatically blocked. So when a quality order is generated automatically, the item sampling plan that is associated with the quality order controls the quantity of items that is blocked and not only the quantity of items to be inspected.


> [!NOTE]
> <P>If the <STRONG>Full blocking</STRONG> check box in the <STRONG>Item sampling</STRONG> form is selected, the full quantity of, for example, a purchase order line is blocked during inspection regardless of the item sampling quantity.</P>



## Example

In the following example, a quality order is generated when a purchase order packing slip is posted. In the **Quality associations** form, posting of a purchase order packing slip is specified as the process that activates the quality order.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Setup</p></th>
<th><p>User action</p></th>
<th><p>Result</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>A quality association specifies that upon posting of a purchase order packing slip a quality order must be generated.</p>
<p>The item sampling setup of the quality order specifies that 10% of the purchase order line quantity must be inspected.</p>
<p>Furthermore, with the <strong>Full blocking</strong> check box selected the item sampling setup indicates that the full quantity of the purchase order line must be blocked during inspection regardless of the quantity that is sent for inspection.</p></td>
<td><p>The packing slip is posted.</p></td>
<td><p>A quality order is generated.</p>
<p>10 % of the purchase order quantity of the item is sent to inspection.</p>
<p>The full quantity of the purchase order line is blocked.</p></td>
</tr>
</tbody>
</table>


## Setup considerations

When working with inventory blocking you must consider the following setup options.

  - Do you want to block the full quantity of items in transactions covered by a sampling plan?

  - Do you want to consider expected receipts for manually blocked items?

## Set up a sampling plan

1.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Item sampling**.

2.  Press CTRL+N to create a new sampling plan and fill in information about the sampling plan.

3.  Select the **Full blocking** check box if you want to block the full quantity of items in transactions covered by the sampling plan.

## Consider expected receipts for manually blocked items

1.  Click **Inventory management** \> **Periodic** \> **Inventory blocking**.

2.  Press CTRL+N to create a new blocking transaction, complete the information about the transaction, and select the **Expected receipts** check box.

## See also

[Block and unblock inventory items](block-and-unblock-inventory-items.md)

  



---
title: About setting up date-controlled reservations
TOCTitle: About setting up date-controlled reservations
ms:assetid: 698f47c1-7b49-43da-b23d-0cc0404d73a2
ms:mtpsurl: https://technet.microsoft.com/library/Aa571170(v=AX.60)
ms:contentKeyID: 36057969
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- reservations
- date-controlled reservations
- reserve batches
audience: Application User
ms.search.region: Global
---

# About setting up date-controlled reservations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the **Item model groups** form, you can select to use the date of receipt of goods when you reserve batches.

When you create order lines that have automatic reservation, you can consider the date of receipt of items from the vendor when you reserve batches.

You can select to reserve batches based on the earliest date of receipt of items, according to the principle of first in, first out (FIFO). By using FIFO you can make sure that the goods that should be received first are reserved first.

You can also select to reserve batches based on the date of receipt that is closest to the sales order ship date. This way you can make sure that the batches that were received last are reserved first.

## Date-controlled and Backward from ship date check boxes (Setup tab)

If you select the **Date-controlled** check box in the **Item model groups** form, the inventory reservation is controlled by a sorting date according to the FIFO principle.

If you also select the **Backward from ship date** check box, the inventory is reserved backward from the desired ship date according to the principle of last in, first out (LIFO). If no receipts are available before the ship date, a FIFO reservation is used.

## Example

The purchase order lines in the following table have three different ship dates.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Purchase order line</p></th>
<th><p>Item number</p></th>
<th><p>Batch number</p></th>
<th><p>Quantity</p></th>
<th><p>Ship date</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>A</p></td>
<td><p>1000</p></td>
<td><p>5</p></td>
<td><p>February 2, 2012</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>A</p></td>
<td><p>1001</p></td>
<td><p>3</p></td>
<td><p>January 1, 2012</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>A</p></td>
<td><p>1002</p></td>
<td><p>7</p></td>
<td><p>March 3, 2012</p></td>
</tr>
</tbody>
</table>


A sales order that should be automatically reserved and delivered on April 4, 2012, reserves the following batch:

  - If both the **Date-controlled** and **Backward from ship date** check boxes are cleared, batch 1000 is reserved because it is the batch with the lowest number.

  - If the **Date-controlled** check box is selected and the **Backward from ship date** check box is cleared, batch 1001 is reserved because it is the batch with the first date of receipt (FIFO).

  - If both the **Date-controlled** and **Backward from ship date** check boxes are selected, batch 1002 is reserved because it is the batch receipt closest to the sales order ship date.

## See also

[Set up manual or automatic inventory reservations](set-up-manual-or-automatic-inventory-reservations.md)

  



---
title: About editing a purchase release order
TOCTitle: About editing a purchase release order
ms:assetid: 73caae6e-9d1d-4d1d-8bbc-dae06162bc03
ms:mtpsurl: https://technet.microsoft.com/library/Hh209231(v=AX.60)
ms:contentKeyID: 36058148
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About editing a purchase release order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you have ordered against a purchase agreement, certain fields in the purchase release order (**Purchase order** form) can be modified only if you remove the link to the associated purchase agreement lines. The following table lists some of these fields.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Delivery date</strong></p></td>
<td><p>If you change the delivery date to a date that is earlier than the <strong>Effective date</strong> value on the purchase agreement line, you must remove the link to the purchase agreement line before you can save the changed delivery date.</p>
<p>If you change the delivery date to a date that is later than the <strong>Expiration date</strong> value on the purchase agreement line, you must remove the link to the purchase agreement line before you can save the changed delivery date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Currency</strong></p>
<p><strong>Discount percent</strong></p>
<p><strong>Discount</strong></p>
<p><strong>Unit price</strong></p>
<p><strong>Price unit</strong></p>
<p><strong>Net amount</strong></p></td>
<td><p>If you change the value in any of these fields, and the <strong>Price and discount is fixed</strong> check box is selected on an associated purchase agreement line, you must respond to the dialog box that prompts you to save the change:</p>
<p>Click <strong>Yes</strong> to remove the link to the purchase agreement line and recalculate the price.</p>
<p>–or–</p>
<p>Click <strong>No</strong> to remove the link to the purchase agreement line without recalculating the price.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Net amount</strong></p></td>
<td><p>If you specify an amount that exceeds the amount specified on a purchase agreement line where the <strong>Max is enforced</strong> check box is selected, you must respond to the dialog box that prompts you to save the changed amount:</p>
<p>Click <strong>Yes</strong> to remove the link to the purchase agreement line and recalculate the price.</p>
<p>–or–</p>
<p>Click <strong>No</strong> to remove the link to the purchase agreement line without recalculating the price.</p></td>
</tr>
<tr class="even">
<td><p><strong>Quantity</strong></p></td>
<td><p>If you specify a quantity that exceeds the quantity on a purchase agreement line where the <strong>Max is enforced</strong> check box is selected, you must respond to the dialog box that prompts you to save the changed quantity:</p>
<p>Click <strong>Yes</strong> to remove the link to the purchase agreement line and recalculate the price.</p>
<p>–or–</p>
<p>Click <strong>No</strong> to remove the link to the purchase agreement line without recalculating the price.</p></td>
</tr>
</tbody>
</table>


## See also

[About purchase agreements](about-purchase-agreements.md)

  



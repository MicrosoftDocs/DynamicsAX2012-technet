---
title: About sales order types
TOCTitle: About sales order types
ms:assetid: df092bab-93ce-41cb-b955-9f7a958f3c95
ms:mtpsurl: https://technet.microsoft.com/library/Aa551278(v=AX.60)
ms:contentKeyID: 36059693
author: Khairunj
ms.date: 03/16/2015
mtps_version: v=AX.60
f1_keywords:
- types
- subscription
- sales order
- inquire
- inquire about orders
- order types
- create sales order
- create sales orders
- sales order journal
- sales order types
audience: Application User
ms.search.region: Global
---

# About sales order types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a sales order, you must indicate the type of order that it is. You can select one of the types that are described here:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Order type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Journal</strong></p></td>
<td><p>Use as a draft; it has no effect on stock quantities and does not generate item transactions. Order journal lines are not included in master scheduling.</p></td>
</tr>
<tr class="even">
<td><p><strong>Subscription</strong></p></td>
<td><p>Use for recurring orders. When the order is invoiced, the order status is set automatically to open order. Quantity delivered invoiced and remaining deliveries are updated.</p>
<div class="alert">

> [!WARNING]
> <P>You cannot use this sales order type if you are using the Warehouse management module.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Sales order</strong></p></td>
<td><p>Use when the customer actually places or confirms an order.</p></td>
</tr>
<tr class="even">
<td><p><strong>Returned order</strong></p></td>
<td><p>Use when the customer returns items to stock. A return-item number (RMA number) is assigned automatically and can be viewed on the <strong>Other</strong> tab.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item requirements</strong></p></td>
<td><p>Created automatically when you make an item sale through a Project module. The project number can be seen in the <strong>Project</strong> column.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>You can change an order type at any time, except when it is an Item requirements order or if it has a Delivered status.</P>


  



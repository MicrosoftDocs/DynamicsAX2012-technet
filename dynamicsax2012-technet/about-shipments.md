---
title: About shipments
TOCTitle: About shipments
ms:assetid: b6d41691-3295-4b96-b9a5-867b717a105f
ms:mtpsurl: https://technet.microsoft.com/library/Aa572241(v=AX.60)
ms:contentKeyID: 36059099
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- shipment
- item transport
- ship items
audience: Application User
ms.search.region: Global
---

# About shipments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

A shipment is a collection of items that are packed in the same container for transport by, for example, ship, rail, truck, or plane. A shipment includes all of an order, a part of an order, or a consolidation of multiple orders.

Based on the contents of the shipment, one or more picking routes, one or more pallet transports, or both are created.

Output order is a request for picking requirements and is the basis of a shipment. From the shipment, you can enable a pallet transport, a picking route, or both. The shipment status is based on the lowest denominator of the shipment line status.

## Shipment states

A shipment can be in one of the following states:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Status</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Registered</strong></p></td>
<td><p>The shipment has been created but not yet reserved or, if just one shipment line exists, without being part of a route.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reserved</strong></p></td>
<td><p>The shipment has been reserved, and picking routes or pallet transports have been generated, but they have not yet been released for picking.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Activated</strong></p></td>
<td><p>Both picking routes and pallet transports have been released, but not all of them have been completed.</p>
<p>Note that picking can start even when all items for the shipment cannot be reserved.</p></td>
</tr>
<tr class="even">
<td><p><strong>Picked</strong></p></td>
<td><p>At least one line of the shipment line is still at the picked stage.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Staged</strong></p></td>
<td><p>At least one line of the shipment line is still at the staged stage.</p></td>
</tr>
<tr class="even">
<td><p><strong>Loaded</strong></p></td>
<td><p>At least one line of the shipment line is still at the loaded stage.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sent</strong></p></td>
<td><p>The shipment has been sent, and it has been fully expedited.</p></td>
</tr>
<tr class="even">
<td><p><strong>Canceled</strong></p></td>
<td><p>The shipment has been canceled.</p></td>
</tr>
</tbody>
</table>


Output orders can be added to shipments automatically. This is controlled by the **Automatic addition status** setting on the **Shipment templates** form or the **Shipments** form. Setting the parameter to **None** means that output orders are not added automatically. Setting the parameter to one of the available states means that output orders that match the shipment criteria automatically are added up to and including this state. For example, if the **Automatic addition status** parameter has been set to **Activated**, output orders can be added when the status of the shipment is **Activated** or one of the earlier states—that is **Registered** or **Reserved**.

## See also

[Create shipments](create-shipments.md)

[Activate shipments](activate-shipments.md)

[Complete shipments](complete-shipments.md)

  



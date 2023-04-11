---
title: About shipment reservations
TOCTitle: Shipment reservation
ms:assetid: bde61f31-99d8-4e86-964f-f0f9b156a645
ms:mtpsurl: https://technet.microsoft.com/library/Gg213622(v=AX.60)
ms:contentKeyID: 39519297
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About shipment reservations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

The method of shipment reservation that you use in the shipment reservation process either reserves a full pallet or creates an output pallet transport from any bulk location. The method can also use a picking route, and reserve from the item picking location, any picking location, any incoming location, any bulk location, or any outgoing location.

The shipment reservation method can be a combination of these methods, and their exact sequence can be defined. For more information, see "Shipment reservation methods" in this topic.

Reservations can only be made from warehouses in the same site, and the warehouses must be of the **Default** type.

The reservation does not have to be specific to the warehouse. You can specify only the site. In such cases, the reservation process uses a random sequence of warehouses.

The combination of methods and the sequence in which they are used are defined in the **Shipment reservation combinations** form.

## Examples

One reservation combination, "Pick," could be defined as follows:

1.  **Picking route - item picking location**

2.  **Picking route - all picking locations**

Another reservation combination, "All," could be defined as follows:

1.  **Output transport - all bulk locations**

2.  **Picking route - item picking location**

3.  **Picking route - all picking locations**

4.  **Picking route - all bulk locations**

5.  **Picking route - all inbound locations**

6.  **Picking route - all outbound locations**

A shipment reservation combination can be used as is, or shipment reservation combinations can be collected into a shipment reservation sequence. Shipment reservation sequences are defined in the **Shipment reservation sequences** form.

One shipment reservation sequence, "S1," could be defined as follows.

Make a reservation on picking locations in warehouse A, and then in warehouse B. You must follow the assigned sequence, and you must ensure that all warehouses in the site have the reservation completed.

1.  Warehouse A, combination "Pick"

2.  Warehouse B, combination "Pick"

3.  No warehouse, combination "All"

Another shipment reservation sequence, "S2," could be defined as follows.

Make a reservation in warehouse A, and then in warehouse B, in all location types. You must follow the assigned sequence, and you must ensure that all warehouses in the site have the reservation completed.

1.  Warehouse A, combination "All"

2.  Warehouse B, combination "All"

3.  No warehouse, combination "All"

Shipment reservation sequences are defined per site and can be specific to a warehouse.

When the combinations for shipment reservation and the shipment reservation sequences have been defined, you can define shipment templates in the **Shipment templates** form.

The **Shipment reservation combinations** form, the **Shipment reservation sequences** form, and the **Shipment templates** form are all available from **Inventory management**\> **Setup** \> **Distribution**.

## Shipment reservation methods

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Output transport - all bulk locations</strong></p></td>
<td><p>A full pallet is physically reserved at the bulk location, based on the <strong>Min. output pallet quantity</strong> setting on the item. Output pallet transports are created.</p></td>
</tr>
<tr class="even">
<td><p><strong>Picking route - item picking location</strong></p></td>
<td><p>If the required quantity is available, items are physically reserved on the item picking location that is defined in the <strong>Warehouse items</strong> form.</p>
<p>For this reservation method, two additional options are available that can be selected individually. This means that the <strong>Picking route - item picking location</strong> reservation method could potentially appear four times in a combination.</p>
<ul>
<li><p><strong>Refill</strong> – If a refill pallet transport does not exist for the picking location, a refill pallet transport is created based on the refill rules, and it is reserved as ordered on the picking location. The items are reserved even if the <strong>Ordered</strong> option has not been selected.</p></li>
<li><p><strong>Ordered</strong> – Reservation can be based on a purchase order line that has the specific item picking location defined.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Picking route - all picking locations</strong></p></td>
<td><p>Reservation is made on random picking locations and assigned to a picking route.</p>
<p>The reservation process finds locations based on the setup specified in the <strong>Item model groups</strong> form. If <strong>FIFO date-controlled</strong> has been selected, the reservation routine sorts and reserves based on date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Picking route - all inbound locations</strong></p></td>
<td><p>Reservation is made on random incoming locations and assigned to a picking route.</p>
<p>The reservation process finds locations based on the setup specified in the <strong>Item model groups</strong> form. If <strong>FIFO date-controlled</strong> has been selected, the reservation process sorts and reserves based on date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Picking route - all bulk locations</strong></p></td>
<td><p>The reservation is made on random bulk locations and assigned to a picking route.</p>
<p>The reservation process finds locations based on the setup specified in the <strong>Item model groups</strong> form. If <strong>FIFO date-controlled</strong> has been selected, the reservation process sorts and reserves based on date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Picking route - all outbound locations</strong></p></td>
<td><p>The reservation is made on random outgoing locations and assigned to a picking route.</p>
<p>The reservation process finds locations based on the setup specified in the <strong>Item model groups</strong> form. If <strong>FIFO date-controlled</strong> has been selected, the reservation process sorts and reserves based on date.</p></td>
</tr>
</tbody>
</table>


## Batch shipment reservations

You can run several shipment reservations at the same time. You can do this when you run the shipment reservation batch job from **Periodic** \> **Shipment reservation** \> **Shipment reservation**. For more information, see [Shipment reservation (class form)](https://technet.microsoft.com/library/hh209536\(v=ax.60\)).

## Running the reservation again

If all items have not been reserved, the shipment reservation process allows the shipment reservation to be rerun, partial reservations to be run, and items to be added to an ongoing shipping process. Picking can be started for the items that are available, even if the complete shipment is not reserved.


> [!NOTE]
> <P>The reservation can only be made from warehouses in the same site.</P>



## See also

[Shipment reservation (class form)](https://technet.microsoft.com/library/hh209536\(v=ax.60\))

  



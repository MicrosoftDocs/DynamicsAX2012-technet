---
title: Picking methods
TOCTitle: Picking methods
ms:assetid: aae46a18-d75e-4281-becc-bdc742de2f4b
ms:mtpsurl: https://technet.microsoft.com/library/Aa589311(v=AX.60)
ms:contentKeyID: 36931878
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Picking methods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Items can be picked by using one of three methods: consolidated picking, order picking, or inventory transaction picking.

## Consolidated picking

With consolidated picking, multiple orders can be combined into one picking list. The orders can potentially be of different types, such as sales orders or transfer orders.

Consolidated picking uses advanced shipment functionality, such as reservation via shipment, activate picking, activate pallet transport, and guided picking routes. Consolidated picking is optimized picking because there is one picking list for multiple orders. It is typically used in a warehouse management environment.

For flexibility of use, the consolidated picking method can be set up in a hierarchy of three levels.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Level</p></th>
<th><p>Form title</p></th>
<th><p>Path</p></th>
<th><p>Action</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p><strong>Item model groups</strong></p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Inventory</strong> &gt; <strong>Item model groups</strong>.</p></td>
<td><p>Select the <strong>Consolidated picking method</strong> check box on the <strong>Setup</strong> FastTab.</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p><strong>Warehouses</strong></p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Inventory breakdown</strong> &gt; <strong>Warehouses</strong>.</p></td>
<td><p>Use the <strong>Use consolidated picking method</strong> field on the <strong>Warehouse management</strong> FastTab to define whether to adhere to the setting in the <strong>Item model groups</strong> form.</p>
<div class="alert">

> [!NOTE]
> <P>The setting in this form overrides the setting in the <STRONG>Item model groups</STRONG> form.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p><strong>Warehouse items</strong></p></td>
<td><p>Click <strong>Product information management</strong> &gt; <strong>Common</strong> &gt; <strong>Released products</strong>. On the <strong>Action Pane</strong>, click the <strong>Manage inventory</strong> tab, and then click <strong>Warehouse items</strong> in the <strong>Warehouse</strong> group.</p></td>
<td><p>Use the <strong>Use consolidated picking method</strong> list on the <strong>Locations</strong> tab to define whether to adhere to the setting in the <strong>Warehouses</strong> form.</p>
<div class="alert">

> [!NOTE]
> <P>The setting in this form overrides the setting in the <STRONG>Warehouses</STRONG> form.</P>


</div>
<p>Whether the setting should be the same as for the warehouse depends on whether the item should be handled differently than most of the other items in the warehouse.</p></td>
</tr>
</tbody>
</table>


Consolidated picking order can also be selected for individual lines during the posting of picking lines. Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, click the **Pick and pack** tab, and then click **Picking list**. By default, the setting from the **Item model groups**, **Warehouses**, or **Warehouse items** form is used, but this setting can be overwritten temporarily on the line.

## Order picking

Order picking is the basic way to handle item picking. One picking list is created for each order.

Order picking can be used only for sales orders and transfer orders. It is the default picking method for those order types.

## Inventory transaction picking

Items can also be picked without creating a picking list and without output order information updates.

Inventory transaction picking is accessed from the individual lines for the relevant journals and orders that are opened from **Inventory management**\> **Journals**.


> [!NOTE]
> <P>It is best not to use inventory transaction picking in combination with one of the other picking methods, because inventory transaction picking does not update information that is related to output orders.</P>


  



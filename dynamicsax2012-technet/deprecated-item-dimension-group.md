---
title: 'Deprecated: Item dimension group'
TOCTitle: Item dimension group
ms:assetid: 8c3ff3c0-abaf-4559-9bb5-9a29b729336c
ms:mtpsurl: https://technet.microsoft.com/library/Dn527169(v=AX.60)
ms:contentKeyID: 59623298
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Item dimension group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, an item dimension encompasses all available item dimensions. The available item dimensions include the following dimensions:

  - Core item-related dimensions – Color, size, and configuration

  - Tracking-related dimensions – Batch and serial number

  - Storage-related dimensions – Site, warehouse, location, and pallet ID

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>As part of the new core shared product definitions, the item dimensions (color, size, and configuration) had to be associated with the product. However, the tracking and storage dimensions could be set up as either shared dimensions or dimensions that were specific to a legal entity. The item dimension group was refactored, and the old grouping table was removed and separated into three individual groups. Any customization in AX 2009 that extends item dimensions must be refactored to accommodate the new table structure.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed, and a replacement feature is available. In Microsoft Dynamics AX 2012, the item-related dimensions (color, size, and configuration) are defined as product dimensions. The tracking-related dimensions (batch and serial number) are defined as tracking dimensions. The storage-related dimensions (site, warehouse, location, and pallet ID) are defined as storage dimensions.</p>
<p>For more information, see <a href="about-inventory-dimensions-and-dimension-groups.md">About inventory dimensions and dimension groups</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Inventory management</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>The upgrade process guarantees that the core item configuration, and tracking and storage dimension values, are mapped to the new product dimension framework.</p></td>
</tr>
</tbody>
</table>

  



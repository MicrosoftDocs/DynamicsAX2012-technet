---
title: 'Deprecated: (IND) Percent exempt replaces load on inventory'
TOCTitle: (IND) Percent exempt replaces load on inventory
ms:assetid: 05c16505-7cf1-47e8-a81d-a759dfb698e9
ms:mtpsurl: https://technet.microsoft.com/library/Dn507112(v=AX.60)
ms:contentKeyID: 59623201
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (IND) Percent exempt replaces load on inventory 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Indian installations, Microsoft Dynamics AX 2009 provides a country-specific feature that supports Indian requirements for load on inventory. Load on inventory enables a tax amount percentage that cannot be claimed as an input tax credit to be loaded into inventory, so that the correct value of the inventory can be reached.

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
<td><p>Foundation changes that were made in Microsoft Dynamics AX 2012 R2 support the load on inventory functionality. Therefore, country-specific modifications are no longer required.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>The load on inventory functionality will be partially removed. Users can use the percent exempt calculation method to override the percent exempt with load on inventory or expression. Because this is only a partial deprecation, any India-specific features that rely on the <strong>Load on inventory</strong> report and inquiry are still available.</p>
<p>For more information, see <a href="ind-create-tax-groups-for-service-tax.md">(IND) Create tax groups for service tax</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  



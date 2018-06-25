---
title: 'Deprecated: Microsoft Dynamics AX Quarantine management'
TOCTitle: Microsoft Dynamics AX Quarantine management
ms:assetid: 7203f418-3699-418d-9fc5-0e8556492a21
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn753832(v=AX.60)
ms:contentKeyID: 62486009
ms.date: 06/04/2014
mtps_version: v=AX.60
---

# Deprecated: Microsoft Dynamics AX Quarantine management [AX 2012]


For the next major release after Microsoft Dynamics AX 2012 R3, the quarantine order functionality will be deprecated.

The quarantine order allows you to block inventory during inspection by transferring physical inventory to a dedicated quarantine warehouse. After inventory is blocked, the quarantined inventory is identified by the material requirements planning (MRP) feature. The quarantine order functionality also allows quarantined inventory to be scrapped.

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
<td><p>The quarantine order functionality duplicates the quality order and the related inventory blocking functionality that is included in the Quality management system (QMS) module. The quarantine order was not integrated into the warehousing features that were introduced in AX 2012 R3.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>For the deprecation of the quarantine management capabilities, we will add the features that are currently conceptually different, such as sales return order processes and scrapping capabilities. These will be added to the QMS module.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Inventory management, Procurement and sourcing, Sales and marketing</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>The impact on upgrade has not been determined. The current assumption is that no changes to upgrade will occur.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


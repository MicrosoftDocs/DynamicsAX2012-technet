---
title: 'Deprecated: (BRA) In-transit warehouse at operation type'
TOCTitle: (BRA) In-transit warehouse at operation type
ms:assetid: 83df6abe-76c9-4e9b-a12c-6ff18aec8e50
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527163(v=AX.60)
ms:contentKeyID: 59623291
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) In-transit warehouse at operation type 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Brazilian installations, Microsoft Dynamics AX 2009 provides country-specific modifications that support the transfer of inventory goods between companies of the same group. These modifications require parameterization of an **In-transit warehouse at operation** type.

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
<td><p>The localization of transfer orders added the capability to issue and receive fiscal documents for the transfer of inventory items between fiscal establishments. Transfers no longer have to be done by using a specific operation type for sales orders and purchase orders.</p>
<p>The <strong>In-transit warehouse</strong> field is disabled for new installations of Microsoft Dynamics AX 2012 R2 but is available for customers who are upgrading. The field will be deprecated in a future release.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature was replaced by functionality that enables the transfer of warehouse items between warehouses that are located in different fiscal establishments, or to third-party warehouses, by using transfer fiscal documents.</p>
<p>For more information, see <a href="bra-about-transfer-orders.md">(BRA) About transfer orders</a>.</p></td>
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
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


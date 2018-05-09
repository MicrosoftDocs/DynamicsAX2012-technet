---
title: 'Deprecated: (BEL) EU sales list transfer'
TOCTitle: (BEL) EU sales list transfer
ms:assetid: 7a0cba9c-35a6-46d7-96ff-2372d4a044f2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527151(v=AX.60)
ms:contentKeyID: 59623280
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BEL) EU sales list transfer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, there are two European Union (EU) sales list transfers, the standard EU sales list transfer and a separate EU sales list transfer for Belgium. The second of these EU sales list transfers is a country/region-specific function that enables the transfer of information to the EU sales list form based on tax information.

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
<td><p>In 2010, a change in legislation in the European community required a new transfer function for the EU sales list. The new EU sales list transfer function is based on the functionality for Belgium, and it transfers data to the EU sales list form based on tax information.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed in Microsoft Dynamics AX 2012 and replaced by the standard EU sales list transfer.</p>
<p>For more information, see <a href="generate-the-eu-sales-list.md">Generate the EU sales list</a> and <a href="https://technet.microsoft.com/en-us/library/aa499405(v=ax.60)">Transfer transactions for EU sales list (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Financial Management</p>
<p>GDL</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Users must check the existing tax code and tax group configuration, because they might have to set up new tax codes. Additionally, users might have either to change the groups that are assigned to service items, or to set up new item sales tax groups and assign them to services or categories. These steps must be completed before any transactions are posted in AX 2012.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


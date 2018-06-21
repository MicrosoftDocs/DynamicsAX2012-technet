---
title: 'Deprecated: Fill Utility'
TOCTitle: Fill Utility
ms:assetid: 99e30ac1-e661-4e3d-9097-72bc96ce4537
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527189(v=AX.60)
ms:contentKeyID: 59623318
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Fill Utility [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2009, the Fill Utility lets users make mass changes to master records and some transactional records.

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
<td><p>The Fill Utility is being deprecated for several reasons:</p>
<ul>
<li><p>The tool does not perform any validation checks before it executes commands. Therefore, data can become corrupted.</p></li>
<li><p>SQL can be used to update multiple records much more efficiently and accurately. By giving this power to a SQL database administrator, we help guarantee data integrity.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed and replaced by the use of standard SQL updates. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa674382(v=ax.60)">update_recordset</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All (A subset of tables is supported within each module.)</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This feature will be removed from the installation and license configuration. The Fill Utility will no longer appear under <strong>Administration</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


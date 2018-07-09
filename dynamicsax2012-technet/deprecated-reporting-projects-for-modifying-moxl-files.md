---
title: 'Deprecated: Reporting Projects for modifying .moxl files'
TOCTitle: Reporting Project
ms:assetid: 270d7390-aa47-4056-8b1e-781d8df9e01a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507139(v=AX.60)
ms:contentKeyID: 59623225
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Reporting Projects for modifying .moxl files [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, a Reporting Project is used when users modify .moxl files, which are representations of report models in files.

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
<td><p>In Microsoft Dynamics AX 2012, the development experience is being aligned with repository-centric development for Microsoft Dynamics AX. Therefore, all model data is stored in the repository and is directly modified on the repository.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. A new project that is known as a Model Project enables direct modification of any reporting data on the repository. Local .moxl files are not required.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa851066(v=ax.60)">How to: Create a Repository</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Developer and Partner Tools</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>None. This feature is installed as a Microsoft Visual Studio integration during setup.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


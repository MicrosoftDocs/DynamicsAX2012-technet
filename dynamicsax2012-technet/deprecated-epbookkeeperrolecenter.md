---
title: 'Deprecated: EPBookkeeperRoleCenter'
TOCTitle: EPBookkeeperRoleCenter
ms:assetid: a2aa3331-2f65-417d-aef1-50f98f298703
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527199(v=AX.60)
ms:contentKeyID: 59623328
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: EPBookkeeperRoleCenter 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, users are assigned to Role Centers based on user profiles, which are sets of default information for a specific role in the organization. Each user is assigned to a user profile, and a Role Center is specified for each profile. The Bookkeeper role is responsible for tasks such as creating and paying vendor invoices, creating sales invoices, billing customers, recording customer payments, depositing payments into bank accounts, reconciling bank statements, printing financial statements, and closing the books at the end of the month.

  - Default user profile: Bookkeeper

  - Role Center page name: EPBookkeeperRoleCenter

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
<td><p>Because of changes in the security model in Microsoft Dynamics AX 2012, the Bookkeeper role is no longer required. Therefore, the Bookkeeper role has been removed from business intelligence (BI) cubes. The Bookkeeper Role Center and the underlying Web Parts have also been removed. In general, Role Centers themselves do not have security, but the securable items that are displayed on a Role Center might. The Accountant role has been identified as equivalent to the Bookkeeper role because of the similarity in duties and privileges.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>No. The feature is no longer available, and there is no replacement feature.</p>
<p>For more information about security roles and licensing, see the <a href="http://download.microsoft.com/download/b/6/6/b66540b2-c8d7-4c5c-91d5-ff6760906a7b/msdax2012_security_roles_licensing_whitepaper.pdf">Security roles and licensing</a> white paper and the <a href="role-based-security-in-microsoft-dynamics-ax.md">Role-based security in Microsoft Dynamics AX</a> topic.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Business Intelligence</p>
<p>Client</p>
<p>Enterprise Portal</p>
<p>General ledger</p></td>
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


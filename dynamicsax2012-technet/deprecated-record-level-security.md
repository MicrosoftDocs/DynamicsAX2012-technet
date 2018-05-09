---
title: 'Deprecated: Record-level security'
TOCTitle: Record-level security
ms:assetid: a4f7a216-8650-46ab-a611-b77555c33b5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527195(v=AX.60)
ms:contentKeyID: 59623324
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Record-level security 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Record-level security (RLS) builds on the restrictions that are enforced by user group permissions. User group permissions let you restrict the menus, forms, and reports that members of a group can access. RLS lets you restrict the information that is shown on reports and in forms.

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
<td><p>This feature will be deprecated in the next version of Microsoft Dynamics AX. It is still functional in the current version. A new framework for data security, Extensible Data Security (XDS), provides all the functionality that the record-level security feature provided. However, XDS also provides more security controls and provides major functionality that is missing from the RLS feature.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature was replaced by the Extensible Data Security feature, which provides all the capabilities that record-level security provided. In addition, XDS lets developers write more powerful queries to restrict the data that users can access. The restrictions are more secure, and are applied not only to the UI but also at the server level. The restrictions can be based not only on the fields in the table that users are accessing but also on data in other tables. This capability becomes increasingly important as the tables become more normalized in each version.</p>
<p>For more information about data security in Microsoft Dynamics AX 2012, see <a href="what-s-new-role-based-security.md">What's new: Role-based security</a> and the <a href="http://www.microsoft.com/en-us/download/details.aspx?id=3110">Developing Extensible Data Security Policies for Microsoft Dynamics AX 2012</a> white paper.</p></td>
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
<td><p>The existing record-level security conditions are not automatically migrated to the new model, because these conditions are based on user groups and companies, whereas the new security framework is global. Because of the limitations of the framework, RLS conditions were very granular. However, conditions can now be written more efficiently. Therefore, it makes sense to manually convert them to the new framework.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


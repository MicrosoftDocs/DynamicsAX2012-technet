---
title: 'Deprecated: Microsoft Dynamics AX domains'
TOCTitle: Microsoft Dynamics AX domains
ms:assetid: 1ec11cc4-c98a-44f6-b543-5c02a421ae56
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507157(v=AX.60)
ms:contentKeyID: 59623242
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Microsoft Dynamics AX domains 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009 and earlier versions, a domain is a group of company accounts. You use domains to set up specific user permissions for a group of company accounts.

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
<td><p>The domain feature was originally added as a mechanism for grouping companies together. You could then easily grant permissions to multiple companies without having to explicitly grant access to each company individually. This support was required, because Microsoft Dynamics AX did not have a way to model the organization structure or a way to base security on an organization structure. Architectural changes in Microsoft Dynamics AX 2012 provide the framework for enforcing security controls by using the organization model structure. Therefore, the domain feature is obsolete.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed, and a replacement feature is available. The organization model and the new extensible data security framework use extensible data security to support hierarchies.</p>
<p>For more information about the organization model and the new extensible data security framework in AX 2012, see the <a href="implementing-and-extending-the-organization-model-white-paper.md">Implementing and Extending the Organization Model (White paper)</a> white paper and the <a href="role-based-security-in-microsoft-dynamics-ax.md">Role-based security in Microsoft Dynamics AX</a> topic.</p></td>
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
<td><p>Upgrade scripts are provided that create hierarchies that are mapped to a domain. The scripts then assign the companies in the domain to a hierarchy of the same name.</p></td>
</tr>
</tbody>
</table>

  



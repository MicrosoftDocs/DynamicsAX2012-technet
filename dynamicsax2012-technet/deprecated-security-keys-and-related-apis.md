---
title: 'Deprecated: Security keys and related APIs'
TOCTitle: Security keys and related APIs
ms:assetid: 6532d48c-93b2-4725-acb4-fc36db6049b2
ms:mtpsurl: https://technet.microsoft.com/library/Dn527137(v=AX.60)
ms:contentKeyID: 59623266
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Security keys and related APIs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Security keys are the permissions that control access to functionality in the application. Security keys are set for individual user groups and users. Permissions determine who can access menus, forms, reports, and tables. Developers can call the security key–related APIs to determine whether users have access to a particular security key and the level of access that those users have.

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
<td><p>The security model has been changed in Microsoft Dynamics AX 2012. The new security model uses the concepts of roles, duties, and privileges. Developers can create privileges and add various securable objects to them. This change enables Microsoft Dynamics AX to move to a standard role-based security model, and provides greater flexibility and manageability.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature was removed, and a replacement feature is available. Security keys have been replaced by role-based security. Role-based security lets a developer or administrator create privileges, duties, and roles, and assign permissions to various resources, based on the security requirements. The framework also automatically identifies the resources that are accessed by some base objects, such as forms, web controls, service operations, and reports. The developer does not have to use security keys to group these related objects. Therefore, the administrator can easily grant access without having to determine which security keys were set by the developer. All the APIs that were based on security keys were removed together with the security keys. These APIs were replaced with APIs that identify access based on objects.</p>
<p>For a high-level overview of the role-based security changes, see the product-wide feature topic <a href="what-s-new-role-based-security.md">What's new: Role-based security</a>. For more detailed information, see the <a href="https://technet.microsoft.com/library/gg864884(v=ax.60)">Role-Based Security System</a> and <a href="security-architecture-of-the-microsoft-dynamics-ax-application.md">Security architecture of the Microsoft Dynamics AX application</a> topics.</p></td>
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
<td><p>Any code that calls APIs to check for access to security keys or to check for the existence of security keys must be upgraded to use the new APIs. To upgrade the configuration keys for objects that use security key–to–configuration key mapping for licensing, run the scripts that are provided.</p></td>
</tr>
</tbody>
</table>

  



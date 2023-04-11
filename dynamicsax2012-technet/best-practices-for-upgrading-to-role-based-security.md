---
title: Best practices for upgrading to role-based security
TOCTitle: Best practices for upgrading to role-based security
ms:assetid: 148d7aad-9092-4cec-8b57-52223ebf3730
ms:mtpsurl: https://technet.microsoft.com/library/Hh575192(v=AX.60)
ms:contentKeyID: 39555321
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Best practices for upgrading to role-based security 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an overview of some best practices that you should consider when you upgrade security. This topic does not describe how to upgrade security settings to Microsoft Dynamics AX 2012. For information about how to upgrade security settings, see the [Security Upgrade Advisor Tool User Guide](security-upgrade-advisor-tool-user-guide.md).

## User groups and roles

When you convert user groups to roles, we recommend that you use the default roles as much as you can. The default roles that are included with Microsoft Dynamics AX 2012 may contain additional permissions that were not available in earlier versions of Microsoft Dynamics AX.

If a user group has more permissions than the related default role, you can create a custom role based on the user group. We recommend that you nest the default role under the custom role, so that the custom role includes the permissions from the default role. The following table provides an example.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>User group in Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009</p></th>
<th><p>Default role in Microsoft Dynamics AX 2012</p></th>
<th><p>Recommendation for upgrade</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>CustomBudgetClerk</strong></p>
<ul>
<li><p>AssetBudgetMaintain</p></li>
<li><p>AssetFixedAssetBudgetsMaintain</p></li>
<li><p>BudgetBudgetCheckResultsInquire</p></li>
<li><p>CustomPrivilege1</p></li>
<li><p>CustomPrivilege2</p></li>
</ul></td>
<td><p><strong>BudgetBudgetClerk</strong></p>
<ul>
<li><p>AssetBudgetMaintain</p></li>
<li><p>AssetFixedAssetBudgetsMaintain</p></li>
<li><p>BudgetBudgetCheckResultsInquire</p></li>
</ul></td>
<td><p><strong>CustomBudgetClerk</strong></p>
<ul>
<li><p>CustomPrivilege1</p></li>
<li><p>CustomPrivilege2</p></li>
<li><p><strong>BudgetBudgetClerk</strong> (nested role)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Use an abbreviation of the company name or function as a prefix in the name of a custom role, such as MS\_CustomRole.

Whenever you can, customize security settings in a custom model. By using a model, you can more easily export security settings from, and import security settings to, a specific layer.

## Security keys

The concept of security keys no longer applies in Microsoft Dynamics AX 2012. Instead, privileges and permissions are used to implement role-based security. By default, thousands of privileges are included in Microsoft Dynamics AX 2012, and each entry point is associated with one or more privileges. If you have created custom entry points, we recommend that you create new privileges that have the View and Full Control access levels. These privileges can then be included in duties or assigned to roles.

## See also

[Upgrade domains](upgrade-domains.md)

  



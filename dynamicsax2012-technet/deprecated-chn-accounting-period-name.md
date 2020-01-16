---
title: 'Deprecated: (CHN) Accounting period name'
TOCTitle: (CHN) Accounting period name
ms:assetid: 597ba234-6d62-49ad-ad99-aa22eb22e3a9
ms:mtpsurl: https://technet.microsoft.com/library/Dn507127(v=AX.60)
ms:contentKeyID: 59623216
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (CHN) Accounting period name 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In the Microsoft Dynamics AX 2009 SP1 GLSCON release, the Accounting period table provides an **Accounting period name** field. This field is a country-specific feature that is provided for Chinese installations, and the field values are not required to be unique in a fiscal year. In Microsoft Dynamics AX 2012, the **Accounting period name** field is included in the Accounting table. Therefore, the country-specific modification is not required.

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
<td><p>Microsoft Dynamics AX 2012 provides support for the <strong>Accounting period name</strong> field in the Accounting table. Therefore, the country-specific modification is no longer required.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. By default, the <strong>Accounting period name</strong> field is available in the Accounting period table. However, in Microsoft Dynamics AX 2012, the <strong>Accounting name</strong> value must be unique in a fiscal year.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>General ledger</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Upgrade scripts are provided that move the existing accounting period names in the China localization version of Microsoft Dynamics AX 2009 to the new <strong>Accounting name</strong> field. During the upgrade process, you must correct duplicate period names.</p></td>
</tr>
</tbody>
</table>

  



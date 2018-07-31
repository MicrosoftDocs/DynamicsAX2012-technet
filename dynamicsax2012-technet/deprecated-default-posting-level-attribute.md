---
title: 'Deprecated: Default posting level attribute'
TOCTitle: Default posting level attribute
ms:assetid: 10c984f9-6475-403f-9503-c3c6444ab662
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507132(v=AX.60)
ms:contentKeyID: 59623220
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Default posting level attribute 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2012, hour journals are used to summarize subledger entries or any subsequent project transactions that are related to timesheets.

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
<td><p>In Microsoft Dynamics AX 2012 Feature Pack, the accounting framework that was introduced in AX 2012 is responsible for posting timesheets.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed, and a replacement feature is available. Timesheets are now posted by using the accounting framework that was introduced in AX 2012. As part of this change, the <strong>Default posting level</strong> attribute that was specific to Project management and accounting has been deprecated.</p>
<p>For more information, see <a href="about-intercompany-timesheets.md">About intercompany timesheets</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Project management and accounting</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>There are no changes during the upgrade from AX 2012 to AX 2012 Feature Pack because of this feature update. However, if you have built any customized solutions on the timesheet functionality in AX 2012, you might have to update those solutions for AX 2012 to accommodate this change, even if you do not intend to use the Intercompany timesheets feature.</p></td>
</tr>
</tbody>
</table>

  



---
title: Deprecated:Task groups
TOCTitle: Task groups
ms:assetid: 95df7e0f-da08-4e4b-b79f-75c3b3c0b7af
ms:mtpsurl: https://technet.microsoft.com/library/Dn527183(v=AX.60)
ms:contentKeyID: 59623313
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated:Task groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, task groups are used to specify alternative work centers that can perform similar tasks. In Microsoft Dynamics AX 2012, task groups are upgraded to resource capabilities.

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
<td><p>Architectural changes in AX 2012 introduced a new resource model and capability-based scheduling. Therefore, the concept of task groups became obsolete.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. Task groups have been replaced by the more versatile concept of capabilities, which can be used to specify resource requirements for operations. Therefore, the scheduling engine can choose between alternative resources that can perform similar tasks.</p>
<p>For more information, see the <a href="https://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_the_operations_resource_model_ax2012.pdf">Implementing the Operations Resource Model for Microsoft Dynamics AX 2012 applications</a> white paper and the <a href="set-up-operations-for-production.md">Set up operations for production</a> topic.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Manufacturing</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>During the upgrade process, any task groups that are used in AX 2009 are upgraded to capabilities. Because capabilities are shared across legal entities in AX 2012, the upgrade process enables task groups to be consolidated across legal entities.</p></td>
</tr>
</tbody>
</table>

  



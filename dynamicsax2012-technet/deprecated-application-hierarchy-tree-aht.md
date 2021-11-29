---
title: 'Deprecated: Application Hierarchy Tree (AHT)'
TOCTitle: Application Hierarchy Tree (AHT)
ms:assetid: bdd68234-881a-46df-9df2-da314af96264
ms:mtpsurl: https://technet.microsoft.com/library/Dn527229(v=AX.60)
ms:contentKeyID: 59623357
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Application Hierarchy Tree (AHT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the Application Hierarchy Tree is used to inspect types and their hierarchical structure, such as a class that extends another class.

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
<td><p>The Application Hierarchy Tree was based on a Help control that has been deprecated in Microsoft Dynamics AX 2012.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The code has been rewritten, and the feature is now called the Type Hierarchy Browser. The overall user interface remains the same, but the tool is now hosted inside the MorphX environment as a multiple-document interface (MDI) child. The tool has also been extended to support table inheritance and navigation to listed element members, such as methods. Additionally, a dockable variant that is known as the Type Hierarchy Context can be used to provide contextual hierarchy information when users navigate the Microsoft Dynamics AX Application Object Tree (AOT).</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/gg864119(v=ax.60)">Type Hierarchy Browser and Type Hierarchy Context</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Developer and Partner Tools</p></td>
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

  



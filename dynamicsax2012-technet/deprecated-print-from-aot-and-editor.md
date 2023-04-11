---
title: 'Deprecated: Print from AOT and Editor'
TOCTitle: Print from AOT and Editor
ms:assetid: 20293ee1-70c9-425f-a296-0041d674f143
ms:mtpsurl: https://technet.microsoft.com/library/Dn507152(v=AX.60)
ms:contentKeyID: 59623237
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Print from AOT and Editor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, users can print nodes in the Microsoft Dynamics AX Application Object Tree (AOT) as .xpo content and code as a report.

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
<td><p>The capability to print relied on support for reporting other than Microsoft SQL Server Reporting Services reporting. However, this support is deprecated in Microsoft Dynamics AX 2012. Except in the case of code, the feature mainly prints .xpo content. Because .xpo content can be manually printed, and because the feature is infrequently used, no investment has been made to implement support in AX 2012.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>No. The feature is no longer available, and there is no replacement feature. As a workaround, nodes can be exported as .xpo files and then printed manually.</p>
<p>For more information, see <a href="how-to-export-application-objects-by-using-the-aot.md">How to: Export Application Objects by Using the AOT</a>.</p></td>
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

  



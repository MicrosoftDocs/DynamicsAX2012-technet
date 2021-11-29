---
title: 'Deprecated: X++ Reporting Framework'
TOCTitle: X++ Reporting Framework
ms:assetid: 95a34245-f7ce-4854-978d-aa71c4be0d3c
ms:mtpsurl: https://technet.microsoft.com/library/Dn527177(v=AX.60)
ms:contentKeyID: 59623304
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: X++ Reporting Framework 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2009 and earlier versions supported the X++ reporting framework, which was used to create custom reports in Microsoft Dynamics AX. The X++ reporting framework is being deprecated in Microsoft Dynamics AX 2012 and will not be available in future versions.

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
<td><p>The X++ reporting framework was deprecated for the following reasons:</p>
<ul>
<li><p>It lacks charting capabilities.</p></li>
<li><p>It lacks support for data sources other than Microsoft Dynamics AX data sources.</p></li>
<li><p>It lacks support for interactive reports.</p></li>
<li><p>It is not an industry-standard solution.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Microsoft SQL Server Reporting Services is now the primary reporting platform for Microsoft Dynamics AX.</p>
<p>For more information, see <a href="what-s-new-reporting.md">What's new: Reporting</a> and <a href="overview-of-reporting-services.md">Overview of Reporting Services</a>.</p></td>
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
<td><p>When you upgrade to AX 2012, reports that are based on the X++ reporting framework are copied to the AX 2012 system but are not upgraded. We recommend that you use one of the Reporting Services reports that are provided with AX 2012 as a template, and customize that report to meet your requirements.</p></td>
</tr>
</tbody>
</table>

  



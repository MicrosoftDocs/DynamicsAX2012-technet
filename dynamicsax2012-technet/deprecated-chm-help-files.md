---
title: 'Deprecated: .chm Help files'
TOCTitle: .chm Help files
ms:assetid: f7a3d1bb-86e5-4f3b-9a88-07903f7cdc54
ms:mtpsurl: https://technet.microsoft.com/library/Dn527237(v=AX.60)
ms:contentKeyID: 59623365
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: .chm Help files 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009 and earlier versions, Help content was available in the **HTML Help Files** node of the Microsoft Dynamics AX Application Object Tree (AOT). This Help content was in the form of .chm files.

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
<td><p>The functionality that this feature provided was limited. A new Help system that provides improved customization scenarios is replacing the legacy system.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature is no longer available, and a replacement feature is available. The HTML-based Help files are being replaced with a more robust Help server that provides Help content to all clients from a centralized location. This Help content is available in HTML and other formats.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>A web service that hosts the Help content is installed when setup.exe is executed. To plan for the installation, verify that you have an Internet Information Services (IIS) server that can host the Help server.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Legacy properties and elements in the AOT are removed during the upgrade. To plan for the upgrade, verify that you have an IIS server that can host the Help server.</p></td>
</tr>
</tbody>
</table>


## See also

[What's new: Help system](what-s-new-help-system.md)

[Install help server](install-help-server.md)

  



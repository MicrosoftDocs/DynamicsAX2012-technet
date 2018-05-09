---
title: 'Deprecated: AOD files'
TOCTitle: AOD files
ms:assetid: 78a4ae5b-acc2-466f-b4b3-48485b985260
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527159(v=AX.60)
ms:contentKeyID: 59623288
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: AOD files 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The layer-based application object files (AOD files) have been replaced by a dedicated Microsoft SQL Server database that is known as the model store. All application elements are stored in the model store. For developers, the storage is transparent. The Setup program creates the model store by using the application elements from Microsoft.

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
<td><p>The use of a state-of-the-art database back end, such as SQL Server, made the proprietary application object database and its AOD files a bottleneck with regard to development, maintenance, and performance.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. AOD files and the proprietary database have been replaced by the SQL Server database. AOD files from Microsoft Dynamics AX 2009 and Microsoft Dynamics AX 4.0 can be loaded into the model store during upgrade or later by using the <strong>Developer</strong> menu in MorphX. AXUTIL.EXE is a command-line tool for managing metadata that is “in transit.” For example, the tool can be used to export, install, and even uninstall metadata.</p>
<p>For more information, see <a href="how-to-export-and-import-a-model-store.md">How to: Export and Import a Model Store</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Developer and Partner Tools</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>The required changes are handled by the Setup program, which installs the models (the new logical packaging of metadata) in the model store in SQL Server. The model store is an integral part of the application database.</p>
<p>For more information, see <a href="models-layers-and-the-model-store.md">Models, Layers, and the Model Store</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>The upgrade process semantically resembles the process that is used in earlier versions, but some new steps are required. The AOD files and directories are no longer copied from the earlier version to the application directory but must now be imported into the model database. Additionally, we recommend that you import the AOD files into a secondary database that is named the “alternate” database. This database effectively mimics the directory for code compare.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


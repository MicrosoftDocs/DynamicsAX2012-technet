---
title: 'Deprecated: Duplicate company feature'
TOCTitle: Duplicate company feature
ms:assetid: b323d938-4839-4e2d-b67d-ed61af57cc25
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527200(v=AX.60)
ms:contentKeyID: 59623329
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Duplicate company feature 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the **Company accounts** form contains a Duplicate company feature that lets users duplicate the data for a company.

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
<td><p>Changes to the underlying architecture of Microsoft Dynamics AX 2012 made the Duplicate company feature obsolete.</p>
<p>The organization model represents a major change in AX 2012. In AX 2009, most of the application data was related to the company or DataAreaID concept, and this data could easily be duplicated by traversing all tables where the <strong>SaveDataPerCompany</strong> metadata property was set to <strong>True</strong>. Because of the new organization model, the data is not purely related to legal entities, and a company is semantically equivalent to a legal entity. The data is related either to one or more types of organization, or to no organization type (shared tables). Therefore, duplication of data based on this property is not valid.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>No. The feature is no longer available, and there is no replacement feature.</p>
<p>Although there is no replacement for the Duplicate company feature, a company can still be used as a template to create other companies. By using the Import and export feature, users can create duplicate reference, setup, and master data by copying data between two companies. For demo data, the Import and export feature can be used to replicate a company from one environment in another environment, or in the same environment. Users can also make additional changes to create an appropriate demo scenario in the new company.</p>
<p>For more information, see <a href="use-dat-and-def-files-to-export-and-import-data.md">Use DAT and DEF files to export and import data</a> and <a href="export-data-to-another-instance-of-microsoft-dynamics-ax.md">Export data to another instance of Microsoft Dynamics AX</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>No modules are directly affected.</p></td>
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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


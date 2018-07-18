---
title: 'Deprecated: Custom date-effective functionality for Human resources forms'
TOCTitle: Custom date-effective functionality for Human resources forms
ms:assetid: fc517f7d-a2f2-4c3e-bee4-c4e29a435662
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527263(v=AX.60)
ms:contentKeyID: 59623391
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Custom date-effective functionality for Human resources forms 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, Employee/contractor, Job, Position, and Department (Organization) records are stored as date-effective records.

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
<td><p>The functionality that the feature provided was limited. The feature has been replaced with the new date-effective framework in Microsoft Dynamics AX 2012.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature is no longer available, and a replacement feature is available. All the records continue to be date-effective, but they use a new date-effective framework. In AX 2012, both the date elements and the time elements are exposed in the user interface.</p>
<p>For more information, see the white paper <a href="http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_and_updating_the_human_resources_framework_ax2012.pdf">Implementing and Updating the Human Resources Framework for Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Human resources</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Existing date-effective records are upgraded to the new tables that store these records. The AX 2012 framework completes the processing of date-effective records.</p>
<div class="alert">

> [!NOTE]
> <P>The table structure has been normalized in <STRONG>Human resources</STRONG>. Therefore, one date-effective record might be split into multiple records, depending on the new table definitions in AX 2012.</P>


</div></td>
</tr>
</tbody>
</table>

  



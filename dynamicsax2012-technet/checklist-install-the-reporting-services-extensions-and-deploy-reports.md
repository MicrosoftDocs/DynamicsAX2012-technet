---
title: 'Checklist: Install the Reporting Services extensions and deploy reports'
TOCTitle: 'Checklist: Install the Reporting Services extensions and deploy reports'
ms:assetid: d414bfd2-4ff1-487c-a4b6-ace0e7e1b73e
ms:mtpsurl: https://technet.microsoft.com/library/Dd362085(v=AX.60)
ms:contentKeyID: 28119591
author: Khairunj
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Checklist: Install the Reporting Services extensions and deploy reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To install the Microsoft SQL Server Reporting Services extensions and deploy reports, complete the tasks in the following checklist.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Complete the preinstallation tasks:</p>
<ol>
<li><p>Verify that you have the permissions that are required to install the Reporting Services extensions.</p></li>
<li><p>Install prerequisites.</p></li>
<li><p>Configure the Reporting Services instance.</p></li>
</ol></td>
<td><p><a href="before-you-install-the-reporting-services-extensions.md">Before you install the Reporting Services extensions</a></p></td>
</tr>
<tr class="even">
<td><p>Install the Reporting Services extensions.</p></td>
<td><p><a href="install-the-reporting-services-extensions.md">Install the Reporting Services extensions</a></p></td>
</tr>
<tr class="odd">
<td><p>Complete the Reporting Services integration. The directions vary, depending on whether you are running Reporting Services in native mode or SharePoint integrated mode.</p>
<div class="alert">

> [!NOTE]
> <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>


</div>
<p>If you are running Reporting Services in native mode, complete the following procedures:</p>
<ol>
<li><p>Deploy the default reports that are included with Microsoft Dynamics AX, if you did not already deploy the reports when you installed the Reporting Services extensions.</p></li>
<li><p>Assign users to the DynamicsAXBrowser role on the Report Manager site.</p></li>
</ol>
<p>If you are running Reporting Services in SharePoint integrated mode, complete the following procedures:</p>
<ol>
<li><p>Create a document library to store reports.</p></li>
<li><p>Deploy the default reports that are included with Microsoft Dynamics AX.</p></li>
<li><p>Grant users permission to view reports in SharePoint.</p></li>
</ol></td>
<td><p><a href="complete-the-reporting-services-integration.md">Complete the Reporting Services integration</a></p></td>
</tr>
</tbody>
</table>

  



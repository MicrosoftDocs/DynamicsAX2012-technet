---
title: 'Checklist: Configure Analysis Services and deploy cubes'
TOCTitle: 'Checklist: Configure Analysis Services and deploy cubes'
ms:assetid: adec63f7-107a-478d-96a6-3beeab12af58
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731892(v=AX.60)
ms:contentKeyID: 35132808
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Checklist: Configure Analysis Services and deploy cubes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure Microsoft SQL Server Analysis Services for use with Microsoft Dynamics AX and to deploy the cubes that are included with Microsoft Dynamics AX, complete the tasks in the following checklist.

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
<td><p>Complete the prerequisite tasks:</p>
<ol>
<li><p>Verify that you have the permissions that are required to configure Analysis Services.</p></li>
<li><p>Create a domain account to run the Analysis Services service.</p></li>
<li><p>Assign the .NET Business Connector proxy account to the server administrator role in Analysis Services.</p></li>
<li><p>Install prerequisites.</p></li>
</ol></td>
<td><p><a href="before-you-configure-analysis-services.md">Before you configure Analysis Services</a></p></td>
</tr>
<tr class="even">
<td><p>Configure Analysis Services by running the Microsoft Dynamics AX Setup Wizard.</p></td>
<td><p><a href="configure-analysis-services-by-running-setup.md">Configure Analysis Services by running Setup</a></p></td>
</tr>
<tr class="odd">
<td><p>Complete the Analysis Services integration:</p>
<ol>
<li><p>Install SQL Server Shared Management Objects on Microsoft Dynamics AX client computers.</p></li>
<li><p>Verify that information about exchange rates has been entered.</p></li>
<li><p>Deploy the default cubes that are included with Microsoft Dynamics AX.</p></li>
<li><p>Update the data source for online analytical processing (OLAP) if your Analysis Services database is not named <em>Dynamics AX</em>.</p>
<div class="alert">

> [!NOTE]
> <P>If you are using Microsoft Dynamics AX 2012 R2 or later, this step does not apply to you.</P>


</div></li>
<li><p>Configure the cubes, based on the changes that you have made to the Microsoft Dynamics AX configuration or license keys.</p></li>
<li><p>Grant users access to the cubes.</p></li>
<li><p>Automate the processing of cubes.</p></li>
<li><p>Create new date dimensions for the cubes.</p></li>
<li><p>Add financial dimensions to the cubes.</p></li>
</ol></td>
<td><p><a href="install-sql-server-shared-management-objects.md">Install SQL Server Shared Management Objects</a></p>
<p><a href="verify-that-exchange-rate-information-has-been-entered.md">Verify that exchange rate information has been entered</a></p>
<p><a href="deploy-the-default-cubes.md">Deploy the default cubes</a></p>
<p><a href="update-the-olap-data-source.md">Update the OLAP data source</a></p>
<p><a href="configure-an-existing-sql-server-analysis-services-project.md">Configure an Existing SQL Server Analysis Services Project</a></p>
<p><a href="grant-users-access-to-cubes.md">Grant users access to cubes</a></p>
<p><a href="automate-the-processing-of-cubes.md">Automate the processing of cubes</a></p>
<p><a href="how-to-create-a-date-dimension-for-a-cube.md">How to: Create a Date Dimension for a Cube</a></p>
<p><a href="how-to-add-a-financial-dimension-to-a-cube.md">How to: Add a Financial Dimension to a Cube</a></p></td>
</tr>
</tbody>
</table>

  



---
title: 'How to: Deploy Reports to a Report Server'
TOCTitle: 'How to: Deploy Reports to a Report Server'
ms:assetid: fa38937f-7a60-4e6a-a401-c802dd50711a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc654602(v=AX.60)
ms:contentKeyID: 28119622
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# How to: Deploy Reports to a Report Server [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to deploy reports to a report server from Microsoft Dynamics AX and from Microsoft Visual Studio.

SQL Server Reporting Services is the reporting platform for Microsoft Dynamics AX. Reporting Services enables developers to create and publish traditional, paper-based reports, and interactive Web-based reports. When you deploy a report, the report design, data sources, and associated business logic assemblies are deployed to the SQL Server Reporting Services server.

Deploying reports to Reporting Services does the following:

  - Uploads the Report Definition Language (RDL) file, which is the report, to the Reporting Services server

  - Copies the business logic assemblies to the Reporting Services server

  - Ensures that the cross referenced report and business logic assemblies are present to have a valid report deployed

To deploy an Microsoft Dynamics AX reporting project in Visual Studio, you must start Visual Studio with administrative privileges or start Microsoft Dynamics AX and the Developer Workspace with administrative privileges. To do this, you must right-click on the icon for Visual Studio or Microsoft Dynamics AX and then choose **Run as administrator**. The following table describes the options to deploy reports:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Deploy option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft Dynamics AX</p></td>
<td><p>Reports can be deployed individually from a developer workspace in Microsoft Dynamics AX.</p>
<p>In the AOT, expand the <strong>SSRS Reports</strong> node, expand the <strong>Reports</strong> node, right-click the report, and then click <strong>Deploy Element</strong>.</p>
<p>The reports are deployed for all the translated languages.</p></td>
</tr>
<tr class="even">
<td><p>Microsoft Visual Studio</p></td>
<td><p>Reports can be deployed individually from Visual Studio.</p>
<p>In Solution Explorer, right-click the reporting project that contains the reports that you want to deploy, and then click <strong>Deploy</strong>.</p>
<p>The reports are deployed for the neutral (invariant) language only.</p></td>
</tr>
<tr class="odd">
<td><p>Microsoft PowerShell</p></td>
<td><p>Used to deploy the default reports that are provided with Microsoft Dynamics AX.</p>
<p>For information about how to deploy from PowerShell, see <a href="deploy-the-default-reports.md">Deploy the default reports</a>.</p></td>
</tr>
</tbody>
</table>


For more information about deployment, see [Report Integration and Customization Overview](report-integration-and-customization-overview.md). For information about the reporting install, see [Install business intelligence components](install-business-intelligence-components.md).

### To deploy reports from Microsoft Dynamics AX

1.  In the AOT, expand the **SSRS Reports** node.

2.  Expand the **Reports** node.

3.  Right-click the report that you want to deploy, and then click **Deploy Element**.

### To deploy reports from Microsoft Visual Studio

  - In Solution Explorer, right-click the reporting project that contains the reports that you want to deploy, and then click **Deploy**. Reports are deployed for the neutral (invariant) language only.

## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md)

[How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md)

[How to: Customize a Report](how-to-customize-a-report.md)


---
title: Report Upgrade
TOCTitle: Report Upgrade
ms:assetid: cb41746e-3995-42df-bf51-b78edf71a71b
ms:mtpsurl: https://technet.microsoft.com/library/Gg724122(v=AX.60)
ms:contentKeyID: 35133481
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Report Upgrade 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides guidance to convert X++ reports, Microsoft Visual Studio tools for Microsoft Dynamics AX reports, and troubleshooting tips for converted reports. To use the reports you created or customized in Microsoft Dynamics AX 2009, they must be converted for Microsoft Dynamics AX 2012. The upgrade readiness checklist checks the reports that will need to be upgraded for the current release. For more information, see [Upgrade overview and preparation](upgrade-overview-and-preparation.md).

## Converting reports

The following sections provide the suggested options to upgrade reports from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012. The options are provided for reports that were originally created with:

  - Morphx Reporting tool

  - Visual Studio tools for Microsoft Dynamics AX 2009

## X++ reports

The X++ reporting framework is being deprecated in Microsoft Dynamics AX 2012. Reports that you created or customized using the Morphx Reporting tool will be copied to the Microsoft Dynamics AX system, but they will not be upgraded. The following table describes the options to upgrade an X++ report.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Option</p></td>
<td><p>Tool</p></td>
</tr>
<tr class="even">
<td><p>Define a new Reporting Services report.</p></td>
<td><p>Visual Studio Reporting Tools for Microsoft Dynamics AX</p>
<p>For more information, see <a href="development-tasks-for-reporting.md">Development Tasks for Reporting</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Customize an existing production report to meet the same reporting purposes that the original X++ report served.</p></td>
<td><p>Visual Studio Reporting Tools for Microsoft Dynamics AX</p>
<p>For more information, see <a href="integrating-and-customizing-reports.md">Integrating and Customizing Reports</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fix the report. This is not the recommended approach as the MorphX Reporting tool is being deprecated.</p></td>
<td><p>Morphx Reporting Tools</p>
<p>For more information, see <a href="morphx-reporting-tools.md">MorphX Reporting Tools</a>.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>The End user settings for report print and parameter settings for X++ reports must be reset after the upgrade.</P>
> <P>You will no longer set security explicitly on X++ report objects. For example, you previously secured a field on the report using a security key. Role and task security on report data sources like tables and fields will be enforced by X++ reports. For information, see <A href="set-up-user-security-in-microsoft-dynamics-ax.md">Set up user security in Microsoft Dynamics AX</A>.</P>



## Microsoft Visual Studio tools for Microsoft Dynamics AX reports

Due to framework changes that affect report formats and queries, you must convert reports that were created using Visual Studio tools for Microsoft Dynamics AX 2009. The following table describes the options for a Reporting Services report that was created or customized using the Visual Studio tools for Microsoft Dynamics AX 2009.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Tool</p></td>
<td><p>Task</p></td>
</tr>
<tr class="even">
<td><p>Report Upgrade Tool</p></td>
<td><p>Convert the Reporting Services report format to the current report format. For more information, see <a href="report-project-upgrade.md">Report Project Upgrade</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Visual Studio tools for Microsoft Dynamics AX</p></td>
<td><p>Define a new report.</p>
<p>Or</p>
<p>Customize an existing production report to meet the same reporting purposes.</p></td>
</tr>
</tbody>
</table>


## Troubleshooting converted reports

After an Microsoft Dynamics AX 2009 report is converted, there may be additional troubleshooting steps required in Visual Studio tools for Microsoft Dynamics AX. The following table describes additional details for specific kinds of Reporting Services reports.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Report issue</p></th>
<th><p>How to resolve</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Report data source is SQL and you are receiving the error:</p>
<p>An SqlParameter with ParameterName ‘AX_CompanyName’ is not contained by this SqlParameterCollection.</p></td>
<td><p>Refresh the dataset for the report to clear out legacy parameters. In Model Editor, right-click the dataset for the report and then click <strong>Refresh</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Report data source is SQL and you are receiving the error:</p>
<p>The ‘AX_CompanyName’ parameter is missing a value.</p></td>
<td><p>Remove the AX_CompanyName parameter. To do this, in Model Editor, select the <strong>AX_CompanyName</strong> parameter. In the Properties window, set the <strong>Default Value</strong> to =Microsoft.Dynamics.Framework.Reports.BuiltInMethods.GetUserComany(Nothing).</p></td>
</tr>
<tr class="odd">
<td><p>Report has data methods and you receive an error that the application requires Full Trust permissions to run correctly.</p></td>
<td><p>Data methods must run with the FullTrust named permission set. For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=224632">Code Access Security</a>.</p></td>
</tr>
<tr class="even">
<td><p>The report parameter values no longer display in the report header.</p></td>
<td><p>The <strong>RenderParameter</strong> property is intended to debug report parameter values. It displays the parameter values in the header of the report. The default value in Microsoft Dynamics AX 2009 for the <strong>RenderParameter</strong> property was True. In Microsoft Dynamics AX 2012, the default value is False. During upgrade, the value is not explicitly set.</p>
<p>To show the parameter values in the report header, in Model Editor, select the auto design for the report and set the <strong>RenderParameter</strong> property to <strong>True</strong>.</p></td>
</tr>
</tbody>
</table>


## See also

[Upgrade overview and preparation](upgrade-overview-and-preparation.md)

[Report Project Upgrade](report-project-upgrade.md)

  



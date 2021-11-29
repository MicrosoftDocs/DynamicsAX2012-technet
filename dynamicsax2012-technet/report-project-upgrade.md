---
title: Report Project Upgrade
TOCTitle: Report Project Upgrade
ms:assetid: b7a7535b-11c7-4ebb-8d88-172bb9577b32
ms:mtpsurl: https://technet.microsoft.com/library/Hh292607(v=AX.60)
ms:contentKeyID: 36655946
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Project Upgrade 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The report upgrade tool is a command line tool that helps you prepare Microsoft Dynamics AX 2009 SQL Server Reporting Services report libraries for the Microsoft Dynamics AX 2012 AOT environment. This is a required step for Microsoft Dynamics AX 2009Reporting Services reports that you want to upgrade to Microsoft Dynamics AX 2012 Reporting Services reports because metadata is now accessed in the AOT nodes instead of .moxl files.

## Report Upgrade Tools Tasks

The report upgrade tool locates the Microsoft Dynamics AX 2009 report projects for the location you specify. The following list describes the tasks that the report upgrade tool performs for each report project:

1.  Creates a Dynamics AX Model Project with the same name. The project is created in the AOT in **Visual Studio Projects** \> **Dynamics AX Model Projects**. Nested business logic is saved but it is not nested.

2.  Identifies the concepts for each Microsoft Dynamics AX model file and creates the appropriate node under the **SSRS Reports** node in the AOT. The **SSRS Reports** node is used to store metadata for the top level element and sub-elements. The **SSRS Reports** node that is created does not contain project files.

3.  Displays the completion status of the upgrade and any errors that occurred.

### Using the Report Upgrade Tool

The default install location of the report upgrade tool is C:\\Program Files\\Microsoft Dynamics AX\\60\\tools. The syntax for the tool is as follows:

UpgradeReports \[command\] –t \[target directory\] \<options\>


> [!IMPORTANT]
> <P>The files in the target directory will be deleted.</P>



You can access Help at the command line from the upgrade tool location, by running **UpgradeReports -?**.

The following table describes the report upgrade tool parameters:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>-p</p></td>
<td><p>The project to upgrade. The extension of the project is <strong>.dynamicsproj</strong>.</p></td>
</tr>
<tr class="even">
<td><p>-d</p></td>
<td><p>The directory that contains projects to upgrade. Subdirectory projects are also upgraded.</p></td>
</tr>
<tr class="odd">
<td><p>-l</p></td>
<td><p>The report library from the AOT to upgrade. The library is first extracted to a temporary location.</p></td>
</tr>
<tr class="even">
<td><p>-list</p></td>
<td><p>A list of the report libraries from the AOT to upgrade. Each report library should be listed on a separate line.</p></td>
</tr>
<tr class="odd">
<td><p>-t</p></td>
<td><p>The target directory where the upgraded project is created.</p></td>
</tr>
</tbody>
</table>


The following table describes the report upgrade tool options:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>-stop</p></td>
<td><p>Stop the upgrade when there is an error. By default, the upgrade continues to run if you do not use the –stop option.</p></td>
</tr>
<tr class="even">
<td><p>-overwritenodes</p></td>
<td><p>Overwrite the nodes in the AOT. By default, the nodes are not overwritten if you do not use the –overwritenodes option.</p></td>
</tr>
<tr class="odd">
<td><p>-createlabels</p></td>
<td><p>Create labels in Microsoft Dynamics AX for strings that are in the .resx files. By default, labels are not created unless you use the –createlabels option.</p></td>
</tr>
<tr class="even">
<td><p>-savetoaod</p></td>
<td><p>Save the project to a report library in Microsoft Dynamics AX.</p></td>
</tr>
</tbody>
</table>


### Examples

The following table provides examples and descriptions of command line uses of the report upgrade tool:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Example</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>UpgradeReports -l CRMReports -t d:\temp</p></td>
<td><p>Upgrades the report from the CRMReports library in the AOT.</p></td>
</tr>
<tr class="even">
<td><p>UpgradeReports -p reportsDir\CRMReports.dynamicsproj -t d:\temp</p></td>
<td><p>Upgrades the CRMReports project from disk.</p></td>
</tr>
<tr class="odd">
<td><p>UpgradeReports -d reportsDir -t d:\temp</p></td>
<td><p>Upgrades all reports in the reportsDir directory and its subdirectories.</p></td>
</tr>
<tr class="even">
<td><p>UpgradeReports -list d:\reports.txt -t d:\temp</p></td>
<td><p>Upgrades the libraries that are specified in the reports.txt file. The contents of the file d:\reports.txt are the following:</p>
<p>AssetAcquisitionReport</p>
<p>AssetAdditionReport</p>
<p>AssetBalanceReportColumnsReport</p></td>
</tr>
</tbody>
</table>


## See also

[Upgrading Reports](upgrading-reports.md)


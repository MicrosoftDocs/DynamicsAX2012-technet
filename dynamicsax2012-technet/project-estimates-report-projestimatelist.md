---
title: Project estimates report (ProjEstimateList)
TOCTitle: Project estimates report (ProjEstimateList)
ms:assetid: a583c476-3097-4de5-8bff-b8b5030f38ad
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa617971(v=AX.60)
ms:contentKeyID: 37832026
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjEstimateList
---

# Project estimates report (ProjEstimateList) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view and print estimates by estimate date and period code. You can select to include the status of the project estimates and any warnings for an estimate on the report.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Period code</strong></p></td>
<td><p>Select the period code. The period code that you select determines the start dates that you select in the <strong>Estimate date</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimate date</strong></p></td>
<td><p>Select a date for the estimate projects that you want to include on the report.</p>
<div class="alert">

> [!NOTE]
> <P>If you do not select an actual start date that is applicable to the selected <STRONG>Period code</STRONG>, the report will be empty.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Included warnings</strong></p></td>
<td><p>Select whether to include warning types on the report from the following options:</p>
<ul>
<li><p><strong>Nothing to print</strong> – No report is created and nothing is displayed.</p></li>
<li><p><strong>Exclude warnings</strong> – A report is created. However, no warnings are included on the report.</p></li>
<li><p><strong>Include warnings</strong>– A report is created and warnings are displayed.</p></li>
<li><p><strong>Only warnings</strong> – A report is created, but only warnings are displayed.</p></li>
</ul>
<div class="alert">

> [!NOTE]
> <P>The following conditions are displayed as warnings on the report:</P>


</div>
<ul>
<li><p>A percentage of completion larger than 100 percent.</p></li>
<li><p>A percentage of completion less than 0 percent.</p></li>
<li><p>A negative amount in the remaining estimate column.</p></li>
<li><p>An estimate that has no corresponding contract amount.</p></li>
<li><p>An estimate that has no cost estimate attached.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Included estimate status</strong></p></td>
<td><p>Select the estimate statuses to include on the report.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>ProjEstimateList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjEstimateList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjEstimateList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Estimates</strong> &gt; <strong>Project estimates</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjEstimateListDP.processReport

  - ProjEstimateListTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjEstimateListDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


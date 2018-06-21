---
title: Resource assignment analysis report (PSAResourceAssignmentAnalysis)
TOCTitle: Resource assignment analysis report (PSAResourceAssignmentAnalysis)
ms:assetid: 66df7ff6-16ba-4b5e-8684-bfe2adfc36b2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh334488(v=AX.60)
ms:contentKeyID: 36676473
ms.date: 05/27/2014
mtps_version: v=AX.60
f1_keywords:
- reports
- project add-in
- SSRS_Reports.Reports.PSAResourceAssignmentAnalysis
- resource assignment analysis reports
- worker assignments
- worker commitment types
---

# Resource assignment analysis report (PSAResourceAssignmentAnalysis) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Resource assignment analysis** report to view a list of worker assignments based on criteria that you select. For example, you can select project types and worker commitment types in a date range. You can also select a specific project, quotation, activity, date, starting time, or ending time to filter the information on the report.


> [!NOTE]
> <P>This form is available only in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



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
<td><p><strong>Include project types</strong></p></td>
<td><p>Select the check boxes for the project types to include on the report. You must select at least one project type.</p>
<ul>
<li><p><strong>Time and material</strong></p></li>
<li><p><strong>Fixed-price</strong></p></li>
<li><p><strong>Internal and cost</strong></p></li>
<li><p><strong>Investment</strong></p></li>
<li><p><strong>Time</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Include commitment types</strong></p></td>
<td><p>Select the check boxes for the types of worker commitments to include on the report. You must select at least one commitment type.</p>
<ul>
<li><p><strong>Hard</strong></p></li>
<li><p><strong>Soft</strong></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the starting date of the date range for which to view worker assignments.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the date range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Display periods</strong></p></td>
<td><p>In the <strong>Layout – rows</strong> section, select this check box to sort the report by worker assignment periods.</p></td>
</tr>
<tr class="even">
<td><p><strong>Display workers</strong></p></td>
<td><p>Select this check box to organize the report by worker.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show descriptions</strong></p></td>
<td><p>In the <strong>Layout – columns</strong> section, select the columns to include on the report.</p>
<ul>
<li><p><strong>Descriptions only</strong></p></li>
<li><p><strong>IDs only</strong></p></li>
<li><p><strong>IDs and descriptions</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Column format</strong></p></td>
<td><p>Select how you want to organize the columns.</p>
<ul>
<li><p><strong>Employee</strong></p></li>
<li><p><strong>Department</strong></p></li>
<li><p><strong>Project</strong></p></li>
</ul></td>
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
<td><p>PSAResourceAssignmentAnalysis</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PSAResourceAssignmentAnalysis</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Resource assignment analysis</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p><strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Resource scheduling</strong> &gt; <strong>Resource assignment analysis</strong></p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PSAResourceAssignmentAnalysisDP.PROCESSREPORT

  - DefaultDimensionView table

  - HcmWorker table

  - ProjTable table

  - PSAResourceAssignmentAnalysisTmp table
    

    > [!NOTE]
    > <P>To determine where the data in the temp table comes from, view the cross-references for the RFQSendDP.processReport class.</P>



  - PSASchedEmplReservation table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


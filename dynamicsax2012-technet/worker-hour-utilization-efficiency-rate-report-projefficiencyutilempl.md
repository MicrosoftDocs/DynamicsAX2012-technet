---
title: Worker hour utilization - efficiency rate report (ProjEfficiencyUtilEmpl)
TOCTitle: Worker hour utilization - efficiency rate report (ProjEfficiencyUtilEmpl)
ms:assetid: 76ea4f5d-41f0-4e39-bff8-30946aedd0f5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500170(v=AX.60)
ms:contentKeyID: 37820219
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjEfficiencyUtilEmpl
---

# Worker hour utilization - efficiency rate report (ProjEfficiencyUtilEmpl) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to review the efficiency rate of worker hours by project for a specified date range. You can view actual values or budgeted values by forecast model.

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
<td><p><strong>Worker period</strong></p></td>
<td><p>Select a worker period. Only workers associated with the selected period are displayed on the report.</p>
<div>

> [!NOTE]
> <P>Workers are associated with a period based on the pay and time reporting schedule that they follow.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for the hour transactions that you want to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><p>Select <strong>Actual</strong> to display actual values on the report.</p>
<p>Select <strong>Budget</strong> to display budgeted values on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Hide employee lines</strong></p></td>
<td><p>Select whether to hide employee lines on the report. Selecting this option makes it easier to analyze totals by department.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Skip zero</strong></p></td>
<td><p>Select whether to exclude rows where the amounts are equal to zero.</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>ProjUtilEmpl</strong> form, in the <strong>Criteria</strong> field, select a worker ID to include on the report. To add more than one worker, click <strong>Add</strong>.</p></td>
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
<td><p>ProjUtilEmpl</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjUtilEmpl</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjEfficiencyUtilEmpl</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Hour utilization</strong> &gt; <strong>Efficiency rate</strong> &gt; <strong>Worker hour utilization (efficiency rate)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjUtilEmplDP.ProcessReport

  - HcmWorker table

  - PROJHOURUTILIZATIONTMP table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjUtilEmplDP.ProcessReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


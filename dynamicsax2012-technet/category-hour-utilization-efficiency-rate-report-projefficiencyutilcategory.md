---
title: Category hour utilization - efficiency rate report (ProjEfficiencyUtilCategory)
TOCTitle: Category hour utilization - efficiency rate report (ProjEfficiencyUtilCategory)
ms:assetid: d8702199-87ca-4b55-a9ec-64062253bec1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500176(v=AX.60)
ms:contentKeyID: 37820234
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjEfficiencyUtilCategory
---

# Category hour utilization - efficiency rate report (ProjEfficiencyUtilCategory) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to review the efficiency rate for actual hours or budgeted hours by project category for a specified date range.

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
<td><p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for the hour transactions that you want to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><p>Select <strong>Actual</strong> to display actual values on the report.</p>
<p>Select <strong>Budget</strong> to display budgeted values on the report. If you select <strong>Budget</strong>, you can select a forecast model for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Forecast model</strong></p></td>
<td><p>Select the forecast model that you want the report to use. This field is available only if you selected <strong>Budget</strong> in the <strong>Actual vs. budget</strong> field.</p>
  
> [!NOTE]
> <P>If you are using project budget control, select the budget forecast model that is used by this project.</P>

</td>
</tr>
<tr class="even">
<td><p><strong>Skip zero</strong></p></td>
<td><p>Select whether to exclude rows where the amounts are equal to zero.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Select</strong> button</p></td>
<td><p>You can select a specific project category to display on the report. Click <strong>Select</strong>. In the <strong>ProjUtilCategory</strong> form, click <strong>Add</strong>. In the <strong>Criteria</strong> field, select a project category to include on the report.</p></td>
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
<td><p>ProjUtilCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjUtilCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjEfficiencyUtilCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Hour utilization</strong> &gt; <strong>Efficiency rate</strong> &gt; <strong>Category hour utilization (efficiency rate)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjUtilCategoryDP.processReport

  - ProjCategory table

  - PROJHOURUTILIZATIONTMP table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjUtilCategoryDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


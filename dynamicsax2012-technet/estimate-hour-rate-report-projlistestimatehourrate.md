---
title: Estimate hour rate report (ProjListEstimateHourRate)
TOCTitle: Estimate hour rate report (ProjListEstimateHourRate)
ms:assetid: 5c0272fd-cdbc-4b6c-9e31-2f52581b8206
ms:mtpsurl: https://technet.microsoft.com/library/Aa583957(v=AX.60)
ms:contentKeyID: 37832004
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListEstimateHourRate
---

# Estimate hour rate report (ProjListEstimateHourRate) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze hours for estimate projects as of a specified date.

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
<td><p>Select the period code of the estimate projects that you want to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong></p></td>
<td><p>Select a transaction date. Only hours for estimate projects as of the selected date are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Column</strong></p></td>
<td><p>Select whether to display only estimated hours, accumulated hours, or total hours on the report. This is a required value.</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimate project</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Estimate hour rate</strong> form, in the <strong>Criteria</strong> field, select an estimate project to display on the report. To add another estimate project, click <strong>Add</strong>.</p></td>
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
<td><p>ProjListEstimateHourRate</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListEstimateHourRate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListEstimateHourRate</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Estimates</strong> &gt; <strong>Fixed-price</strong> &gt; <strong>Estimate hour rate</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjControlPeriodTable

  - ProjControlPeriodTableColumn table

  - ProjTable

  - ProjWIPTable

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



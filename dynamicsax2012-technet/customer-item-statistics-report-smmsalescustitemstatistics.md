---
title: Customer/item statistics report (smmSalesCustItemStatistics)
TOCTitle: Customer/item statistics report (smmSalesCustItemStatistics)
ms:assetid: 7626dc27-408c-4161-acfa-b99703fac455
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh412247(v=AX.60)
ms:contentKeyID: 36916357
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.smmSalesCustItemStatistics
---

# Customer/item statistics report (smmSalesCustItemStatistics) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view sales based on customer or item.

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
<td><p><strong>Posting</strong></p></td>
<td><p>Select to view sales based on customer or item.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>Period 1</strong>)</p>
<p><strong>From date</strong>/<strong>To date</strong></p></td>
<td><p>Select the start and finish dates to view sales for the first period.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Period 2</strong>)</p>
<p><strong>From date</strong>/<strong>To date</strong></p></td>
<td><p>Select start and finish dates to view sales for the second period.</p></td>
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
<td><p>smmSalesCustItemStatistics</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\smmSalesCustItemStatistics</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>smmSalesCustItemStatistics</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Customer</strong> &gt; <strong>Customer/item statistics</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - smmSalesCustItemStatisticsDP.processReport

  - tmpSmmSalesCustItemStatistics

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


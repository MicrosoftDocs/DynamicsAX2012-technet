---
title: Fixed asset mid-quarter applicability report (AssetMidQuarter)
TOCTitle: Fixed asset mid-quarter applicability report (AssetMidQuarter)
ms:assetid: 64f52e76-101d-470c-9213-a676bdffc863
ms:mtpsurl: https://technet.microsoft.com/library/Aa585325(v=AX.60)
ms:contentKeyID: 37832007
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetMidQuarter
---

# Fixed asset mid-quarter applicability report (AssetMidQuarter) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view information about fixed asset acquisitions by quarter and by depreciation book.

This report displays the following information:

  - The total cost basis, which includes acquisition and acquisition adjustment amounts

  - The cost basis percentage of the total value of the property that was placed in service for the reporting year

The mid-quarter convention applies when more than 40 percent of the depreciable property that is placed in service during the year is placed in service during the last three months of the year.

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
<td><p><strong>Depreciation book</strong></p></td>
<td><p>Select the depreciation book to print the report for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Year ending</strong></p></td>
<td><p>Select the calendar year to print the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show disposed assets</strong></p></td>
<td><p>Select this check box to include fixed assets on the report, even if the fixed assets have been disposed of.</p></td>
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
<td><p>AssetMidQuarter</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\AssetMidQuarter</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetMidQuarter</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Movement</strong> &gt; <strong>Fixed asset mid-quarter applicability</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetMidQuarterTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the AssetMidQuarterDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



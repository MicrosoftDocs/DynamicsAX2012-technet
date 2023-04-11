---
title: (IND) Depreciation schedule (report)
TOCTitle: (IND) Depreciation schedule (report)
ms:assetid: 89ab836a-f464-4fbe-a273-fa4de1f6daae
ms:mtpsurl: https://technet.microsoft.com/library/Xx187159(v=AX.60)
ms:contentKeyID: 52055986
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Depreciation schedule (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays the depreciation schedule for fixed asset groups.

The generated report shows values under gross block, depreciation, and net block for tangible and intangible assets, including the following values.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Gross block value</p></th>
<th><p>Depreciation/amortization value</p></th>
<th><p>Net block value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Opening balance</p></td>
<td><p>Opening balance</p></td>
<td><p>Net block value for the current year</p></td>
</tr>
<tr class="even">
<td><p>Additions and adjustments made during the year</p></td>
<td><p>Deductions and adjustments made during the year</p></td>
<td><p>Net block value for the previous year</p></td>
</tr>
<tr class="odd">
<td><p>Deductions and adjustment made during the year</p></td>
<td><p>Year-end total</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Reversals or impairments made during the year</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Year-end total</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


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
<td><p><strong>Closing date prior year</strong></p></td>
<td><p>Select the closing date of the previous year.</p></td>
</tr>
<tr class="even">
<td><p><strong>Closing date this year</strong></p></td>
<td><p>Select the closing date of the current year.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From</strong></p></td>
<td><p>Select the starting value for fixed asset group inclusion on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong></p></td>
<td><p>Select the end point for fixed asset group inclusion on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Book type</strong></p></td>
<td><p>Select the book type of the fixed asset groups.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting layers</strong></p></td>
<td><p>Select the posting layer of the value model.</p>
<p>This field is available only if you selected <strong>Value model</strong> in the <strong>Book type</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Depreciation book</strong></p></td>
<td><p>Select the depreciation book.</p>
<p>This field is available only if you selected <strong>Depreciation book</strong> in the <strong>Book type</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Schedule number</strong></p></td>
<td><p>Enter the depreciation schedule number.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Header note</strong></p></td>
<td><p>Enter any text that you want to appear in the header of the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Footer note</strong></p></td>
<td><p>Enter any text that you want to appear in the footer of the report.</p></td>
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
<td><p>AssetDepreciationSchedule_IN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\AssetDepreciationSchedule_IN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetDepreciationSchedule_IN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Periodic</strong> &gt; <strong>Depreciation schedule</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpAssetTable\_IN

  - TmpDepreciationSchedule\_IN

  - TmpItemGroup\_IN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



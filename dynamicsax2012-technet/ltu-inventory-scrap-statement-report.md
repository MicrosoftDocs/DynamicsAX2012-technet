---
title: (LTU) Inventory scrap statement (report)
TOCTitle: (LTU) Inventory scrap statement (report)
ms:assetid: 771ce255-9f87-4371-ae20-4248f90c9ba2
ms:mtpsurl: https://technet.microsoft.com/library/JJ874409(v=AX.60)
ms:contentKeyID: 50619725
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LTU) Inventory scrap statement (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report that displays a list of all inventory that has been scrapped within a specified period.

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
<td><p><strong>From date</strong></p></td>
<td><p>Select the start date to begin including transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the date on which to stop including transactions on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show zero lines</strong></p></td>
<td><p>Select this check box to include item lines on the report, even if the total number of transactions in the selected period is 0 (zero).</p></td>
</tr>
<tr class="even">
<td><p><strong>Financial dimensions</strong></p></td>
<td><p>Select this check box to include financial dimension information for the transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View</strong></p></td>
<td><p>Select the check boxes in the <strong>View</strong> field group to include selections on the report. For example, you might select to include the site, warehouse, and location information for each transaction line.</p></td>
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
<td><p>InventScrapStatement</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventScrapStatement</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventScrapStatement</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Inventory scrap statement</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InventScrapStatementTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



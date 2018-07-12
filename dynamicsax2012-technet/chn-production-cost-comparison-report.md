---
title: (CHN) Production cost comparison (report)
TOCTitle: (CHN) Production cost comparison (report)
ms:assetid: 1c600a37-85da-45b9-acc6-3f38385bc2df
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn169450(v=AX.60)
ms:contentKeyID: 53865941
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Production cost comparison (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Generate and print a report that displays a comparison of product costs during two specified periods, so that you can analyze trends or changes in cost.

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
<td><p><strong>Dimension type</strong></p></td>
<td><p>Select the dimension type to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Dimension</strong></p></td>
<td><p>Select the dimension to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Product range</strong></p></td>
<td><p>Select the product to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date:</strong></p></td>
<td><p>Select the start date of the first period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date:</strong></p></td>
<td><p>Select the end date of the first period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Compared from date</strong></p></td>
<td><p>Select the start date of the comparison period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Compared to date</strong></p></td>
<td><p>Select the end date of the comparison period.</p></td>
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
<td><p>ProdCostComparison_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProdCostComparison_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProdCostComparison_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Production control</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Production cost comparison report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProdCostComparisonTmp\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



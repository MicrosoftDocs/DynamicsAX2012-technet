---
title: (CHN) Account analysis by dimensions (report)
TOCTitle: (CHN) Account analysis by dimensions (report)
ms:assetid: 75c7b241-2600-4742-9ddd-505101604204
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ873745(v=AX.60)
ms:contentKeyID: 50593462
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Account analysis by dimensions (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report that displays the dimension values for the account balances of selected accounts during a specified period.

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
<td><p><strong>Account</strong></p></td>
<td><p>Select the account for which to include the dimensions and transaction types on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From dimension</strong></p></td>
<td><p>Select the starting range for the dimensions to include on the report. The dimensions available are based on the selected dimension type.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date:</strong></p></td>
<td><p>Select the start date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transactions</strong></p></td>
<td><p>Select the transactions types to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension type</strong></p></td>
<td><p>Select the dimension type to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To dimension</strong></p></td>
<td><p>Select the end of the range of dimensions to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date:</strong></p></td>
<td><p>Select the end date.</p></td>
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
<td><p>LedgerAccountAnalysisByDimension</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerAccountAnalysisByDimension</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerAccountAnalysisByDimension</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Account analysis by dimensions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerAccountAnalysisByDimensionTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



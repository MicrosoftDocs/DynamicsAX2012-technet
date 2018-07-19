---
title: (EEUR) Access log (report)
TOCTitle: (EEUR) Access log (report)
ms:assetid: ad81c6b9-c985-4ede-bb02-a7e0fd7239b0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ874414(v=AX.60)
ms:contentKeyID: 50619730
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Access log (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays the fields and tables in Microsoft Dynamics AX that are related to an employee’s personal information, and that have been accessed within a specified time frame.

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
<td><p><strong>Person</strong></p></td>
<td><p>Select the employee about whom the report is generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the start date for which to include information on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the last date for which to include information on the report.</p></td>
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
<td><p>EeAccessLog</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\EeAccessLog</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EeAccessLog</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Personal data</strong> &gt; <strong>Access log</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - EeAccessLogTmp

  - AccessedByUser

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



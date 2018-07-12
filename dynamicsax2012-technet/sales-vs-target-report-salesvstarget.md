---
title: Sales vs. target report (SalesVsTarget)
TOCTitle: Sales vs. target report (SalesVsTarget)
ms:assetid: 451fe29c-9dfe-403b-b886-ac7c2e139b21
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh412244(v=AX.60)
ms:contentKeyID: 36916353
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SalesVsTarget
---

# Sales vs. target report (SalesVsTarget) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the total number of sales versus the total number of sales targets, based on either the salesperson or the sales unit.

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
<td><p><strong>Group by</strong></p></td>
<td><p>Select whether to view the report by employee or sales unit.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the date from which you want to start viewing the sales versus sales targets.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the date on which you want to stop viewing the sales versus sales targets.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales person</strong></p></td>
<td><p>Select one or more salespeople whose sales are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales unit</strong></p></td>
<td><p>Select one or more sales units to include on the report.</p></td>
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
<td><p>SalesVsTarget</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SalesVsTarget</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>smmSalesVsTarget</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Sales management</strong> &gt; <strong>Sales vs. target</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



---
title: Sales tax deviations report (TaxDeviation)
TOCTitle: Sales tax deviations report (TaxDeviation)
ms:assetid: 6eb6028f-3c71-459d-b652-a43d415b0e0a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa586002(v=AX.60)
ms:contentKeyID: 37820217
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxDeviation
---

# Sales tax deviations report (TaxDeviation) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Prepare a report that specifies the actual sales tax due, compared to the sales tax that was calculated and posted.

The report shows transactions for a specified interval and displays the following columns:

  - **Date**

  - **Voucher**

  - **Sales tax code**

  - **Origin**

  - **Sales tax amount**

  - **Sales tax percentage**

  - **Calculated sales tax percentage**

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
<td><p><strong>Deviations only</strong></p></td>
<td><p>Select this check box to display only transactions that have a deviation between the sales tax percentages.</p></td>
</tr>
<tr class="even">
<td><p><strong>Deviation value</strong></p></td>
<td><p>Enter a deviation value. Transactions that have a deviation that is equal to this value will be displayed on the report.</p>
<p>This field is available only if you select the <strong>Deviations only</strong> check box.</p></td>
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
<td><p>TaxDeviation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRSReports\Reports\TaxDeviation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxDeviation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Sales tax deviations</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxTrans table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


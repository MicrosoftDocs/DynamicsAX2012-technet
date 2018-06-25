---
title: Spend optimization report (VendSpendOptimization)
TOCTitle: Spend optimization report (VendSpendOptimization)
ms:assetid: 20b72973-88be-49f6-b933-43f98282d933
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500167(v=AX.60)
ms:contentKeyID: 37820207
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendSpendOptimization
---

# Spend optimization report (VendSpendOptimization) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view a percentage of the amount spent in each procurement category. The amount spent is broken down by procurement category, number of vendors in the category, and the amount spent by the vendors in the category. The report also displays this information based on the vendor’s status: approved, preferred, or unknown.


> [!TIP]
> <P>To view a breakdown of spend by vendor in a category, click the number in the <STRONG>Number of vendors accounting for specified threshold</STRONG> column for the category.</P>



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
<td><p><strong>Legal entity</strong></p></td>
<td><p>Select one or all legal entities. Only the vendors for the selected legal entities are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Currency</strong></p></td>
<td><p>Select a currency code. Only the vendors who invoice your organization in the selected currency are displayed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Start date</strong></p></td>
<td><p>Enter the earliest date for transactions that you want to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Procurement categories</strong></p></td>
<td><p>Select a procurement category. Only vendors who are authorized to do business in the selected category are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Threshold</strong></p></td>
<td><p>Enter a threshold number. The threshold is the percentage of all spend in a given category and the vendors associated with that percentage of spend. The default value is 80%.</p>
<p>For example, you might want to see all vendors who represent 60% of the amount spent in all categories. In this case, you set the threshold to 60. The report output shows the number of vendors who represent 60 percent spent in each procurement category, and their percentage contribution to the amount spent.</p></td>
</tr>
<tr class="even">
<td><p><strong>End date</strong></p></td>
<td><p>Enter the most recent date for transactions that you want to include on the report.</p></td>
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
<td><p>VendSpendOptimization</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendSpendOptimization</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendSpendOptimization</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Spend analysis</strong> &gt; <strong>Spend optimization</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - EcoResProcurementCategoryExpanded table

  - VendInvoiceTransExpanded table

  - BICOMPANYVIEW table

  - VENDTABLECUBE

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Spend by procurement category over consecutive years report (VendSpendCategoryYears)
TOCTitle: Spend by procurement category over consecutive years report (VendSpendCategoryYears)
ms:assetid: f91fe740-0cc9-40bd-acd0-995c188099e0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500178(v=AX.60)
ms:contentKeyID: 37820239
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendSpendCategoryYears
---

# Spend by procurement category over consecutive years report (VendSpendCategoryYears) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view a comparison of calendar year purchases from vendors by procurement category. Select the year you want to view, and the report output displays the annual purchases for the selected year compared to the annual purchases for the preceding year.

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
<td><p><strong>Procurement category</strong></p></td>
<td><p>Select a procurement category. Only vendors who are authorized to do business in the selected category are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Year</strong></p></td>
<td><p>Select the calendar year that you want to review annual purchases for.</p></td>
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
<td><p>VendSpendCategoryYears</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendSpendCategoryYears</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendSpendCategoryYears</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Spend analysis</strong> &gt; <strong>Spend by procurement category over consecutive years</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendInvoiceTransExpanded table

  - BICOMPANYVIEW table

  - EcoResProcurementCategoryExpanded table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


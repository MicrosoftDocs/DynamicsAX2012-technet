---
title: Project contracts report (ProjListInvoiceTable)
TOCTitle: Project contracts report (ProjListInvoiceTable)
ms:assetid: 6bee8b68-033f-4703-b3a3-40a0e313eee6
ms:mtpsurl: https://technet.microsoft.com/library/Aa615032(v=AX.60)
ms:contentKeyID: 37820215
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListInvoiceTable
---

# Project contracts report (ProjListInvoiceTable) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view project contract details. You can filter the report to display only project contracts for a specified currency.

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
<td><p><strong>Project contract ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Project contracts</strong> form, in the <strong>Criteria</strong> field, select a project contract ID to include on the report. To add more than one project contract ID, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales currency</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Project contracts</strong> form, select a sales currency to include on the report. To add more than one <strong>Sales currency</strong>, click <strong>Add</strong>.</p></td>
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
<td><p>ProjListInvoiceTable</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListInvoiceTable</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListInvoiceTable</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Project contracts</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LogisticsPostalAddressView table

  - ProjFundingSource table

  - ProjGrant table

  - ProjInvoiceTable

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



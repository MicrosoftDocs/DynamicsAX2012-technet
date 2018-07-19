---
title: Project invoice journals report (ProjInvoiceJournal)
TOCTitle: Project invoice journals report (ProjInvoiceJournal)
ms:assetid: fa44bed7-0484-42e4-8836-3e4e2fbb74e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa600591(v=AX.60)
ms:contentKeyID: 37820240
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjInvoiceJournal
---

# Project invoice journals report (ProjInvoiceJournal) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view customer invoices for projects.

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
<td><p><strong>Invoice</strong></p></td>
<td><p>Select whether to include invoices for specific transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>On-account</strong></p></td>
<td><p>Select whether to include on-account invoices on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Select a starting and an ending date for invoices to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sorting</strong></p></td>
<td><p>Select the sorting sequence of rows on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Layout invoice totals columns</strong></p></td>
<td><p>Select the invoice columns to display on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Layout general ledger columns</strong></p></td>
<td><p>Select the general ledger columns to display on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales currency</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Invoice journal</strong> form, in the <strong>Criteria</strong> field, select a sales currency. Only the customer invoices that reference the selected sales currency are displayed on the report. To select more than one sales currency, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice account</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Invoice journal</strong> form, in the <strong>Criteria</strong> field, select an invoice account. To select more than one invoice account, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project contract ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Invoice journal</strong> form, in the <strong>Criteria</strong> field, select a project contract ID. To select more than one project contract ID, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Invoice journal</strong> form, in the <strong>Criteria</strong> field, select an invoice. To select more than one invoice, click <strong>Add</strong>.</p></td>
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
<td><p>ProjInvoiceJournal</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjInvoiceJournal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjInvoiceJournal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Project invoices</strong> &gt; <strong>Project invoice journals</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjInvoiceJour table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



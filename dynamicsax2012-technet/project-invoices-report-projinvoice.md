---
title: Project invoices report (ProjInvoice)
TOCTitle: Project invoices report (ProjInvoice)
ms:assetid: 7706550a-9e2b-4778-a646-fd22e389ff9b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527784(v=AX.60)
ms:contentKeyID: 37832009
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjInvoice
---

# Project invoices report (ProjInvoice) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view customer invoices for projects for a specified date range.

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
<td><p>Select whether to include customer invoices for actual project transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>On-account</strong></p></td>
<td><p>Select whether to include on-account invoices on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice date</strong></p></td>
<td><p>Select a starting date and an ending date for invoices to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice account</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>ProjPrintInvoice</strong> form, in the <strong>Criteria</strong> field, select an invoice account to include on the report. To add more than one invoice account, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project contract ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>ProjPrintInvoice</strong> form, in the <strong>Criteria</strong> field, select a project contract to include on the report. To add more than one project contract, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales currency</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>ProjPrintInvoice</strong> form, in the <strong>Criteria</strong> field, select a sales currency to include on the report. To add more than one sales currency, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>ProjPrintInvoice</strong> form, in the <strong>Criteria</strong> field, select an invoice to include on the report. To add more than one invoice, click <strong>Add</strong>.</p></td>
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
<td><p>ProjInvoice</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjInvoice</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjPrintInvoice</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Project invoices</strong> &gt; <strong>Project invoice proposals</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjInvoiceDP.processReport

  - PROJINVOICETMP table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjInvoiceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


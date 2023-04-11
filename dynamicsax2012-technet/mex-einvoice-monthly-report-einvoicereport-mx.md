---
title: (MEX) Einvoice monthly report (EInvoiceReport_MX)
TOCTitle: (MEX) Einvoice monthly report (EInvoiceReport_MX)
ms:assetid: d715a1fe-9dc5-4e7b-8881-ec9d3cc404f5
ms:mtpsurl: https://technet.microsoft.com/library/Hh371730(v=AX.60)
ms:contentKeyID: 36814944
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (MEX)
- SSRS_Reports.Reports.EInvoiceReport_MX
- Electronic invoices
- monthly report
---

# (MEX) Einvoice monthly report (EInvoiceReport\_MX) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **EInvoice monthly report** displays all the electronic and paper invoices that have been issued for the month. You can use the Sistema de comprobantes fiscales digitales CFD Plus (SICOFI) application website to submit the monthly report to the Servicio de Administración Tributaria (SAT) in .txt format. The report is due on or before the fifth day of the following month. This report is typically used by collections agents, collections managers, chief financial officers, accounts receivable clerks, accounts receivable managers, accountants, accounting managers, accounting supervisors, financial controllers, and accounts receivable centralized payments clerks.

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
<td><p><strong>Month/Year</strong></p></td>
<td><p>Select the month and year that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>EInvoice</strong></p></td>
<td><p>Select this check box to include only the electronic invoices issued for the month in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>File path</strong></p></td>
<td><p>Specify a file name and file path to store the monthly report.</p></td>
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
<td><p>EInvoiceReport_MX</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ EInvoiceReport_MX</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EinvoiceMonthlyReport_MX</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Periodic</strong> &gt; <strong>CFD - Electronic invoices</strong> &gt; <strong>EInvoice monthly report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - EInvoiceReportTmp\_MX


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the EInvoiceReportDP_MX.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



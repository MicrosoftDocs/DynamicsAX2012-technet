---
title: (POL) EU summary VAT register (report)
TOCTitle: (POL) EU summary VAT register (report)
ms:assetid: 29b73b13-21c1-4173-8cf2-d24b1f253e07
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863716(v=AX.60)
ms:contentKeyID: 50396399
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) EU summary VAT register (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays information about value-added tax (VAT) registers for European Union trade.

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
<td><p><strong>From date</strong></p></td>
<td><p>Select the start date of the VAT reporting period to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>VAT code</strong></p></td>
<td><p>Select the starting point of the VAT report code range to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the end date of the VAT reporting period to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>VAT code</strong></p></td>
<td><p>Select the end point of the VAT report code range to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print summary only</strong></p></td>
<td><p>Select this check box to generate a summary report. Only the information about the origin, sales tax, and gross amounts for selected tax codes is displayed on the report.</p>
<p>If you do not select this check box, the report displays detailed information about each tax transaction. The information includes voucher and invoice numbers, customer and vendor names, and VAT register dates.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show service description</strong></p></td>
<td><p>Select whether to display the service tariff number description on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Discrepancy report</strong></p></td>
<td><p>Select this check box to show the VAT transactions from the VAT register for periods earlier than the current VAT reporting period.</p></td>
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
<td><p>TaxVATSummaryReport_MX</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxVATSummaryReport_MX</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxVatRegisterWNT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Periodic</strong> &gt; <strong>VAT registers</strong> &gt; <strong>EU summary VAT register</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxVATSummaryReportTmp\_MX

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



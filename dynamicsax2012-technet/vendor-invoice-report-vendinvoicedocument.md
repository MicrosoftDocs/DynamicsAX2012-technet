---
title: Vendor invoice report (VendInvoiceDocument)
TOCTitle: Vendor invoice report (VendInvoiceDocument)
ms:assetid: bea45cdf-020a-4574-9bd3-6f1fd4719e14
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209551(v=AX.60)
ms:contentKeyID: 36060338
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.VendEditInvoicePostDropDialog
- SSRS_Reports.Reports.VendInvoiceDocument
- Forms.VendEditInvoicePrintDropDialog
- MsDynAx060.Forms.VendEditInvoicePostDropDialog
- MsDynAx060.Forms.VendEditInvoicePrintDropDialog
---

# Vendor invoice report (VendInvoiceDocument) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Vendor invoice** report displays account, pricing, and discount information for vendor invoices.

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
<td><p><strong>Print invoice</strong></p></td>
<td><p>If this check box is selected, an invoice will be printed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print sequence</strong></p></td>
<td><p>Select the print sequence for the invoice.</p>
<ul>
<li><p><strong>Current</strong> – Print invoices before processing, such as automatic consolidation, occurs. Each individual invoice is printed.</p></li>
<li><p><strong>After</strong> – Print invoices after processing, such as automatic consolidation, occurs. The consolidated invoice is printed.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Print sales documents</strong></p></td>
<td><p>If this check box is selected, any applicable intercompany sales documents are printed. For example, the corresponding customer invoice is printed at the same time as the vendor invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>Use print management destination</strong></p></td>
<td><p>If this check box is selected, the report will be printed by using the settings defined in print management.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print Intra-Community invoice</strong></p></td>
<td><p>If this check box is selected, an Intra-Community invoice is printed.</p></td>
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
<td><p>VendInvoiceDocument</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendInvoiceDocument</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendInvoiceDocument</p>
<p>VendInvoiceDocumentCopy</p>
<p>VendInvoiceDocumentOriginal</p>
<p>VendEditInvoicePostDropDialog</p>
<p>VendEditInvoicePrintDropDialog</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Common</strong> &gt; <strong>Vendor invoices</strong> &gt; <strong>Pending vendor invoices</strong>. On the <strong>Action Pane</strong>, on the <strong>Process</strong> tab, click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendInvoiceDocumentTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the VendInvoiceDocumentDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Set up print management for a transaction](set-up-print-management-for-a-transaction.md)

[Print management setup (form)](https://technet.microsoft.com/en-us/library/hh209383\(v=ax.60\))

  



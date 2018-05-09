---
title: Vendor invoice transactions report (VendInvoice)
TOCTitle: Vendor invoice transactions report (VendInvoice)
ms:assetid: 786ba203-86e6-4498-bad6-65101ee8c906
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa615393(v=AX.60)
ms:contentKeyID: 36059355
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendInvoice
---

# Vendor invoice transactions report (VendInvoice) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Vendor invoice transactions** report displays Accounts payable vendor invoice transactions, sorted by the general ledger account that was charged on each line of the invoice.

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
<td><p><strong>Dimension set</strong></p></td>
<td><p>Select a financial dimension set for the report. These were defined in the <strong>Financial dimension sets</strong> form. A dimension set is a named group of accounts or dimensions that contains either account values for the account or dimension values for a single dimension. Examples include main accounts, departments, and cost centers, or combinations such as the cost center and main account, or the department and cost center.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa597282(v=ax.60)">Financial dimension sets (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the start of the date range for the posted vendor invoice transactions to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the end of the date range for the posted vendor invoice transactions to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice type</strong></p></td>
<td><p>Select the type of invoice transactions to include on the report. You can select invoices that are open, paid, or both open and paid.</p></td>
</tr>
<tr class="odd">
<td><p><strong>With transaction text</strong></p></td>
<td><p>Select this check box to display a <strong>Description</strong> column on the report that identifies the document type and document ID.</p>
<p>Clear this check box to omit the <strong>Description</strong> column and instead include columns for the method of payment and cash discount date.</p>
<div class="alert">

> [!NOTE]
> <P>The <STRONG>Method of payment</STRONG> and <STRONG>Cash discount date</STRONG> fields are displayed on the <STRONG>Payment</STRONG> tab of the <STRONG>Vendor transactions</STRONG> form. Payment methods are set up in the <STRONG>Methods of payment - vendors</STRONG> form.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Vendor accounts</strong></p></td>
<td><p>The selected vendor account or accounts whose transactions will be included on the report. Click <strong>Select</strong> to select vendor accounts.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Approved</strong></p></td>
<td><p>Click <strong>Select</strong> and select <strong>Yes</strong> for the <strong>Approved</strong> field to include only approved vendor invoice transactions. For information about how invoices are approved, see <a href="https://technet.microsoft.com/en-us/library/aa599011(v=ax.60)">Journal voucher - Vendor payment journal (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoices</strong></p></td>
<td><p>The selected vendor invoice or invoices that will be included on the report. Click <strong>Select</strong> to select vendor invoices.</p></td>
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
<td><p>VendInvoice</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendInvoice</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendInvoice</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Invoice</strong> &gt; <strong>Vendor invoice transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - GeneralJournalAccountEntry table

  - GeneralJournalEntry table

  - LedgerEntry table

  - SubledgerVoucherGeneralJournalEntry table

  - VendInvoiceJour table

  - VendTable table

  - VendTrans table

  - VendInvoiceTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the VendInvoiceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


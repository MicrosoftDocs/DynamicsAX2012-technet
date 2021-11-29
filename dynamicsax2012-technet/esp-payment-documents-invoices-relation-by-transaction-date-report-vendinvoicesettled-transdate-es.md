---
title: (ESP) Payment documents-invoices relation by transaction date report (VendInvoiceSettled_TransDate_ES)
TOCTitle: (ESP) Payment documents-invoices relation by transaction date report (VendInvoiceSettled_TransDate_ES)
ms:assetid: 40969048-3e1e-4da0-bd47-51cfe2a9c90f
ms:mtpsurl: https://technet.microsoft.com/library/Hh352247(v=AX.60)
ms:contentKeyID: 36687873
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payment
- invoice
- SSRS_Reports.Reports.VendInvoiceSettled_TransDate_ES
- promisory notes
- transaction date
---

# (ESP) Payment documents-invoices relation by transaction date report (VendInvoiceSettled\_TransDate\_ES) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment documents-invoices relation by transaction date** report displays the relationship between promissory notes and invoices, grouped by transaction date. This report is used to inquire into the status of promissory notes. This report is typically used by chief financial officers, accountants, accounting managers, accounting supervisors, financial controllers, accounts payable clerks, and accounts payable managers.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



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
<td><p><strong>From vendor</strong></p></td>
<td><p>Select or enter the starting vendor account number for the vendor account range to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To vendor</strong></p></td>
<td><p>Select or enter the ending vendor account number for the vendor account range to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>Select or enter the starting date of the date range in which the transactions are posted or are due.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select or enter the ending date of the date range in which the transactions are posted or are due.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Enable status</strong></p></td>
<td><p>Select this check box to include the status of the promissory note in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>Select the status of the promissory note to be included in the report from the following options:</p>
<ul>
<li><p><strong>None</strong> – No promissory note has been drawn.</p></li>
<li><p><strong>Drawn</strong> –The promissory note is posted in a draw promissory note journal.</p></li>
<li><p><strong>Redrawn</strong> – The promissory note was previously protested and is redrawn in a redraw promissory note journal.</p></li>
<li><p><strong>Protested</strong> – The promissory note was not honored by the bank and is protested in a protest promissory note journal.</p></li>
<li><p><strong>Honored</strong> – The promissory note is settled.</p></li>
<li><p><strong>Remitted</strong> – The promissory note was posted in a remittance journal.</p></li>
<li><p><strong>Invoiced</strong> – The promissory note for an invoice that uses the promissory note method of payment has been posted.</p></li>
<li><p><strong>Invoice remitted</strong> – The promissory note for an invoice that uses the promissory note method of payment has been drawn and posted.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Select the vendor method of payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Note ID</strong></p></td>
<td><p>Select the identification for promissory notes.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice</strong></p></td>
<td><p>Enter the invoice number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Amount</strong></p></td>
<td><p>Enter the transaction amount.</p></td>
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
<td><p>VendInvoiceSettled_TransDate_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendInvoiceSettled_TransDate_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendInvoiceSettledTransDate_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Payment documents-invoices relation by transaction date</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendInvoiceSettled\_TransDateTmp\_ES table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendInvoiceSettled_TransDateDP_ES.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



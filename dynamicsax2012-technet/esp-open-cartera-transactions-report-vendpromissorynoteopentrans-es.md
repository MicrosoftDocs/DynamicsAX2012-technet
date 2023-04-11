---
title: (ESP) Open cartera transactions report (VendPromissoryNoteOpenTrans_ES)
TOCTitle: (ESP) Open cartera transactions report (VendPromissoryNoteOpenTrans_ES)
ms:assetid: 61700b8f-9477-485b-90ea-39901dde3dc7
ms:mtpsurl: https://technet.microsoft.com/library/Hh433496(v=AX.60)
ms:contentKeyID: 36941263
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendPromissoryNoteOpenTrans_ES
- Accounts payable
- VendPromissoryNoteOpenTrans_ES
- (ESP)
- Open cartera transactions
---

# (ESP) Open cartera transactions report (VendPromissoryNoteOpenTrans\_ES) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Open cartera transactions** report prints a list of open promissory note transactions that can be grouped by vendor, due date, or promissory note. This report is typically used by chief financial officers, financial controllers, accountants, accounting managers, and accounting supervisors to inquire into the status of promissory notes.


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
<td><p><strong>Note ID</strong></p></td>
<td><p>Select the identification number of the promissory note.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>Select the status of the promissory note from one of the following options:</p>
<ul>
<li><p><strong>None</strong> – Include promissory notes without a status.</p></li>
<li><p><strong>Drawn</strong> - Include promissory notes that are automatically drawn or invoices using the promissory note method of payment that are posted in a draw promissory note journal.</p></li>
<li><p><strong>Redrawn</strong> - Include promissory notes that have not been honored by the bank and are redrawn in a redraw promissory note journal.</p></li>
<li><p><strong>Protested</strong> - Include promissory notes that are protested.</p></li>
<li><p><strong>Honored</strong> - Include promissory notes that are settled.</p></li>
<li><p><strong>Remitted</strong> - Include promissory notes that are posted in a remittance journal.</p></li>
<li><p><strong>Invoiced</strong> - Include promissory notes that are invoiced.</p></li>
<li><p><strong>Invoice remitted</strong> - Include promissory notes that have remitted invoices.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>Enter the voucher number for the promissory note.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong> (<strong>Transaction date</strong>)</p></td>
<td><p>Enter the starting date of the transaction period for which the report is to be generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong> (<strong>Transaction date</strong>)</p></td>
<td><p>Enter the ending date of the transaction period for which the report is to be generated.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong> (<strong>Due date</strong>)</p></td>
<td><p>Select the starting due date for the due date range to include in the report. The transactions that have due dates in the specified range will be included in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong> (<strong>Due date</strong>)</p></td>
<td><p>Select the ending due date for the due date range to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting profile</strong></p></td>
<td><p>Enter the posting profile for the promissory note. The posting profile determines how vendor transactions are posted to the general ledger.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Grouping by</strong></p></td>
<td><p>Select the criteria for grouping the posting profiles. The profiles can be grouped by <strong>Vendor</strong>, <strong>Promissory note</strong>, or <strong>Due date</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor account</strong></p></td>
<td><p>The account details of the vendor for the promissory note transactions.</p></td>
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
<td><p>VendPromissoryNoteOpenTrans_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendPromissoryNoteOpenTrans_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendPromissoryNoteReports_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Open cartera transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendPromissoryNoteOpenTransTmp\_ES table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendPromissoryNoteOpenTransDP_ES.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



---
title: Posted advanced ledger entry transactions report (Public sector) (SourceDocumentPostedTrans)
TOCTitle: Posted advanced ledger entry transactions report (Public sector) (SourceDocumentPostedTrans)
ms:assetid: 2eff9b60-66fe-4d6c-8802-a028d6b8c2af
ms:mtpsurl: https://technet.microsoft.com/library/Dn535767(v=AX.60)
ms:contentKeyID: 60103052
author: Khairunj
ms.date: 11/17/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SourceDocumentPostedTrans
---

# Posted advanced ledger entry transactions report (Public sector) (SourceDocumentPostedTrans) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use this report to print a list of posted advanced ledger entry transactions by voucher.

This form is available only if the **Public Sector** configuration key is selected.

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
<td><p><strong>Date interval</strong></p></td>
<td><p>Select the date interval to select transactions from.</p>
<p>When you select a date interval, the beginning and ending dates of the interval are entered in the <strong>From date</strong> and <strong>To date</strong> fields.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p>
<p><strong>To date</strong></p></td>
<td><p>Enter the first and last date of the date range to select transactions from.</p>
<p>If you enter dates in these fields, the value in the <strong>Date interval</strong> field is removed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From account</strong></p>
<p><strong>To account</strong></p></td>
<td><p>Select the first and last account in the range of accounts to select transactions from.</p>
<div class="alert">

> [!TIP]
> <P>If you specify a range of accounts, a transaction must be included in both the range of dates and the range of accounts to be included on the report.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Source document type</strong></p></td>
<td><p>This report is limited to advanced ledger entry transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Document number</strong></p></td>
<td><p>Select the ID of the document to select transactions from.</p>
<p>You can click <strong>Select</strong> and use the advanced query form to specify a range of document numbers instead of a single document number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project</strong></p></td>
<td><p>Select the project to select transactions from.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Ledger account types only</strong></p></td>
<td><p>Select this check box to print the transactions that have an account type of <strong>Ledger journal</strong> in the <strong>Journal voucher</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Ledger account</strong></p></td>
<td><p>Select this check box to print the ledger accounts on the report. The ledger account is the combination of the main account and any financial dimension values. If this check box is not selected, only the main account is displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Financial dimensions</strong></p></td>
<td><p>Select this check box to print the details of the financial dimensions on the report. These details include the account distributions.</p></td>
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
<td><p>SourceDocumentPostedTrans</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SourceDocumentPostedTrans</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AdvancedLedgerEntryPostedTrans</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Journals</strong> &gt; <strong>Posted advanced ledger entry transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SourceDocumentPostedTransactionsTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the SourceDocumentPostedTransactionsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



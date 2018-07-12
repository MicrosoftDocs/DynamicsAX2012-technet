---
title: (BEL) Posting journal list - totaled report (LedgerPostingJournalTotal)
TOCTitle: (BEL) Posting journal list - totaled report (LedgerPostingJournalTotal)
ms:assetid: 9e123d07-8c15-4578-8e6e-e92a01da3cc0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527155(v=AX.60)
ms:contentKeyID: 37823206
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerPostingJournalTotal
- (BEL)
- LedgerPostingJournalTotal
- Posting journal list
- Posting journal list - totaled report
---

# (BEL) Posting journal list - totaled report (LedgerPostingJournalTotal) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Posting journal list - totaled** report is an internal control report that is used to display and print a list of the total debit amounts and credit amounts per month for each journal. This report is typically used by accounting managers, accounting supervisors, and financial controllers to inquire into the status of the general ledger.


> [!NOTE]
> <P>(BEL) This report is available only to legal entities whose primary address is in Belgium.</P>



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
<td><p><strong>Detail</strong></p></td>
<td><p>Select this check box to sort the totals by general ledger account number by using the number of digits specified in the <strong>Number of account digits</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Number of account digits</strong></p></td>
<td><p>Enter the prefix length of the account numbers to group the transactions. For example, if you enter 3, the transactions are grouped by the first three digits of the account number that is used for posting.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The date of the journal transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal</strong></p></td>
<td><p>The journal name that is used to post transactions to journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Ledger account</strong></p></td>
<td><p>The account number, including financial dimensions, that is used to post transactions to the general ledger.</p></td>
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
<td><p>LedgerPostingJournalTotal</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerPostingJournalTotal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerPostingJournalTotal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Journals</strong> &gt; <strong>Posting journal list - totaled</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerPostingJournalTotalTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerPostingJournalTotalDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



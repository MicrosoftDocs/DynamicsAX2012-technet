---
title: Sales tax specification by ledger transaction report (TaxSpecPerLedgerTrans)
TOCTitle: Sales tax specification by ledger transaction report (TaxSpecPerLedgerTrans)
ms:assetid: 7581786b-1afa-41a9-953b-84195c314fc7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa596988(v=AX.60)
ms:contentKeyID: 43894480
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxSpecPerLedgerTrans
---

# Sales tax specification by ledger transaction report (TaxSpecPerLedgerTrans) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to show and print information about ledger transactions for which sales tax is calculated.

For each main account, the ledger transactions with calculated sales tax amounts are listed chronologically.

For each transaction, the voucher number, transaction text, transaction amount (debit or credit), sales tax code, and sales tax amount, including sales tax direction, are listed.

Transaction amounts and sales tax amounts are summed for each main account.

Starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2, this report includes options that let you sort the report by sales tax code or ledger account, include subtotals by sales tax code, and print only totals or both totals and details.

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
<td><p><strong>Main accounts only</strong></p></td>
<td><p>Select this check box to print only main accounts on the report.</p></td>
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
<td><p>TaxSpecPerLedgerTrans</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\TaxSpecPerLedgerTrans</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxSpecPerLedgerTrans</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Groupings</strong> &gt; <strong>Sales tax specification by ledger transaction</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxSpecPerLedgerTransTmp table


> [!NOTE]
> <P>To learn where the data in the temp tables comes from, view the cross-references for the TaxSpecPerLedgerTransDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



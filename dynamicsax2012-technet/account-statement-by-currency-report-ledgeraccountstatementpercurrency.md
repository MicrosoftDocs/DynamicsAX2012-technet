---
title: Account statement by currency report (LedgerAccountStatementPerCurrency)
TOCTitle: Account statement by currency report (LedgerAccountStatementPerCurrency)
ms:assetid: 360cde09-5d57-4c8c-ba57-715167b01dc2
ms:mtpsurl: https://technet.microsoft.com/library/Aa553274(v=AX.60)
ms:contentKeyID: 36687351
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerAccountStatementPerCurrency
---

# Account statement by currency report (LedgerAccountStatementPerCurrency) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays the account statement by currency for one or more main accounts. The report information includes the voucher date and number, main account, transaction description, and amount and currency information.


> [!NOTE]
> <P>An account that is followed by an asterisk (*) means that the voucher contains more than two main accounts.</P>



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
<td><p>Select the date for the opening balance. The starting and ending dates must be in the same fiscal year.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the date for the ending balance. The starting and ending dates must be in the same fiscal year.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include opening transaction amounts in detail</strong></p></td>
<td><p>Select this check box to exclude opening transactions from the line on the report that lists the opening balance. Opening transactions are displayed in the report detail.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include reversed</strong></p></td>
<td><p>Select this check box to display all transactions on the report. The report will include open, settled, and reversed transactions. Clear this check box to exclude reversed transactions from the report.</p>
<p>When this check box is selected, the <strong>Trace number</strong> column is added to the report. The trace number is the identifier of the reversal transaction.</p></td>
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
<td><p>LedgerAccountStatemenPerCurrency</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\LedgerAccountStatemenPerCurrency</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerAccountStatemenPerCurrency</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Groupings</strong> &gt; <strong>Account statement by currency</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerAccountStatementPerCurrencyTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the LedgerAccountStatementPerCurrencyDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



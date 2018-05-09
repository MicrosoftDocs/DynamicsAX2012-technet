---
title: (MYS, SGP) Bank cash flow report (BankCashflowReport)
TOCTitle: (MYS, SGP) Bank cash flow report (BankCashflowReport)
ms:assetid: 2035efcc-a547-4626-b1ab-ce4c825746d7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh535214(v=AX.60)
ms:contentKeyID: 39092154
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankCashflowReport
---

# (MYS, SGP) Bank cash flow report (BankCashflowReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Bank cash flow** report prints a cash flow report that displays the transactions, totals, and details of the deposits and withdrawals for a specific date range for selected bank accounts. You can use the **Comparative balances** field group to specify a different period to compare totals with the totals of the transactions that you select in the **Period** field group. This report is typically used by accounts managers, accountants, and financial controllers to help reconcile bank statements and verify incoming and outgoing cash flow.


> [!NOTE]
> <P>(MYS, SGP) This is available only to legal entities whose primary address is in Malaysia or Singapore.</P>



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
<td><p><strong>Period start date</strong>(<strong>Period</strong>)</p></td>
<td><p>Enter a starting date to specify which deposits and withdrawals to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Period end date</strong>(<strong>Period</strong>)</p></td>
<td><p>Enter an ending date to specify which deposits and withdrawals to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Period start date</strong>(<strong>Comparative balances</strong>)</p></td>
<td><p>Enter a starting date to include totals for the deposits and withdrawals within the range of dates on the report. You can use this field group to specify a different period to compare totals with the totals of the transactions that you select in the <strong>Period</strong> field group. For example, you can use this field group for a specific period in the previous year to do a comparative study of the company’s profits/losses.</p></td>
</tr>
<tr class="even">
<td><p><strong>Period end date</strong>(<strong>Comparative balances</strong>)</p></td>
<td><p>Enter an ending date to include totals for the deposits and withdrawals within the range of dates on the report. You can use this field group to specify a different period to compare totals with the totals of the transactions that you select in the <strong>Period</strong> field group. For example, you can use this field group for a specific period in the previous year to do a comparative study of the company’s profits/losses.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank account</strong></p></td>
<td><p>The bank account for which the report is generated.</p></td>
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
<td><p>BankCashflowReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankCashflowReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankAccountCashflow</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Bank cash flow</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankCashflowReportTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the BankCashflowReportDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


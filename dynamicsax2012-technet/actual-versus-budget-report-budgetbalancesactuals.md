---
title: Actual versus budget report (BudgetBalancesActuals)
TOCTitle: Actual versus budget report (BudgetBalancesActuals)
ms:assetid: 686cc36f-6fed-40c6-b1e2-99efb17d9713
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335154(v=AX.60)
ms:contentKeyID: 36687366
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BudgetBalancesActuals
---

# Actual versus budget report (BudgetBalancesActuals) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Actual versus budget** report displays budget balances for the original budget, revised budget, actual expenditures, and variances. The original budget amounts are the sum of expense and revenue budget amounts. The revised budget amounts are the sum of original budget, revisions, transfers, and carry-forward amounts. The actual expenditures are the sum of the debits and credits that were posted for the selected financial dimension values. Variances are the differences between actual and revised budget amounts, expressed as amounts and percentages. The report is grouped by budget model and dimension values.


> [!NOTE]
> <P>This report will not show budget details for encumbrances and pre-encumbrances. To create reports that include those budget types, use either the <STRONG>Budget funds available</STRONG> or <STRONG>Encumbrance and ledger reconciliation</STRONG> reports. For more information, see <A href="budget-funds-available-report-budgetfundsavailable.md">Budget funds available report (BudgetFundsAvailable)</A> or <A href="encumbrance-and-ledger-reconciliation-report-ledgerencumbrancereconciliation.md">Encumbrance and ledger reconciliation report (LedgerEncumbranceReconciliation)</A>.</P>



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
<td><p><strong>Financial dimension set</strong></p></td>
<td><p>Select a financial dimension set for the report. These were defined in the <strong>Financial dimension sets</strong> form. A financial dimension set is a named group of accounts or dimensions that contains either account values for the account or dimension values for a single dimension. Examples include main accounts, departments, and cost centers, or combinations such as a cost center and main account, or a department and cost center.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa597282(v=ax.60)">Financial dimension sets (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Budget model</strong></p></td>
<td><p>Select a budget model. If you leave this field blank, all budget models will be included on the report.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa586905(v=ax.60)">Budget model (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select the ledger classification for the actual balances: <strong>Current</strong>, <strong>Operations</strong>, or <strong>Tax</strong>.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa575927(v=ax.60)">Posting layer</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date for budget balances to include on the report. This date must be in a fiscal year that is included in the fiscal calendar that is used by your organization.</p>
<div class="alert"> 

> [!TIP]
> <P>To include report dates from one fiscal year, you do not have to enter values in both the <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields. If you enter a value in the <STRONG>From date</STRONG> field, all the periods in the fiscal year after that date will be included on the report.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date for budget balances to include on the report. This date must be in a fiscal year that is included in the fiscal calendar that is used by your organization.</p>
<div class="alert"> 

> [!TIP]
> <P>To include report dates from one fiscal year, you do not have to enter values in both the <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields. If you enter a value in the <STRONG>To date</STRONG> field, all the periods in the fiscal year before that date will be included on the report.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>View by</strong></p></td>
<td><p>Select <strong>Show net change</strong> to view budget balances by period. Select <strong>Show accumulated</strong> to view cumulative budget balances for the fiscal year.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Budget register entry status</strong></p></td>
<td><p>The status, <strong>Completed</strong> or <strong>Draft</strong>, of the budget register entries that will be included on the report.</p>
<p>The default status is <strong>Completed</strong>. Click <strong>Select</strong> to open an inquiry form to change the value. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa575929(v=ax.60)">Inquiry (form)</a>.</p>
<p>For more information about the status types, see <a href="https://technet.microsoft.com/en-us/library/hh227354(v=ax.60)">Budget registry entry (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong> (<strong>Budget account entries</strong>)</p></td>
<td><p>The date that determines the period for the budget account entries to include on the report. This field cannot be updated.</p></td>
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
<td><p>BudgetBalancesActuals</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BudgetBalancesActuals</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BudgetBalancesActualsReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Basic budgeting</strong> &gt; <strong>Actual versus budget</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BudgetBalancesActualsDP.processReport class instance method

  - BudgetTmpBalance table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Budget funds available report (BudgetFundsAvailable)](budget-funds-available-report-budgetfundsavailable.md)

[Budget details report (BudgetDetails)](budget-details-report-budgetdetails.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


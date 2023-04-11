---
title: Budget details report (BudgetDetails)
TOCTitle: Budget details report (BudgetDetails)
ms:assetid: 111de53d-e9ce-4b58-aee5-dee38b6c73cf
ms:mtpsurl: https://technet.microsoft.com/library/Hh335133(v=AX.60)
ms:contentKeyID: 36687343
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BudgetDetails
---

# Budget details report (BudgetDetails) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Budget details** report displays details about the budget register entries for the financial dimension set and date range that you select. You can select a specific budget model and budget type by using an inquiry form, or include all available budget models and budget types. The report is grouped by budget model, dimension values, and budget type. Columns display dates and amounts for the budget register entries.


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
<p>For more information, see <a href="https://technet.microsoft.com/library/aa597282(v=ax.60)">Financial dimension sets (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include draft transactions</strong></p></td>
<td><p>Select this check box to include budget register entries that have a <strong>Draft</strong> status, or clear the check box to include only budget register entries that have a <strong>Completed</strong> status.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh227354(v=ax.60)">Budget registry entry (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include submodels</strong></p></td>
<td><p>Select this check box to include budget register entries for submodels of the parent budget models.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/aa586905(v=ax.60)">Budget model (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date for budget register entries to include on the report.</p>
<p>You can select a date range from one fiscal year or from multiple fiscal years. Both dates must be in the range of fiscal years that are included in the fiscal calendar that is used by your organization.</p>
<div class="alert">

> [!TIP]
> <P>To include report dates from one fiscal year, you do not have to enter a value in both the <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields. If you enter a value in the <STRONG>From date</STRONG> field, all the periods in the fiscal year after that date will be included on the report.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date for budget register entries to include on the report.</p>
<p>You can select a date range from one fiscal year or from multiple fiscal years. Both dates must be in the range of fiscal years that are included in the fiscal calendar that is used by your organization.</p>
<div class="alert">

> [!TIP]
> <P>To include report dates from one fiscal year, you do not have to enter a value in both the <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields. If you enter a value in the <STRONG>To date</STRONG> field, all the periods in the fiscal year before that date will be included on the report.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Budget model</strong></p></td>
<td><p>Click <strong>Select</strong> to open an inquiry form and select a budget model. You can leave this field blank to include all budget models on the report.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/aa575929(v=ax.60)">Inquiry (form)</a>.</p>
<div class="alert">

> [!NOTE]
> <P>If you selected the <STRONG>Include submodels</STRONG> check box, the report will also include all submodels for the budget models that you select.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Budget type</strong></p></td>
<td><p>Click <strong>Select</strong> to open an inquiry form and select a budget type. You can leave this field blank to include all available budget types.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/aa575929(v=ax.60)">Inquiry (form)</a>.</p>
<div class="alert">

> [!NOTE]
> <P>This report will not show budget details for encumbrances and pre-encumbrances if you select those two budget types. To create reports that include encumbrances and pre-encumbrances, use either the <STRONG>Budget funds available</STRONG> or <STRONG>Encumbrance and ledger reconciliation</STRONG> reports. For more information, see <A href="budget-funds-available-report-budgetfundsavailable.md">Budget funds available report (BudgetFundsAvailable)</A> or <A href="encumbrance-and-ledger-reconciliation-report-ledgerencumbrancereconciliation.md">Encumbrance and ledger reconciliation report (LedgerEncumbranceReconciliation)</A>.</P>


</div></td>
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
<td><p>BudgetDetails</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BudgetDetails</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BudgetDetailReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Basic budgeting</strong> &gt; <strong>Budget details</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BudgetDetailsDP.processReport class instance method

  - BudgetTmpDetails table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Actual versus budget report (BudgetBalancesActuals)](actual-versus-budget-report-budgetbalancesactuals.md)

[Budget funds available report (BudgetFundsAvailable)](budget-funds-available-report-budgetfundsavailable.md)

  



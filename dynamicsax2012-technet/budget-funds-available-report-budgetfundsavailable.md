---
title: Budget funds available report (BudgetFundsAvailable)
TOCTitle: Budget funds available report (BudgetFundsAvailable)
ms:assetid: d40b0746-2a81-4ee1-8985-7df6b02d7fd8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335168(v=AX.60)
ms:contentKeyID: 36687382
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BudgetFundsAvailable
---

# Budget funds available report (BudgetFundsAvailable) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Budget funds available** report displays totals grouped by budget model and dimension values for actual expenditures, budget revisions, encumbrances, pre-encumbrances, and the budget funds that are available. The totals for the budget funds that are available are determined by the budget funds available calculation in the **Budget control configuration** form.


> [!NOTE]
> <P>For information about how to define the calculation that determines the budget funds that are available, see <A href="set-up-budget-control.md">Set up budget control</A>.</P>



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
<td><p><strong>Budget cycle time span</strong></p></td>
<td><p>Select a budget cycle time span from those that are used by your organization. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh227604(v=ax.60)">Budget cycle time spans (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include carry-forward</strong></p></td>
<td><p>Select this check box to include budget amounts that were carried forward from a previous fiscal year.</p></td>
</tr>
<tr class="even">
<td><p><strong>Dates to include</strong></p></td>
<td><p>Select dates for the budget information to include on the report. Select <strong>Budget cycle</strong> to use the dates that were specified for the budget cycle that you select. Select <strong>Date range</strong> to enter a range of dates that differ from those that are assigned to a budget cycle.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Budget cycle</strong></p></td>
<td><p>If you selected <strong>Budget cycle</strong> in the <strong>Dates to include</strong> field group, select the name of a budget cycle. The report will include information for the dates that were set up for the selected budget cycle in the <strong>Budget cycle time spans</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh227604(v=ax.60)">Budget cycle time spans (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>If you selected <strong>Date range</strong> in the <strong>Dates to include</strong> field group, select the starting date for budget funds to include on the report. This date must be in a fiscal year that is included in the fiscal calendar that was selected when the budget cycle time span was set up.</p>
<p>For example, a fiscal calendar for a budget cycle includes fiscal years with dates from January 1, 2011, to December 31, 2015. The <strong>From date</strong> value cannot be before January 1, 2011.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>If you selected <strong>Date range</strong> in the <strong>Dates to include</strong> field group, select the ending date for budget funds to include on the report. This date must be in a fiscal year that is included in the fiscal calendar that was selected when the budget cycle time span was set up.</p>
<p>For example, a fiscal calendar for a budget cycle includes fiscal years with dates from January 1, 2011, to December 31, 2015. The <strong>To date</strong> value cannot be after December 31, 2015.</p></td>
</tr>
<tr class="even">
<td><p><strong>Balance type</strong></p></td>
<td><p>Select <strong>Show net change</strong> to view balances by running totals. Select <strong>Show accumulated</strong> to view totals as cumulative amounts for the fiscal year.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Budget model</strong></p></td>
<td><p>Click <strong>Select</strong> to create the report for a selected budget model. You can leave this field blank to include all budget models on the report.</p></td>
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
<td><p>BudgetFundsAvailable</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS-Reports\Reports\BudgetFundsAvailable</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BudgetFundsAvailable</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Budget control</strong> &gt; <strong>Budget funds available</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BudgetTmpControlStatistics table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the BudgetFundsAvailableDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Actual versus budget report (BudgetBalancesActuals)](actual-versus-budget-report-budgetbalancesactuals.md)

[Budget details report (BudgetDetails)](budget-details-report-budgetdetails.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


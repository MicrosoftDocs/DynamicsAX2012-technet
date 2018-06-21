---
title: Budget plan audit report (BudgetPlanBudgetTransAuditReport)
TOCTitle: Budget plan audit report (BudgetPlanBudgetTransAuditReport)
ms:assetid: c4274ef2-b2c9-4586-809c-ed18813fbc6e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ714213(v=AX.60)
ms:contentKeyID: 49651322
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BudgetPlanBudgetTransAuditReport
---

# Budget plan audit report (BudgetPlanBudgetTransAuditReport) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report to verify that the correct budget plan lines were used to generate the budget register entries. You can also determine whether the budget plan lines or the budget register entries have changed since the budget register entries were generated. The report lists revenue amounts and expense amounts for financial dimensions across budget plans and budget register entries. The report can be grouped and subtotaled by using a summary option.

This report is available only if Microsoft Dynamics AX 2012 R2 is installed.

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
<td><p><strong>Budget plan scenario</strong></p></td>
<td><p>Select the budget plan scenario to use for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show discrepancies only</strong></p></td>
<td><p>Select this check box to include on the report only budget register account entries that differ from the source budget plan lines. Clear this check box to include all budget register account entries.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date for the budget plan lines for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date for the budget plan lines for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Option 1</strong></p></td>
<td><p>Select a budget plan header field, such as <strong>Budget cycle</strong> or <strong>Budget plan priority</strong>, to group and subtotal the report by that field.</p></td>
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
<td><p>BudgetPlanBudgetTransAuditReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BudgetPlanBudgetTransAuditReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BudgetPlanBudgetTransAuditReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Budget planning</strong> &gt; <strong>Budget plan audit</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BudgetPlanHeader table

  - BudgetPlanLine table

  - BudgetPlanLineBudgetTransactionLineLink table

  - BudgetPlanLineSource table

  - BudgetPlanningProcess table

  - BudgetPlanScenario table

  - BudgetTransactionHeader table

  - BudgetTransactionLine table

  - DimensionAttributeValueCombination table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


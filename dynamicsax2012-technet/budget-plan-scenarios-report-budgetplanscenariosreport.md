---
title: Budget plan scenarios report (BudgetPlanScenariosReport)
TOCTitle: Budget plan scenarios report (BudgetPlanScenariosReport)
ms:assetid: ec19b7f5-9819-41aa-9125-b918f6586c39
ms:mtpsurl: https://technet.microsoft.com/library/Dn305855(v=AX.60)
ms:contentKeyID: 54912954
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Budget plan scenarios report
- SSRS_Reports.Reports.BudgetPlanScenariosReport
---

# Budget plan scenarios report (BudgetPlanScenariosReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This report displays details about ledger accounts for up to five budget planning scenarios. The report can be grouped and subtotaled by using one, two, or three summary options.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



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
<td><p>Select a financial dimension set for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Budget class</strong></p></td>
<td><p>Select a budget class for the report.</p></td>
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
<td><p><strong>Scenario 1</strong> to <strong>Scenario 5</strong></p></td>
<td><p>Select up to five budget plan scenarios for the report. The data for the budget plan scenario is filtered by the scenario constraints. For example, if a budget plan is in a budget planning stage that doesn’t allow for view or edit access to a scenario, the data from the scenario is not included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Option 1</strong></p></td>
<td><p>Select a budget plan header or line field, such as <strong>Budget planning process</strong> or <strong>Document status</strong>, to group and subtotal the report by that header or line field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Option 2</strong></p></td>
<td><p>If a value is selected in the <strong>Option 1</strong> field, select an additional option to group and subtotal the report by.</p></td>
</tr>
<tr class="even">
<td><p><strong>Option 3</strong></p></td>
<td><p>If a value is selected in the <strong>Option 2</strong> field, select an additional option to group and subtotal the report by.</p></td>
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
<td><p>BudgetPlanScenariosReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BudgetPlanScenariosReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BudgetPlanScenariosReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Budget planning</strong> &gt; <strong>Budget plan scenarios</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BudgetPlanHeader table

  - BudgetPlanLine table

  - BudgetPlanLineSource table

  - BudgetPlanningProcess table

  - BudgetPlanScenario table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



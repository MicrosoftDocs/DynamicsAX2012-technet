---
title: Worker/item forecast transactions report (ProjListBudgetID)
TOCTitle: Worker/item forecast transactions report (ProjListBudgetID)
ms:assetid: 5b6e6024-a1ff-4477-9dd6-38dc93176f98
ms:mtpsurl: https://technet.microsoft.com/library/Bb147553(v=AX.60)
ms:contentKeyID: 37832003
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListBudgetID
---

# Worker/item forecast transactions report (ProjListBudgetID) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze forecasted worker and item transactions by project for a specified date range.

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
<td><p><strong>Include project types</strong></p></td>
<td><p>Select the types of projects that you want to include on the report. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select the types of transactions that you want to include on the report. You must select at least one transaction type.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Project date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Select a starting date and an ending date for transactions posted to projects to include on the report.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>Ledger date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Select a starting date and an ending date for transactions posted to the general ledger to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project statement</strong></p></td>
<td><p>Select a statement type to display on the report from the following options:</p>
<ul>
<li><p><strong>Profit and loss</strong> – Include project transactions that are posted to profit and loss accounts.</p></li>
<li><p><strong>WIP</strong> – Include project transactions that are posted to balance sheet accounts.</p></li>
<li><p><strong>Payroll</strong> – Include project transactions for hours that are posted to revenue and cost accounts.</p></li>
<li><p><strong>Consumption</strong> – Include project transactions for consumption of hours, items, expense, and payroll transactions.</p></li>
<li><p><strong>Invoice</strong> – Include project transactions for customer invoices and on-account invoicing.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Forecast model</strong></p></td>
<td><p>Select the forecast model that you want the report to use.</p>
<div class="alert">

> [!NOTE]
> <P>If you are using project budget control, select the budget forecast model that is used by this project.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Layout - rows</strong></p>
<p><strong>Level 1</strong> / <strong>Level 2</strong> / <strong>Level 3</strong></p></td>
<td><p>Select how you want to group the information on the report. Transactions are listed by <strong>Level 1</strong>, then by <strong>Level 2</strong>, and then by <strong>Level 3</strong>. For each level, you can select <strong>Project</strong>, <strong>Category</strong>, <strong>Worker/Item</strong>, or <strong>Funding source</strong>. By default, if you leave these fields empty, the report is grouped by <strong>Worker/Item</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Skip zero</strong></p></td>
<td><p>Select whether to exclude rows where the amounts are equal to zero.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show amount</strong></p></td>
<td><p>Select how you want decimals to appear on the report from the following options:</p>
<ul>
<li><p><strong>With decimals</strong> – Amounts are displayed to two decimals of your company currency.</p></li>
<li><p><strong>Without decimals</strong> – Amounts are rounded to integers.</p></li>
<li><p><strong>Amount in 1,000</strong> – Amounts are rounded to the nearest 1,000 units of your company currency.</p></li>
<li><p><strong>Amount in 1,000,000</strong> – Amounts are rounded to the nearest million units of your company currency.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Show hour</strong></p></td>
<td><p>Select whether to display the quantity of hours, the cost value for hours posted to a category, or both on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>PL ratio</strong></p></td>
<td><p>Select to display a <strong>PL ratio</strong> column on the report from the following options:</p>
<ul>
<li><p><strong>None</strong> – Do not display a <strong>PL ratio</strong> column.</p></li>
<li><p><strong>Gross margin</strong> – Display the gross margin amount for a category, which is calculated as actual revenue less actual costs.</p></li>
<li><p><strong>Value-added</strong> – Display the gross margin, expressed as a percentage of revenue.</p></li>
<li><p><strong>Both</strong> – Display both the <strong>Gross margin</strong> amount and <strong>Value-added</strong> percentage columns.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Specify transactions</strong></p></td>
<td><p>Select whether to display all transactions in a project by project date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Specify budget updates</strong></p></td>
<td><p>Select whether to include ledger updates in the transactions on the report.</p>
<div class="alert">

> [!NOTE]
> <P>You must also select the <STRONG>Specify transactions</STRONG> check box to view ledger updates on the report.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Project ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transaction list</strong> form, in the <strong>Criteria</strong> field, select a project ID to include on the report. To add more than one project ID, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transaction list</strong> form, in the <strong>Criteria</strong> field, select a project category to include on the report. To add more than one category, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transaction list</strong> form, in the <strong>Criteria</strong> field, select a worker to include on the report. To add more than one worker, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Transaction list</strong> form, in the <strong>Criteria</strong> field, select an item to include on the report. To add more than one item, click <strong>Add</strong>.</p></td>
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
<td><p>ProjListBudget</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListBudget</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListBudgetID</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Forecast transactions</strong> &gt; <strong>Worker/item forecast transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListBudgetDP.processReport

  - ProjListBudgetTmp table

  - ProjTransBudget table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListBudgetDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



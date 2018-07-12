---
title: Category profit and loss report (ProjProfitLossCateg)
TOCTitle: Category profit and loss report (ProjProfitLossCateg)
ms:assetid: 6ce34920-1065-4c2a-b6cf-3cb2f2c3422d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Bb147562(v=AX.60)
ms:contentKeyID: 36966703
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjProfitLossCateg
---

# Category profit and loss report (ProjProfitLossCateg) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze the profit or loss for projects by project category. You can specify a date range for the report.

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
<td><p>Select the type of project that you want to include on the report. You can select more than one type. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select the transaction types that you want to include on the report. You can select more than one transaction type. You must select at least one transaction type.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Project date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Select a starting date and an ending date to include transactions that are posted to projects.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>Ledger date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date to include project transactions that are posted to the ledger.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><p>Select <strong>Actual</strong> to display actual values on the report.</p>
<p>Select <strong>Budget</strong> to display budgeted values on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Forecast model</strong></p></td>
<td><p>Select the forecast model that you want the report to use.</p>
  
> [!NOTE]
> <P>If you are using project budget control, select the budget forecast model that is used by this project.</P>

</td>
</tr>
<tr class="odd">
<td><p><strong>Skip blank ID</strong></p></td>
<td><p>Select whether to exclude the transactions that are not assigned to a project.</p></td>
</tr>
<tr class="even">
<td><p><strong>Skip zero</strong></p></td>
<td><p>Select whether to exclude all rows on the report where the amounts are equal to zero.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show amount</strong></p></td>
<td><p>Select how you want decimals to appear on the report. Select from the following options:</p>
<ul>
<li><p><strong>With decimals</strong> – Amounts are displayed to two decimal places of your company currency.</p></li>
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
<td><p>Select a column to include the P&amp;L ratio percentage on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Category profit and loss</strong> form, select the project categories to include on the report. To add more than one category, click <strong>Add</strong>.</p></td>
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
<td><p>ProjProfitLossCateg</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS reports\Reports\ProjProfitLossCateg</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListProjProfitLossCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Project statements</strong> &gt; <strong>Profit and loss</strong> &gt; <strong>Category profit and loss</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListProjProfitLossCategoryDP.processReport

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Worker/item profit and loss report (ProjProfitLossEmpl)
TOCTitle: Worker/item profit and loss report (ProjProfitLossEmpl)
ms:assetid: 8cac464c-94b2-48b1-90e1-2db33af95fc5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Bb220726(v=AX.60)
ms:contentKeyID: 36966705
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjProfitLossEmpl
---

# Worker/item profit and loss report (ProjProfitLossEmpl) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze the profit or loss for projects by worker and by item.

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
<td><p>Select a type of project that you want to include on the report. You can select more than one type. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select a transaction type that you want to include on the report. You can select more than one type. You must select at least one transaction type.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Project date</strong>)</p>
<p><strong>From date</strong> /<strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date to include transactions that are posted to projects.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>Ledger date</strong>)</p>
<p><strong>From date</strong> /<strong>To date</strong></p></td>
<td><p>Specify a starting date and ending date to include project transactions that are posted to the ledger.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><p>Select <strong>Actual</strong> to display values that are the sum of actual and budget amounts.</p>
<p>Select <strong>Budget</strong> to display values that are the net balance of actual amounts less budget amounts.</p></td>
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
<td><p><strong>Skip blank ID</strong></p></td>
<td><p>Select whether to exclude rows where the project identification is blank.</p></td>
</tr>
<tr class="even">
<td><p><strong>Skip zero</strong></p></td>
<td><p>Select whether to exclude rows where the amounts are equal to zero.</p></td>
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
<td><p>Select whether to display the quantity of hours, the cost value for hours posted to a project, or both in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>PL ratio</strong></p></td>
<td><p>Select to display a <strong>PL ratio</strong> column on the report, from the following options:</p>
<ul>
<li><p><strong>None</strong> – Do not display a <strong>PL ratio</strong> column.</p></li>
<li><p><strong>Gross margin</strong> – Display the gross margin amount for a category, which is calculated as actual revenue minus actual costs.</p></li>
<li><p><strong>Value-added</strong> – Display the gross margin expressed as a percentage of revenue.</p></li>
<li><p><strong>Both</strong> – Display both the <strong>Gross margin</strong> amount and <strong>Value-added</strong> percentage columns.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Worker/item profit and loss</strong> form, in the <strong>Criteria</strong> field, select an item number to include on the report. To add more than one item, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Service subscription</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Worker/item profit and loss</strong> form, in the <strong>Criteria</strong> field, select a service subscription to include on the report. To add more than one service subscription, click <strong>Add</strong>.</p></td>
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
<td><p>ProjProfitLossEmpl</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjProfitLossEmpl</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListProjProfitLossEmplItem</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Project statements</strong> &gt; <strong>Profit and loss</strong> &gt; <strong>Worker/item profit and loss</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListProjProfitLossEmplItemDP.processReport

  - DirPerson table

  - HcmWorker table

  - InventTable table

  - PROJLISTPROJPROFITLOSSTMP table

  - SMASubscriptionTable


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the ProjListTransProjDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



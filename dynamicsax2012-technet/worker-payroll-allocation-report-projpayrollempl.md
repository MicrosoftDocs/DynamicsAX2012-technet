---
title: Worker payroll allocation report (ProjPayrollEmpl)
TOCTitle: Worker payroll allocation report (ProjPayrollEmpl)
ms:assetid: 1e412d9e-d3cd-457c-8b5a-04203bd006d0
ms:mtpsurl: https://technet.microsoft.com/library/Aa499455(v=AX.60)
ms:contentKeyID: 37831982
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjPayrollEmpl
---

# Worker payroll allocation report (ProjPayrollEmpl) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view a list of the values posted to payroll allocation accounts by worker and by item for a specified date range.

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
<td><p>(<strong>Project date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for the project transactions that you want to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Ledger date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for the ledger transactions that you want to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><p>Select <strong>Actual</strong> to display actual values on the report.</p>
<p>Select <strong>Budget</strong> to display budgeted values on the report.</p>
<div class="alert">

> [!NOTE]
> <P>If you select <STRONG>Budget</STRONG>, you must select a value in the <STRONG>Forecast model</STRONG> field.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Forecast model</strong></p></td>
<td><p>Select the <strong>Forecast model</strong> that you want the report to use.</p>
<div class="alert">

> [!NOTE]
> <P>If you are using project budget control, select the budget forecast model that is used by this project.</P>


</div></td>
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
<td><p>Select whether to display the quantity of hours, the cost value for hours posted to a project, or both on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Item number</strong></p></td>
<td><p>Click <strong>Select</strong> to select items. Only transactions for the selected items are displayed on the report. To add more than one item number, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Service subscription</strong></p></td>
<td><p>Click <strong>Select</strong> to select a subscription service. Only the items associated with the subscription service are displayed on the report.</p>
<p>For more information, see <a href="about-service-subscriptions.md">About service subscriptions</a>.</p></td>
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
<td><p>ProjPayrollEmpl</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjPayrollEmpl</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListProjPayRollEmplItem</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Payroll allocation</strong> &gt; <strong>Worker payroll allocation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListProjPayrollEmplItemDP.processReport

  - DirPerson table

  - HcmWorker table

  - InventTable

  - ProjListProjPayrollTmp table

  - SMASubscriptionTable


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the ProjListProjPayrollEmplItemDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md)

  



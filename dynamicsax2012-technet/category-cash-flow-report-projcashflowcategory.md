---
title: Category cash flow report (ProjCashFlowCategory)
TOCTitle: Category cash flow report (ProjCashFlowCategory)
ms:assetid: 5e95ba1f-f8bc-4f2c-8148-c260a0b9e94f
ms:mtpsurl: https://technet.microsoft.com/library/Hh433495(v=AX.60)
ms:contentKeyID: 36941261
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjCashFlowCategory
---

# Category cash flow report (ProjCashFlowCategory) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the amount of cash inflows and outflows by project category for a specified date range. You can compare the cash flows to the related project budget amounts.

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
<td><p>Select the project types that you want to include on the report. You can select more than one type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select the transaction types that you want to include on the report. You can select more than one transaction type. You must select at least one transaction type.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Project date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for project transactions to include on the report.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>Payment date</strong>)</p>
<p><strong>From date</strong> / <strong>To date</strong></p></td>
<td><p>Specify a starting date and an ending date for project-related payments to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Actual vs. budget</strong></p></td>
<td><ul>
<li><p>Select <strong>Deviation</strong> to display the difference between actual values and budgeted values.</p></li>
<li><p>Select <strong>Sum</strong> to display the actual values plus budgeted values.</p></li>
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
<td><p><strong>Include paid payment</strong></p></td>
<td><p>Select whether you want to include payments already made.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include expected payment</strong></p></td>
<td><p>Select whether you want to include pending payments.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>Expected sales payment date</strong>)</p>
<p><strong>Add days to due payment</strong> / <strong>Minimum payment date</strong></p></td>
<td><p>Enter the number of days from today to include in the calculation of unpaid customer invoices, or you can enter a future date. The number of days is automatically calculated from today's date to the date you select.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if you select the <STRONG>Include expected payment</STRONG> check box.</P>


</div></td>
</tr>
<tr class="even">
<td><p>(<strong>Expected cost payment dates</strong>)</p>
<p><strong>Add days to due payment</strong> / <strong>Expected cost payment dates</strong></p></td>
<td><p>Select the number of days from today to include in the calculation of pending payments to vendors, or you can enter a future date. The number of days is automatically calculated from today's date to the date you select.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if you select the <STRONG>Include expected payment</STRONG> check box.</P>


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
<td><p>Select how you want decimals to appear on the report, from the following options:</p>
<ul>
<li><p><strong>With decimals</strong> – Amounts are displayed to two decimal places of your company currency.</p></li>
<li><p><strong>Without decimals</strong> – Amounts are rounded to integers.</p></li>
<li><p><strong>Amount in 1,000</strong> – Amounts are rounded to the nearest 1,000 units of your company currency.</p></li>
<li><p><strong>Amount in 1,000,000</strong> – Amounts are rounded to the nearest million units of your company currency.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Cash flow - category</strong> form, select the project categories to include on the report. To add more than one category, click <strong>Add</strong>.</p></td>
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
<td><p>ProjCashFlowCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjCashFlowCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjCashFlowCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Cash flow</strong> &gt; <strong>Category cash flow</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjCashFlowCategoryReportDP.processReport

  - PROJCASHFLOWTMP table

  - ProjCategory table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjCashFlowCategoryReportDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



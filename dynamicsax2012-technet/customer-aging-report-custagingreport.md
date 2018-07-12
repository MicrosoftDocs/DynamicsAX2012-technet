---
title: Customer aging report (CustAgingReport)
TOCTitle: Customer aging report (CustAgingReport)
ms:assetid: 4502bde0-2241-49ec-8323-8e4fb914a243
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa575855(v=AX.60)
ms:contentKeyID: 36058376
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustAgingReport
---

# Customer aging report (CustAgingReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Customer aging** report displays the balances that are due from customers, sorted by date interval or aging period.

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
<td><p><strong>Billing classification</strong></p></td>
<td><p>Select one or more billing classifications to include on the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Include transactions without a billing classification</strong></p></td>
<td><p>If this check box is selected, all transactions that do not have a billing classifications assigned to them will be displayed on the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Balance as of</strong></p></td>
<td><p>Enter the date to view the customer balances for. This is also known as a cutoff date for transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Start date</strong></p></td>
<td><p>Enter a date that is in the first period interval or aging period to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Criteria</strong></p></td>
<td><p>Select the type of date to base the report on.</p>
<ul>
<li><p><strong>Transaction date</strong> – The posting date of the transactions. For example, this might be an invoice date that is the basis for the calculation of the due date.</p></li>
<li><p><strong>Due date</strong> – The due date of the transactions, based on the terms of payment.</p></li>
<li><p><strong>Document date</strong> – A user-defined document date that is the basis for the calculation of the due date.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Aging period definition</strong></p></td>
<td><p>Select an aging period definition. The <strong>Interval</strong> field is not used if you select an aging period definition.</p>
<p>Aging period definitions that have more than six aging periods cannot be used on the printed report.</p>
<div class="alert">

> [!NOTE]
> <P>You can set up aging periods in the <STRONG>Aging period definitions</STRONG> form.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Print aging period description</strong></p></td>
<td><p>Select <strong>Yes</strong> to include aging period descriptions at the top of each aging period column on the report. Select <strong>No</strong> to print the report without column headers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Interval</strong></p></td>
<td><p>Define the period to use by entering the number of the day or month units in each period. For example, to view aging information by week, enter 7 in this field and select <strong>Day</strong> in the <strong>Day/Mth</strong> field.</p>
<div class="alert">

> [!NOTE]
> <P>The information that you enter in this field is used only if you have not selected an aging period definition.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Day/Mth</strong></p></td>
<td><p>Select the unit, either <strong>Day</strong> or <strong>Month</strong>, that is used to define the period in the <strong>Interval</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Printing direction</strong></p></td>
<td><p>Select whether to calculate balances and print the aging report for past or future periods. The dates are evaluated relative to the date that is selected in the <strong>Balance as on</strong> field. Select <strong>Backward</strong> to show information for past periods. Select <strong>Forward</strong> to show information for future periods.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Details</strong></p></td>
<td><p>Select this check box to list the transactions that are included in the balances that are shown on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include amounts in transaction currency</strong></p></td>
<td><p>Select this check box to include amounts in the transaction currency in addition to amounts in the accounting currency. If this check box is not selected, the amounts on the report are displayed only in the accounting currency.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Negative balance</strong></p></td>
<td><p>Select this check box to include customer accounts that have negative balances.</p></td>
</tr>
<tr class="even">
<td><p><strong>Exclude zero balance accounts</strong></p></td>
<td><p>Select this check box to exclude customer accounts that have a zero balance.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment positioning</strong></p></td>
<td><p>Select this check box to display payments that have not been settled. These are displayed in the first column of the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customers</strong></p></td>
<td><p>The information displayed in this field group is determined by your selections when you create a query.</p></td>
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
<td><p>CustAgingReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustAgingReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustAgingBalance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Customer aging</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustTable table

  - CustAgingReportTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the CustAgingReportDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Aging period definitions (form)](https://technet.microsoft.com/en-us/library/aa634713\(v=ax.60\))

  



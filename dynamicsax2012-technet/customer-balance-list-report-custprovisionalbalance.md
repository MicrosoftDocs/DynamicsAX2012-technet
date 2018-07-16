---
title: Customer balance list report (CustProvisionalBalance)
TOCTitle: Customer balance list report (CustProvisionalBalance)
ms:assetid: 07bbbd60-efc0-45cd-a739-0e9b659a70c8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550100(v=AX.60)
ms:contentKeyID: 36956680
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustProvisionalBalance
---

# Customer balance list report (CustProvisionalBalance) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to show, side by side, how the customer balances have changed during a defined subperiod, such as the last month, and a defined period, such as the current year.

The report shows debit totals, which often represent the amounts that were invoiced, and credit totals, which usually are the amounts that were paid. You can use this report to quickly analyze changes in accounts receivable.

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


</div>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Include transactions without a billing classification</strong></p></td>
<td><p>If this check box is selected, all transactions that do not have a billing classification assigned to them will be displayed on the report.</p>
<div class="alert"> 

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p>
<p></p></td>
<td><p>The date that is used to calculate the amount that is shown in the <strong>Opening balance</strong> column.</p></td>
</tr>
<tr class="even">
<td><p><strong>Report period start date</strong></p></td>
<td><p>The starting date for the report period that is used to calculate the amounts that are displayed in the <strong>Debit</strong> and <strong>Credit</strong> columns.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>The ending date for the report period that is used to calculate the amounts that are displayed in the <strong>Debit</strong> and <strong>Credit</strong> columns. This date is also used to calculate the amount that is displayed in the <strong>Closing balance</strong> column.</p></td>
</tr>
<tr class="even">
<td><p><strong>Group and sort by</strong></p></td>
<td><p>Select how the information on the report will be sorted:</p>
<ul>
<li><p><strong>Customer</strong> – Group account information by customer, to see activity for each customer account.</p></li>
<li><p><strong>Main account</strong> – Group customer information by main account, to see activity for each accounts receivable summary account.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Criteria</strong></p></td>
<td><p>Select filter criteria for printing an account:</p>
<ul>
<li><p><strong>None</strong> – Print accounts, regardless of whether transactions or a balance exist in the date interval.</p></li>
<li><p><strong>Opening balance</strong> – Print accounts that have a balance on the date in the <strong>From date</strong> field.</p></li>
<li><p><strong>Transactions</strong> – Print accounts that have transactions in the date interval.</p></li>
<li><p><strong>Closing balance</strong> – Print accounts that have a balance on the date in the <strong>To date</strong> field.</p></li>
</ul>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Include details</strong></p></td>
<td><p>If <strong>Customer</strong> is selected in the <strong>Group and sort by</strong> field, select this check box to show details for each main account. If this check box is not selected, the customer account will include balance information for all accounts receivable summary accounts for the selected customers.</p>
<p>If <strong>Main account</strong> is selected in the <strong>Group and sort by</strong> field, this check box is selected automatically.</p></td>
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
<td><p>CustProvisionalBalance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustProvisionalBalance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustProvisionalBalance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Customer balance list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustProvisionalBalanceTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustProvisionalBalanceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


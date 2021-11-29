---
title: Vendor balance list report (VendProvisionalBalance)
TOCTitle: Vendor balance list report (VendProvisionalBalance)
ms:assetid: 6e2af74f-cdb1-46c7-bfe0-64df12ae4496
ms:mtpsurl: https://technet.microsoft.com/library/Aa596500(v=AX.60)
ms:contentKeyID: 37832008
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendProvisionalBalance
---

# Vendor balance list report (VendProvisionalBalance) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to show, side-by-side, how vendor balances have changed during a defined sub-period, such as last month, and a defined period, such as the current year.

The report shows credit totals, which often represent the amounts that were invoiced. The report also shows debit totals, which are usually the amounts that were paid. You can use this report to quickly analyze accounts payable developments.

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
<td><p><strong>From date</strong></p></td>
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
<td><p>Select how to sort the information on the report:</p>
<ul>
<li><p><strong>Vendor</strong> – Group account information by vendor to see activity for each vendor account.</p></li>
<li><p><strong>Main account</strong> – Group vendor information by main account to see activity for each accounts payable summary account.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Criteria</strong></p></td>
<td><p>Select criteria for printing information about an account on the report:</p>
<ul>
<li><p><strong>None</strong> – Print accounts regardless of whether transactions or balances exist in the date interval.</p></li>
<li><p><strong>Opening balance</strong> – Print accounts that have a balance on the date that is specified in the <strong>From date</strong> field.</p></li>
<li><p><strong>Transactions</strong> – Print accounts that have transactions in the date interval.</p></li>
<li><p><strong>Closing balance</strong> – Print accounts that have a balance on the date that is specified in the <strong>To date</strong> field.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Include details</strong></p></td>
<td><p>If <strong>Vendor</strong> is selected in the <strong>Group and sort by</strong> field, select this check box to show details for each main account. If this check box is not selected, the vendor account will include balance information for all accounts payable summary accounts for the selected vendors.</p>
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
<td><p>VendProvisionalBalance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\VendProvisionalBalance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendProvisionalBalance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Vendor balance list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendProvisionalBalanceTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the VendProvisionalBalanceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



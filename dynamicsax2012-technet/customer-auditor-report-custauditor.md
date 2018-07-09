---
title: Customer auditor report (CustAuditor)
TOCTitle: Customer auditor report (CustAuditor)
ms:assetid: 7432de43-0e0d-430b-b6bb-4185d18817a2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa586399(v=AX.60)
ms:contentKeyID: 36956698
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustAuditor
---

# Customer auditor report (CustAuditor) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the total amounts posted for each posting profile, sorted by customer account.

This is useful, for example, to trace customer transactions that are posted to the general ledger. Transactions are grouped by the posting profiles that are set up to process invoices, payments, and other types of transactions.

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
<td><p><strong>Print details</strong></p></td>
<td><p>Select this check box to print details for each transaction, and also the opening balance and closing balance for the selected date interval. Transaction details include the customer account, name, posting profile, and main account.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date interval</strong></p></td>
<td><p>Select this option to enable the <strong>From date</strong> and <strong>To date</strong> fields.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>If <strong>Date interval</strong> is selected, enter the starting date for the range of transaction dates to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>If <strong>Date interval</strong> is selected, enter the ending date for the range of transaction dates to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date interval code</strong></p></td>
<td><p>Select this option to enable the <strong>Date interval code</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date interval code</strong></p></td>
<td><p>Select the date interval code that defines the range of transaction dates to include on the report. Date interval codes are specified in the <strong>Date intervals</strong> form. (Click <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Periods</strong> &gt; <strong>Date intervals</strong>.)</p></td>
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
<td><p>CustAuditor</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\CustAuditor</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustReport_Auditor</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Customer</strong> &gt; <strong>Customer auditor</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustAuditorTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustAuditorDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


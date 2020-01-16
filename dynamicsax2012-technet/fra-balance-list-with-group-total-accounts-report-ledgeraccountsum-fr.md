---
title: (FRA) Balance list with group total accounts report (LedgerAccountSum_FR)
TOCTitle: (FRA) Balance list with group total accounts report (LedgerAccountSum_FR)
ms:assetid: 9550508b-2b78-4f8b-95c0-7a14fab1ab77
ms:mtpsurl: https://technet.microsoft.com/library/Aa588024(v=AX.60)
ms:contentKeyID: 36687909
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerAccountSum_FR
---

# (FRA) Balance list with group total accounts report (LedgerAccountSum\_FR) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Balance list with group total accounts** report displays a balance list for a specific date interval and ledger account range. This report includes the following information:

  - On the first page, a summary of the parameters that are used to generate the report. For example, the starting and ending dates, the ledger account range, the posting layer, and a summary of the selected editing options.

  - The title, the opening balance, the debit and credit amounts for the period, and the ending balance for each account, in the order of the accounting.

  - The totals for each page, and the grand total.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



This report is used by chief executive officers, chief financial officers, compliance managers, accounting managers, accounting supervisors, and financial controllers.


> [!NOTE]
> <P>(FRA) This report is available only to legal entities whose primary address is in France.</P>



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
<td><p>Enter a starting date for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter an ending date for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From</strong></p></td>
<td><p>Enter a starting ledger account number for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong></p></td>
<td><p>Enter an ending ledger account number for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select a posting layer that has transactions to be included in the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Include closing transactions</strong></p></td>
<td><p>Select this check box to include closing transactions in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include group total accounts</strong></p></td>
<td><p>Select this check box to include ledger accounts that have an account type of <strong>Group total</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Without transactions</strong></p></td>
<td><p>Select this check box to include the ledger accounts that do not have transactions on the report.</p></td>
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
<td><p>LedgerAccountSum_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerAccountSum_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerReport_AccountSum_FR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>France</strong> &gt; <strong>Balance list with group total accounts</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerAccountSumTmp\_FR table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerAccountSumDP_FR.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



---
title: (FRA) Ledger totals by periods report (LedgerPeriodSum_FR)
TOCTitle: (FRA) Ledger totals by periods report (LedgerPeriodSum_FR)
ms:assetid: 55fa7c8f-0863-43d7-9957-9ad2200b0094
ms:mtpsurl: https://technet.microsoft.com/library/Hh335149(v=AX.60)
ms:contentKeyID: 36687360
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerPeriodSum_FR
---

# (FRA) Ledger totals by periods report (LedgerPeriodSum\_FR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Ledger totals by periods** report is used to print ledger account totals by period for a date interval and a voucher interval. The report displays the changes in accounts for a period or time interval that you specify. The report allows you to review the accounting records. This is an annual statement that you can generate at the end of the year. The report includes the following information:

  - On the first page, a summary of the parameters that are used to generate the report. For example, the starting and ending dates, and the posting layer.

  - The starting and ending dates, the type and status, the debtor and creditor balances, and the balance sheet for each account, in chronological order.

  - The totals for each page, and the grand total.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



This report is used by account managers and accountants.


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
<td><p><strong>Start date</strong></p></td>
<td><p>Enter the starting date of the period.</p></td>
</tr>
<tr class="even">
<td><p><strong>End date</strong></p></td>
<td><p>Enter the ending date of the period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher filter</strong></p></td>
<td><p>Enter the voucher number. The transactions for only this voucher are included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select a posting layer that has transactions to be included in the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
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
<td><p>LedgerPeriodSum_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerPeriodSum_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerReport_PeriodSum_FR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>France</strong> &gt; <strong>Ledger totals by periods</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerPeriodSumTmp\_FR Table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerPeriodSumDP_FR.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



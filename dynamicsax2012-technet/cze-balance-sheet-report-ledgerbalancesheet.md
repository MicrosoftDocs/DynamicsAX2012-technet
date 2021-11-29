---
title: (CZE) Balance sheet report (LedgerBalanceSheet)
TOCTitle: (CZE) Balance sheet report (LedgerBalanceSheet)
ms:assetid: d4458adc-23e4-4ac4-8f36-7da6c044a50e
ms:mtpsurl: https://technet.microsoft.com/library/JJ710617(v=AX.60)
ms:contentKeyID: 49385014
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- balance sheet
- balance sheet report
- SSRS_Reports.Reports.LedgerBalanceSheet
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Balance sheet report (LedgerBalanceSheet) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Balance sheet report displays the ledger balance for individual accounts and the totals for all accounts for a specified period. This report is used by accounting managers and accounting supervisors to review the general ledger status.

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
<td><p><strong>Period start</strong></p></td>
<td><p>Enter the starting date of the period that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>End of period</strong></p></td>
<td><p>Enter the ending date of the period that the report is generated for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Declaring amounts</strong></p></td>
<td><p>Select how the declared amounts are rounded, from the following options:</p>
<ul>
<li><p><strong>1</strong> – The declared amounts are rounded to the nearest whole number based on the rounding method selected in the <strong>Rounding form</strong> field in the <strong>Balance sheet definition</strong> form.</p></li>
<li><p><strong>1000</strong> – The declared amounts are rounded to the nearest thousands based on the rounding method selected in the <strong>Rounding form</strong> field in the <strong>Balance sheet definition</strong> form.</p></li>
</ul>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj710630(v=ax.60)">(CZE) Balance sheet definition (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include opening balance</strong></p></td>
<td><p>Select this check box to include the opening balance in the report.</p></td>
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
<td><p>LedgerBalanceSheet</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerBalanceSheet</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerBalanceSheet</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Balance sheet</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerBalanceSheetTmp table

  - LedgerBalanceSheetCorrection table

  - LedgerBalanceSheetGross table

  - LedgerBalanceSheetHeader table

  - MainAccount table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerBalanceSheetDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(CZE) Generate the balance sheet report](cze-generate-the-balance-sheet-report.md)

  



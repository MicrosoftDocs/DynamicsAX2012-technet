---
title: Closing sheet report (LedgerClosing)
TOCTitle: Closing sheet report (LedgerClosing)
ms:assetid: 2baec0f7-7988-48d8-9624-607716d4a0c9
ms:mtpsurl: https://technet.microsoft.com/library/Hh781065(v=AX.60)
ms:contentKeyID: 43894463
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerClosing
---

# Closing sheet report (LedgerClosing) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays the closing sheet, the fiscal period range, the ledger account, and the trial balance amount. It also displays the transferred balance from ledger accounts, the difference between the trial balance amounts, including the transfer amount and the contribution of the account, as well as the amounts that the account contributes to the operating results, to the balance, and to equity. This report also provides the details of balances that are transferred from selected ledger accounts to the closing sheet during the fiscal year-end close process.

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
<td><p><strong>Cover page</strong></p></td>
<td><p>Select this check box to print a cover page that includes company information.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transactions</strong></p></td>
<td><p>Select this check box to print the closing transactions with detail.</p></td>
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
<td><p>LedgerClosing</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\LedgerClosing</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerClosing</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Fiscal year close</strong> &gt; <strong>Closing sheet</strong>. Click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerClosingTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the LedgerClosingDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



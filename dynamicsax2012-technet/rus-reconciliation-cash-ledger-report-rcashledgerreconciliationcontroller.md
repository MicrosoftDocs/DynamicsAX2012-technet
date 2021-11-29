---
title: (RUS) Reconciliation cash ledger report (RCashLedgerReconciliationController)
TOCTitle: (RUS) Reconciliation cash ledger report (RCashLedgerReconciliationController)
ms:assetid: 9195ab1b-9858-4682-b445-abdc5314254f
ms:mtpsurl: https://technet.microsoft.com/library/Xx187161(v=AX.60)
ms:contentKeyID: 52055987
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RCashLedgerReconciliation
---

# (RUS) Reconciliation cash ledger report (RCashLedgerReconciliationController) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

Use the Reconciliation cash ledger report to view information about balance amounts and cash flow for the reconciliation of petty cash balances. Accountants generate this report periodically to analyze cash account information.

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
<td><p><strong>Cash</strong></p></td>
<td><p>Select the identification code of the cash account for which the cash reconciliation information is included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Start date</strong></p></td>
<td><p>Enter the starting date of the date range during which the cash reconciliation information is included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the date range during which the cash reconciliation information is included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Specification</strong></p></td>
<td><p>Select one of the following specification criteria to print the cash account reconciliation report:</p>
<ul>
<li><p><strong>Balances</strong> – Print the cash balances report.</p></li>
</ul>
<ul>
<li><p><strong>Cash transactions</strong> – Print the cash transactions report.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Main accounts only</strong></p></td>
<td><p>Select this check box to display the information that is related to main accounts. Clear this check box to display the information that is related to ledger accounts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Zero balance</strong></p></td>
<td><p>Select this check box to print transactions for the cash accounts that are posted to the general ledger.</p></td>
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
<td><p>RCashLedgerReconciliationController</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RCashLedgerReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RCashLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Cash</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RCashLedgerReconciliationTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RCashLedgerReconciliation.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Reconcile and post an unposted transaction to a bank account](rus-reconcile-and-post-an-unposted-transaction-to-a-bank-account.md)

[(RUS) Reconcile posted transactions](rus-reconcile-posted-transactions.md)

  



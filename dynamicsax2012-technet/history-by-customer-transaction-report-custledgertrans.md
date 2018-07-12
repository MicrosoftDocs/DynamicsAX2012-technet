---
title: History by customer transaction report (CustLedgerTrans)
TOCTitle: History by customer transaction report (CustLedgerTrans)
ms:assetid: eba247b3-e808-44a1-a280-77615f4cbcd2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa599765(v=AX.60)
ms:contentKeyID: 36956717
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustLedgerTrans
---

# History by customer transaction report (CustLedgerTrans) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to document the connection between the customer accounts and the ledger accounts or main accounts.

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
<td><p><strong>Main accounts only</strong></p></td>
<td><p>Select this check box to display information for main accounts instead of ledger accounts.</p>
<p>Clear this check box to display information for ledger accounts instead of main accounts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Totals per account only</strong></p></td>
<td><p>Select this check box to display only a total for each ledger account or main account. The report then displays the total of all customer transactions for the selected customer accounts in the selected period.</p>
<p>Clear this check box to include the date, voucher number, and invoice number for each transaction on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Billing classification</strong></p></td>
<td><p>Select one or more billing classifications to include on the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


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
<td><p>CustLedgerTrans</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustLedgerTrans</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustLedgerTrans</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Customer</strong> &gt; <strong>History by transaction</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustLedgerTransTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustLedgerTransDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



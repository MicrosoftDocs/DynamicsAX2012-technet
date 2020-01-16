---
title: Deposit summary by date report (BankDepositByDate)
TOCTitle: Deposit summary by date report (BankDepositByDate)
ms:assetid: dc597d0e-9b6a-4e44-8f8f-43ac18fa4817
ms:mtpsurl: https://technet.microsoft.com/library/Aa591430(v=AX.60)
ms:contentKeyID: 36931904
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankDepositByDate
---

# Deposit summary by date report (BankDepositByDate) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the deposits in selected bank accounts for particular dates or date intervals.


> [!TIP]
> <P>If you do not want the report to display deposit slips for which cancellations have been entered but not yet posted, create a query where the <STRONG>Pending cancellation</STRONG> field in the <STRONG>Bank transactions</STRONG> table is set to <STRONG>No</STRONG>.</P>



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
<td><p>BankDepositByDate</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankDepositByDate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankDepositByDate</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Deposit summary by date</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankAccountTable table

  - BankAccountTrans table

  - BankDeposit table

  - BankDepositByDateTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the BankDepositByDateDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Add additional tables to advanced queries](add-additional-tables-to-advanced-queries.md)

  



---
title: Open transactions report (CustTransOpenPerDate)
TOCTitle: Open transactions report (CustTransOpenPerDate)
ms:assetid: ac98f074-f967-4193-81cf-45c07fc75e3f
ms:mtpsurl: https://technet.microsoft.com/library/Aa618471(v=AX.60)
ms:contentKeyID: 36956705
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustTransOpenPerDate
---

# Open transactions report (CustTransOpenPerDate) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to provide detailed information about the open transactions for each customer as of the date entered in the **Open transactions per** field. For each transaction, the report includes the date of the transaction, voucher number, amount in the transaction currency, balance in the transaction currency, subtotal amount in the accounting currency, due date, and collection letter code.

If no date is entered, the date is set to the maximum date, which is December 31, 2154.

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
<td><p><strong>Open transactions per</strong></p></td>
<td><p>Enter a date as of which transactions that are open will be included on the report.</p>
<p>If no date is entered, the date is set to the maximum date, but the date that was last used is proposed the next time that you access the report.</p></td>
</tr>
<tr class="even">
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
<td><p>CustTransOpenPerDate</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustTransOpenPerDate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustTransOpenPerDate</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Customer</strong> &gt; <strong>Open transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustTransOpenPerDateTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustTransOpenPerDateDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



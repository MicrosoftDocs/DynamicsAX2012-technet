---
title: (MYS) Customer balance list with payments in transfer report (CustBalanceList_MY)
TOCTitle: (MYS) Customer balance list with payments in transfer report (CustBalanceList_MY)
ms:assetid: 85702127-5039-4fe0-9fba-651c9c2596c4
ms:mtpsurl: https://technet.microsoft.com/library/Hh433506(v=AX.60)
ms:contentKeyID: 36941279
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustBalanceList_MY
---

# (MYS) Customer balance list with payments in transfer report (CustBalanceList\_MY) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Customer balance list with payments in transfer** report displays customer check transactions that have a future payment due date and checks that have a sent, approved, or rejected payment status. This report is used to review and inquire into the invoice and cash collections process. The report is typically used by accounts receivable managers, accountants, accounting managers, financial controllers, collections agents, and collections managers.


> [!NOTE]
> <P>(MYS) This report is available only to legal entities whose primary address is in Malaysia.</P>



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
<td><p><strong>As on</strong></p></td>
<td><p>Select a specific date for which the customer balance list report is printed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Zero balance</strong></p></td>
<td><p>Select this check box to include customer accounts that have a zero balance.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer account</strong></p></td>
<td><p>The customer account number.</p></td>
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
<td><p>CustBalanceList_MY</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustBalanceList_MY</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustBalanceList_MY</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Customer balance list with payments in transfer</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustBalanceListTmp\_MY table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustBalanceListDP_MY.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



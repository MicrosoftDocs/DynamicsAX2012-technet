---
title: (RUS) Cash statement report (RCashAccountStatement)
TOCTitle: (RUS) Cash statement report (RCashAccountStatement)
ms:assetid: a936fb76-1035-4c12-9e4f-6e4c8053f430
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Xx187162(v=AX.60)
ms:contentKeyID: 52055988
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RCashAccountStatement
---

# (RUS) Cash statement report (RCashAccountStatement) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

Use the Cash statement report to monitor the cash flow of petty cash accounts. Accountants generate this report daily or periodically to analyze cash operations.

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
<td><p>Select the identification code for the cash account that is included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Start date</strong></p></td>
<td><p>Enter the starting date of the date range during which the cash statement information is included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the date range during which the cash statement information is included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main accounts only</strong></p></td>
<td><p>Select this check box to display the information about main accounts instead of ledger accounts. Clear this check box to display the information about ledger accounts instead of main accounts.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Without transactions</strong></p></td>
<td><p>Select this check box to exclude cash transactions from the report and display only the opening and closing balances. Clear this check box to display cash transactions along with the opening and closing balances on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>New page</strong></p></td>
<td><p>Select this check box to print the details for each account on a separate page.</p></td>
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
<td><p>RCashAccountStatement</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RCashAccountStatement</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RCashAccountStatement</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Cash statement</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RCashAccountStatementTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RCashAccountStatementDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Modify and post an unrecognized payment](rus-modify-and-post-an-unrecognized-payment.md)

[(RUS) Generate the cash statement report](rus-generate-the-cash-statement-report.md)

[(RUS) Check a cash balance limit](rus-check-a-cash-balance-limit.md)

[(RUS) Generate the cash book and cashier report](rus-generate-the-cash-book-and-cashier-report.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


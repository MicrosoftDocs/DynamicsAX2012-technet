---
title: (RUS) Cash transactions report (RCashTransList)
TOCTitle: (RUS) Cash transactions report (RCashTransList)
ms:assetid: dec27e39-9b21-45ae-ab2c-250f780423a0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ945856(v=AX.60)
ms:contentKeyID: 51543176
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RCashTransList
---

# (RUS) Cash transactions report (RCashTransList) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Cash transactions report displays the transactions that are made using petty cash accounts. Accountants generate this report to review petty cash account transactions to reconcile cash flow.

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
<td><p>Select the petty cash account that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Start date</strong></p></td>
<td><p>Select the starting date of the period that the report is generated for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the period that the report is generated for.</p></td>
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
<td><p>RCashTransList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RCashTransList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RCashTransList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Cash transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RCashTable table

  - RCashTrans table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(EEUR) Cash transactions (form)](https://technet.microsoft.com/en-us/library/jj710778\(v=ax.60\))

[(EEUR) Cash accounts (form)](https://technet.microsoft.com/en-us/library/jj710760\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: (ESP) Print report (LedgerOpeningReport_ES)
TOCTitle: (ESP) Print report (LedgerOpeningReport_ES)
ms:assetid: 035e472a-0a2c-435a-81ef-a10913f67321
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh416705(v=AX.60)
ms:contentKeyID: 36931892
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerOpeningReport_ES
---

# (ESP) Print report (LedgerOpeningReport\_ES) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Print** report is used to print the details of the opening transactions during the year-end closing of transactions from the current fiscal year. This report is typically used by chief financial officers, accountants, accounting managers, and accounting supervisors to maintain and inquire into the status of opening transactions.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



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
<td><p>Select this check box to include a cover page in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transactions</strong></p></td>
<td><p>Select this check box to include transaction details in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Opening sheets</strong></p></td>
<td><p>The name of the reconciliation category that the current line is attached to.</p></td>
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
<td><p>LedgerOpeningReport_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerOpeningReport_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerOpening_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Fiscal year close</strong> &gt; <strong>Opening sheets</strong>. Create a new record or select an existing record, and then click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerOpeningSheet\_ES table

  - LedgerOpeningTable\_ES table

  - LedgerOpeningTrans\_ES table

  - MainAccount table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Opening transactions (form)](https://technet.microsoft.com/en-us/library/aa572506\(v=ax.60\))

[Transfer opening balances to a new fiscal year](transfer-opening-balances-to-a-new-fiscal-year.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


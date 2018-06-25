---
title: (NOR) Norwegian tax reconciliation report (TaxReconciliationReport)
TOCTitle: (NOR) Norwegian tax reconciliation report (TaxReconciliationReport)
ms:assetid: 84bb6984-3724-41f9-863d-29fb4d3917ed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335159(v=AX.60)
ms:contentKeyID: 36687371
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Norway
- report
- SSRS_Reports.Reports.TaxReconciliationReport
- reconciliation
- tax reconciliation
---

# (NOR) Norwegian tax reconciliation report (TaxReconciliationReport) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Norwegian tax reconciliation** report displays sales tax transactions for a settlement period, range of ledger accounts, and period that you specify. This report is used to review the status of the sales tax process and inquire into the status of sales tax transactions. This report is typically used by chief executive officers, compliance managers, accounting managers, accounting supervisors, and accountants.

You can also print and sort the sales tax codes in the report. When you print the sales tax transactions, you can exclude tax details.


> [!NOTE]
> <P>(NOR) This report is available only to legal entities whose primary address is in Norway.</P>



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
<td><p><strong>From account</strong></p></td>
<td><p>Select the starting account number in the range of ledger accounts that you want to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To account</strong></p></td>
<td><p>Select the ending account number in the range of ledger accounts that you want to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Settlement period</strong></p></td>
<td><p>Select the settlement period for which sales tax transactions must be included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the starting date for which you want to print the tax reconciliation report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date for which you want to print the tax reconciliation report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show details</strong></p></td>
<td><p>Select this check box to include the details of the sales tax transactions in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print sales tax codes</strong></p></td>
<td><p>Select this check box to print the sales tax codes in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sort order sales tax codes</strong></p></td>
<td><p>Select this check box to sort and print the sales tax codes in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show transactions without VAT</strong></p></td>
<td><p>Select this check box to print sales transactions without VAT.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales tax code</strong></p></td>
<td><p>The sales tax code used for the tax reconciliation.</p></td>
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
<td><p>TaxReconciliationReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReconciliationReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReconciliationReport_NO</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Norwegian tax reconciliation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReconciliationReportTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReconciliationReportDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


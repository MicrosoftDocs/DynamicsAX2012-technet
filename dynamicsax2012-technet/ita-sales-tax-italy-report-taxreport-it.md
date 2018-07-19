---
title: (ITA) Sales tax (Italy) report (TaxReport_IT)
TOCTitle: (ITA) Sales tax (Italy) report (TaxReport_IT)
ms:assetid: ca767b87-6900-40ea-8c99-70e0a40e9787
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352288(v=AX.60)
ms:contentKeyID: 36687916
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxReport_IT
- (ITA)
- Sales tax report report
---

# (ITA) Sales tax (Italy) report (TaxReport\_IT) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Sales tax (Italy)** report displays Italian sales tax reports and sales tax payments. The report is sorted chronologically by voucher number for each sales tax book section. The voucher numbers are continuous, without gaps between them. All sales tax book sections of the **Sales tax book** are included in the report. A subtotal is printed for each sales tax book section, and an overall total is printed. This report is used to inquire into the status of sales tax transactions. This report is typically used by collections managers, accounts receivable clerks, accounts receivable managers, accountants, accounting managers, accounting supervisors, sales clerks, sales managers, and accounts payable clerks.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p><strong>Settlement period</strong></p></td>
<td><p>Select the settlement period for which the report should be printed.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select or enter the starting date of the selected settlement period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax book type</strong></p></td>
<td><p>Select the type of sales tax book to be printed. To print sales tax books of both the <strong>Sales</strong> and <strong>Purchase</strong> types, do not select a type in this field. If a sales tax book of the type <strong>Not included</strong> is selected, you can select any <strong>Purchase</strong>, <strong>Sales</strong> or <strong>Not included</strong> number sequence that has not already been selected for a different sales tax book section. The sales tax books of the type <strong>Not included</strong> will not be included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From sales tax book</strong></p></td>
<td><p>Depending on the selection in the <strong>Sales tax book type</strong> field, select the first sales tax book to be printed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To sales tax book</strong></p></td>
<td><p>Depending on the selection in the <strong>Sales tax book type</strong> field, select the last sales tax book to be printed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales tax books</strong></p></td>
<td><p>Select this check box to print the detailed lines in the sales tax book section.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax summary</strong></p></td>
<td><p>Select this check box to print the sales tax summary for the sales tax book.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales tax payment</strong></p></td>
<td><p>Select this check box to print the sales tax payment for the period.</p>
<div class="alert">

> [!NOTE]
> <P>The sales tax payment can only be printed if the <STRONG>Sales tax book type</STRONG>, <STRONG>From sales tax book</STRONG>, and <STRONG>To sales tax book</STRONG> fields are empty.</P>


</div></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Regardless of the selection in the <STRONG>Sales tax book type</STRONG> field, all sales tax books will be displayed in the <STRONG>From sales tax book</STRONG> and <STRONG>To sales tax book</STRONG> fields.</P>



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
<td><p>TaxReport_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReport_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Sales tax (Italy)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReportTmp\_IT table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReportDP_IT.processReport table.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(ITA) Italian sales tax book sections (form)](https://technet.microsoft.com/en-us/library/aa600627\(v=ax.60\))

  



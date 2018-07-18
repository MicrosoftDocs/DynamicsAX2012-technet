---
title: (BEL) Sales tax list report (TaxList_BE)
TOCTitle: (BEL) Sales tax list report (TaxList_BE)
ms:assetid: d75601d0-2d76-4b20-9d00-1b0ff95d51ca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527159(v=AX.60)
ms:contentKeyID: 37823210
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxList_BE
- (BEL)
- (BEL) Sales tax list report
- (BEL) Sales tax list report (TaxList_BE)
- TaxList_BE
---

# (BEL) Sales tax list report (TaxList\_BE) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Sales tax list** report displays and prints details of posted sales tax. This report includes the total amounts, original amounts, and tax amounts for each sales tax code and ledger account. This report is typically used by accounts receivable managers, accounting managers, accounting supervisors, sales managers, sales clerk, accountants, and collections managers to inquire into the status of sales tax transactions.


> [!NOTE]
> <P>(BEL) This report is available only to legal entities whose primary address is in Belgium.</P>



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
<td><p><strong>Voucher</strong></p></td>
<td><p>The voucher number for the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong></p></td>
<td><p>The date of the current transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax code</strong></p></td>
<td><p>The unique identifier of the sales tax code. The sales tax code identifies a tax that is connected with a sale, such as a sales tax, fee, duty, purchase duty, or packing duty.</p></td>
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
<td><p>TaxList_BE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxList_BE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxList_BE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Sales tax payments</strong> &gt; <strong>Belgium</strong> &gt; <strong>Sales tax list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxListTmp\_BE table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the TaxListDP_BE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



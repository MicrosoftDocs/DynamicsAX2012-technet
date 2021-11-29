---
title: (THA) Sales tax report (TaxReportUnrealizedInputOutput)
TOCTitle: (THA) Sales tax report (TaxReportUnrealizedInputOutput)
ms:assetid: 29954b8c-9da2-4e2c-9e5a-0619bb3bb1ef
ms:mtpsurl: https://technet.microsoft.com/library/Hh335138(v=AX.60)
ms:contentKeyID: 36687348
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- SSRS_Reports.Reports.TaxReportUnrealizedInputOutput
- sales tax
- tax
- Input sales tax report
---

# (THA) Sales tax report (TaxReportUnrealizedInputOutput) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sales tax reports for Thailand can be generated for input sales tax and output sales tax for a specified period:

The **Input sales tax** report displays details of transactions for which you have paid input tax.

The **Output sales tax** report displays details of transactions for which you have paid output tax.

These reports are used to inquire into the status of sales tax transactions. These reports are typically used by accountants, accounting managers, and accounting supervisors.


> [!NOTE]
> <P>(THA) This report is available only to legal entities whose primary address is in Thailand.</P>



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
<td><p><strong>From date</strong></p></td>
<td><p>Enter the starting date of the period for which you want to print the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the period for which you want to print the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>The voucher number for the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong></p></td>
<td><p>The transaction date.</p></td>
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
<td><p>TaxReportUnrealizedInputOutput</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReportUnrealizedInputOutput</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReportUnrealized_Input</p>
<p>TaxReportUnrealized_Output</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Other tax</strong> &gt; <strong>Input sales tax</strong>.</p>
<p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Other tax</strong> &gt; <strong>Output sales tax</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReportUnrealizedInputOutputTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReportUnrealizedInputOutputDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



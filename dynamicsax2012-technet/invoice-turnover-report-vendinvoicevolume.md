---
title: Invoice turnover report (VendInvoiceVolume)
TOCTitle: Invoice turnover report (VendInvoiceVolume)
ms:assetid: b2b279fa-b16f-4ed4-af36-bec1faea2e5e
ms:mtpsurl: https://technet.microsoft.com/library/Aa556369(v=AX.60)
ms:contentKeyID: 37832029
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendInvoiceVolume
---

# Invoice turnover report (VendInvoiceVolume) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print a turnover report for vendor invoices. Turnover refers to the total invoice amount in a specified time period, such as a year.

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
<td><p><strong>Grouping by</strong></p></td>
<td><p>Select how to group the invoices on the report:</p>
<ul>
<li><p><strong>Account number</strong> – Group the invoices by vendor account.</p></li>
<li><p><strong>Tax exempt number</strong> – Group the invoices by tax exempt number.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the first date in the date range of transactions to include on the report. The opening balance on this date is displayed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the last date in the date range of transactions to include on the report. The closing balance on this date is displayed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Minimum amount</strong></p></td>
<td><p>Enter the minimum invoice amount to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Amount excl. sales tax</strong></p></td>
<td><p>Select this check box to exclude sales tax amounts from the report.</p></td>
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
<td><p>VendInvoiceVolume</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\VendInvoiceVolume</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendInvoiceVolume</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Invoice</strong> &gt; <strong>Vendor invoice turnover</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendInvoiceVolumeTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the VendInvoiceVolumeDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Processing batch jobs](processing-batch-jobs.md)

  



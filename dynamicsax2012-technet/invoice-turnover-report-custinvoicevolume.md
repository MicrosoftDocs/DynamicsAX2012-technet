---
title: Invoice turnover report (CustInvoiceVolume)
TOCTitle: Invoice turnover report (CustInvoiceVolume)
ms:assetid: e3377a6c-7126-47c5-82af-ecac88116ac8
ms:mtpsurl: https://technet.microsoft.com/library/Aa558245(v=AX.60)
ms:contentKeyID: 37832037
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustInvoiceVolume
---

# Invoice turnover report (CustInvoiceVolume) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print a turnover report for customer invoices. Turnover includes the total invoice amount in a specified time period, such as a year.

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
<td><p><strong>Billing classification</strong></p></td>
<td><p>Select one or more billing classifications to include.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Include transactions without a billing classification</strong></p></td>
<td><p>If this check box is selected, all transactions that do not have a billing classification assigned to them will be displayed on the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Grouping by</strong></p></td>
<td><p>Select how to group the invoices on the report:</p>
<ul>
<li><p><strong>Account number</strong> – Group the invoices by customer account.</p></li>
<li><p><strong>Tax exempt number</strong> – Group the invoices by tax exempt number.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the first date in the date range of transactions to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the last date in the date range of transactions to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Minimum amount</strong></p></td>
<td><p>Select the minimum invoice amount to include on the report.</p></td>
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
<td><p>CustInvoiceVolume</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustInvoiceVolume</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustInvoiceVolume</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Invoice</strong> &gt; <strong>Invoice turnover</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustInvoiceVolumeTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustInvoiceVolumeDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



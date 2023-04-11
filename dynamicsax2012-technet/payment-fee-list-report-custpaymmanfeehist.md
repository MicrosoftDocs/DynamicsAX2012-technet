---
title: Payment fee list report (CustPaymManFeeHist)
TOCTitle: Payment fee list report (CustPaymManFeeHist)
ms:assetid: b08c04c0-758b-4920-8d29-0d8832489ca3
ms:mtpsurl: https://technet.microsoft.com/library/Hh527786(v=AX.60)
ms:contentKeyID: 37832028
author: tonyafehr
ms.date: 04/29/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustPaymManFeeHist
---

# Payment fee list report (CustPaymManFeeHist) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print a list of payment fees that have been assessed by using payment management.

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
<td><p><strong>Customer account</strong></p></td>
<td><p>Specify the range of customer accounts to include on the report. To include all customer accounts, leave both fields blank.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong>/<strong>To date</strong></p></td>
<td><p>Specify the range of payment dates to include on the report. To include all dates, leave both fields blank.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>Specify the range of vouchers to include on the report. To include all vouchers, leave both fields blank.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong>/<strong>To date</strong></p></td>
<td><p>Specify the range of payment dates for payment management to include on the report. To include all dates, leave both fields blank.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>Specify the range of vouchers to include on the report. To include all vouchers, leave both fields blank.</p></td>
</tr>
<tr class="even">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Specify the range of payment methods to include on the report. To include all payment methods, leave both fields blank.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment step identification</strong></p></td>
<td><p>Specify the range of payment step identifications to include on the report. To include all payment step identifications, leave both fields blank.</p></td>
</tr>
<tr class="even">
<td><p><strong>Number</strong></p></td>
<td><p>Specify the range of payment numbers to include on the report. To include all payment numbers, leave both fields blank.</p></td>
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
<td><p>CustPaymManFeeHist</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustPaymManFeeHist</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustPaymManFeeHist</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Inquiries</strong> &gt; <strong>History</strong> &gt; <strong>Payments</strong> &gt; <strong>History on payment fee</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustPaymManFeeHistTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustPaymManFeeHistDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



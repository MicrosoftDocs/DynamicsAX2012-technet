---
title: (IND) TCS certificate (report)
TOCTitle: (IND) TCS certificate (report)
ms:assetid: aafbd1d7-17d4-4f6b-81de-06e6de8992a0
ms:mtpsurl: https://technet.microsoft.com/library/JJ969580(v=AX.60)
ms:contentKeyID: 51554466
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) TCS certificate (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report to generate a Form 27D certificate for the Tax collected at source (TCS) transactions that are posted to the payable accounts as defined for TCS tax codes.

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
<td><p><strong>Tax Account Number (TAN)</strong></p></td>
<td><p>Select the Tax Account Number (TAN).</p></td>
</tr>
<tr class="even">
<td><p><strong>Withholding tax component group</strong></p></td>
<td><p>Select the TCS tax component group for which to issue the certificate.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Select the start date of the period for which to issue the certificate.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer account</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Select the starting value for customer account inclusion in the statement.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Select the end date of the period for which to issue the certificate.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer account</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Select the end point for customer account inclusion in the statement.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Designation</strong></p></td>
<td><p>Enter the designation of the person responsible for collecting TCS for the period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Printing date</strong></p></td>
<td><p>Select the date to print the certificate.</p></td>
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
<td><p>TaxWithholdCertificate</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxWithholdCertificate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdCertificateTCS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>India</strong> &gt; <strong>TCS</strong> &gt; <strong>TCS certificate</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxWithholdCertificateTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



---
title: (CHN) Due amount analysis Accounts payable (China) (report)
TOCTitle: (CHN) Due amount analysis Accounts payable (China) (report)
ms:assetid: 23bc0089-ce9e-42dc-87b9-14e7af6a451b
ms:mtpsurl: https://technet.microsoft.com/library/JJ945387(v=AX.60)
ms:contentKeyID: 51442778
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Due amount analysis Accounts payable (China) (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report that displays, for a vendor, the amount due, any prepayments, and the vendor’s credit limit as of a specified date. You can use this information to analyze the vendor’s amount due status.

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
<td><p><strong>As on</strong></p></td>
<td><p>Select the date for which to view the following information about the selected vendor:</p>
<ul>
<li><p>The amount that your organization owes</p></li>
<li><p>Any prepayments your organization has made</p></li>
<li><p>The vendor’s credit limit</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Vendor account</strong></p></td>
<td><p>Click <strong>Select</strong> to select the vendor that the report is generated for.</p></td>
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
<td><p>VendDueAmountAnalysis_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendDueAmountAnalysis_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendDueAmountAnalysis_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Due amount analysis (China)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendDueAmountAnalysisTmp\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



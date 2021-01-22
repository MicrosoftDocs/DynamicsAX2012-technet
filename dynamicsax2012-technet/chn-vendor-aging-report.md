---
title: (CHN) Vendor aging (report)
TOCTitle: (CHN) Vendor aging (report)
ms:assetid: d84a7ff6-bfd4-4a6f-be7f-3d95ea57429a
ms:mtpsurl: https://technet.microsoft.com/library/JJ945395(v=AX.60)
ms:contentKeyID: 51442786
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Vendor aging (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report that displays the balances that are due to vendors. The balances are sorted by date interval or by the aging period definition.

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
<td><p><strong>Aging period 1</strong></p></td>
<td><p>Enter the number that represents the interval for the size or length of aging period 1.</p></td>
</tr>
<tr class="even">
<td><p><strong>Aging period 2</strong></p></td>
<td><p>Enter the number that represents the interval for the size or length of aging period 2.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Aging period 3</strong></p></td>
<td><p>Enter the number that represents the interval for the size or length of aging period 3.</p></td>
</tr>
<tr class="even">
<td><p><strong>Aging period 4</strong></p></td>
<td><p>Enter the number that represents the interval for the size or length of aging period 4.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Aging period 5</strong></p></td>
<td><p>Enter the number that represents the interval for the size or length of aging period 5.</p></td>
</tr>
<tr class="even">
<td><p><strong>Report aging type</strong></p></td>
<td><p>Select whether the aging periods are based on the invoice date or the payment date for a transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>As on</strong></p></td>
<td><p>Select the date for which the information on this report should be generated.</p></td>
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
<td><p>VendAging_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendAging_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendAgingBalance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Vendor aging</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendAgingTmp\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



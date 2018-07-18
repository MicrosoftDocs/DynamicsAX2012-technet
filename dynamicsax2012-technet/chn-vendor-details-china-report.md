---
title: (CHN) Vendor details (China) (report)
TOCTitle: (CHN) Vendor details (China) (report)
ms:assetid: fd7b8205-166f-4967-848e-65696500530f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ944986(v=AX.60)
ms:contentKeyID: 51412486
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Vendor details (China) (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report of vendor transactions, including information about the posted ledger account.

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
<td><p><strong>From period</strong></p></td>
<td><p>The start date for the report based on the selected period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To period</strong></p></td>
<td><p>The end date for the report based on the selected period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From posting profile:</strong></p></td>
<td><p>Select the first posting in the list of posting profiles to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To posting profile:</strong></p></td>
<td><p>Select the last profile in the list of posting profiles to include on the report.</p></td>
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
<td><p>VendLedgerTransactions_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendLedgerTransactions_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendLedgerTransactions_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Vendor details (China)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendLedgerTransactionTmp\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



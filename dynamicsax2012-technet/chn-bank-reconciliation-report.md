---
title: (CHN) Bank reconciliation (report)
TOCTitle: (CHN) Bank reconciliation (report)
ms:assetid: d19dcb3d-133d-4111-beaa-fe279babc88b
ms:mtpsurl: https://technet.microsoft.com/library/JJ873748(v=AX.60)
ms:contentKeyID: 50593461
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Bank reconciliation (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report that displays the summary information from the last reconciliation and the current reconciliation in the **Bank reconciliation** form. The report also displays detailed transactions that are grouped by transaction type.

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
<td><p><strong>Date</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Select the start date for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Voucher</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Enter the starting voucher number to include on the report.</p>
<p>The report will include all voucher numbers from this voucher number to the number that you enter in the <strong>Voucher</strong> field in the <strong>To</strong> field group.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Main account</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Select the starting account to include on the report.</p>
<p>The report will include all main accounts from this account to the account that you select in the <strong>Main account</strong> field in the <strong>To</strong> field group.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Select the end date for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Enter the last voucher number to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main account</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Select the last account to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include details</strong></p></td>
<td><p>Select this check box to include the reconciliation details on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Differences only</strong></p></td>
<td><p>Select this check box to include only the differences between the last reconciliation and the current reconciliation on the report.</p></td>
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
<td><p>BankReconciliationHeader</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankReconciliationHeader</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankReconciliationHeaderReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Bank</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankReconciliationHeaderTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



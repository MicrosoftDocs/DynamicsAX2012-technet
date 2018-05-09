---
title: (CHN) Ledger inquiry (report)
TOCTitle: (CHN) Ledger inquiry (report)
ms:assetid: a099a383-e1d7-4f00-aa4a-2a32a4aa2666
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ874413(v=AX.60)
ms:contentKeyID: 50619729
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Ledger inquiry (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays information for selected ledger accounts during a specified time period.

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
<td><p><strong>Year</strong></p></td>
<td><p>Select the fiscal year for generating the report information.</p></td>
</tr>
<tr class="even">
<td><p><strong>Period</strong></p></td>
<td><p>Select the period within the selected fiscal year for generating the report information.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From account</strong></p></td>
<td><p>Select the starting account in the list of accounts to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To account</strong></p></td>
<td><p>Select the last account in the list of accounts to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pre-printed paper</strong></p></td>
<td><p>Select this option if you are using pre-printed paper to print the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print layout code</strong></p></td>
<td><p>Select the print layout code of the voucher type.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Blank paper</strong></p></td>
<td><p>Select this option if you are using blank paper to print the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print layout currency</strong></p></td>
<td><p>Select the currency layout for the printed report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maximum lines</strong></p></td>
<td><p>Select the maximum number of lines that a printed report page can contain.</p></td>
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
<td><p>LedgerGeneralLedger_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>Forms\LedgerGeneralLedger_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerGeneralLedger_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Inquiries</strong> &gt; <strong>General ledger</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpGeneralLedger\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


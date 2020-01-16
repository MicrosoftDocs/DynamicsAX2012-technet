---
title: (RUS) FA transactions report (RAssetTransactionListing)
TOCTitle: (RUS) FA transactions report (RAssetTransactionListing)
ms:assetid: 17842306-bea9-47c1-a571-7f1bcc83f0d8
ms:mtpsurl: https://technet.microsoft.com/library/JJ955215(v=AX.60)
ms:contentKeyID: 51831848
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetTransactionListing
---

# (RUS) FA transactions report (RAssetTransactionListing) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The FA transactions report displays information about fixed asset transactions such as the transaction date, transaction currency, transaction type, a description of the transaction, and the transaction amount. Accountants generate and print this report to review the transactions for the fixed assets for a reporting period.

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
<td><p><strong>FA accounting type</strong></p></td>
<td><p>Select the value model of the fixed asset to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reporting date</strong></p></td>
<td><p>Select a date to generate the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Exclude zero turnovers</strong></p></td>
<td><p>Select this check box to exclude the fixed assets that have a net book value of zero from the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>FA group</strong></p></td>
<td><p>The fixed asset group of the fixed assets that are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The inventory identification number of the fixed assets that are included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>The current status of the fixed assets that are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Transaction type</strong></p></td>
<td><p>The transaction type of the fixed asset transactions that are included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transaction date</strong></p></td>
<td><p>The transaction date of the fixed asset transactions that are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Value model</strong></p></td>
<td><p>The identification code of the value model of the fixed assets that are included on the report.</p></td>
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
<td><p>RAssetTransactionListing</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetTransactionListing</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetTransactionListing</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>FA transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetTransactionListingTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RAssetTransactionListingDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Set up fixed asset value models](rus-set-up-fixed-asset-value-models.md)

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/library/jj923580\(v=ax.60\))

[(RUS) FA value models (form)](https://technet.microsoft.com/library/jj856113\(v=ax.60\))

  



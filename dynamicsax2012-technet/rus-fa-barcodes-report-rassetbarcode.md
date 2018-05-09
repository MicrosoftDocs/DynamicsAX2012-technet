---
title: (RUS) FA barcodes report (RAssetBarcode)
TOCTitle: (RUS) FA barcodes report (RAssetBarcode)
ms:assetid: c447f71a-8a48-40c7-b690-1994a1b52018
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ955221(v=AX.60)
ms:contentKeyID: 51831853
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetBarcode
---

# (RUS) FA barcodes report (RAssetBarcode) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The FA barcodes report displays a list of barcodes that are assigned to fixed assets. Accountants generate this report periodically to review the list of barcodes that are assigned to the fixed assets.

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
<td><p><strong>FA group</strong></p></td>
<td><p>The identification number of the fixed assets group that is included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The identification number of the fixed asset.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bar code</strong></p></td>
<td><p>The bar code of the fixed assets that is included on the report.</p></td>
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
<td><p>RAssetBarcode</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetBarcode</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetBarcode</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>FA barcodes</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetMainGroup table

  - RAssetTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Create bar codes from fixed asset numbers](rus-create-bar-codes-from-fixed-asset-numbers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


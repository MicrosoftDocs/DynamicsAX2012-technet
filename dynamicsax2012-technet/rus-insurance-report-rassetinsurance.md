---
title: (RUS) Insurance report (RAssetInsurance)
TOCTitle: (RUS) Insurance report (RAssetInsurance)
ms:assetid: 1ba6ef48-0c12-4c6f-bda1-acbe0cbec395
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ955216(v=AX.60)
ms:contentKeyID: 51831849
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetInsurance
---

# (RUS) Insurance report (RAssetInsurance) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Insurance report displays information about fixed assets that are insured. The data on the report can include the insurance policy number, insured amount, and the date when the fixed asset is insured. Accountants generate this report periodically to review the insurance information for fixed assets that are insured.

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
<td><p>The fixed asset group for the fixed assets to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The inventory number of the fixed asset to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Type</strong></p></td>
<td><p>The type of fixed assets to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Insurance date 1</strong></p></td>
<td><p>The starting coverage date for the insurance policy.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Insurance date 2</strong></p></td>
<td><p>The ending coverage date for the insurance policy.</p></td>
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
<td><p>RAssetInsurance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetInsurance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetInsurance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Insurance</strong>.</p></td>
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

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/en-us/library/jj923580\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


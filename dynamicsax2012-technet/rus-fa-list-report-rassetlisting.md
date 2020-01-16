---
title: (RUS) FA list report (RAssetListing)
TOCTitle: (RUS) FA list report (RAssetListing)
ms:assetid: 20e423f0-fef7-4705-a326-8151ec65268c
ms:mtpsurl: https://technet.microsoft.com/library/JJ992749(v=AX.60)
ms:contentKeyID: 51739436
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetListing
---

# (RUS) FA list report (RAssetListing) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The FA list report displays information about fixed assets, such as the identification number, name, status, and net book value. Accountants generate this report periodically to verify the information for a list of fixed assets.

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
<td><p>Select the value model of the fixed assets to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reporting date</strong></p></td>
<td><p>Select a date to generate the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Exclude zero turnovers</strong></p></td>
<td><p>Select this check box to exclude fixed assets that have a net book value of zero from the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The identification number of the fixed asset.</p></td>
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
<td><p>RAssetListing</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetLendingHistory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetListing</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>FA list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetListingTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp tables comes from, view the cross-references for the RAssetListingDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) FA value models (form)](https://technet.microsoft.com/library/jj856113\(v=ax.60\))

  



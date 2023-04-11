---
title: (RUS) Sheet of FA and depreciation charges report (RAssetDepreciation)
TOCTitle: (RUS) Sheet of FA and depreciation charges report (RAssetDepreciation)
ms:assetid: b711062f-d0a7-4438-9c48-2cda35933192
ms:mtpsurl: https://technet.microsoft.com/library/JJ992745(v=AX.60)
ms:contentKeyID: 51739431
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetDepreciation
---

# (RUS) Sheet of FA and depreciation charges report (RAssetDepreciation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Sheet of FA and depreciation charges report displays a list of fixed assets and their accrued depreciation charges for a period that you specify. Accountants generate this report periodically to review the list of fixed assets and their accrued depreciation charges, and then print and submit this report to the tax authorities.

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
<td><p><strong>Start date</strong></p></td>
<td><p>Select the starting date of the period that the report is generated for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the period that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Exclude zero turnovers</strong></p></td>
<td><p>Select this check box to exclude fixed assets with a net book value of zero from the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>FA group</strong></p></td>
<td><p>The fixed asset group number of the fixed asset to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The inventory number of the fixed asset to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p>The name of the fixed asset.</p></td>
</tr>
<tr class="even">
<td><p><strong>Acquisition date</strong></p></td>
<td><p>The date when the fixed asset is acquired.</p></td>
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
<td><p>RAssetDepreciation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetDepreciation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetDepreciation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Sheet of FA and depreciation charges</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetDepreciationTMP table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RAssetDepreciationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Calculate or reverse depreciation using the tax group non-linear depreciation method](rus-calculate-or-reverse-depreciation-using-the-tax-group-non-linear-depreciation-method.md)

[(RUS) FA value models (form)](https://technet.microsoft.com/library/jj856113\(v=ax.60\))

[(RUS) Set up fixed asset value models](rus-set-up-fixed-asset-value-models.md)

  



---
title: Fixed asset mass update report (AssetDepBookMassUpdate)
TOCTitle: Fixed asset mass update report (AssetDepBookMassUpdate)
ms:assetid: 13ed60f4-bdd1-4806-a5ec-5dd745687084
ms:mtpsurl: https://technet.microsoft.com/library/Aa550662(v=AX.60)
ms:contentKeyID: 37820203
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetDepBookMassUpdate
---

# Fixed asset mass update report (AssetDepBookMassUpdate) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print information about fixed asset records that have been updated by using the mass update process. To specify the information to view, you can select a depreciation book, the dates when the fixed assets were placed in service, and the depreciation conventions.

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
<td><p><strong>Depreciation book</strong></p></td>
<td><p>Select a depreciation book.</p></td>
</tr>
<tr class="even">
<td><p><strong>Placed in service start</strong></p></td>
<td><p>Select the starting date of the date range when the fixed assets were placed in service.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Placed in service end</strong></p></td>
<td><p>Select the ending date of the date range when the fixed assets were placed in service.</p></td>
</tr>
<tr class="even">
<td><p><strong>Current depreciation convention</strong></p></td>
<td><p>Select the current depreciation convention to display fixed asset records that use this depreciation convention.</p></td>
</tr>
<tr class="odd">
<td><p><strong>New depreciation convention</strong></p></td>
<td><p>Select the new depreciation convention to display fixed asset records that use this depreciation convention.</p></td>
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
<td><p>AssetDepBookMassUpdate</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports/Reports/AssetDepBookMassUpdate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetDepBookMassUpdate</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Periodic</strong> &gt; <strong>Mass update</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetDepBookMassUpdateTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the AssetDepBookMassUpdateDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Fixed asset mass update](fixed-asset-mass-update.md)

[Change depreciation conventions for multiple fixed assets](change-depreciation-conventions-for-multiple-fixed-assets.md)

  



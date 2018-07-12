---
title: (RUS) FA movement report (RAssetMoveSum)
TOCTitle: (RUS) FA movement report (RAssetMoveSum)
ms:assetid: f3fecdd2-5dd3-4f3c-b82e-b772199e2cac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ992746(v=AX.60)
ms:contentKeyID: 51739432
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetMoveSum
---

# (RUS) FA movement report (RAssetMoveSum) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The FA movement report displays the depreciation value and the revaluation costs of fixed assets. Accountants generate this report periodically to review the quantity and value of the fixed assets that are acquired or written-off during a period that you specify.

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
<td><p><strong>Depreciation group</strong></p></td>
<td><p>The depreciation group of the fixed asset.</p></td>
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
<td><p>RAssetMoveSum</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetMoveSum</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetMoveSum</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>FA movement report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetMoveSumTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RAssetMoveSumDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Factors for deferrals writing off (form)](https://technet.microsoft.com/en-us/library/jj853189\(v=ax.60\))

  



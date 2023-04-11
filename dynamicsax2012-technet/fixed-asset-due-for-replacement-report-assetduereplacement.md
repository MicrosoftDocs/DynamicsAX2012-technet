---
title: Fixed asset due for replacement report (AssetDueReplacement)
TOCTitle: Fixed asset due for replacement report (AssetDueReplacement)
ms:assetid: 93550391-0db1-411e-b0ed-9cea4c647687
ms:mtpsurl: https://technet.microsoft.com/library/Hh556866(v=AX.60)
ms:contentKeyID: 39509599
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetDueReplacement
---

# Fixed asset due for replacement report (AssetDueReplacement) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays a list of fixed assets that are scheduled for replacement, based on the **Replacement date** field on the **General** tab in the **Value models** form. The report displays the replacement cost, replacement date, asset group, asset number, asset name, value model, acquisition date, and acquisition price for the fixed assets.

## How to filter data on this report

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
<td><p><strong>Date from</strong></p></td>
<td><p>Select the starting date for the information to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date to</strong></p></td>
<td><p>Select the ending date for the information to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension</strong></p></td>
<td><p>Select the financial dimension by which to group the information on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Subtotal</strong></p></td>
<td><p>Select this check box to calculate and display totals for each financial dimension value.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select the posting layer for which to print information.</p></td>
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
<td><p>AssetDueReplacement</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\AssetDueReplacement</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetDueReplacement</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Fixed asset due for replacement</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetDueReplacementTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the AssetDueReplacementDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



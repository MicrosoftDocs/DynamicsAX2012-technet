---
title: Fixed asset replacements report (AssetReplacementReport)
TOCTitle: Fixed asset replacements report (AssetReplacementReport)
ms:assetid: c2070c5e-5f4e-4894-b938-df6df57f60c6
ms:mtpsurl: https://technet.microsoft.com/library/Hh556871(v=AX.60)
ms:contentKeyID: 39509605
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetReplacementReport
---

# Fixed asset replacements report (AssetReplacementReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view a list of fixed assets that are scheduled for replacement, based on the **Replacement date** field on the **General** tab in the **Value models** form. The report displays the replacement cost, replacement date, asset group, asset number, asset name, value model, acquisition date, and acquisition price for the fixed assets.


> [!NOTE]
> <P>This report is designed for use on Role Centers.</P>



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
<td><p>AssetReplacementReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\AssetReplacementReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetReplacement</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Treasurer Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetReplacementTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the AssetReplacementDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



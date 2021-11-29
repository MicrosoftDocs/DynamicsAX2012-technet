---
title: Fixed asset physical inventory worksheet report (AssetInventoryWorkSheet)
TOCTitle: Fixed asset physical inventory worksheet report (AssetInventoryWorkSheet)
ms:assetid: 8cd62006-3393-44ad-ab41-43d5f84572b1
ms:mtpsurl: https://technet.microsoft.com/library/Hh556865(v=AX.60)
ms:contentKeyID: 39509598
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetInventoryWorkSheet
---

# Fixed asset physical inventory worksheet report (AssetInventoryWorkSheet) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use this report as a checklist to identify assets during a physical inventory process.

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
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select a posting layer. The assets that are associated with this posting layer will be included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Group by</strong></p></td>
<td><p>Select how to group the information on the report.</p>
<ul>
<li><p><strong>Dimension</strong> – Group the information by the specified financial dimension.</p></li>
<li><p><strong>Responsible organization unit</strong> – Group the information by the organization unit that is responsible for the assets.</p></li>
<li><p><strong>Responsible person</strong> – Group the information by the person who is responsible for the assets.</p></li>
<li><p><strong>Physical location</strong> – Group the information by the physical location of the assets.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension</strong></p></td>
<td><p>If you selected <strong>Dimension</strong> in the <strong>Group by</strong> field group, select the financial dimension by which to group the report information.</p></td>
</tr>
<tr class="even">
<td><p><strong>Subtotal</strong></p></td>
<td><p>Select this check box to calculate and display the totals by the option that you selected in the <strong>Group by</strong> field.</p></td>
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
<td><p>AssetInventoryWorkSheet</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\AssetInventoryWorkSheet</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetInventoryWorkSheet</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Fixed asset physical inventory worksheet</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetTmpInventoryWorkSheet table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the AssetInventoryWorkSheetDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



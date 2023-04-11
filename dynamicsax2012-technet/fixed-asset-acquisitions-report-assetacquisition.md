---
title: Fixed asset acquisitions report (AssetAcquisition)
TOCTitle: Fixed asset acquisitions report (AssetAcquisition)
ms:assetid: f803f637-027f-4cae-b6e4-fcedb7f54a6a
ms:mtpsurl: https://technet.microsoft.com/library/Aa634704(v=AX.60)
ms:contentKeyID: 36687391
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetAcquisition
---

# Fixed asset acquisitions report (AssetAcquisition) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print information about fixed asset acquisitions. This includes the acquisition date, price, and vendor information.

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
<td><p>AssetAcquisition</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\AssetAcquisition</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetAcquisition</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Movement</strong> &gt; <strong>Fixed asset acquisitions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetBookMerge table

  - AssetTable table

  - DirPartyTable table

  - VendTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



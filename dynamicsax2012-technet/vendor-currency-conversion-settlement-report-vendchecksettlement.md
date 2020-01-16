---
title: Vendor currency conversion settlement report (VendCheckSettlement)
TOCTitle: Vendor currency conversion settlement report (VendCheckSettlement)
ms:assetid: ffcb5233-ace2-4ccc-b2a8-b533fb20dbaf
ms:mtpsurl: https://technet.microsoft.com/library/Aa601020(v=AX.60)
ms:contentKeyID: 36676499
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendCheckSettlement
---

# Vendor currency conversion settlement report (VendCheckSettlement) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this currency conversion report to view vendor settlements that have a rounding difference as a result of the currency conversion. The report shows the date of settlement, the difference, and a grand total.

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
<td><p>VendCheckSettlement</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendCheckSettlement</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendReport_CheckSettlement</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Currency conversions</strong> &gt; <strong>Settlements</strong> &gt; <strong>Vendor</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable table

  - VendSettlement table

  - VendTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



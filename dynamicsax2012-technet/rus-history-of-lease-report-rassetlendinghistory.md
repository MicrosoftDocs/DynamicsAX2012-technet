---
title: (RUS) History of lease report (RAssetLendingHistory)
TOCTitle: (RUS) History of lease report (RAssetLendingHistory)
ms:assetid: 62b72035-63f6-4752-8e51-36cec231ac6f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ992744(v=AX.60)
ms:contentKeyID: 51739433
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetLendingHistory
---

# (RUS) History of lease report (RAssetLendingHistory) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The History of Lease report displays details about the lending history of a fixed asset. Accountants generate this report periodically to review the lending history of a fixed asset and to identify fixed assets that are available for lease.

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
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The identification number of the fixed asset to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date of lease</strong></p></td>
<td><p>The date when the fixed asset is leased.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expected return date</strong></p></td>
<td><p>The date when the fixed asset is expected to be returned.</p></td>
</tr>
<tr class="even">
<td><p><strong>Location</strong></p></td>
<td><p>The current location of the fixed asset.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Leaseholder</strong></p></td>
<td><p>The individual or organization that the fixed asset is leased to.</p></td>
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
<td><p>RAssetLendingHistory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetLendingHistory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetLendingHistory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>History of lease</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetLending table

  - RAssetMainGroup table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Create a fixed asset lease and a return from lease transaction](rus-create-a-fixed-asset-lease-and-a-return-from-lease-transaction.md)

  



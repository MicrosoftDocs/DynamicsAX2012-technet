---
title: On-hand inventory report (InventOnhand)
TOCTitle: On-hand inventory report (InventOnhand)
ms:assetid: 87bcf61f-33ff-4e30-a099-445721df8f32
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227364(v=AX.60)
ms:contentKeyID: 36059575
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventOnhand
---

# On-hand inventory report (InventOnhand) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **On-hand inventory** report to print on-hand inventory according to quantity. The quantity is based on the on-hand inventory and the product, tracking, and storage dimensions. Select which product, tracking, and storage dimensions you want to include in the report.

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
<td><p>View</p></td>
<td><p>Use the check boxes in this field group to print available information for on-hand inventory. The options are as follows:</p>
<p><strong>Configuration</strong></p>
<p><strong>Size</strong></p>
<p><strong>Color</strong></p>
<p><strong>Site</strong></p>
<p><strong>Warehouse</strong></p>
<p><strong>Batch number</strong></p>
<p><strong>Location</strong></p>
<p><strong>Pallet ID</strong></p>
<p><strong>Serial number</strong></p>
<div class="alert">

> [!NOTE]
> <P>It is possible to add more criteria.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Inventory dimensions</p></td>
<td><p>Click <strong>Select</strong> and then create a query that is based on the following dimensions:</p>
<p><strong>Configuration</strong></p>
<p><strong>Size</strong></p>
<p><strong>Color</strong></p></td>
</tr>
<tr class="odd">
<td><p>Item number</p></td>
<td><p>Click <strong>Select</strong> to indicate one or more item numbers.</p></td>
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
<td><p>InventOnhand</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventOnhand</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventOnhand</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>On-hand</strong> &gt; <strong>On-hand inventory</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InventOnhandTmp table


> [!NOTE]
> <P>To learn where the data in the temp table comes from, view the cross-references for the InventOnhandDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[On-hand inventory (form)](https://technet.microsoft.com/en-us/library/aa616522\(v=ax.60\))

  



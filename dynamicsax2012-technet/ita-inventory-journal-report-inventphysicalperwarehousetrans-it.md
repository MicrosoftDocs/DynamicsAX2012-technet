---
title: (ITA) Inventory journal report (InventPhysicalPerWarehouseTrans_IT)
TOCTitle: (ITA) Inventory journal report (InventPhysicalPerWarehouseTrans_IT)
ms:assetid: ba29b05c-d064-40bc-84e1-d4e47c53b5b0
ms:mtpsurl: https://technet.microsoft.com/library/Aa556744(v=AX.60)
ms:contentKeyID: 36687912
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventPhysicalPerWarehouseTrans_IT
---

# (ITA) Inventory journal report (InventPhysicalPerWarehouseTrans\_IT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Inventory journal** report prints a summary of physical inventory transactions in chronological order, sorted by physical transaction date or by warehouse. This report is used to inquire into the status of inventory processes. This report is typically used by materials managers, quality control managers, production supervisors, project assistants, project managers, service delivery managers, and warehouse managers.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p><strong>Group by warehouse</strong></p></td>
<td><p>Select this check box to group and sort information by warehouse.</p></td>
</tr>
<tr class="even">
<td><p><strong>Configuration</strong></p></td>
<td><p>Select this check box to include the item dimension, which is used to identify item attributes.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Size</strong></p></td>
<td><p>Select this check box to include the size of each item.</p></td>
</tr>
<tr class="even">
<td><p><strong>Color</strong></p></td>
<td><p>Select this check box to include the color of each item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Warehouse</strong></p></td>
<td><p>Select this check box to include the warehouse where each item is located.</p></td>
</tr>
<tr class="even">
<td><p><strong>Batch number</strong></p></td>
<td><p>Select this check box to include the batch number for each item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Location</strong></p></td>
<td><p>Select this check box to include the location for each item.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pallet ID</strong></p></td>
<td><p>Select this check box to include the pallet ID for each item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Serial number</strong></p></td>
<td><p>Select this check box to include the serial number for each item.</p></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong></p></td>
<td><p>The identification number of the item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Physical date</strong></p></td>
<td><p>The date of the physical transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Physical voucher</strong></p></td>
<td><p>The voucher number of the physical transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension No.</strong></p></td>
<td><p>The identification number of the item’s dimension.</p></td>
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
<td><p>InventPhysicalPerWarehouseTrans_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventPhysicalPerWarehouseTrans_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventPhysicalPerWarehouseTrans_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Inventory journal</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InventPhysicalPerWarehouseTransTmp\_IT table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the InventPhysicalPerWarehouseTransDP_IT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



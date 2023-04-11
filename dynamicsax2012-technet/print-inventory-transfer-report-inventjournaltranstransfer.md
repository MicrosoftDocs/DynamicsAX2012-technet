---
title: Print inventory transfer report (InventJournalTransTransfer)
TOCTitle: Print inventory transfer report (InventJournalTransTransfer)
ms:assetid: 69eac42d-5913-4d47-8f80-f2163f4f3e5e
ms:mtpsurl: https://technet.microsoft.com/library/Hh242742(v=AX.60)
ms:contentKeyID: 36059043
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventJournalTransTransfer
---

# Print inventory transfer report (InventJournalTransTransfer) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Print inventory transfer** report to print information about inventory transfers.

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
<td><p>Print log</p></td>
<td><p>Select this check box if you want to include any infolog messages in the report.</p></td>
</tr>
<tr class="even">
<td><p>View</p></td>
<td><p>Use the check boxes in this field group to print available product, storage, and tracking dimensions for the inventory transfer lines. The options are as follows:</p>
<p><strong>Configuration</strong></p>
<p><strong>Size</strong></p>
<p><strong>Color</strong></p>
<p><strong>Site</strong></p>
<p><strong>Warehouse</strong></p>
<p><strong>Batch number</strong></p>
<p><strong>Location</strong></p>
<p><strong>Pallet ID</strong></p>
<p><strong>Serial number</strong></p></td>
</tr>
<tr class="odd">
<td><p>Inventory dimensions</p></td>
<td><p>Click <strong>Select</strong> and create a query based on the following product, tracking, and storage dimensions:</p>
<p><strong>Warehouse</strong></p></td>
</tr>
<tr class="even">
<td><p>Journal type</p></td>
<td><p>The journal type determines what the journal is used for. Microsoft Dynamics AX will populate this field.</p></td>
</tr>
<tr class="odd">
<td><p>Journal</p></td>
<td><p>Microsoft Dynamics AX will populate this field with the current journal number.</p></td>
</tr>
<tr class="even">
<td><p>Voucher</p></td>
<td><p>Microsoft Dynamics AX will populate this field with the current voucher number.</p></td>
</tr>
<tr class="odd">
<td><p>Item number</p></td>
<td><p>Click <strong>Select</strong> to indicate one or more specific item numbers to include in the report.</p></td>
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
<td><p>InventJournalTransTransfer</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventJournalTransTransfer</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventJournalTransTransfer</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Item transactions</strong> &gt; <strong>Transfer</strong>. Select <strong>Print</strong> and then click <strong>Journal</strong>.</p>
<div class="alert">

> [!NOTE]
> <P>To enable the Print option, you must create a new line. To create a new line, click <STRONG>New</STRONG>.</P>


</div></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - InventDim table

  - InventJournalTrans table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Journal lines, Inventory transfer (form)](https://technet.microsoft.com/library/aa587291\(v=ax.60\))

  



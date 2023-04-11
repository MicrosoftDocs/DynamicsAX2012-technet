---
title: Print inventory journal report (InventJournalTrans)
TOCTitle: Print inventory journal report (InventJournalTrans)
ms:assetid: 29da10f3-d0de-4ae9-aa00-5f7367231c96
ms:mtpsurl: https://technet.microsoft.com/library/Hh209118(v=AX.60)
ms:contentKeyID: 36057556
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventJournalTrans
---

# Print inventory journal report (InventJournalTrans) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Print inventory journal** report to print information about inventory journals. The report can be run from different inventory and warehouse management forms. These include **Item transactions** \> **Movement**, **Inventory adjustment**, and **Bills of materials** and **Item counting** \> **Counting**.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).


> [!NOTE]
> <P>The default parameters included in each report vary depending on the journal type. The default parameters described in the following table are for the reports generated from <STRONG>Item transactions</STRONG> &gt; <STRONG>Movement</STRONG>, <STRONG>Inventory adjustment</STRONG>, and <STRONG>Bills of materials</STRONG> and from <STRONG>Item counting</STRONG> &gt; <STRONG>Counting</STRONG>.</P>



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
<td><p>Use the check boxes in this field group to print available product, tracking, and storage dimensions for the inventory journal lines. The options are as follows:</p>
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
<td><p>Journal</p></td>
<td><p>Microsoft Dynamics AX will populate this field with the current journal number. The type of journal used to run the report varies depending on where you access the report.</p></td>
</tr>
<tr class="even">
<td><p>Voucher</p></td>
<td><p>Microsoft Dynamics AX will populate this field with the current voucher number.</p></td>
</tr>
<tr class="odd">
<td><p>Item number</p></td>
<td><p>Click <strong>Select</strong> to indicate one or more specific item numbers to include in the report.</p></td>
</tr>
<tr class="even">
<td><p>Inventory dimensions</p></td>
<td><p>Click <strong>Select</strong> and create a query based on one or more of the following product, tracking and storage dimensions:</p>
<p><strong>Configuration</strong></p>
<p><strong>Size</strong></p>
<p><strong>Color</strong></p></td>
</tr>
<tr class="odd">
<td><p>Personnel number</p></td>
<td><p>Click <strong>Select</strong> to indicate one or more specific worker personnel numbers to include in the report.</p></td>
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
<td><p>InventJournalTrans</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventJournalTrans</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventJournalTrans</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Navigate to the report from the following locations:</p>
<ul>
<li><p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Item transactions</strong> &gt; <strong>Movement</strong>.</p></li>
<li><p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Item transactions</strong> &gt; <strong>Inventory adjustment</strong>.</p></li>
<li><p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Item transactions</strong> &gt; <strong>Bills of materials</strong>.</p></li>
<li><p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Item counting</strong> &gt; <strong>Counting</strong>.</p></li>
</ul>
<p>Select <strong>Print</strong> and then click <strong>Journal</strong>.</p>
<div class="alert">

> [!NOTE]
> <P>To enable the Print option, you must create a new line by clicking <STRONG>New</STRONG>.</P>


</div></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmWorker table

  - InventDim table

  - InventJournalTrans table

  - ProjCategory table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Using inventory journals](using-inventory-journals.md)

[Inventory journal (form)](https://technet.microsoft.com/library/aa558607\(v=ax.60\))

  



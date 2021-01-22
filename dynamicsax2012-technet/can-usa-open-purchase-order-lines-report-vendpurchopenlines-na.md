---
title: (CAN, USA) Open purchase order lines report (VendPurchOpenLines_NA)
TOCTitle: (CAN, USA) Open purchase order lines report (VendPurchOpenLines_NA)
ms:assetid: 1cc11d20-6589-46da-89d4-5a2403980d17
ms:mtpsurl: https://technet.microsoft.com/library/Hh433482(v=AX.60)
ms:contentKeyID: 36941242
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendPurchOpenLines_NA
- (CAN, USA)
- Open purchase order lines
- Open purchase order lines report
- VendPurchOpenLines_NA
---

# (CAN, USA) Open purchase order lines report (VendPurchOpenLines\_NA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Open purchase order lines reports are generated to view the status of open purchase order lines. You can generate the following reports:

  - **Open purchase order lines by delivery date** – This report displays the status of open purchase order lines by delivery date.

  - **Open purchase order lines by item** – This report displays the status of open purchase order lines by item.

  - **Open purchase order lines by vendor** - This report displays the status of open purchase order lines by vendor.


> [!NOTE]
> <P>(CAN, USA) These reports are available only to legal entities whose primary address is in Canada or the United States.</P>



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
<td><p><strong>Line status</strong></p></td>
<td><p>The delivery and invoicing status of the purchase order line.</p></td>
</tr>
<tr class="even">
<td><p><strong>Delivery date</strong></p></td>
<td><p>The delivery date of the purchase order line.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Purchase order</strong></p></td>
<td><p>The purchase number that the purchase order line is attached to.</p></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong></p></td>
<td><p>The item number that is included in the purchase order line.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor account</strong></p></td>
<td><p>The vendor account number of the purchase order line.</p></td>
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
<td><p>VendPurchOpenLines_NA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendPurchOpenLines_NA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendPurchOpenLinesByDelvDate_NA</p>
<p>VendPurchOpenLinesByItem_NA</p>
<p>VendPurchOpenLinesByVend_NA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Open purchase order lines by delivery date</strong>.</p>
<p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Open purchase order lines by item</strong>.</p>
<p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Open purchase order lines by vendor</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendPurchOpenLines table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



---
title: Order lines report (SalesLinesExtended)
TOCTitle: Order lines report (SalesLinesExtended)
ms:assetid: 84125ed2-d3ec-46d8-96f8-4cc6ee6a3225
ms:mtpsurl: https://technet.microsoft.com/library/Aa586909(v=AX.60)
ms:contentKeyID: 36059545
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SalesLinesExtended
---

# Order lines report (SalesLinesExtended) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Order lines** report to print sales order lines and basic information for each sales order line such as item number, sales price, and discount.

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
<td><p>Print</p></td>
<td><p>Use the check boxes in this field group to print information about the sales order lines per order status. The options are:</p>
<p><strong>Quantity</strong></p>
<p><strong>Allocation</strong></p>
<p><strong>Weight</strong></p>
<p><strong>Volume</strong></p>
<p><strong>Gross amount</strong></p>
<p><strong>Discount</strong></p>
<p><strong>Net amount</strong></p>
<p><strong>Cost value</strong></p>
<p><strong>Margin</strong></p></td>
</tr>
<tr class="even">
<td><p>View</p></td>
<td><p>Use the check boxes in this field group to print available inventory dimensions for each sales order line. The options are:</p>
<p><strong>Configuration</strong></p>
<p><strong>Size</strong></p>
<p><strong>Color</strong></p>
<p><strong>Site</strong></p>
<p><strong>Warehouse</strong></p>
<p><strong>Batch number</strong></p>
<p><strong>Serial number</strong></p></td>
</tr>
<tr class="odd">
<td><p>Order lines</p></td>
<td><p>To create a query based on the following sales order criteria, click <strong>Select</strong>. You can indicate one or more of the following:</p>
<p><strong>Item number</strong></p>
<p><strong>Sales order</strong></p>
<p><strong>Line status</strong></p></td>
</tr>
<tr class="even">
<td><p>Inventory dimensions</p></td>
<td><p>To create a query based on the following inventory dimensions, click <strong>Select</strong>. You can indicate one or more of the following:</p>
<p><strong>Configuration</strong></p>
<p><strong>Size</strong></p>
<p><strong>Color</strong></p>
<p><strong>Site</strong></p>
<p><strong>Warehouse</strong></p></td>
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
<td><p>SalesLinesExtended</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SalesLinesExtended</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SalesLinesExtended</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Sales orders</strong> &gt; <strong>Order lines</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SalesLinesExtendedTmp table


> [!NOTE]
> <P>To learn where the data in the temp table comes from, view the cross-references for the SalesLinesExtendedDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



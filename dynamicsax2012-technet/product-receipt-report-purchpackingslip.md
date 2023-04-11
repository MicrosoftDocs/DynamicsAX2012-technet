---
title: Product receipt report (PurchPackingSlip)
TOCTitle: Product receipt report (PurchPackingSlip)
ms:assetid: 54eeaf09-b0b9-4a8a-bb55-1efe209830b0
ms:mtpsurl: https://technet.microsoft.com/library/Hh209404(v=AX.60)
ms:contentKeyID: 36058649
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.PurchPackingSlip
---

# Product receipt report (PurchPackingSlip) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Product receipt** report for internal documentation to record the product and quantity as they are received by inventory and the date they are received. You can also use the report as a packing slip when products are returned to the vendor.

## How to filter the data on this report

There are several parameters that can be used to filter the data that is displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

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
<td><p>PurchPackingSlip</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PurchPackingSlip</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PurchPackingSlip</p>
<p>PurchPackingSlipCopy</p>
<p>PurchPackingSlipOriginal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Common</strong> &gt; <strong>Purchase orders</strong> &gt; <strong>All purchase orders</strong>. Click <strong>Receive</strong> and then click <strong>Pro forma product receipt</strong>.</p>
<div class="alert">

> [!NOTE]
> <P>To enable Pro forma product receipt, you must confirm the purchase order.</P>


</div></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PurchPackingSlipHeaderTmp table

  - PurchPackingSlipTmp table


> [!NOTE]
> <P>To learn where the data in the temp tables comes from, view the cross-references for the PurchPackingSlipDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



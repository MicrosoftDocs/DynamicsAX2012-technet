---
title: Bottom 10 product performers role center report (RetailBottom10Products)
TOCTitle: Bottom 10 product performers role center report (RetailBottom10Products)
ms:assetid: 7b877169-52c0-4700-8988-307472162ef6
ms:mtpsurl: https://technet.microsoft.com/library/Hh697616(v=AX.60)
ms:contentKeyID: 42518425
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Bottom 10 product performers role center report (RetailBottom10Products) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view a list of the products that are the lowest performers. You can use this information to optimize your assortments. This report lists the product name, the quantities sold, and the profit margin for the product.


> [!NOTE]
> <P>This report is designed for use on Role Centers.</P>



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
<td><p>RetailBottom10Products</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RetailBottom10Products</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RetailBottom10Products</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Merchandising Manager Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP sales cube

  - CUSTINVOICETRANSEXPANDED table

  - INVENTTABLEEXPANDED table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  



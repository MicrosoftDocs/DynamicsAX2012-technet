---
title: Inventory value cube (InventValueCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Inventory value cube (InventValueCube)
ms:assetid: 4d369d42-3086-4e6b-b837-cb26f64dba72
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710385(v=AX.60)
ms:contentKeyID: 49384279
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Inventory value cube (InventValueCube) for Microsoft Dynamics AX 2012 R2 and R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Inventory value cube for Microsoft Dynamics AX provides data that can help you evaluate the performance of your inventory. It provides measurements that provide insight into how the value of inventory has evolved over time. A set of key performance indicators (KPIs) are available to assist the process of improving financial performance of inventory management. This article provides details about the cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
<p>Deployment</p>
<p>Configuration keys</p>
<p>Tables and views</p>
<p>Measures</p>
<p>Calculated measures</p>
<p>Key performance indicators</p>
<p>Security</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p></td>
</tr>
</tbody>
</table>


## Deployment

The Inventory value cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Inventory value cube:

  - Trade (LogisticsBasic)

## Tables and views

The Inventory value cube uses data from the following tables and views:

  - InventSite table

  - InventValueCube view

## Measures

The Inventory value cube includes the following measure groups.

## Inventory value

This measure group is based on the InventValueCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Net amount change
  </p> </td>
    <td> <p>
   
	 InventValueCube.Amount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of transactions between two periods, in monetary value.
  </p> </td>
    <td rowspan="6"> <p>
   
	 Company
  </p> <p>
   
	 Sites
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Fiscal period date
  </p> <p>
   
	 Inventory value
  </p> <p>
   
	 Date (exchange rate date)
  </p> <div><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/JJ710385.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 The Date (exchange rate date) dimension is associated with this measure only in Microsoft Dynamics AX 2012 R3.
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p>
   
	 Net quantity change
  </p> </td>
    <td> <p>
   
	 InventValueCube.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of transactions between two periods, disregarding the unit of measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net issue quantity change
  </p> </td>
    <td> <p>
   
	 InventValueCube.IssueQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of issue transactions between two periods, disregarding the unit of measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net receipt quantity change
  </p> </td>
    <td> <p>
   
	 InventValueCube.ReceiptQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of receipt transactions between two periods, disregarding the unit of measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net issue amount change
  </p> </td>
    <td> <p>
   
	 InventValueCube.IssueAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of issue transactions between two periods, in monetary value.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net receipt amount change
  </p> </td>
    <td> <p>
   
	 InventValueCube.ReceiptAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of receipt transactions between two periods, in monetary value.
  </p> </td>
  </tr>
</table>


## Exchange rates by day

This measure group is based on the BIExchangeRateView view and includes the following measures.


> [!NOTE]
> <P>This measure group is available only in Microsoft Dynamics AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Exchange rate</p></td>
<td><p>BIExchangeRateView.CrossRate</p></td>
<td><p>Max</p></td>
<td><p>The exchange rate.</p></td>
<td><p>Currency</p>
<p>Date (exchange rate date)</p>
<p>Analysis currency</p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Inventory value cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Associated measure group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Beginning quantity</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The balance as of period start, disregarding the unit of measure.</p></td>
</tr>
<tr class="even">
<td><p>Ending quantity</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The balance as of period end, disregarding the unit of measure.</p></td>
</tr>
<tr class="odd">
<td><p>Net issues quantity</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The sum of issue transactions holding an InventTransType specified in the <strong>Issue transaction</strong> field, disregarding the unit of measure.</p></td>
</tr>
<tr class="even">
<td><p>Beginning amount</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The balance as of period start, in monetary value.</p></td>
</tr>
<tr class="odd">
<td><p>Ending amount</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The balance as of period end, in monetary value.</p></td>
</tr>
<tr class="even">
<td><p>Net issues amount</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The sum of issue transactions holding an InventTransType specified in the <strong>Issue transaction</strong> field, in monetary value.</p></td>
</tr>
<tr class="odd">
<td><p>Days to date</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The number of days between periods.</p></td>
</tr>
<tr class="even">
<td><p>Products with transactions quantity</p></td>
<td><p>No aggregation</p></td>
<td><p>Not applicable</p></td>
<td><p>The products that hold an ending balance of type Quantity.</p></td>
</tr>
<tr class="odd">
<td><p>Product rank quantity</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The numeric ranking of products based on quantity.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative quantity</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative quantity value of product N.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative quantity previous</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative quantity value of product N-1.</p></td>
</tr>
<tr class="even">
<td><p>Total quantity</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The total quantity value of all products.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative % of the total quantity</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative percentage of the total quantity of product N.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative % of the total quantity previous</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative percentage of the total quantity of product N-1.</p></td>
</tr>
<tr class="odd">
<td><p>ABC category quantity</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The ABC classification of the product based on quantity measurement (C:80%, B:15%, A:5%).</p></td>
</tr>
<tr class="even">
<td><p>Products with transactions amount</p></td>
<td><p>No aggregation</p></td>
<td><p>Not applicable</p></td>
<td><p>The products that hold an ending balance of type Amount.</p></td>
</tr>
<tr class="odd">
<td><p>Product rank amount</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The numeric ranking of products based on quantity.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative amount</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative amount of product N.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative amount previous</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative amount of product N-1.</p></td>
</tr>
<tr class="even">
<td><p>Total amount</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The total amount of all products.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative % of the total amount</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative percentage of the total amount of product N.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative % of the total amount previous</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative percentage of the total amount of product N-1.</p></td>
</tr>
<tr class="odd">
<td><p>ABC category amount</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>The ABC classification of the product based on amount measurement (C:80%, B:15%, A:5%).</p></td>
</tr>
<tr class="even">
<td><p>Inventory turn quantity</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>Net issues quantity / ((Beginning quantity + Ending quantity) / 2)</p></td>
</tr>
<tr class="odd">
<td><p>Inventory turn amount</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>Net issues amount / ((Beginning amount + Ending amount) / 2)</p></td>
</tr>
<tr class="even">
<td><p>Unit cost</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>Ending amount / Ending quantity</p></td>
</tr>
<tr class="odd">
<td><p>Rank</p></td>
<td><p>No aggregation</p></td>
<td><p>Undefined</p></td>
<td><p>Inventory turn quantity / Ending amount</p></td>
</tr>
<tr class="even">
<td><p>Issue transactions</p></td>
<td><p>No aggregation</p></td>
<td><p>Not applicable</p></td>
<td><p>Used to filter InventTransType of type Sales, ProdLine, Project, Asset, KanbanJobPickingList, KanbanJobWIP, and KanbanEmptied.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the Inventory value cube.

## KPI calculations

The following table lists the KPIs that are associated with the Inventory value cube. You can use the information in the following table to help verify the information in your KPIs.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Associated measure group</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Days of inventory quantity</p></td>
<td><p>All</p></td>
<td><p>Ending quantity / (Net issues quantity / Days to date)</p></td>
</tr>
<tr class="even">
<td><p>Weeks of inventory quantity</p></td>
<td><p>All</p></td>
<td><p>Ending quantity / (Net issues quantity / (Days to date / 7))</p></td>
</tr>
<tr class="odd">
<td><p>Months of inventory quantity</p></td>
<td><p>All</p></td>
<td><p>Ending quantity / (Net issues quantity / (Days to date / 30))</p></td>
</tr>
<tr class="even">
<td><p>Inventory turn quantity</p></td>
<td><p>All</p></td>
<td><p>Net issues quantity / ((Beginning quantity + Ending quantity) / 2)</p></td>
</tr>
<tr class="odd">
<td><p>Days of inventory amount</p></td>
<td><p>All</p></td>
<td><p>Ending amount / (Net issues amount / Days to date)</p></td>
</tr>
<tr class="even">
<td><p>Weeks of inventory amount</p></td>
<td><p>All</p></td>
<td><p>Ending amount / (Net issues amount / (Days to date / 7))</p></td>
</tr>
<tr class="odd">
<td><p>Months of inventory amount</p></td>
<td><p>All</p></td>
<td><p>Ending amount / (Net issues amount / (Days to date / 30))</p></td>
</tr>
<tr class="even">
<td><p>Inventory turn amount</p></td>
<td><p>All</p></td>
<td><p>Net issues amount / ((Beginning amount + Ending amount) / 2)</p></td>
</tr>
</tbody>
</table>


## Role Centers

Except for the Cost controller Role Center page which displays KPIs by default, the KPIs of the Inventory value cube are not displayed on Role Center pages. For information about how to add them to Role Center pages, see [Manage KPIs](manage-kpis.md).

## Security

The Inventory value cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief executive officer

  - Chief financial officer

  - Cost accountant

  - Cost clerk

  - Materials manager

  - Warehouse manager

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


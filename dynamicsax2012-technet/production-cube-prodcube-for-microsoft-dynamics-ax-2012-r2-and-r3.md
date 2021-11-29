---
title: Production cube (ProdCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Production cube (ProdCube)
ms:assetid: 306e60b1-757a-493b-abcd-642597fafa19
ms:mtpsurl: https://technet.microsoft.com/library/JJ710386(v=AX.60)
ms:contentKeyID: 49384278
author: Khairunj
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Production cube (ProdCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Production cube for Microsoft Dynamics AX is used to manage and track production activities. This article provides details about the cube.

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

The Production cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Production cube:

  - Production series I (Prod)

  - Production series II (ProdRouting)

  - Trade (LogisticsBasic)

  - Resources (WrkCtr)

  - Product dimension – configuration (Config)

  - Product dimension – color (EcoResProductColor)

  - Product dimension – size (EcoResProductSize)

## Tables and views

The Production cube uses data from the following tables and views:

  - InventLocationExpanded view

  - InventTableExpanded view

  - PmfCoByProdCalcTransExpanded view

  - ProdCalcTransExpanded view

  - ProdCalcTransLevel view

  - ProdRouteTransExpanded view

  - ProdTableExpanded view

  - WrkCtrTableExpanded view

## Measures

The Production cube includes the following measure groups.

## Released products

This measure group is based on the InventTableExpanded view and includes the following measures.

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
<td><p>Released products count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of released products.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Released products</p>
<p>Styles</p>
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p></td>
</tr>
</tbody>
</table>


## Co-product cost calculation

This measure group is based on the PmfCoByProdCalcTransExpanded view and includes the following measures.

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
   
	 Co-product cost calculation count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of cost calculations performed for the co-product.
  </p> </td>
    <td rowspan="5"> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Production level
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Co-product cost calculation
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (ended date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p></p> <p></p> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Co-product cost amount
  </p> </td>
    <td> <p>
   
	 PmfCoByProdCalcTransExpanded.CostAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total cost amount for the co-product.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Co-product cost markup
  </p> </td>
    <td> <p>
   
	 PmfCoByProdCalcTransExpanded.CostMarkup
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total markup cost amount for the co-product.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Co-product real cost adjustment
  </p> </td>
    <td> <p>
   
	 PmfCoByProdCalcTransExpanded.RealCostAdjustment
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total adjusted realized cost amount for the co-product.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Co-product actual cost amount
  </p> </td>
    <td> <p>
   
	 PmfCoByProdCalcTransExpanded.RealCostAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total actual cost amount for the co-product.
  </p> </td>
  </tr>
</table>


## Cost calculation

This measure group is based on the ProdCalcTransExpanded view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Cost calculation count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of calculations.
  </p> </td>
    <td rowspan="5"> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Production level
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Cost calculation
  </p> <p>
   
	 Production order
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (ended date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Cost amount
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdCalcTransExpanded.CostAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The estimated cost of production.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Cost markup
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdCalcTransExpanded.CostMarkup
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The estimated cost of miscellaneous charges.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Actual cost amount
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdCalcTransExpanded.RealCostAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The actual cost of the production.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Real cost adjustment
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdCalcTransExpanded.RealCostAdjustment
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The actual adjustment made by inventory closing.
  </p> </td>
  </tr>
</table>


## Route transactions

This measure group is based on the ProdRouteTransExpanded view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Route transactions count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of route transactions.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Resources
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Route transactions
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Amount posted to ledger
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdRouteTransExpanded.Amount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The amount that the transaction has been posted to the ledger.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Error quantity
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdRouteTransExpanded.QtyError
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of error items reported on the operation or job.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Good quantity
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdRouteTransExpanded.QtyGood
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of good items reported on the operation or job.
  </p> </td>
  </tr>
</table>


## Production order

This measure group is based on the ProdTableExpanded view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Production order count 
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of production orders.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Production order
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (ended date)
  </p> <p>
   
	 Date (production order – ship date)
  </p> <p>
   
	 Date (started)
  </p> <p>
   
	 Date (reported as finished)
  </p> <p>
   
	 Date (start date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Days delayed
  </p> </td>
    <td colspan="1"> <p>
   
	 ProdTableExpanded.DaysDelayed
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of days the production order has been delayed based on the scheduled end date and the actual end date.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Lead time
  </p> </td>
    <td> <p>
   
	 ProdTableExpanded.LeadTime
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The actual lead time in production, that is, the average time from production start to finish.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Planned lead time
  </p> </td>
    <td> <p>
   
	 ProdTableExpanded.PlannedLeadTime
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The planed lead time in production, that is, the average time from the planned start of production to the planned end of production.
  </p> </td>
  </tr>
</table>


## Exchange rates by day

This measure group is based on the BIExchangeRateView view and includes the following measures.

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

The Production cube contains the following calculated measures.

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
<td><p>Production efficiency</p></td>
<td><p>Average</p></td>
<td><p>Production order</p></td>
<td><p>The actual processing time as a percentage of the processing time estimated based on the route.</p></td>
</tr>
<tr class="even">
<td><p>Planned cost amount</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The planned resource and materials consumption.</p></td>
</tr>
<tr class="odd">
<td><p>Planned cost markup</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The calculated additional charges.</p></td>
</tr>
<tr class="even">
<td><p>Realized cost amount</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The actual cost of production.</p></td>
</tr>
<tr class="odd">
<td><p>Realized cost adjustment</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The actual additional charges.</p></td>
</tr>
<tr class="even">
<td><p>Cost of planned consumption</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The total cost of planned resource and materials consumption, including calculated additional charges.</p></td>
</tr>
<tr class="odd">
<td><p>Cost of actual consumption</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The total cost of actual resource and materials consumption, including actual additional charges.</p></td>
</tr>
<tr class="even">
<td><p>Actual vs. planned consumption</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The difference between actual and planned consumption.</p></td>
</tr>
<tr class="odd">
<td><p>Defect ratio</p></td>
<td><p>Average</p></td>
<td><p>Route transactions</p></td>
<td><p>The number of reported errors in parts per million.</p></td>
</tr>
<tr class="even">
<td><p>WIP level</p></td>
<td><p>Average</p></td>
<td><p>Cost calculation</p></td>
<td><p>The cost associated with the current work-in-progress.</p></td>
</tr>
<tr class="odd">
<td><p>On-time production rate</p></td>
<td><p>Average</p></td>
<td><p>Production order</p></td>
<td><p>The percentage of production orders that are completed on or before the requested date.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the Production cube.

## KPI calculations

The following table lists the KPIs that are associated with the Production cube. You can use the information in the following table to help verify the information in your KPIs.

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
<td><p>Production cost</p></td>
<td><p>Cost calculation</p></td>
<td><p>This KPI is bound to the <strong>Actual vs. planned consumption</strong> calculated measure.</p></td>
</tr>
<tr class="even">
<td><p>Production efficiency</p></td>
<td><p>Production order</p></td>
<td><p>This KPI is bound to the <strong>Production efficiency</strong> calculated measure.</p></td>
</tr>
</tbody>
</table>


## Role Centers

The following table lists the Role Centers and web parts that display the KPIs associated with the Production cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role Center</p></th>
<th><p>Web parts and KPIs</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Production manager</p></td>
<td><p>Production KPIs:</p>
<ul>
<li><p>On-time production rate (%)</p></li>
<li><p>Planned vs. actual cost (%)</p></li>
<li><p>Defect ration (ppm)</p></li>
<li><p>Production efficiency (%)</p></li>
<li><p>Production lead time (seconds)</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Operations manager</p></td>
<td><p>Production KPIs:</p>
<ul>
<li><p>On-time production rate (%)</p></li>
<li><p>Planned vs. actual cost (%)</p></li>
<li><p>Defect ration (ppm)</p></li>
<li><p>Production efficiency (%)</p></li>
<li><p>Production lead time (seconds)</p></li>
</ul>
<p>Graphs:</p>
<ul>
<li><p>Defect ratio</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>CEO</p></td>
<td><p>Organization performance indicators:</p>
<ul>
<li><p>Production efficiency</p></li>
<li><p>Production cost</p></li>
</ul>
<p>Graphs:</p>
<ul>
<li><p>Actual vs. planned consumption</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Security

The Production cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief executive officer

  - Production manager

  



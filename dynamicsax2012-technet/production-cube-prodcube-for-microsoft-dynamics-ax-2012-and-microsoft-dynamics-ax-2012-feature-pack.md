---
title: Production cube (ProdCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Production cube (ProdCube)
ms:assetid: dfc15733-9d29-4250-9b13-36cccb718f9e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781076(v=AX.60)
ms:contentKeyID: 43894475
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Production cube (ProdCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Production cube to manage and track production activities.

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
   
	 Number of calculations.
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
   
	 Estimated cost of production.
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
   
	 Estimated cost of miscellaneous charges.
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
   
	 Actual cost of the production.
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
   
	 Actual adjustment made by inventory closing.
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
   
	 Number of route transactions.
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
   
	 Number of error items reported on the operation or job.
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
   
	 Number of good items reported on the operation or job.
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
   
	 The actual lead time in production, for example, the average time from production start to finish.
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
   
	 The planed lead time in production, for example, the average time from the planned start of production to the planned end of production.
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
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Production efficiency</p></td>
<td><p>Average</p></td>
<td><p>The actual processing time as a percentage of the processing time estimated based on the route.</p></td>
</tr>
<tr class="even">
<td><p>Planned cost amount</p></td>
<td><p>Average</p></td>
<td><p>The planned resource and materials consumption.</p></td>
</tr>
<tr class="odd">
<td><p>Planned cost markup</p></td>
<td><p>Average</p></td>
<td><p>The calculated additional charges.</p></td>
</tr>
<tr class="even">
<td><p>Realized cost amount</p></td>
<td><p>Average</p></td>
<td><p>The actual cost of production.</p></td>
</tr>
<tr class="odd">
<td><p>Realized cost adjustment</p></td>
<td><p>Average</p></td>
<td><p>The actual additional charges.</p></td>
</tr>
<tr class="even">
<td><p>Cost of planned consumption</p></td>
<td><p>Average</p></td>
<td><p>The total cost of planned resource and materials consumption, including calculated additional charges.</p></td>
</tr>
<tr class="odd">
<td><p>Cost of actual consumption</p></td>
<td><p>Average</p></td>
<td><p>The total cost of actual resource and materials consumption, including actual additional charges.</p></td>
</tr>
<tr class="even">
<td><p>Actual vs. planned consumption</p></td>
<td><p>Average</p></td>
<td><p>The difference between actual and planned consumption.</p></td>
</tr>
<tr class="odd">
<td><p>Defect ratio</p></td>
<td><p>Average</p></td>
<td><p>The number of reported errors in parts per million.</p></td>
</tr>
<tr class="even">
<td><p>WIP level</p></td>
<td><p>Average</p></td>
<td><p>The cost associated with the current work-in-progress.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the Production cube.

## KPI calculations

The following table lists the KPIs that are associated with the Production cube. You can use the information in the following table to help verify the information in your KPIs.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Production cost</p></td>
<td><p>This KPI is bound to the <strong>Actual vs. planned consumption</strong> calculated measure.</p></td>
</tr>
<tr class="even">
<td><p>Production efficiency</p></td>
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
<td><p>Business overview:</p>
<ul>
<li><p>On-time production rate (%)</p></li>
<li><p>Actual vs. planned cost (%)</p></li>
<li><p>Defect ration (ppm)</p></li>
<li><p>Production efficiency (%)</p></li>
<li><p>Production lead time (days)</p></li>
<li><p>WIP level</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>CEO</p></td>
<td><p>Production KPIs:</p>
<ul>
<li><p>Production efficiency</p></li>
<li><p>Production cost</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Security

The Production cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief executive officer

  - Production manager

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


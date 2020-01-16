---
title: Demand forecast cube (ReqDemandPlanningCube) for Microsoft Dynamics AX 2012 R3
TOCTitle: Demand forecast cube (ReqDemandPlanningCube
ms:assetid: 2dedf602-3be7-4f0e-bcb9-83809f7b4001
ms:mtpsurl: https://technet.microsoft.com/library/Dn716004(v=AX.60)
ms:contentKeyID: 62200227
author: Khairunj
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Demand forecast cube (ReqDemandPlanningCube) for Microsoft Dynamics AX 2012 R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Demand forecast cube for Microsoft Dynamics AX is used to store historical demand data and demand forecast data. This article provides details about the cube.

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

The Demand forecast cube is included in the Demand Forecast project. For information about how deploy the Demand Forecast project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Demand forecast cube:

  - Demand forecasting (ReqDemandPlanning)

## Tables and views

The Demand forecast cube uses data from the following tables and views:

  - EcoResColor table

  - EcoResConfiguration table

  - EcoResSize table

  - EcoResStyle table

  - WHSInventStatus table

  - ReqDemPlanCubeFactView view

  - ReqDemPlanCurrentForecastView view

  - ReqDemPlanDimAllocKey view

  - ReqDemPlanDimCountryRegion view

  - ReqDemPlanDimCustomer view

  - ReqDemPlanDimCustomerGroup view

  - ReqDemPlanDimReleasedItem view

  - ReqDemPlanDimState view

  - ReqDemPlanForecastModel view

  - ReqDemPlanForecastView view

  - ReqDemPlanInventLocation view

  - ReqDemPlanInventSite view

  - ReqDemPlanMiningModelStagingView view

## Measures

The Demand forecast cube includes the following measure groups.

## Historical data

This measure group is based on the ReqDemPlanCubeFactView view and includes the following measures.

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
<td><p>Actual demand</p></td>
<td><p>ReqDemPlanCubeFactView.TransactionQty</p></td>
<td><p>Sum</p></td>
<td><p>Past, current, and future sales order lines, BOM requirement lines, and transfer lines that are recorded in the Microsoft Dynamics AX database that represent the actual demand.</p></td>
<td><p>Item allocation key</p>
<p>Country region</p>
<p>Customer</p>
<p>Customer group</p>
<p>Released product</p>
<p>State</p>
<p>Warehouse</p>
<p>Site</p>
<p>Company</p>
<p>Styles</p>
<p>Inventory status</p>
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p>
<p>Historical data</p>
<p>Date</p></td>
</tr>
</tbody>
</table>


## Current AX forecast

This measure group is based on the ReqDemPlanCurrentForecastView view and includes the following measures.

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
<td><p>Current AX forecast</p></td>
<td><p>ReqDemPlanCurrentForecastView.Qty</p></td>
<td><p>Sum</p></td>
<td><p>Demand forecast lines that are recorded in the Microsoft Dynamics AX database and consumed by master planning. They represent the current Microsoft Dynamics AX forecast.</p></td>
<td><p>Item allocation key</p>
<p>Country region</p>
<p>Customer</p>
<p>Customer group</p>
<p>Released product</p>
<p>State</p>
<p>Forecast models</p>
<p>Warehouse</p>
<p>Site</p>
<p>Company</p>
<p>Styles</p>
<p>Inventory status</p>
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p>
<p>Date</p></td>
</tr>
</tbody>
</table>


## Demand forecast

This measure group is based on the ReqDemPlanForecastView view and includes the following measures.

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
   
	 Forecasted quantity
  </p> </td>
    <td colspan="1"> <p>
   
	 ReqDemPlanForecastView.Qty
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The demand forecast projection that is calculated based on different forecasting methods.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Item allocation key
  </p> <p>
   
	 Country region
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Customer group
  </p> <p>
   
	 Released product
  </p> <p>
   
	 State
  </p> <p>
   
	 Warehouse
  </p> <p>
   
	 Site
  </p> <p>
   
	 Company
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Inventory status
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Demand forecast
  </p> <p>
   
	 Date
  </p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Quantity
  </p> </td>
    <td> <p>
   
	 ReqDemPlanForecastView.OriginalQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The demand forecast projection that is calculated based on different forecasting methods.
  </p> </td>
  </tr>
</table>


## Calculated measures

The Demand forecast cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Associated measure group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Adjusted quantity</p></td>
<td><p>Demand forecast</p></td>
<td><p>Manual adjustments made to the forecasted demand quantity that is calculated by various forecasting methods.</p></td>
</tr>
<tr class="even">
<td><p>Read only historical and forecast quantity</p></td>
<td><p>Demand forecast</p></td>
<td><p>Past actual demand and projected future demand quantities.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Demand forecast cube does not include any key performance indicators (KPIs).

## Security

The Demand forecast cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Production planner

  - Production manager

  



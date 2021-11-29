---
title: Demand forecast accuracy cube (ReqDemPlanAccuracyCube) for Microsoft Dynamics AX 2012 R3
TOCTitle: Demand forecast accuracy cube (ReqDemPlanAccuracyCube)
ms:assetid: 7832825d-0b3c-47ec-b45a-9476bfbf6da6
ms:mtpsurl: https://technet.microsoft.com/library/Dn716005(v=AX.60)
ms:contentKeyID: 62200228
author: Khairunj
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Demand forecast accuracy cube (ReqDemPlanAccuracyCube) for Microsoft Dynamics AX 2012 R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Demand forecast accuracy cube for Microsoft Dynamics AX is used to calculate and store demand forecast versus realized demand accuracy measurements. This article provides details about the cube.

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

The Demand forecast accuracy cube is included in the Demand Forecast Accuracy project. For information about how deploy the Demand Forecast Accuracy project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Demand forecast accuracy cube:

  - Demand forecasting (ReqDemandPlanning)

## Tables and views

The Demand forecast accuracy cube uses data from the following tables and views:

  - EcoResColor table

  - EcoResConfiguration table

  - EcoResSize table

  - EcoResStyle table

  - WHSInventStatus table

  - ReqDemPlanAdjustedCubeFactView view

  - ReqDemPlanAdjustedForecastView view

  - ReqDemPlanDimAllocKey view

  - ReqDemPlanDimCountryRegion view

  - ReqDemPlanDimCustomer view

  - ReqDemPlanDimCustomerGroup view

  - ReqDemPlanDimReleasedItem view

  - ReqDemPlanDimState view

  - ReqDemPlanForecastModel view

  - ReqDemPlanInventLocation view

  - ReqDemPlanInventSite view

## Measures

The Demand forecast accuracy cube includes the following measure groups.

## Historical demand

This measure group is based on the ReqDemPlanAdjustedCubeFactView view and includes the following measures.

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
<td><p>Historical demand quantity</p></td>
<td><p>ReqDemPlanAdjustedCubeFactView.TransactionQty</p></td>
<td><p>Sum</p></td>
<td><p>Past sales order lines, BOM requirement lines, and transfer lines, recorded in the Microsoft Dynamics AX database represent the historical demand quantity.</p></td>
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
<p>Historical demand</p>
<p>Date</p></td>
</tr>
</tbody>
</table>


## Adjusted forecast

This measure group is based on the ReqDemPlanAdjustedForecastView view and includes the following measures.

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
<td><p>ReqDemPlanAdjustedForecastView.Qty</p></td>
<td><p>Sum</p></td>
<td><p>Demand forecast lines recorded in the Microsoft Dynamics AX database and consumed by master planning represent the current forecast.</p></td>
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


## Calculated measures

The Demand forecast accuracy cube contains the following calculated measures.

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
<td><p>Error percentage</p></td>
<td><p>Adjusted forecast</p></td>
<td><p>The discrepancy between realized demand and projected demand, expressed in percentage.</p></td>
</tr>
<tr class="even">
<td><p>Error absolute</p></td>
<td><p>Adjusted forecast</p></td>
<td><p>The discrepancy between realized demand and projected demand, expressed in absolute values.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Demand forecast accuracy cube does not include any key performance indicators (KPIs).

## Security

The Demand forecast accuracy cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Production planner

  - Production manager

  



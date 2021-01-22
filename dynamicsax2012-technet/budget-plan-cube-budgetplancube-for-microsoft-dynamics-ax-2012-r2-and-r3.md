---
title: Budget plan cube (BudgetPlanCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Budget plan cube (BudgetPlanCube)
ms:assetid: 015155b3-1af0-402d-8b85-5ff1b394534a
ms:mtpsurl: https://technet.microsoft.com/library/JJ710380(v=AX.60)
ms:contentKeyID: 49384271
author: Khairunj
ms.author: daxcpft
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Budget plan cube (BudgetPlanCube) for Microsoft Dynamics AX 2012 R2 and R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Budget plan cube for Microsoft Dynamics AX is used to analyze data from the budget plan documents. Analysis of budget planning data is required for organizations to effectively manage their budget planning process and make decisions based on accurate information. This article provides details about the cube.

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

The Budget plan cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Budget plan cube:

  - Budget planning configuration key (LedgerAdv2BudgetPlanning)

## Tables and views

The Budget plan cube uses data from the following tables and views:

  - AssetTable table

  - BudgetCycle table

  - BudgetPlanHeader table

  - BudgetPlanningProcess table

  - BudgetPlanningStage table

  - BudgetPlanPriority table

  - BudgetPlanProposedAsset table

  - BudgetPlanProposedProject table

  - BudgetPlanScenario table

  - UnitOfMeasure table

  - UserGroupInfo table

  - BudgetPlanCube view

  - BudgetPlanHeaderView view

  - HcmPositionForecastCube view

  - OMDepartmentView view

## Measures

The Budget plan cube includes the following measure groups.

## Budget plan lines

This measure group is based on the BudgetPlanCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
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
   
	 Amount
  </p> </td>
    <td> <p>
   
	 BudgetPlanCube.PlanCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The sum of field Amount from budget plan lines in the selected data set.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Responsibility center
  </p> <p>
   
	 Budget plan header
  </p> <p>
   
	 Budget planning process
  </p> <p>
   
	 Budget planning stage
  </p> <p>
   
	 Budget plan priorities
  </p> <p>
   
	 Budget plan proposed asset
  </p> <p>
   
	 Budget plan proposed project
  </p> <p>
   
	 Budget plan scenario
  </p> <p>
   
	 Budget cycle
  </p> <p>
   
	 Units
  </p> <p>
   
	 User group information
  </p> <p>
   
	 Fixed assets
  </p> <p>
   
	 Forecast positions
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Ledger derived financial attribute value combinations
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Budget plan lines
  </p> <p>
   
	 Budget plan header (parent budget plan)
  </p> <p>
   
	 Date (effective date)
  </p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Quantity
  </p> </td>
    <td> <p>
   
	 BudgetPlanCube.Quantity
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of field Quantity from budget plan lines in the selected data set.
  </p> </td>
  </tr>
</table>


## Budget plan header

This measure group is based on the BudgetPlanHeader view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
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
   
	 Number of budget plans
  </p> </td>
    <td> <p>
   
	 BudgetPlanHeaderView.DocumentNumber
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of budget plan documents in the selected data set.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Responsibility center
  </p> <p>
   
	 Budget plan header
  </p> <p>
   
	 Budget planning process
  </p> <p>
   
	 Budget planning stage
  </p> <p>
   
	 Budget plan priorities
  </p> <p>
   
	 Budget cycle
  </p> <p>
   
	 User group information
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Budget plan header (parent budget plan)
  </p> <p></p> </td>
  </tr>
</table>


## Calculated measures

The Budget plan cube contains the following calculated measures.

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
<td><p>Budget net income</p></td>
<td><p>Budgeted revenues minus budgeted expenses.</p></td>
<td><p>Budget plan lines</p></td>
<td><p>Defines budgeted profitability of the selected budget plan document lines.</p>
<p>A total budget net income is calculated as a total of budget plan line field Amount. Budget amount for the expense accounts is stored in the budget plan document line as a positive number. Budget amount for the revenue accounts is stored as a negative number.</p></td>
</tr>
<tr class="even">
<td><p>Percentage of plans completed</p></td>
<td><p>Count of budget plans with document status of Finalized, divided by count of all budget plans.</p></td>
<td><p>Budget plan header</p></td>
<td><p>Defines the progress of budget planning processes.</p>
<p>This percentage is calculated based on the total number of budget plan documents, and the number of budget plan documents that have a status of Finalized.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Budget plan cube does not include any key performance indicators (KPIs).

## Security

The Budget plan cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accounting manager

  - Accounting supervisor

  - Budget manager

  - Chief executive officer

  - Chief financial officer

  - Compliance manager

  - Financial controller

  



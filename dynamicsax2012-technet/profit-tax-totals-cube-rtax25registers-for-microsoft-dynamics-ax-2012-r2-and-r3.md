---
title: Profit tax totals cube (RTax25Registers) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Profit tax totals cube (RTax25Registers)
ms:assetid: 46f413df-d652-46cc-a865-c1c8136d5770
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916230(v=AX.60)
ms:contentKeyID: 50877511
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Profit tax totals cube (RTax25Registers) for Microsoft Dynamics AX 2012 R2 and R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Profit tax totals cube for Microsoft Dynamics AX provides data that can help you track tax information. This cube can be useful only for Russia because it is based on Russian tables. This article provides details about the cube.

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

The Profit tax totals cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Profit tax totals cube:

  - Registers OLAP totals (RTax25OLAP)

## Tables and views

The Profit tax totals cube uses data from the following tables and views:

  - RTax25ProfitTableOLAP view

  - RTax25RegisterTransOLAP view

## Measures

The Profit tax totals cube includes the following measure groups.

## Balance

This measure group is based on the RTax25RegisterTransOLAP view and includes the following measures.

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
   
	 Balance
  </p> </td>
    <td> <p>
   
	 RTax25RegisterTransOLAP.ProfitAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Revenue or expense of certain type.
  </p> </td>
    <td rowspan="5"> <p>
   
	 Company
  </p> <p>
   
	 Expense code
  </p> <p>
   
	 Register
  </p> </td>
  </tr>
</table>


## Calculated measures

The Profit tax totals cube does not include any calculated measures.

## Key performance indicators

The Profit tax totals cube does not include any key performance indicators (KPIs).

## Security

The Profit tax totals cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accountant

  - Accounting manager

  - Accounting supervisor

  



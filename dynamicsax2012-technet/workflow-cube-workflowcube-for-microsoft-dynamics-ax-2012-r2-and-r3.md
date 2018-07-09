---
title: Workflow cube (WorkflowCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Workflow cube (WorkflowCube)
ms:assetid: 8dc2dc60-3dc1-42a2-bfbe-9775dd296ddd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710393(v=AX.60)
ms:contentKeyID: 49384285
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Workflow cube (WorkflowCube) for Microsoft Dynamics AX 2012 R2 and R3 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Workflow cube for Microsoft Dynamics AX provides data that can help you track the performance and degree of automation associated with business processes in your organization, which will enable you to identify processes that have become inefficient. This article provides details about the cube.

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

The Workflow cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The Workflow cube does not require any configuration keys.

## Tables and views

The Workflow cube uses data from the following tables and views:

  - WorkflowCubeElementLookup view

  - WorkflowCubeLookup view

  - WorkflowCubeTransaction view

## Measures

The Workflow cube includes the following measure groups.

## Workflow transactions

This measure group is based on the WorkflowCubeTransaction view and includes the following measures.

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
   
	 Workflow transactions count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of workflow transactions, such as work items processed and work items past due.
  </p> </td>
    <td rowspan="5"> <p>
   
	 WorkflowCubeElementLookup
  </p> <p>
   
	 Workflow cube lookup
  </p> <p>
   
	 Workflow transactions
  </p> <p>
   
	 Date (end date)
  </p> <p>
   
	 Date (start date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Duration
  </p> </td>
    <td> <p>
   
	 WorkflowCubeTransaction.Duration
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The duration of workflow transactions, for example, the workflow instance processing duration.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 MinDuration
  </p> </td>
    <td> <p>
   
	 WorkflowCubeTransaction.MinDuration
  </p> </td>
    <td> <p>
   
	 Min
  </p> </td>
    <td> <p>
   
	 The minimum duration of workflow transactions, for example, the minimum workflow instance processing duration.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 MaxDuration
  </p> </td>
    <td> <p>
   
	 WorkflowCubeTransaction.MaxDuration
  </p> </td>
    <td> <p>
   
	 Max
  </p> </td>
    <td> <p>
   
	 The maximum duration of workflow transactions, for example, the maximum workflow instance processing duration.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Workflow tracking status
  </p> </td>
    <td> <p>
   
	 WorkflowCubeTransaction.TrackingStatus
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of workflow transactions, for example, a count of the activated, completed, pending, canceled, stopped, and unrecoverable workflow instances.
  </p> </td>
  </tr>
</table>


## Calculated measures

The Workflow cube does not include any calculated measures.

## Key performance indicators

The Workflow cube does not include any key performance indicators (KPIs).

## Security

The Workflow cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accountant

  - Accounting manager

  - Accounting supervisor

  - Accounts payable manager

  - Budget manager

  - Chief executive officer

  - Chief financial officer

  - Compensation and benefits manager

  - Compliance manager

  - Customer service representative

  - Field service technician

  - Financial controller

  - Human resource assistant

  - Human resource manager

  - Information technology manager

  - Product designer

  - Project accountant

  - Project manager

  - Purchasing manager

  - Receiving clerk

  - Sales manager

  - Treasurer

  - Vendor account manager

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


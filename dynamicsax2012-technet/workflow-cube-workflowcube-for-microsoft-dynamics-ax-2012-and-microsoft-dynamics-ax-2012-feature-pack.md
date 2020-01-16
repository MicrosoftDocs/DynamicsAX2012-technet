---
title: Workflow cube (WorkflowCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Workflow cube (WorkflowCube)
ms:assetid: 05464503-9af8-4593-b61f-5de15e57b35e
ms:mtpsurl: https://technet.microsoft.com/library/Hh857319(v=AX.60)
ms:contentKeyID: 45688534
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Workflow cube (WorkflowCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Workflow cube provides data that can help you track the performance and degree of automation associated with business processes in your organization, which will enable you to identify processes that have become inefficient.

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

  



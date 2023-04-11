---
title: About service tasks
TOCTitle: About service tasks
ms:assetid: 936f02fb-e32e-43fa-ae57-5582128af12c
ms:mtpsurl: https://technet.microsoft.com/library/Aa498387(v=AX.60)
ms:contentKeyID: 36058582
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About service tasks 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use service tasks to describe the task to be completed during a service order. Both technicians and customers can see this information.

You create service tasks in the **Service tasks** form, and you associate service tasks with a specific service agreement or service order by creating service task relations. Every time that you create a service task relation, you can create the following:

  - Internal notes for the task, such as detailed technical requests for the task that are important for the technician to know.

  - External notes that the customer can see. These might provide a less technical explanation of the task that is being completed, according to the agreement between the customer and the service company.

When you have set up a service task relation between a service task and a service order or service agreement, you can specify this service task when you create service order lines or service agreement lines for the current service order or service agreement.

When you generate service orders from a service agreement, you can use the service tasks that are assigned to each service agreement line to group service order lines into service orders.

## Example

A technician must complete two jobs on a gearbox (service object GB-1234) at a customer site. A service agreement is created for the customer, and several transactions are associated with the jobs. The service agreement and service agreement lines for the two jobs are as follows:

## Service agreement

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Project</p></th>
<th><p>Service agreement</p></th>
<th><p>Description</p></th>
<th><p>Group</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>9012</p></td>
<td><p>000008_001</p></td>
<td><p>Inspection and routine replacement – GB-1234</p></td>
<td><p>Premium</p></td>
</tr>
</tbody>
</table>


## Service agreement lines

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Description</p></th>
<th><p>Transaction type</p></th>
<th><p>Service object</p></th>
<th><p>Service task</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Inspection and cleaning</p></td>
<td><p><strong>Hour</strong></p></td>
<td><p>GB-1234</p></td>
<td><p>I/C - GB1234</p></td>
</tr>
<tr class="even">
<td><p>Travel</p></td>
<td><p><strong>Expense</strong></p></td>
<td><p>GB-1234</p></td>
<td><p>I/C - GB1234</p></td>
</tr>
<tr class="odd">
<td><p>Materials</p></td>
<td><p><strong>Item</strong></p></td>
<td><p>GB-1234</p></td>
<td><p>I/C - GB1234</p></td>
</tr>
<tr class="even">
<td><p>Routine replacement</p></td>
<td><p><strong>Hour</strong></p></td>
<td><p>GB-1234</p></td>
<td><p>RR - GB1234</p></td>
</tr>
<tr class="odd">
<td><p>GR-1</p></td>
<td><p><strong>Item</strong></p></td>
<td><p>GB-1234</p></td>
<td><p>RR - GB1234</p></td>
</tr>
<tr class="even">
<td><p>GR-5</p></td>
<td><p><strong>Item</strong></p></td>
<td><p>GB-1234</p></td>
<td><p>RR - GB1234</p></td>
</tr>
</tbody>
</table>


The service agreement lines for the two jobs have two service tasks attached to them. The service tasks determine the transactions that belong to each job. In the first case, service task I/C - GB1234 identifies all the service agreement lines that are involved in the inspection and cleaning of object GB-1234. In the second case, service task RR - GB1234 identifies all the service agreement lines that are involved in completing a routine replacement job.

The service task relations that connect the service tasks to the specific agreement are as follows:

## Service tasks

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service task</p></th>
<th><p>Description</p></th>
<th><p>Internal note</p></th>
<th><p>External note</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>I/C - GB1234</p></td>
<td><p>Inspection of gearbox GB-1234</p></td>
<td><p>Visual and mechanical inspection and cleaning of gearbox GB-1234</p></td>
<td><p>Routine inspection of gearbox</p></td>
</tr>
<tr class="even">
<td><p>RR - GB1234</p></td>
<td><p>Routine replacement of parts in GB-1234</p></td>
<td><p>Routine service replacement of GR-1 and GR-5 components (for gearboxes manufactured before 2002, also replace GR-2 component)</p></td>
<td><p>Routine replacement of parts</p></td>
</tr>
</tbody>
</table>


## Grouping of service orders

When you create service orders automatically, you can use service tasks as grouping criteria. To group service orders by service tasks, define on the service agreement that service orders that are based on the service agreement should be grouped by service task ID as their initial grouping criteria.

## Group by service task

1.  Click **Service management** \> **Common** \> **Service agreements** \> **Service agreements**.

2.  On the **Setup** tab, select **By service task** in the **Combine service orders** field.

## See also

[Create service tasks](create-service-tasks.md)

[Create service task relations](create-service-task-relations.md)

  



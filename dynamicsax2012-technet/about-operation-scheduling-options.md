---
title: About operation scheduling options
TOCTitle: About operation scheduling options
ms:assetid: 6b8eec93-f1bc-446d-a798-6b2abbbb119e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571187(v=AX.60)
ms:contentKeyID: 36057992
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- schedule
- operation
- scheduling
---

# About operation scheduling options 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Operations scheduling is the expected schedule for a production order. It calculates the following information:

  - Start and end dates are set for the production order and each operation

  - Resources are assigned to operations

There are several settings that determine how production schedules are calculated. You can define these settings on the **General** tab in the **Operations scheduling** form.

The following information describes scheduling options.

## Scheduling direction and date

The scheduling direction is fundamental to the scheduling process. Production can be scheduled forward or backward from any date, depending on timing and scheduling needs.

  - **Forward from scheduling date** – Schedule production to start as early as possible. It can be started today, tomorrow, or from any given date in the future. The production is scheduled to start at the earliest date possible and is planned forward in time to the earliest possible end date.

  - **Backward from scheduling date** – Schedule production to start as late as possible. It is based on the date that the production must be completed and counts backward to the latest possible date that the production can be started without missing its target deadline.

## Finite capacity

Scheduling depends on the availability of the resources required to complete production. If there is not enough capacity, production orders can be delayed or even stopped.

If **Finite capacity** is applied to the operation scheduling, existing capacity reservations made on the resources are considered and that capacity is seen as unavailable. The production order is scheduled based on the availability of capacity on the resources needed.

Operations scheduling uses the specified sequence of operations to determine the order of operations in the production route. Operations scheduling reserves capacity on the resource groups based on the operation times defined on the production route. The capacity of the resource groups is the sum of available capacity on all the resources in the resource groups.

## Finite material

Scheduling also depends on the availability of the materials that are required for production. Insufficient component availability can also cause production delays. Scheduling can also be based on the use of materials by specifying the materials that must be available for production instead of those that are not critical. This is called scheduling with finite material. When you specify finite materials, production is scheduled based on whether materials are available.


> [!NOTE]
> <P>When optimizing on both capacity and materials, production is calculated to meet both restrictions. The availability of capacity and materials is considered and the production order’s operations cannot be scheduled to start until capacity and materials are available at the same time and in the required quantities.</P>



## References

References, which are also known as subproductions when dependent on production orders, can be scheduled as part of the scheduling of a production order. You can also decide to synchronize references with the production order. If this option is selected, the dates of the subproductions are moved and aligned when changes are made to the production order’s schedule.

If a production order has one or more subproductions, you might want to schedule these together with the main production. The main production then cannot be started until the related subproductions have finished.

## Resource parameter

  - **Efficiency percentage** – You can set up an efficiency percentage when you create a resource. An efficiency percentage reduces or increases the throughput of the resource and therefore the time that is reserved for the resource. The lead time for the operations that use the resource is also increased or decreased accordingly. For more information, see the **Efficiency percentage** field description in [Resources (form)](https://technet.microsoft.com/en-us/library/aa557962\(v=ax.60\)).

## See also

[Production - Operations scheduling (class form)](https://technet.microsoft.com/en-us/library/aa571353\(v=ax.60\))

[Resources (form)](https://technet.microsoft.com/en-us/library/aa557962\(v=ax.60\))

[Create and maintain operations resources](create-and-maintain-operations-resources.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


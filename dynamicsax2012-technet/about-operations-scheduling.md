---
title: About operations scheduling
TOCTitle: About operations scheduling
ms:assetid: 12c8e85f-d0f2-4b26-8137-e0d503e73151
ms:mtpsurl: https://technet.microsoft.com/library/Aa496589(v=AX.60)
ms:contentKeyID: 44080946
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- plan
- planning
- resources
- schedule
- operation
- production
- operations
- manufacturing
- scheduling
audience: Application User
ms.search.region: Global
---

# About operations scheduling 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can schedule production at the operation level and the job level. Scheduling at the operation level is the less detailed method, and provides a general estimate of the production process over time. Operations scheduling does not explode the operations for the production route into jobs.

If you want to include more detail in the scheduling, such as information about current capacity, you can run job scheduling after operations scheduling. You can also run a job scheduling only. Job scheduling is typically used to schedule individual jobs on the shop floor for an immediate or short-term time frame. For more information see [Production - Job scheduling (class form)](https://technet.microsoft.com/library/aa584348\(v=ax.60\)).

## Components of operations scheduling

The main components of operations scheduling are the scheduling direction, the capacity of resources, and materials optimization. By using operations scheduling, you can do the following:

  - Control the planning method by scheduling forward or backward from a given date.

  - Optimize the use of resources by scheduling productions based on the capacity of the resources. This also helps identify when to use alternative resources.

  - Optimize the use of materials by scheduling productions based on the availability of the required materials.

  - Schedule and synchronize reference productions. The dates of the reference productions are adjusted when changes are made to the production order’s schedule.

You must estimate the cost of a production order before you can run operations scheduling. If you have not run an estimate, it is run automatically before the operations scheduling process is initiated.

An operations schedule specifies the following:

  - The product that is planned for production

  - The configuration of the product

  - The quantities involved in the production

  - The dates that the production will start and end

  - The capacity reservations for the resources that perform the production activities

  - The setup time, process time, and run time are set for operations in the production

After you run operations scheduling, the status of the production order is **Scheduled**, and all operations are scheduled in the order that is specified by the production route. However, only the duration of the operation is considered. Start times and end times are not scheduled.

## Scheduling direction and date

The scheduling direction is fundamental to the scheduling process. Production can be scheduled forward or backward from any date, depending on timing and scheduling requirements.

  - **Forward from the scheduling date** – Schedule production to start as early as possible. It can be started today, tomorrow, or on any date in the future. The production is scheduled forward in time to the earliest possible end date.

  - **Backward from the scheduling date** – Schedule production to start as late as possible. Backward scheduling is based on the date that the production must be completed. The schedule counts backward from that date to the latest possible date that the production can be started and still be completed on time.

## Resource scheduling

When you run an operations schedule, each operation in the production route is scheduled for the resource that is specified for the operation. In addition, the duration of each operation is specified on the production route. If a resource group is specified for an operation, the scheduling reserves capacity on the group. However, unlike job scheduling, operations scheduling does not select the specific resources in the group. For more information, see [Resource groups (form)](https://technet.microsoft.com/library/hh227450\(v=ax.60\)).

If you are working with finite capacity, the schedule depends on the availability of the resources that are required to complete production. Operations scheduling follows the sequence of operations that is specified on the production route.

The scheduling reserves capacity on the resource groups based on the operation times that are defined on the production route. The sum of available capacity on the resources involved determines the capacity for the resource group. Capacity reservations that already exist for the resources are considered as unavailable capacity. If available capacity is insufficient for production, the production orders can be delayed or even stopped.

You can also specify the efficiency that you expect from the resources that are involved in the production. You specify the efficiency as a percentage on the resource. The efficiency percentage adjusts the throughput of the resource. This affects the time that is reserved for the resource. The lead times for the operations that use the resource are also adjusted accordingly. For more information, see [Resources (form)](https://technet.microsoft.com/library/aa557962\(v=ax.60\)).

## Operations scheduling and master planning

The operations schedule also drives master planning and determines material requirement calculations. Operations scheduling considers the following:

  - **Backlogged productions** – Products that are planned, released, or started

  - **Material availability** – Inventory, subproduction, suppliers, and vendors

  - **Capacity availability** – Resources that are required for production

## Cancellations

When you run operations scheduling, you can cancel certain parts of the routing. These include the queue time, setup time, process time, overlap time, and transport times. For more information, see [Production - Job scheduling (class form)](https://technet.microsoft.com/library/aa584348\(v=ax.60\)).

## Finite materials

If you are working with finite materials, scheduling also depends on the availability of the materials that are required for production. If available components are not sufficient for the production, production can be delayed. You can base scheduling on the use of materials by specifying the materials that must be available for production. When you optimize on both resource capacity and the availability of materials, production is calculated according to these restrictions. A production order cannot be scheduled to start until capacity and materials are available at the same time and in the required quantities.

## See also

[Run operations scheduling](run-operations-scheduling.md)

[Production - Operations scheduling (class form)](https://technet.microsoft.com/library/aa571353\(v=ax.60\))

[Released product details (form)](https://technet.microsoft.com/library/aa615563\(v=ax.60\))

  



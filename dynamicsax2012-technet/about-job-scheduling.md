---
title: About job scheduling
TOCTitle: About job scheduling
ms:assetid: 5222e57e-0ee5-4c9a-8a3d-b1c03f3e3fbd
ms:mtpsurl: https://technet.microsoft.com/library/Aa548918(v=AX.60)
ms:contentKeyID: 44080982
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- plan
- planning
- schedule
- job
- production
- jobs
- scheduling jobs
audience: Application User
ms.search.region: Global
---

# About job scheduling 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Job scheduling is a more detailed form of scheduling than operations scheduling. You can use job scheduling to schedule individual jobs or shop orders and to control the manufacturing environment. It breaks down each operation into its individual tasks or jobs. These jobs are then assigned to the operations resources that will perform them.

## Job scheduling

Job scheduling also enables you to synchronize all jobs that are referenced by the selected job. You can specify a starting date and time or finishing date and time for the job, and then run scheduling. The time that you specify can be the starting time or the finishing time depending on the scheduling direction. This is useful, for example, when a job can be run only on one machine at a time, or to optimize the job that is run for each resource.

For more information, see [Dispatching (form)](https://technet.microsoft.com/library/aa552714\(v=ax.60\)).

## Tasks in the job scheduling process

The job scheduling process includes the following tasks:

  - Split operations into jobs.

  - Schedule jobs that are based on the dates and times for the resources that are specified for the related operation.

  - Calculate starting times and ending times for each job. You can use finite capacity to make sure that there are no overlapping times.

  - Determine which resources in the resource group to run the job on. To make this determination, a resource group must be specified for an operation. The job scheduling selects the resources or resource groups based on the shortest lead time and considers any previous reservations on the resources.

  - Explode operations into jobs when you run job scheduling. The jobs are scheduled by date and time according to the order that is specified by the production route. The setup of the operation determines which jobs to explode during the scheduling process. The route group that is assigned to the operation controls whether jobs are generated. A job is generated only if it has a specific duration. For example, a transport time job is generated if a transport time was specified for the selected operation.

## Scheduling direction

You can schedule jobs either forward or backward.

  - **Forward** – Use the forward scheduling direction to start the production as early as possible. This is also known as the push method, because the production is being pushed forward through the production process. The production is scheduled to start and end on the earliest possible dates.

  - **Backward** – Use the backward scheduling direction to start the production as late as possible. This is also known as the pull method, because it is based on the date that the production must be completed. Backward scheduling counts backward to the latest possible date that the production can be started without missing its target deadline.

## Finite capacity

You can schedule jobs by using finite capacity. When you use finite capacity, the capacity that is scheduled cannot be larger than the capacity that is available for the resource. Available time is defined as the time interval when the resource is available, and where there are no other reservations on capacity.

Scheduling that is based on finite capacity makes sure that start times and end times for an operation on a specific date do not overlap. The resource capacity that is already reserved is considered, and overlaps between those start times and end times are considered. Finite capacity determines the amount of capacity that must be available for the resource for optimal use, balanced with calculating the shortest possible lead time between operations.

## Finite materials

Job scheduling that is based on finite materials makes sure that the required materials are available when the operation starts. The coverage rules for items define these limits. Scheduling uses a requirement explosion to determine when the component items are available. If you schedule without setting finite materials, the system assumes that all items are available when they are required.

## Finite properties

Job scheduling that is based on special properties requires that properties be specified for the operations on the production route. These properties must be fulfilled to reserve capacity. For more information, see [Properties (form)](https://technet.microsoft.com/library/aa634336\(v=ax.60\)).

## References

Job scheduling schedules all productions that are referenced by the current production. If a production has one or more subproductions, the subproductions should be scheduled at the same time as the main production, because the main production cannot be started until the related subproductions are finished.

## Schedule resources

The scheduling engine examines combinations of resources to identify those that can satisfy requirements. You can specify selection criteria by selecting one of the following values in the **Primary resource selection** field in the **Scheduling parameters** form:

  - **Duration** – The scheduling engine selects the resource that has the shortest lead time.
    

    > [!NOTE]
    > <P>Scheduling by duration can cause decreased performance when the same resource group contains many resources and secondary operations are used. You can schedule a maximum of 32 resources per operation. If you exceed this quantity, an Infolog message is displayed, and the job scheduling does not find the best alternative resource.</P>



  - **Priority** – The scheduling engine selects the resource that has the highest priority when two or more resources have identical capabilities and levels. The resource that has the lowest numeric value in this field has the highest priority.

When job scheduling is run, the system plans the resources based on the limitations that are defined in the resource parameters. You can control the capacity of the resources by using calendar settings. The system calculates loads for resources during the scheduling process.


> [!NOTE]
> <P>For productions that use the operations scheduling function, you can run job scheduling after operations scheduling. If you are not using operations scheduling, you can run job scheduling alone.</P>



## Maximum capacities for resources per job order

Resources are assigned to jobs through job scheduling. You can establish maximum capacities for resources per job order.

For example, you can set up the system to schedule no more than 50 percent of total capacity for a production order. This allows you more control over the scheduling of resources on the job scheduling level, which prevents problems from arising when not enough capacity is available to perform simultaneous productions.

## Resource efficiency

Job scheduling considers the efficiency percentages that are specified for the resources. Efficiency percentages reduce or increase the time that is reserved for the resource. Consequently, lead time is also increased or decreased. The calculation is as follows:

  - Scheduling time = Time \* 100 / Efficiency percentage, where time includes both the run time and setup time.

## See also

[Run job scheduling](run-job-scheduling.md)

[Set up job scheduling (form)](https://technet.microsoft.com/library/aa553462\(v=ax.60\))

[Production - Job scheduling (class form)](https://technet.microsoft.com/library/aa584348\(v=ax.60\))

  



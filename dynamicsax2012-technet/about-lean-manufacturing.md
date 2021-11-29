---
title: About lean manufacturing
TOCTitle: About lean manufacturing
ms:assetid: ead08595-169c-442e-9d88-f8f3f91e4a32
ms:mtpsurl: https://technet.microsoft.com/library/Hh227483(v=AX.60)
ms:contentKeyID: 36059859
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- production flow activities
- lean manufacturing
- production flows
- set up lean manufacturing
- kanban boards
- kanban rules
- lean architecture
- lean manufacturing concepts
- kanban jobs
- lean replenishment strategy
- lean methodology
- model business processes
- lean pull system
- lean tools
- lean operations
- lean manufacturing foundation
audience: Application User
ms.search.region: Global
---

# About lean manufacturing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an overview and description of the lean manufacturing features in Microsoft Dynamics AX 2012.

Lean manufacturing offers tools that you can use to model lean operations. These tools support and promote the following concepts and business activities:

  - Create a lean manufacturing foundation by modeling manufacturing and logistics processes as production flows.

  - Implement a lean pull system by using kanbans to signal demand requirements.

  - Monitor and maintain kanban jobs by using the kanban boards.

The lean manufacturing architecture in Microsoft Dynamics AX 2012 consists of production flows, activities, and kanban rules. These structures are fully integrated with Microsoft Dynamics AX 2012 processes. You can use lean manufacturing in a mixed-mode manufacturing environment that combines various supply, production, and sourcing strategies. These strategies include production orders, batch orders for process industries, purchase orders, and transfer orders.


> [!IMPORTANT]
> <P>You can use Microsoft Dynamics AX 2012 to support the implementation of lean manufacturing. However, a successful implementation of lean principles depends on the internal business processes that you use, and the actual production conditions and environment.</P>



## Modeling manufacturing and logistics processes as production flows

To create a lean manufacturing foundation, model the manufacturing and logistics processes as production flows. This activity consists of the following tasks:

1.  Identify the processes for which you want to implement a lean replenishment strategy, and then model these processes as production flows. You can then analyze and streamline the processes. One of the goals of a lean implementation is to reduce waste by improving the flow of material and information.

2.  Define a production flow as a sequence of activities that describes the flow of material. A transfer activity defines the movement of a product or products from one location to another. A process activity defines a value-added operation that is applied to a product.

3.  Create a version of the production flow that defines the requirements for takt time. These requirements are used to calculate the cycle times of each activity in the production flow. You can create multiple versions of production flows, and then use these versions to improve processes.

## Using kanbans to signal demand requirements

A pull system produces goods only when goods are needed. This practice reduces delivery lead times and excess inventory. You can use kanbans to plan, track, and process requirements that are based on production flows. To create a kanban framework, create kanban rules that define when kanbans are created, and how the requirements are fulfilled. You can create two types of kanban rules. Manufacturing rules create process kanban jobs, and withdrawal kanban rules create transfer kanban jobs.

You can set up the following replenishment strategies:

  - Fixed quantity kanban rules replenish material handling units that are consumed from inventory. You can use fixed quantity kanban rules to plan the flow of material that supplies work cells.
    
    When you create fixed quantity kanban rules, you can calculate the optimal kanban quantities and the product quantities that are used. This calculation is based on the product demand that occurs during a specific period.

  - Scheduled kanban rules replenish requirements that are calculated by master planning. Master planning generates planned kanbans.

  - Event kanban rules replenish requirements that originate from sales order lines, production BOM lines, kanban lines, and minimum inventory settings. When event kanbans are generated, they are pegged to the source requirements.

When kanbans are created, one or more kanban jobs are generated based on the kanban flow activities that are defined in the kanban rules.

## Monitoring and maintaining kanban jobs by using the kanban boards

Lean manufacturing provides visibility into the current status of manufacturing and logistics activities that are governed by the kanban rules. As a result, you can plan and prioritize the following tasks:

  - Gain an overview of the current kanban job schedule.

  - Plan and reschedule kanban jobs.

  - Track the status of kanban jobs.

The following list describes the specialized kanban boards:

  - Kanban schedule board – This board provides an overview of the kanban jobs that are scheduled for a work cell. The board displays kanban jobs and their status. The jobs are grouped according to the planning periods that are defined in the production flow model. The board also displays the capacity percentage for each planning period, so that you can monitor the scheduled load. You can change the status of kanban jobs, reschedule kanban jobs to different planning periods, and perform other tasks.

  - Kanban board for transfer jobs – This board provides an overview of the current transfer jobs. You can update and register picking lists, start and complete transfer jobs, and perform other tasks.

  - Kanban board for process jobs – This board provides an overview of the current production status of a work cell. The tasks that users can perform are grouped on tabs that support different production-related roles and the main activities of those roles. You can schedule upcoming jobs, prepare picking lists, monitor kanban levels in supermarkets, register the status of kanban jobs, and perform other tasks.

## Kanban jobs and integration with Microsoft Dynamics AX 2012 processes

Kanban jobs are fully integrated with current processes for inventory transactions in Microsoft Dynamics AX 2012.

  - You can perform picking activities to replenish material that is used to fulfill the requirements of kanban jobs.

  - You can print kanban cards, circulating kanban cards, and picking lists to support the use of kanbans. These documents are used to represent, track, and register kanban jobs in the warehouse and on the production floor.

  - You can register the picking and transfer activities in inventory by scanning bar codes.

In addition, lean manufacturing supports the purchasing and invoicing processes for services that are referenced by subcontracted activities.

  - You can assign purchase agreement lines and services to subcontracted activities.

  - You can create periodic purchase orders and receipt advices to support the purchase and invoicing of the services.

## See also

[Production flows (form)](https://technet.microsoft.com/library/hh208997\(v=ax.60\))

[Create new plan activity (form)](https://technet.microsoft.com/library/hh227522\(v=ax.60\))

[Kanban rules (form)](https://technet.microsoft.com/library/hh227370\(v=ax.60\))

[Kanban schedule board (form)](https://technet.microsoft.com/library/hh597153\(v=ax.60\))

[Kanban board for transfer jobs (form)](https://technet.microsoft.com/library/hh781100\(v=ax.60\))

[Kanban board for process jobs (form)](https://technet.microsoft.com/library/hh781101\(v=ax.60\))

  



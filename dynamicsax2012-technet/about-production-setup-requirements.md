---
title: About production setup requirements
TOCTitle: About production setup requirements
ms:assetid: f4909a96-bdd2-4fb5-be4d-c01ccaf8dace
ms:mtpsurl: https://technet.microsoft.com/library/Aa551641(v=AX.60)
ms:contentKeyID: 37832550
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About production setup requirements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Production control** module integrates with features in other modules in Microsoft Dynamics AX. This interconnectivity enables you to change production orders and make sure that they are automatically updated in all other related processes and calculations in the system. The following setup processes are listed in the order that they should occur in.

## Required baseline setup in other modules

Information in other modules must be set up before you can work with the **Production orders** module. This setup includes the following:

  - Set up general company information.

  - Set up the general ledger.

  - Define item groups.

  - Set up ledger accounts for item groups.

  - Set up the inventory item table in the **Inventory management** module.

  - Create bills of material (BOMs) and BOM versions in the **Inventory management** module.

## Required calendar and resource setup

Before you use the **Production control** module, open the **Organization administration** module, and create and define the calendar and operations resources in the following sequence:

1.  **Working time templates** – Set up working time templates to define the times that are available for production scheduling. Set up templates before you create working time calendars. For more information, see [Create working time templates](create-working-time-templates.md).

2.  **Calendars** – Set up working time calendars to define the days of the year that are available for production scheduling. For more information, see [Create working time calendars](create-working-time-calendars.md).

3.  **Resource groups** – Set up resource groups to group the operations resources to gain an overview of any free capacity when you run scheduling. You do not have to set up resource groups before you set up operations resources. However, we recommend that you understand how to group resources when you set up the **Production control** module. For more information, see [Set up and define resource groups for operations resources](set-up-and-define-resource-groups-for-operations-resources.md).

4.  **Resources** – Set up operations resources to define the resources that are used to complete the production process and plan for capacity. For more information, see [Create and maintain operations resources](create-and-maintain-operations-resources.md).

## Required production parameters setup

**Production control parameters** – Set up basic production parameters to define how the application handles and processes production orders. Define how they are created, estimated, scheduled, and consumed. You can also select what kind of feedback you want, and how cost accounting is conducted. For more information, see [Set up production control parameters](set-up-production-control-parameters.md).

## Required journal name identification

**Production journal names** – Identify the production journal names that you want to use to record and post transactions.

## Setup if you use operations

Operations represent the specific activities that occur to produce the finished product.


> [!NOTE]
> <P>You have to know the kinds of activities that are required to produce your item, the order and priorities of these activities, and which and how many resources are involved.</P>



1.  **Operations** – Set up operations to represent the tasks that must be completed to produce the finished item. For more information, see [Set up operations for production](set-up-operations-for-production.md).

2.  **Relations** – Set up operation relations to establish detailed properties. To define operation relations, click the **Relations** button. For more information, see [Set up operations for production](set-up-operations-for-production.md).

## Setup if you use routes

If you are working with routes, operations must be defined for each production route that you set up. The route represents the path that the item takes from operation to operation, from the start of the production process to the end.

1.  **Cost categories** – Set up cost categories to define the cost per hour of specified processes and setup times. For more information, see [Create cost categories](create-cost-categories.md).

2.  **Cost groups** – Set up cost groups to create and maintain different types of costing.

3.  **Route groups** – Set up route groups to define parameters that pertain to groups of routes. You must set up route groups before creating production routes. For more information, see [Create route groups](create-route-groups.md).

4.  **Routes** – Set up production routes, and define default settings to control scheduling, costing and pricing of route operations, and progress reporting. For more information, see [Create and update production routes](create-and-update-production-routes.md).

5.  **Routes** – Set up route versions to enable item variations in production. For more information, see [Create route versions](create-route-versions.md).

## Define optional, advanced settings

1.  **Production groups** – Set up production groups to establish relationships between the production order and ledger accounts. The ledger accounts are used to post or group orders for reporting. For more information, see [Create production groups](create-production-groups.md).

2.  **Production pools** – Create production pools to group production orders for processing urgent production orders, or for deleting and posting groups of orders. For more information, see [Create production pools](create-production-pools.md).

3.  **Properties** – Define properties to create special attributes that you can assign to your resources to control the sequence of productions. These attributes are connected to the working time template. For more information, see [Set up properties for operations resources](set-up-properties-for-operations-resources.md).

  



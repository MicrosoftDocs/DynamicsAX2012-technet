---
title: About the production process
TOCTitle: About the production process
ms:assetid: a3144f75-3c8f-4cb2-a495-f7a1eee87d9c
ms:mtpsurl: https://technet.microsoft.com/library/Aa571840(v=AX.60)
ms:contentKeyID: 37822153
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- production orders
- production
audience: Application User
ms.search.region: Global
---

# About the production process 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The production of items, sometimes also known as the production life cycle, follows specific steps that are needed to complete the manufacture of an item. The life cycle begins with the creation of the production order and ends with a finished, manufactured item that is ready for the customer. Each step in the life cycle requires different kinds of information to complete the process. When each step is completed, the production order reflects this by showing a change in production status.

The **Production control** module in Microsoft Dynamics AX is linked to other modules. These include **Inventory management**, **General ledger**, and **Organization administration**. This integration supports the information flow that is required to complete the manufacturing of a finished item.

## Overview of the production life cycle

1.  **Created** – You can create a product order manually, or you can set up the system to create one from a sales order or master planning schedule.  

2.  **Estimated** – You can calculate estimates for material and resource consumption. You can also create inventory transactions for raw materials with the status **On order**. You can create receipt transactions for a bill of materials (BOM) that has the status **Ordered**. You can also create purchase orders and subproductions for the production order. Items are reserved, and the price of the finished goods is calculated, based on parameter settings.  

3.  **Scheduled**– You can schedule production based on operations, individual jobs, or both.
    
      - **Operations scheduling** – This scheduling method provides a rough, long-term plan. By using this method, you can assign start and end dates to production orders. If the production orders are attached to route operations, you can assign them to cost center groups.
    
      - **Job scheduling** – This scheduling method provides a detailed plan. Each operation is broken down into individual jobs with specific dates, times, and assigned operations resources. If finite capacity is used, jobs are assigned to operations resources based on availability. You can view and change the schedule in a Gantt chart.

4.  **Released** – You can release the production order when the schedule is finished. You can also print the production order documents, such as the job card, route card, and route job. When the production order is released, the status of the order changes to indicate that the production can begin.  

5.  **Started** – After a production order is started, you can post costs against the order. The system can be configured to estimate material and route costs that are allocated to the order when the order is started. This allocation is known as preflushing or autoconsumption. You can manually allocate material to the order by creating picking list journals. You can also manually allocate labor and other route costs to the order. If you are using operations scheduling, you can allocate these costs by creating a route card journal. If you are using job scheduling, you can allocate these costs by creating a job card journal.  

6.  **Reported as finished** – When a production order is reported as finished, the quantity of the finished goods completed is updated in the **Inventory management** module. If you are using work-in-process (WIP) accounting, a ledger journal is made to reduce the WIP accounts and increase the inventory of the finished goods. The journal uses the standard cost from the item form. When the cost of a production order is calculated, the actual cost of the production is posted. The posting that occurs during reporting as finished is reversed. If the material and labor costs that are associated with a production are not already allocated in a journal or by preflushing, they can be automatically allocated by back-flushing. This involves the post-deducting of inventory transaction processes. If the production order is complete, select the **End job** check box to change the remaining status to **Ended**. Otherwise, the field is left empty to allow for the reporting of additional quantities that are produced.  

7.  **Ended** – Before production is ended, actual costs are calculated for the quantity that was produced. All estimated costs of material, labor, and overhead are reversed and replaced with actual costs.  
       
    If you select the **End job** check box when you run the cost calculation, the production order status changes to **Ended**. This status prevents any additional costs from being unintentionally posted to a completed production order.

## See also

[About production order status](about-production-order-status.md)

  



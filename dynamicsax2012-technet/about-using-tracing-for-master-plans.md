---
title: About using tracing for master plans
TOCTitle: About using tracing for master plans
ms:assetid: e2858109-05cd-4818-b794-ec690165983a
ms:mtpsurl: https://technet.microsoft.com/library/JJ677369(v=AX.60)
ms:contentKeyID: 49384145
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- log
- plan
- schedul
audience: Application User
ms.search.region: Global
---

# About using tracing for master plans 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can enable tracing for master planning if you want to view information about the causes behind the outcome of a complete master planning run, or about the explosion of a particular planned order. Before you can use tracing for a complete master planning run, you must set up a Data Collector Set in Windows Performance Monitor. For more information, see [Set up tracing for master plans](set-up-tracing-for-master-plans.md).

The following are examples of how you can use the tracing information:

  - View relations between the actions on planned orders to optimize the supply chain and inventory reservations.

  - View relations to orders that are already approved. You can focus on automatically firming derived requirements, and then prioritize orders more accurately.

  - Simulate planning results to determine whether the planning parameters are optimal.

  - Identify how information such as production dates, quantities, and priorities for an order were determined.

## Viewing log information for a specific planned order

You can view details about futures and actions for a selected planned order. In the **Explosion** form, tracing information is available on the **Explanation** tab in the upper pane. Tracing occurs when you explode a planned order. To start tracing for the planned order, click **Update**, and then select the **Enable trace** check box.

You can use the **Find text** field to search the log for specific information. Search results are highlighted in the tree.

## Viewing log information for a complete master planning run

If tracing is enabled, details about a complete master planning run are available in Event Viewer in Windows. Tracing information is recorded in a searchable .etl log file. In Event Viewer, expand the **Saved Logs** node, and then select the appropriate log file. Select the event to view. Information is displayed on the **General** and **Details** tabs in the lower pane.

Event IDs 107 (ReqExplanation) and 108 (ReqExplanationDetails) are specific to the tracing features in Microsoft Dynamics AX. Event ID 108 provides full details about the master planning run.

## See also

[About action messages](about-action-messages.md)

  



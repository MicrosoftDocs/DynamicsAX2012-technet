---
title: About production order status
TOCTitle: About production order status
ms:assetid: 5fd1dffe-02d4-478a-89e1-d89a68d08d17
ms:mtpsurl: https://technet.microsoft.com/library/Aa571100(v=AX.60)
ms:contentKeyID: 36057602
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About production order status 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Manufactured items move through the production process sequentially. The sequence starts when a production order is created and ends when the product is ready for shipment. In Microsoft Dynamics AX, each sequential step is associated with a specific status. The status reflects where the item is in the production life cycle.

You can monitor the activities in each step of the production and move the production to the next status when you are ready. If you omit intervening steps when you change the status, the system automatically runs the necessary missed steps for you.

## Overview of production order statuses

  - **Create** – Status of the production order when it is created.

  - **Estimate** – Status of the production order after you run a material and cost estimation.

  - **Scheduled** – Status after you run operation or job scheduling.

  - **Release** – Status when the production order is scheduled and has been released to production.

  - **Start** – Status of the production order when production starts.

  - **Report as finished** – Status of the production order when production is finished and ready for final action.

  - **End** – Status of the production order after final costs have been applied, the item is complete, and the order is no longer active.


> [!NOTE]
> <P>You can change information about production orders up to and including those with <STRONG>Start</STRONG> status. However, if the changes affect cost estimates or scheduling, you must run <STRONG>Estimation</STRONG> and scheduling again to update the information.</P>



## See also

[About reversing production order status](about-reversing-production-order-status.md)

[About the production process](about-the-production-process.md)

  



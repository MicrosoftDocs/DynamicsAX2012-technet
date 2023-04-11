---
title: Configure and schedule data distribution for retail stores (Retail essentials)
TOCTitle: Configure and schedule data distribution for retail stores (Retail essentials)
ms:assetid: e1724759-d67a-446a-a693-c5273187e0de
ms:mtpsurl: https://technet.microsoft.com/library/Dn736970(v=AX.60)
ms:contentKeyID: 62200465
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Configure and schedule data distribution for retail stores (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Retail Scheduler is the mechanism that coordinates communication and data distribution between Retail essentials and stores.

The topics in this section contain information about how to configure and schedule data distribution.

[Enter parameters for Retail Scheduler (Retail essentials)](enter-parameters-for-retail-scheduler-retail-essentials.md)

[Schedule Retail data distribution (Retail essentials)](schedule-retail-data-distribution-retail-essentials.md)

[Set up connection profiles (Retail essentials)](set-up-connection-profiles-retail-essentials.md)

[Troubleshoot data distribution issues (Retail essentials)](troubleshoot-data-distribution-issues-retail-essentials.md)

To configure and schedule retail data distribution in Retail essentials, complete the following procedures:

1.  Set up connection profiles that enable the components of Retail essentials to communicate with each other. For more information, see [Set up connection profiles (Retail essentials)](set-up-connection-profiles-retail-essentials.md).

2.  Set up channel data groups. A channel data group is a group of one or more retail channel databases. When you run a distribution schedule, a data package is generated for each data group. All channel databases in a data group subscribe to the same data. A database can belong to only one data group. For more information, see [Create a channel data group (Retail essentials)](create-a-channel-data-group-retail-essentials.md).

3.  Set up jobs in Retail Scheduler to distribute the data. Scheduler jobs are the mechanism that distributes data to and from locations. Jobs consist of subjobs, which specify the tables and table fields that contain the data to distribute. For more information, see [Configure jobs and subjobs in Retail Scheduler (Retail essentials)](configure-jobs-and-subjobs-in-retail-scheduler-retail-essentials.md).

4.  Set up distribution schedules. The distribution schedule is used to run the data transfer, either manually or through a batch job that is scheduled in Retail essentials. A distribution schedule can contain one or more channel data groups, and one or more scheduler jobs. For more information, see [Schedule and run jobs in Retail Scheduler (Retail essentials)](schedule-and-run-jobs-in-retail-scheduler-retail-essentials.md).

The following illustration shows the relationships between jobs, channel data groups, and distribution schedules.

![How Retail Scheduler works](images/JJ679920.RetailScheduler(en-us,AX.60).gif "How Retail Scheduler works")

  



---
title: Configure and schedule retail data distribution
TOCTitle: Configure and schedule retail data distribution
ms:assetid: 65b29a72-c7a7-453e-8f97-8281548df0a6
ms:mtpsurl: https://technet.microsoft.com/library/JJ679920(v=AX.60)
ms:contentKeyID: 49557902
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure and schedule retail data distribution 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Retail Scheduler is the mechanism that coordinates communication and data distribution between Microsoft Dynamics AX and stores.

## Retail data distribution in AX 2012 R3

To configure and schedule retail data distribution in AX 2012 R3, you must complete the following procedures:

1.  Set up connection profiles that enable the components of Retail to communicate with each other. For more information, see [Set up connection profiles](set-up-connection-profiles.md).

2.  Set up channel data groups. A channel data group is a group of one or more retail channel databases. When you run a distribution schedule, a data package is generated for each data group. All channel databases in a data group subscribe to the same data. A database can belong to only one data group. For more information, see [Create a channel data group](create-a-channel-data-group.md).

3.  Set up jobs in Retail Scheduler to distribute the data. Scheduler jobs are the mechanism for distributing data to and from locations. Jobs are made up of subjobs, which specify the tables and table fields that contain the data to distribute. For more information, see [Configure jobs and subjobs in Retail Scheduler](configure-jobs-and-subjobs-in-retail-scheduler.md).

4.  Set up distribution schedules. The distribution schedule is used to run the data transfer, either manually or by scheduling a batch job in Microsoft Dynamics AX. A distribution schedule can contain one or more channel data groups and one or more scheduler jobs. For more information, see [Schedule and run jobs in Retail Scheduler](schedule-and-run-jobs-in-retail-scheduler.md).

The following illustration shows the relationships between jobs, channel data groups, and distribution schedules.

![Retail Scheduler process in AX 2012 R3](images/JJ679920.RetailSchedulerR3(en-us,AX.60).gif "Retail Scheduler process in AX 2012 R3")

## Retail data distribution in AX 2012 R2 and AX 2012 Feature Pack

To configure and schedule retail data distribution in AX 2012 R2 or AX 2012 Feature Pack, you must complete the following procedures:

1.  Set up connection profiles that enable the components of Retail to communicate with each other. For more information, see [Set up connection profiles](set-up-connection-profiles.md).

2.  Set up data distribution locations and distribution location lists. A distribution location is a record that links a store to the database. Distribution locations represent the destinations of distributed data. A distribution location list is a group of distribution locations. For example, you can set up a distribution location list per region or per time zone.
    
    For more information, see [Create distribution locations for retail databases](create-distribution-locations-for-retail-databases.md) and [Set up a distribution location list](set-up-a-distribution-location-list.md).

3.  Set up action filters and table distributions. Action filters specify which tables and fields are monitored for changes. When a record in one of the tables is modified, the distribution settings for the table determine whether the modified record is distributed, and whether records in child tables are distributed together with that record.
    
    For more information, see [Set up action filters for Retail data](set-up-action-filters-for-retail-data.md) and [Set up or modify table distributions](set-up-or-modify-table-distributions.md).

4.  Set up jobs in Retail Scheduler to distribute the data. Scheduler jobs are the mechanism for distributing data to and from locations. Jobs are made up of subjobs, which specify how to distribute the data in selected tables and selected table fields. For more information, see [Configure jobs and subjobs in Retail Scheduler](configure-jobs-and-subjobs-in-retail-scheduler.md).

5.  Set up distribution schedules. The distribution schedule is used to run the data transfer, either manually or by scheduling a batch job in Microsoft Dynamics AX. A distribution schedule can contain one or more distribution location lists and one or more scheduler jobs. For more information, see [Schedule and run jobs in Retail Scheduler](schedule-and-run-jobs-in-retail-scheduler.md).


> [!WARNING]
> <P>Setting up data distribution is a complex task. We recommend that you conduct tests to determine the distribution structure and settings that provide the best results and performance for your organization.</P>



The following illustration shows the relationships between jobs, subjobs, distribution locations, and schedules.

![How Retail Scheduler works](images/JJ679920.RetailScheduler(en-us,AX.60).gif "How Retail Scheduler works")

  



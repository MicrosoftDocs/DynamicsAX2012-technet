---
title: Configure an AOS instance as a batch server
TOCTitle: Configure an AOS instance as a batch server
ms:assetid: 74687f8d-fd55-4a99-bea9-835655905fb4
ms:mtpsurl: https://technet.microsoft.com/library/Gg731831(v=AX.60)
ms:contentKeyID: 35132680
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Configure an AOS instance as a batch server 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to configure an Application Object Server (AOS) instance to function as a batch server.

A batch server is an AOS instance that processes batch jobs. Batch jobs are used to run tasks at a specified time and on a specified AOS.

It is assumed that you are familiar with the concepts that are described in [Batch server overview](batch-server-overview.md).

## Configuring an AOS instance as a batch server

The first AOS instance that is set up in an environment is automatically designated as a batch server. You can designate multiple AOS instances as batch servers to increase throughput and reduce the time that is required to run batches.

When you set up a batch server, you can specify the times that the server is available for batch processing. We recommend that you exclude a server from batch processing when the server is busy with regular transaction processing. For example, if you have servers in different time zones, you can set the server schedules so that each AOS instance is available for user traffic during the day and batch traffic overnight.

## Configure an AOS instance as a batch server

1.  Click **System administration** \> **Setup** \> **System** \> **Server configuration**.

2.  Select **Is batch server** to enable batch processing on the server.

3.  On the **Batch server schedule** FastTab, enter the maximum number of batch threads that can be run on the AOS instance at the same time. The server continues to collect threads from the queue until the maximum number is reached.

4.  To specify the period when the server is available for batch processing, enter a starting time in the **Start time** field and an ending time in the **End time** field.
    

    > [!NOTE]
    > <P>If the server is running a task when its batch processing availability ends, the task continues to run until it is completed. However, the server does not collect more tasks from the queue.</P>



5.  To specify an additional period, click **Add**, and then repeat step 4.

6.  On the **Batch server groups** FastTab, use the arrow buttons to add or remove batch groups from the list of groups that can run on the selected server.

## See also

[Batch server overview](batch-server-overview.md)

  



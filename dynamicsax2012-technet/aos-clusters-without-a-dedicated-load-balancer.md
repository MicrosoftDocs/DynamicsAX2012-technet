---
title: AOS clusters without a dedicated load balancer
TOCTitle: AOS clusters without a dedicated load balancer
ms:assetid: e3fea2c2-abdb-49ad-b409-48a182d53bf9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362108(v=AX.60)
ms:contentKeyID: 35949370
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# AOS clusters without a dedicated load balancer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure Microsoft Dynamics AX Application Object Server (AOS) clusters that include a dedicated load balancer. You can also configure clusters that do not include a dedicated load balancer. This topic describes planning considerations for an AOS cluster that does not include a dedicated load balancer.

## Overview

The following figure shows how a client establishes a connection with an AOS instance in a cluster when a dedicated load balancer is not present.

1.  When a Microsoft Dynamics AX client starts, the client reads the list of AOS instances that is specified in the Microsoft Dynamics AX 2012 Configuration utility. The client initiates a handshake with the first AOS instance in the list. If the first AOS instance does not respond, the client initiates a handshake with the next AOS instance in the list. The client continues in this manner until the handshake occurs.

2.  The AOS instance that received the client request queries the database and all active AOS instances in the cluster. The AOS instance returns to the client a list of all active AOS instances in the cluster, sorted by workload. The server that has the smallest workload is at the top of the list. The workload is based on the number of connected clients, divided by the maximum number of clients that are allowed on the server.

3.  The client attempts to connect to each AOS instance in the sorted list until a successful connection is established. The client then uses the AOS instance that it connected to for the whole session.

![AOS cluster that does not include a dedicated load](images/Dd362108.AOS_cluster_without_dedicated_load_balancer(AX.60).gif "AOS cluster that does not include a dedicated load")

## Considerations for using an AOS instance in a cluster that does not include a dedicated load balancer

  - If a dedicated load balancer is not present, each AOS instance in the cluster functions as both an active AOS instance and a load balancer.

  - An active AOS instance has higher hardware requirements than an AOS instance that functions as a dedicated load balancer.

For information about how to configure load balancing clusters, see [Create a load balancing cluster](create-a-load-balancing-cluster.md).

## See also

[AOS clusters with a dedicated load balancer](aos-clusters-with-a-dedicated-load-balancer.md)

[Manage a client configuration](manage-a-client-configuration.md)

[Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md)

[AOS architecture](aos-architecture.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


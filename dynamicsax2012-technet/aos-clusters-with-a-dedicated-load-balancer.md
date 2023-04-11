---
title: AOS clusters with a dedicated load balancer
TOCTitle: AOS clusters with a dedicated load balancer
ms:assetid: 6a8d228b-3ab9-4ecb-bf3a-dce7a141c19a
ms:mtpsurl: https://technet.microsoft.com/library/Dd309704(v=AX.60)
ms:contentKeyID: 35949307
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# AOS clusters with a dedicated load balancer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure Microsoft Dynamics AX Application Object Server (AOS) clusters that include a dedicated load balancer. You can also configure clusters that do not include a dedicated load balancer. This topic describes planning considerations for an AOS cluster that includes a dedicated load balancer.

## Overview

The following figure shows how a client establishes a connection with an AOS instance in a cluster when a dedicated load balancer is present.

1.  When a Microsoft Dynamics AX client starts, the client reads the list of active AOS instances that is specified in the Microsoft Dynamics AX 2012 Configuration utility. The client initiates a handshake with the first AOS instance in the list. In this scenario, the administrator has configured the first AOS instance as a dedicated load balancer.

2.  The load balancing AOS instance that received the client request queries the database and all active AOS instances in the cluster. The AOS instance returns to the client a list of all active AOS instances in the cluster, sorted by workload. The server that has the smallest workload is at the top of the list. The workload is based on the number of connected clients, divided by the maximum number of clients that are allowed on the server.

3.  The client attempts to connect to each AOS instance in the sorted list until a successful connection is established. The client then uses the AOS instance that it connected to for the whole session.

![AOS clusters with a dedicated load balancer](images/Dd309704.AOS_cluster_with_dedicated_load_balancer_AOS(AX.60).gif "AOS clusters with a dedicated load balancer")

## Considerations for using an AOS instance as a dedicated load balancer

  - An AOS instance that is configured as a load balancer does not accept any client connections as either an application server or a batch server. This AOS instance functions only as a load balancer.

  - A dedicated load balancer can be used only for remote procedure call (RPC) connections. To balance the load of connections for Application Integration Framework (AIF) and services, you must use Microsoft Network Load Balancing (NLB). For more information, see [Configuring network load balancing for services](configuring-network-load-balancing-for-services.md).

  - An AOS instance that is configured as a load balancer does not require an AOS license, because the server does not provide any application services to the clients.

  - If you configure an AOS instance as a dedicated load balancer, you do not have to update client configurations when AOS instances are added to or removed from the cluster.

  - A dedicated load balancer has lower hardware requirements than an AOS instance that functions as an application server, because the load balancer does not process application requests or business logic.

  - You can configure multiple AOS instances to function as dedicated load balancers. However, you must make sure that dedicated load balancers appear first in the list of active servers in the client configuration.

For information about how to configure load balancing clusters, see [Create a load balancing cluster](create-a-load-balancing-cluster.md).

## See also

[AOS clusters without a dedicated load balancer](aos-clusters-without-a-dedicated-load-balancer.md)

[Manage a client configuration](manage-a-client-configuration.md)

[Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md)

[AOS architecture](aos-architecture.md)

  



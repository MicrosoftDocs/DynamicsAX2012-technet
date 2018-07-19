---
title: Create a load balancing cluster
TOCTitle: Create a load balancing cluster
ms:assetid: b070501d-cf46-49fb-8168-785259178d27
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362041(v=AX.60)
ms:contentKeyID: 35949345
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Create a load balancing cluster 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can distribute the user load in Microsoft Dynamics AX across multiple instances of Application Object Server (AOS) by creating a load balancing cluster.

## Clustering overview

Microsoft Dynamics AX offers two types of load balancing clusters:

  - A cluster that includes a load balancer

  - A cluster that does not include a load balancer

## A cluster that includes a load balancer

If you set up a cluster that includes a load balancer, the load balancing AOS instance is dedicated to distributing the user load. The load balancing AOS instance does not process Microsoft Dynamics AX business logic or data.

In this configuration, you must set up client configurations to connect to the load balancing AOS instance. You can then add and remove other AOS instances from the cluster without updating client configurations.

When a client starts, it connects to the load balancing AOS instance. The load balancing AOS instance returns a list of active AOS instances in the cluster, sorted by workload. The client attempts to connect to the first AOS instance in the list. If that connection fails, the client attempts to connect to the second AOS instance in the list, and so on.

## A cluster that does not include a load balancer

If you set up a cluster that does not include a load balancer, each AOS instance functions as both a load balancer and an active AOS instance that accepts client connections.

When a client starts, it sends a request to the first server that is listed in the client configuration. That server returns the list of active AOS instances in the cluster, sorted by workload. The client attempts to connect to the first AOS instance in the list. If that connection fails, the client attempts to connect to the second AOS instance in the list, and so on.

## Before you begin

Before you can create a cluster, you must install multiple AOS instances. Each instance must point to the same database. For more information, see [Install multiple AOS instances](install-multiple-aos-instances.md) and [Configure an AOS to access a different database](configure-an-aos-to-access-a-different-database.md).

## Create a cluster

1.  Click **System administration** \> **Setup** \> **System** \> **Cluster configuration**.

2.  Press CTRL+N to create a new cluster.
    

    > [!WARNING]
    > <P>You cannot configure the <STRONG>Non Load Balanced AOS Instances</STRONG> as a load balancing cluster. The <STRONG>Non Load Balanced AOS Instances</STRONG> is a default entity that enables AOS communications for non-load balanced AOSs. To create an AOS cluster, you must create a new cluster.</P>



3.  Enter a name and description for the cluster.

4.  Press CTRL+S to save your changes.

## Add an AOS instance to a cluster

1.  Click **System administration** \> **Setup** \> **System** \> **Cluster configuration**.

2.  In the **Map AOS instances to clusters** section, select an AOS instance.

3.  If you want the AOS instance that you selected to function as a load balancer, select the **Load balancer** option.
    

    > [!NOTE]
    > <P>If an AOS instance is used as a load balancer, it cannot be used as a batch server.</P>



4.  Click the **Cluster name** field to display a list of available clusters. Select the cluster that you want to add the AOS instance to.

5.  Press CTRL+S to save your changes.

## Change client configurations

If the cluster uses one or more load-balancing AOS instances, set client configurations to connect to these load balancing AOS instances.

Use the Microsoft Dynamics AX Configuration utility to change client configurations. For more information, see [Manage a client configuration](manage-a-client-configuration.md).

## See also

[AOS clusters with a dedicated load balancer](aos-clusters-with-a-dedicated-load-balancer.md)

[AOS clusters without a dedicated load balancer](aos-clusters-without-a-dedicated-load-balancer.md)

[Manage AOS performance and availability](manage-aos-performance-and-availability.md)

[Set processor affinity](set-processor-affinity.md)

  



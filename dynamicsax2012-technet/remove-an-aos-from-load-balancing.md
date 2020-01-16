---
title: Remove an AOS from load balancing
TOCTitle: Remove an AOS from load balancing
ms:assetid: 3adb9485-096a-4a05-bbfc-2602e37f7aeb
ms:mtpsurl: https://technet.microsoft.com/library/Dd309645(v=AX.60)
ms:contentKeyID: 36941288
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- load balancing
- load balance
---

# Remove an AOS from load balancing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to configure an instance of Application Object Server (AOS) for Microsoft Dynamics AX as a stand-alone server by removing it from a load-balancing cluster. System administrators typically remove an AOS instance from a load-balancing cluster to perform maintenance.

## Before you begin

We recommend that you complete the following tasks before you remove an AOS instance from load balancing.

1.  Determine whether the AOS instance is configured as a load balancer. If the server is a load balancer, and no other load balancer is available, client connections may fail when you take the server offline. For more information, see [Create a load balancing cluster](create-a-load-balancing-cluster.md).

2.  Determine whether the AOS instance is a batch server. If the server is a batch server, and no other batch server is available, batch processes do not run. Verify that other servers in the environment are available for batch processing, or configure a different server for batch processing. For more information, see [Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md).

3.  Drain all users from the AOS instance that you want to remove from load balancing. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

## Remove the AOS instance from the load-balancing cluster

1.  Connect to the AOS instance that you want to remove from load balancing. You can either change your client configuration so that it points to the AOS instance, or use the following command-line parameters: -aos2= *Server\_name* and -loadbalance=0. For more information about how to change a client configuration, see [Manage a client configuration](manage-a-client-configuration.md). For more information about command-line parameters, see [Client configuration commands](client-configuration-commands.md).

2.  Click **System administration** \> **Common** \> **Users** \> **Online users**.

3.  Verify that you are connected to the correct AOS instance and the AOS instance is not servicing any other clients.

4.  Click **System administration** \> **Setup** \> **System** \> **Cluster configuration**.

5.  In the **Max concurrent sessions** field, enter 1.

6.  Verify that the **Load balancer** option is not selected.

7.  In the **Map AOS instances to clusters** section, select the AOS instance that you want to remove, and then click **Remove**. The AOS instance is now a stand-alone server. To delete the AOS instance from the environment, you must uninstall it by using Setup.

## See also

[Manage AOS performance and availability](manage-aos-performance-and-availability.md)

  



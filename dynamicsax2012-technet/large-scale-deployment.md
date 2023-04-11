---
title: Large-scale deployment
TOCTitle: Large-scale deployment
ms:assetid: 745d6a4c-a973-4da5-a35f-571890d11336
ms:mtpsurl: https://technet.microsoft.com/library/Dd309717(v=AX.60)
ms:contentKeyID: 39555370
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Large-scale deployment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The sample topology for a large-scale deployment of Microsoft Dynamics AX focuses on high availability. To achieve high availability, the topology includes load-balancing server clusters for the application servers and failover server clusters for the database server.

## Topology diagram

The following diagram shows the sample topology for a large-scale deployment.

Large-scale deployment

  
![Large-scale\_deployment\_topology](images/Dd309717.Large-scale_deployment_topology(AX.60).gif "Large-scale_deployment_topology")Large-scale deployment

This diagram shows a layered topology that helps provide security through the strategic placement of firewalls and the use of a perimeter network. A perimeter network, which is also known as a demilitarized zone (DMZ) or a screened subnet, prevents external users from directly accessing the corporate intranet.

Inside the corporate intranet, servers are divided among the following layers:

  - An applications layer, which contains servers that specialize in serving information to clients.

  - A database and platform layer, which contains servers that specialize in storing information that can be retrieved by servers in the applications layer. This layer also contains servers that provide company-wide administrative and security functions, such as directory servers and mail servers.

Microsoft Dynamics AX Windows clients that connect over a wide area network (WAN) are configured to use Terminal Services to communicate with Application Object Server (AOS). Microsoft Dynamics AX Windows clients on the local area network (LAN) are configured to communicate with AOS directly.

## Perimeter network

The perimeter network provides external users access to Microsoft Dynamics AX functionality through the following types of server clusters:

  - A Terminal Services cluster provides virtual private network (VPN) access to authorized users.

  - An Internet Information Services (IIS) cluster provides access to services through the Web services on IIS feature for Microsoft Dynamics AX.

  - An IIS cluster is dedicated to Enterprise Portal for Microsoft Dynamics AX (EP).

## Applications layer

The applications layer contains servers that provide information both to internal clients and to external clients that access Microsoft Dynamics AX through the perimeter network. This layer contains the following servers:

1.  A single AOS cluster supports clients and application components. You can configure one or more AOS instances in the cluster to act as batch servers. The AOS cluster natively provides functionality for services and Application Integration Framework (AIF), Workflow, and batch processing tasks. This cluster typically uses Network Load Balancing (NLB) to distribute the workload among the AOS instances.

2.  A cluster of integration servers connects to pre-existing systems.

3.  Dedicated servers provide internal clients access to Enterprise Portal, Microsoft Dynamics AX Help Server, Search Server, and Microsoft Project Server.

## Database and platform layer

The database and platform layer contains the following servers:

  - A Microsoft SQL Server failover cluster contains the Microsoft Dynamics AX database. This cluster may support additional database requirements. For example, the cluster may host the database that is required for Microsoft SharePoint 2010 products.
    

    > [!NOTE]
    > <P>You must determine whether additional database clusters are required, based on the expected workload.</P>



  - A second SQL Server failover cluster is dedicated to Microsoft SQL Server Analysis Services and Microsoft SQL Server Reporting Services.

  - All data is backed up through a storage area network (SAN).

  - System Center Operations Manager (SCOM) enables monitoring for the whole system.

  - An Active Directory domain controller is required to deploy Microsoft Dynamics AX components.

## See also

[System architecture](system-architecture.md)

[Single-server deployment](single-server-deployment.md)

[Small-scale deployment](small-scale-deployment.md)

  



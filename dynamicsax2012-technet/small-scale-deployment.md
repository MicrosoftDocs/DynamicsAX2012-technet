---
title: Small-scale deployment
TOCTitle: Small-scale deployment
ms:assetid: 71bfc45d-c7a8-489a-a945-145c58bf251d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309710(v=AX.60)
ms:contentKeyID: 39555369
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Small-scale deployment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The topology for a small-scale deployment of Microsoft Dynamics AX expands on the topology for a single-server deployment that is described in [Single-server deployment](single-server-deployment.md).

This topology does not offer scalability or high availability. Scalability and high availability are introduced in the large-scale topology that is described in the [Large-scale deployment](large-scale-deployment.md) topic. This topology is suitable as a test environment and for training purposes.

The following diagram shows a sample topology for a small-scale deployment.

Small-scale deployment topology

  
![Small\_scale\_deployment](images/Dd309710.Small_scale_deployment(AX.60).gif "Small_scale_deployment")Small-scale deployment topology

The following list describes how the computers in this sample topology are used:

  - An Active Directory domain controller is required to deploy Microsoft Dynamics AX components.

  - Windows clients for Microsoft Dynamics AX that connect over a wide area network (WAN) are configured to use Terminal Services to communicate with Application Object Server (AOS). Windows clients on the local area network (LAN) are configured to communicate with AOS directly.

  - AOS is deployed on a single-server computer. AOS can host the following components:
    
      - Workflow
    
      - Services and Application Integration Framework (AIF)

  - External applications use services and AIF to exchange data with Microsoft Dynamics AX.

  - A web server can host the following components:
    
      - Search server
    
      - Enterprise Portal for Microsoft Dynamics AX
    
      - Web services on IIS
    
      - Microsoft Project Server

  - The server that runs Microsoft SQL Server can host the following components:
    
      - Microsoft Dynamics AX online transaction processing (OLTP) database
    
      - Model files in the OLTP database
    
      - Microsoft SQL Server Analysis Services (SSAS)
    
      - Microsoft SQL Server Reporting Services (SSRS)

## See also

[System architecture](system-architecture.md)

[Single-server deployment](single-server-deployment.md)

[Large-scale deployment](large-scale-deployment.md)

  



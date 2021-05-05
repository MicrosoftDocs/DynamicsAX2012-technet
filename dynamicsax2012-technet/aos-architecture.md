---
title: AOS architecture
TOCTitle: AOS architecture
ms:assetid: 0f8174e4-1f5f-41eb-843a-7c7faf133cc3
ms:mtpsurl: https://technet.microsoft.com/library/Dd309593(v=AX.60)
ms:contentKeyID: 35132546
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# AOS architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

## Introduction to the Application Object Server architecture

An Application Object Server (AOS) is a core component of the Microsoft Dynamics AX installation and is installed by using Setup. An AOS enforces security, manages connections between clients and the database, and provides the foundation where business logic for Microsoft Dynamics AX is executed. An AOS is implemented as a Microsoft Windows service. By default, an AOS is listed in the **Services** pane as **Microsoft Dynamics AX Object Server 6.0$** *InstanceName*. As a Windows service, AOS works in the following ways:

  - An AOS runs in the security context of either a specific domain account or the NT Authority/Network Service account, depending on the setup.

  - The status of an AOS is reported to the Windows event logs. Therefore, administrators can view errors and warnings that can help them troubleshoot problems.

You can install an AOS on a single computer, together with the database, model store, and other Microsoft Dynamics AX components. Alternatively, you can install application object servers on multiple computers and group these computers in a load-balanced cluster. Because Microsoft Dynamics AX requires Windows-integrated authentication for all servers in the system, you must be running Active Directory.

## Client/AOS communications

Clients communicate with an AOS by using remote procedure calls (RPCs), Windows Communication Foundation (WCF), or AOS services. In previous releases, other components and third-party programs could communicate with an AOS by using either .NET Business Connector or Application Integration Framework (AIF). For this release, we recommend that third-party programs use AOS services to communicate with AOS.

The following diagram shows the AOS architecture.

![Application Object Server](images/Dd309593.AOS(AX.60).gif "Application Object Server")

## See also

[System architecture](system-architecture.md)

[AOS topology](aos-topology.md)

[Application integration](application-integration.md)

  



---
title: .NET Business Connector architecture
TOCTitle: .NET Business Connector architecture
ms:assetid: 492d0d1c-5697-482a-9893-54a06756a4a2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309664(v=AX.60)
ms:contentKeyID: 35132621
ms.date: 06/04/2014
mtps_version: v=AX.60
---

# .NET Business Connector architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

## The .NET Business Connector architecture

The .NET Business Connector is a component of the development environment for Microsoft Dynamics AX and is used to interpret and execute code. During execution, applications that are created by using the .NET Framework are managed by the common language runtime (CLR). These applications are called managed applications. The .NET Business Connector enables these managed applications to interact with instances of an Application Object Server (AOS) by providing a set of .NET managed classes. These .NET managed classes, in turn, enable access to X++ classes in Microsoft Dynamics AX. For more information about the .NET Business Connector, see [NET Business Connector Overview](http://go.microsoft.com/fwlink/?linkid=401459) on MSDN.

By default, the .NET Business Connector is installed together with the Application Integration Framework (AIF). However, the .NET Business Connector can also be installed as a stand-alone component and used to develop third-party applications that can be integrated with Microsoft Dynamics AX.

For more information about how to integrate other applications with Microsoft Dynamics AX, see [Application integration](application-integration.md).

The following diagram shows the Business Connector architecture.

![Business connector kernel](images/Dd309664.BCKernel(AX.60).gif "Business connector kernel")

## See also

[System architecture](system-architecture.md)

[Services and AIF architecture](services-and-aif-architecture.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


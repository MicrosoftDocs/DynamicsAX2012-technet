---
title: Adapters
TOCTitle: Adapters
ms:assetid: 0bfad6cb-37b8-42c8-994e-f7433a9d656c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751348(v=AX.60)
ms:contentKeyID: 35132537
ms.date: 04/23/2014
mtps_version: v=AX.60
---

# Adapters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012. To find out if this information applies to you, contact your administrator.</P>



In Microsoft Dynamics AX 2012 services and Application Integration Framework (AIF), integration ports use adapters. These adapters enable Microsoft Dynamics AX to communicate by using various transport protocols. AX 2012 provides the following five adapters that represent predefined bindings:

  - **HTTP adapter** – This adapter provides for synchronous message exchanges by using an HTTP or HTTPs transport.

  - **NetTCP adapter** – This adapter provides for synchronous exchanges by using WS-\* standards support over the Transmission Control Protocol (TCP) transport. This adapter corresponds to the WCF-NetTcp binding in Windows Communication Foundation (WCF).

  - **MSMQ adapter** – This adapter provides support for queuing by using Message Queuing as a transport. Message Queuing is also known as MSMQ. Message Queuing is a type of asynchronous communication. This adapter corresponds to the WCF-NetMsmq binding in WCF.

  - **File system adapter** – This adapter provides support for the asynchronous exchange of documents through file system directories.

  - **Windows Azure Service Bus adapter** – This adapter enables publishing AX 2012 services by using the Windows Azure Service Bus. The Service Bus provides the messaging channel for connecting your cloud applications to your on-premises applications, services and systems. This adapter requires Internet Information Services (IIS) 7.5, authentication for inbound Service Bus messages, and registration of a Service Bus namespace. Cumulative update 6 or later for AX 2012 provides classes to support the required authentication in addition to the infrastructure to register a Service Bus namespace from AX 2012.
    

    > [!IMPORTANT]
    > <P>This adapter is only available if you’re using cumulative update 6 for Microsoft Dynamics AX 2012 or later. Don’t know what version you’re using? See <A href="find-out-which-version-of-microsoft-dynamics-ax-you-are-using.md">Find out which version of Microsoft Dynamics AX you are using</A>.</P>



For more information about integration ports, see [Integration ports](integration-ports.md). For detailed information about how to configure and manage integration ports, see [Services and AIF operations](services-and-aif-operations.md).

## About addresses

Addresses depend on the type of adapter being used. An address consists of a Uniform Resource Identifier (URI) that is associated with a particular adapter. A URI provides the location of the source or destination that the adapter can use, for example a file folder path or an HTTP URL.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


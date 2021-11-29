---
title: Planning considerations for the Help system
TOCTitle: Planning considerations for the Help system
ms:assetid: 73dea160-55e3-4444-8087-d2afdbbb1798
ms:mtpsurl: https://technet.microsoft.com/library/Gg866978(v=AX.60)
ms:contentKeyID: 35256672
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Planning considerations for the Help system 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before installing Microsoft Dynamics AX and implementing the Help system, you should prepare a plan covering each of the following areas.

## Topology

Before selecting a topology, consider the following questions.

## What computer will host the Help server?

The Microsoft Dynamics AX Help server manages the storage and display of Microsoft Dynamics AX product documentation. You must install the Help server on a computer that is running Internet Information Services (IIS). Keep in mind that you can install other web applications on this same computer, such as Enterprise Portal.

## What computer will host the AOS?

When installing the Help server, you will need to specify the name of the computer that is running the Microsoft Dynamics AX Application Object Server (AOS). The Help server must have access to the AOS in order to retrieve label definitions. For more information, see [Help system architecture](help-system-architecture.md).

## Security

To help plan for security, consider the following question.

## Have you defined an account for the .NET Business Connector proxy?

The .NET Business Connector enables the Help server to communicate with an AOS instance. The Help server must have access to the AOS in order to retrieve label definitions.

The .NET Business Connector must be configured to connect to Microsoft Dynamics AX with a proxy account. The use of a proxy enables the .NET Business Connector to connect on behalf of Microsoft Dynamics AX users when authenticating with an AOS instance. We recommend that the proxy account be set up using the guidelines listed in [Specify the .NET Business Connector proxy account](specify-the-net-business-connector-proxy-account.md).

## Performance

To ensure good performance of the Help system, consider the following questions.

## Are other applications installed on the same computer?

The Help topics that are installed with the Help server must be indexed by the Windows Search Service. If other applications are installed on the same computer, those applications may affect the performance of the Windows Search Service.

## What computer will host the AOS?

As noted above, the Help server must have access to the AOS in order to retrieve label definitions. If the AOS is installed on a computer in a different geographic location from the computer running the Help server, performance may suffer.

For more information about how the Help server and the AOS work together, see [Help system architecture](help-system-architecture.md).

## Customization

If you plan to customize your Help system, consider the following question.

## How will you publish your custom Help topics?

You can create custom Help topics and add them to the Help system. If you are going to create custom topics, consider how you are going to install them. For example, you may need to create a file share for the topics on the computer hosting the Help server. For more information about installing custom Help topics, see [Developing on the Help server](developing-on-the-help-server.md).

  



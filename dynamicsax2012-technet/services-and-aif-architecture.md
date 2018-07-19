---
title: Services and AIF architecture
TOCTitle: Services and AIF architecture
ms:assetid: 6ae086a5-f525-451b-8cd8-5322aebfdc23
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309705(v=AX.60)
ms:contentKeyID: 35132672
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Services and AIF architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the high-level architecture of services and Application Integration Framework (AIF).

Microsoft Dynamics AX exposes its functionality through services that are based on Windows Communication Foundation (WCF) and hosted on Application Object Server (AOS). External applications and client applications on the local area network consume Microsoft Dynamics AX services by accessing them directly from AOS. These clients and applications include Microsoft Dynamics AX components such as the Microsoft Dynamics AX client, Office Add-ins for Microsoft Dynamics AX, and Enterprise Portal for Microsoft Dynamics AX. Internet-based external applications and clients access the Microsoft Dynamics AX services through Internet Information Services (IIS). IIS routes the incoming requests for Microsoft Dynamics AX services to AOS. All services requests, regardless of their origin, are handled by the WCF runtime that is hosted on AOS.

The AIF request preprocessor, if it is configured, can intercept the inbound request messages for custom preprocessing, such as message transforms or value substitutions. The Microsoft Dynamics AX service invokes the necessary business logic to process the inbound request message. Similarly, the AIF response postprocessor, if it is configured, can intercept the outbound response messages for custom post-processing, such as message transforms or value substitutions. The AIF response postprocessor then returns the response to the client.

Note that Microsoft Dynamics AX 2012 no longer includes a BizTalk adapter. For more information about how to use Microsoft BizTalk Server together with Microsoft Dynamics AX 2012, see [Exchanging documents between BizTalk Server and AIF](exchanging-documents-between-biztalk-server-and-aif.md).

The following diagram illustrates the services and AIF architecture.

![Services and AIF architecture](images/Dd309705.ServicesAndAIFArchitecture(AX.60).png "Services and AIF architecture")

**Services and Application Integration Framework architecture**

## See also

[Key concepts in AIF](key-concepts-in-aif.md)

[System architecture](system-architecture.md)

  



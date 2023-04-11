---
title: AIF Messages
TOCTitle: AIF Messages
ms:assetid: 41727657-fbe0-4b06-a7dc-c98c8ceab697
ms:mtpsurl: https://technet.microsoft.com/library/Aa627117(v=AX.60)
ms:contentKeyID: 35242949
author: tfehr
ms.author: daxcpft
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# AIF Messages 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This section of the documentation describes the tags used in Microsoft Dynamics AX services Application Integration Framework (AIF) messages. An AIF message uses XML to describe a self-contained unit of data that can consist of several parts. These parts include a \<Header\> tag section and a \<Body\> tag section. All XML used in AIF is validated against the appropriate schema. For more information about AIF messages and schemas, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

When you set up an inbound integration port and run an inbound service, AIF receives and processes an inbound message and generates an outbound message in response. When you set up an outbound integration port and run an outbound service to send data outside Microsoft Dynamics AX, AIF sends an outbound message. For more information about inbound and outbound integration ports, see [Integration ports](integration-ports.md) and [Managing integration ports](managing-integration-ports.md).

The tag names in the \<Body\> section vary between different types of inbound and outbound messages. The tags that are required in the \<Body\> section for Microsoft Dynamics AX document services depend on which service operation is specified in the \<Action\> tag in the \<Header\> section.

## In This Section

The topics covered in this section describe and provide examples for the \<Header\> tag schema and the \<Body\> tag schema for AIF messages.

[Message Header](message-header.md)

[Message Body](message-body.md)

[How to: Enable Checking for Duplicate Messages](how-to-enable-checking-for-duplicate-messages.md)

[Example Messages for AIF Document Service Operations](example-messages-for-aif-document-service-operations.md)

## See also

[Sequential and parallel processing in services and AIF](sequential-and-parallel-processing-in-services-and-aif.md)

[Message Header](message-header.md)

[Message Body](message-body.md)

[Document Class Service Operations](document-class-service-operations.md)


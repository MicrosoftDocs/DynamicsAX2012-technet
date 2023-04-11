---
title: Application integration
TOCTitle: Application integration
ms:assetid: 9882a593-9cb8-45d9-aa40-0b4323deec71
ms:mtpsurl: https://technet.microsoft.com/library/Dd362007(v=AX.60)
ms:contentKeyID: 35132776
author: tonyafehr
ms.author: daxcpft
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Application integration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The capability to integrate Microsoft Dynamics AX with other systems inside and outside the enterprise is a common requirement. Application Integration Framework (AIF) provides this capability by enabling the exchange of data through formatted XML. This formatted XML is referred to as a document, and each document contains data and business logic. Documents are based on a document class and defined by using Microsoft Dynamics AX.

Microsoft Dynamics AX is shipped together with many standard document services that support common business processes. By using the capabilities that AIF provides, you can also customize existing document services or create your own document services. For more information about standard document services and how to create your own document services, see [Services and AIF development](services-and-aif-development.md).

## How documents are exchanged

AIF provides an extensible framework for the exchange of XML documents with external systems. The framework supports both synchronous and asynchronous transports. In synchronous mode, requests are tightly coupled to responses. This means that the submitter of the request must wait for a response from AIF before proceeding. In this case, AIF immediately processes the request and then sends a response. In asynchronous mode, requests are placed into a queue, called the gateway queue. Queued messages are processed at a later time and AIF sends a response when processing is completed. In this case, responses are delayed, but large volumes of messages can be processed more efficiently, and message processing can be controlled by changing various configuration settings.

AIF can be used to send data into Microsoft Dynamics AX. This kind of exchange is called an inbound exchange. For example, during an inbound exchange, an external system may send a sales order so that the sales order can be saved to the Microsoft Dynamics AX database. AIF can also be used to retrieve data from Microsoft Dynamics AX. This kind of exchange is called an outbound exchange. For example, during an outbound exchange, an external system may send a request for a purchase order and receive the purchase order. The inbound and outbound exchanges can be categorized in the following ways:

  - **Send data** – Microsoft Dynamics AX sends documents to an external system.

  - **Send data in response to requests** – Microsoft Dynamics AX receives requests for documents from another authorized system, and retrieves the requested information, such as a document or a list of documents, from the Microsoft Dynamics AX database. Microsoft Dynamics AX then returns the information to the requesting system, and the appropriate filtering and security are applied. The request message contains the entity keys or a query that specifies the data that the external system is requesting.

  - **Receive and create data** – Microsoft Dynamics AX receives documents from another authorized system and creates new records in the Microsoft Dynamics AX database.

## See also

[Integration components](integration-components.md)


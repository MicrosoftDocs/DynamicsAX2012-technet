---
title: Messages and transforms in AIF
TOCTitle: Messages and transforms
ms:assetid: 94d668e0-db8c-4fe4-b7e3-b144e57f4026
ms:mtpsurl: https://technet.microsoft.com/library/Gg731873(v=AX.60)
ms:contentKeyID: 35132771
author: tonyafehr
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Messages and transforms in AIF 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2012 services and Application Integration Framework (AIF), a message corresponds to a Windows Communication Foundation (WCF) message. A message is a self-contained unit of data that can consist of several parts. These parts include a body and headers. When AIF receives and processes an inbound message, it generates an outbound message in response.

Although AIF supports the transfer of data in any arbitrary format, most information exchanges with AIF services use XML documents. In order to create an XML document that adheres to a standard for a particular exchange of information, AIF requires XML documents to follow an XML style definition (XSD). XSD files (which have a .xsd file name extension) are meta-documents that describe the format, or schema, of XML documents that declare the namespace of the XSD. Each schema includes rules about the hierarchical arrangement of XML elements, which elements must be present in the document, and other such requirements.

## Schemas

This section lists and describes the various schemas used by AIF.

### Document service schemas

Each document service has a unique schema that describes the fields that can be added, read, updated, and so forth, by using the particular document service.

### Message schema

Asynchronous exchanges require XML messages to be contained by the AIF message envelope. The namespace for the message schema is:

https://schemas.microsoft.com/dynamics/2011/01/documents/Message

For more information about the format of XML messages in AIF, see [AIF Messages](https://go.microsoft.com/fwlink/?linkid=223878).

### Message-set schema

AIF uses the message-set, or batch, schema to contain batched AIF messages in asynchronous exchanges. The namespace for the message-set schema is:

https://schemas.microsoft.com/dynamics/2009/06/documents/Batch

For more information about batched messages, see [Processing batched messages in AIF](processing-batched-messages-in-aif.md).

### Entity key schemas

AIF uses entity key schemas to contain name-value pairs, such as those used to query for a particular item during a read operation or when sending a response to a create operation. The namespaces for entity keys and entity key lists are:

https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey

https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKeyList

### Shared types schema

AIF aggregates common property types in the shared-types schema. The namespace for the shared-types schema is:

https://schemas.microsoft.com/dynamics/2008/01/sharedtypes

### Fault schema

AIF uses the fault schema to contain response messages about error conditions. The namespace for the fault schema is:

https://schemas.microsoft.com/dynamics/2008/01/documents/Fault

## Schema locations

You can save XSDs for particular document services, including their imported schemas (such as the shared-types schema) and any port-specific customizations, when you configure data policies for an integration port. For more information, see the "Customizing documents" section of [Customize service contracts](customize-service-contracts.md).

You can retrieve XSDs for common schemas from the following directory where you installed Microsoft Dynamics AX:

Program files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin\\Application\\Share\\Include

## Processing messages

When you use an enhanced integration port for services and AIF, you can perform custom processing of data, such as XML documents, as each message passes through the integration port. Enhanced integration ports use the following two concepts to process messages during inbound or outbound exchanges:

  - Transforms provide an extensible framework that developers can use to apply Extensible Stylesheet Language Transformations (XSLT) or .NET-based transforms to messages. .Net-based transforms can convert messages to or from any proprietary format. Microsoft Dynamics AX services and AIF can process XML documents only if the documents comply with the service XSD. If an incoming document is based on XML but uses a different schema, you can use Extensible Stylesheet Language (XSL) to transform the document to the AIF schema. If an incoming document is not based on XML, such as a comma-delimited file, you can use a .NET Framework assembly to convert the file to the AIF schema.
    
    Transforms are run for inbound exchanges before they are run for outbound exchanges. Transforms process the whole message. Headers are included in the processing.
    
    Transforms apply only to asynchronous exchanges.

  - Pipelines use components to enable the processing of requests for service operations. These components include custom components that are written in X++ code. For example, if an inbound message contains customer records, your AIF pipeline can contain an XSLT component that updates an element in the XML, based on the value of the customer status element. Your AIF pipeline can contain one or more of any available transformation component. Alternatively, your AIF pipeline can contain no transformation components.
    
    Processing that occurs in pipelines, including XML transformation, applies to both synchronous and asynchronous exchanges.
    
    For inbound exchanges, pipelines are run after transforms. For outbound exchanges, pipelines are run before transforms.
    
    For more information about pipelines, see [About the AIF Pipeline and Transforms](about-the-aif-pipeline-and-transforms.md).

The following diagram shows how data moves through an enhanced inbound integration port.

![Data flow in an AIF enhanced integration port](images/Gg731873.AX6_AIF_Document_Service_Data_Flow(AX.60).png "Data flow in an AIF enhanced integration port")

**Data flow in an enhanced integration port**

## See also

[Managing integration ports](managing-integration-ports.md)


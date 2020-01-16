---
title: Exchanging documents between BizTalk Server and AIF
TOCTitle: Exchanging documents between BizTalk Server and AIF
ms:assetid: 703527e1-4b5b-4eed-a8bd-74c0f419c14b
ms:mtpsurl: https://technet.microsoft.com/library/Hh352300(v=AX.60)
ms:contentKeyID: 36687928
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Exchanging documents between BizTalk Server and AIF 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2009 included a specialized adapter that provided the ability to integrate with Microsoft BizTalk Server through Application Integration Framework (AIF). Microsoft Dynamics AX 2012 no longer includes this adapter. Instead, you can connect AIF with BizTalk by using the Windows Communication Framework (WCF)-based adapters that are included with AIF.

## Frequently asked questions

This section answers questions that you may already have about integration between BizTalk and AIF. These answers can help you to correct many common issues. To read complete walkthroughs of scenarios that connect BizTalk with AIF, see [Using Microsoft BizTalk Server 2010 to exchange documents with Microsoft Dynamics AX](https://go.microsoft.com/fwlink/?linkid=221937).

## Services and AIF

**What happened to the BizTalk adapter?**

Microsoft Dynamics AX 2012 introduces a new design for services and AIF. As a result, the BizTalk adapter was removed. In Microsoft Dynamics AX 2012, you must use various adapters to exchange documents between BizTalk and AIF.

**What happened to channels and endpoints?**

In Microsoft Dynamics AX 2012, AIF exposes virtual integration ports to simplify administration of inbound and outbound connections for document exchanges. These virtual ports replace the channels and endpoints used by previous versions of Microsoft Dynamics AX. For more information about AIF configuration, see [Services and AIF operations](services-and-aif-operations.md).

**Why don't I see the services that I expect when I configure my AIF port?**

In Microsoft Dynamics AX 2012, AIF requires that you register services. To register services, follow these steps.

1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.

2.  Expand the **Initialize system** node.

3.  Click **Set up Application Integration Framework**.

**Why do I get a permissions error from Microsoft Dynamics AX when attempting to transmit a document from BizTalk to an inbound port?**

Make sure that the account that BizTalk runs under is listed as a user account in Microsoft Dynamics AX and has the required roles for the services that BizTalk uses.

## Schemas

**How does my document need to be formatted before submitting to AIF?**

**What format can I expect when AIF sends me a document?**

AIF service documents are always constructed from XML that conforms to a service schema definition and is contained in a special wrapper, called an envelope. For exchanges that use SOAP, such as exchanges over TCP/IP or HTTP, the envelope is the standard SOAP envelope. For other exchanges, such as through Message Queuing or the file system, AIF provides an envelope schema. The namespace for the AIF envelope schema is:

    https://schemas.microsoft.com/dynamics/2011/01/documents/Message

For message sets, AIF uses the message-set schema. The namespace of the message-set schema is:

    https://schemas.microsoft.com/Microsoft Dynamics/2009/06/documents/Batch

AIF uses entity key schemas to contain name-value pairs, such as those used to query for a particular item during a read operation or when sending a response to a create operation. The namespaces for entity keys and entity key lists are:
    
```
https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey
```
    
```
https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKeyList
```

AIF aggregates common property types in the shared-types schema. The namespace for the shared-types schema is:

    https://schemas.microsoft.com/dynamics/2008/01/sharedtypes

AIF uses the fault schema to contain response messages about error conditions. The namespace for the fault schema is:

    https://schemas.microsoft.com/dynamics/2008/01/documents/Fault

**Where can I get the schema definitions for Microsoft Dynamics AX services?**

You can retrieve common schema files from the following directory where you installed Microsoft Dynamics AX:

    Program files\Microsoft Dynamics AX\60\Server\Microsoft Dynamics AX\bin\Application\Share\Include 

You can save a full or customized version of a service schema by creating a custom data policy during configuration of an AIF integration port. The **Data policies** button (in the **Inbound ports** and **Outbound ports** forms) opens the **Document data policies** form. You can use this form to set rules for the fields that can be used in documents processed by an integration port for a given service operation. However, you cannot disable fields that are required by the service schema. The **View schema** button opens the XML viewer, where you can view and save the schema (and its imported schemas, such as the shared-types schema) to an XSD file.

You can generate schemas from the published WSDL document of an exposed network-protocol-based service, such as from a port that uses the NetTcp adapter. The WCF Consuming Services Wizard can generate the schema documents (and binding information) for you.

**How do I generate an instance of an XML document based on an XSD?**

The Generate Sample XML feature in Microsoft Visual Studio generates a sample XML file based on an XSD file. In **Solution Explorer**, right-click the XSD file name and then click **Generate Instance**.

## Message exchanges

**Does AIF integration require exchanges to be synchronous or asynchronous?**

Messages can be exchanged either synchronously or asynchronously, depending on the types of ports and adapters used.

**How do I receive documents that originate in Microsoft Dynamics AX?**

Documents that originate in Microsoft Dynamics AX are sent through an outbound port. Microsoft Dynamics AX includes outbound port adapters for the file system adapter and the MSMQ adapter. This means that, by default, you can perform only asynchronous exchanges for scenarios that start with Microsoft Dynamics AX. It is possible to write a custom adapter for synchronous, outbound scenarios.

**How can Microsoft Dynamics AX consume a BizTalk Web service?**

Download the white paper titled Consuming Microsoft Dynamics AX 2012 Web Services ([https://go.microsoft.com/fwlink/?LinkID=213142](https://go.microsoft.com/fwlink/?linkid=213142)).

## BizTalk project

**Do I need to use an orchestration to construct an AIF document?**

No. You can provide an orchestration if you need to, but no orchestration is required to create an AIF message. Envelope assembly or disassembly happens in a pipeline. You can use the standard XML Receive and XML Transmit pipelines; a custom pipeline is not required. You configure the default pipelines when you configure the ports, after you have deployed your BizTalk Server application.

**What must the project contain?**

Add the schemas (including imported schemas) that the document exchange requires to the BizTalk project. Usually, these schemas include a source schema, a destination schema, and the AIF message (envelope) schema, if it is required. Whether the AIF document service schema is the source or the destination depends on the direction of the message.

Create a map to translate values from elements in the source schema to elements in the destination schema.

**How do I configure the envelope?**

For asynchronous exchanges, you must configure the AIF message schema as an envelope in your Visual Studio project, as follows:

  - Set the **Envelope** property to Yes.

  - Set **RootReference** to **Envelope**.

  - For the **Envelope** element, set the **Body XPath** property to point to the **MessageParts** element (not the **Body** element).

For synchronous exchanges, you can configure the SOAP envelope properties in the administration console during port configuration of the send port.

**How do I copy values from a source document to the envelope header?**

BizTalk's property demotion feature can copy values from a source document to a destination header. This copying happens automatically when the elements have been promoted and they share the same name and data type. You may find this feature useful for copying the message ID between headers, for example.

**How should I configure my project for deployment?**

In the BizTalk deployment project properties, provide an application name, set **Restart Host Instances** to **True**, and provide a signing key.

**How do I enable matching of requests to responses in asynchronous scenarios?**

For asynchronous exchanges, always provide a unique **MessageId** value, because you will use this value to correlate requests and responses. Microsoft Dynamics AX requires the message ID to be a GUID. AIF contains the initial message ID in its responses by using the **RequestMessageId** element.

## BizTalk administration

**Why don't I see my project in the administration console?**

Your deployed Visual Studio project will be listed in the **Applications** node in the BizTalk Server Administration Console. If you did not provide an application name before deployment, your application was given a default name, such as "BizTalk Application 1".

**How do I configure a pipeline to assemble an AIF message?**

To assemble an AIF message envelope, provide the **EnvelopeDocSpecNames** and **DocumentSpecNames** values in the XML Transmit pipeline's properties dialog box. These values take the form: "full schema name, full assembly name". You can view the schema and assembly names in the schema properties dialog box in the BizTalk Server Administration Console. The following text shows an example of specifying the AIF message schema in **EnvelopeDocSpecNames**:

    MyProj.AIFMessage, MyProj, Version=1.0.0.0, Culture=neutral, PublicKeyToken=MyKeyToken

If you need to assemble multiple documents within the envelope, separate the document spec names by using a pipe character ("|").

**How do I configure a pipeline to disassemble an AIF message?**

To disassemble an AIF message, provide the **EnvelopeDocSpecNames** and **DocumentSpecNames** values in the XML Receive pipeline's properties dialog box. See the previous answer for details.

**How do I connect the ports without using an orchestration?**

In BizTalk, you can connect ports to each other (creating a subscription) by using a filter. For example, you can set the **BTS.ReceivePortName** property in a filter to subscribe a send port to all messages from a particular receive port. You can also subscribe by using other filters, such as message type or port ID. You can subscribe to the receive pipeline of a solicit-response port by using the **BTS.SPName** property.

**How do I match a response to its original request?**

This process, called correlation, requires you to match a value (or set of values) from the request document with corresponding values in the response document. You will typically match the **MessageId** element from the request (a GUID that you generate) to the **RequestMessageId** from the response.

BizTalk Server requires that you create a correlation set only if you use an orchestration in a synchronous document exchange. In this case, the correlation set can contain these same ID values. For asynchronous exchanges, and synchronous exchanges that do not use an orchestration, no BizTalk correlation set is required. In this case, you can use whatever method you choose to correlate requests and responses by using the ID values.

  



---
title: Guide to the Services and AIF Documentation
TOCTitle: Guide to the Services and AIF Documentation
ms:assetid: 4e917ee3-5ab4-4852-8a53-fb24bd3316a4
ms:mtpsurl: https://technet.microsoft.com/library/JJ710373(v=AX.60)
ms:contentKeyID: 49384265
author: Khairunj
ms.date: 01/09/2013
mtps_version: v=AX.60
---

# Guide to the Services and AIF Documentation 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

This topic provides a guide to the Microsoft Dynamics AX Services and Application Integration Framework (AIF) documentation. The linked documents are recommended starting points grouped according to specific interests and levels of expertise.

Use the information in the following sections if you are:

  - New to Services and AIF in Microsoft Dynamics AX

  - Familiar with a previous version of Microsoft Dynamics AX

  - Upgrading services and AIF from a previous version

  - Operating the Microsoft Dynamics AX 2012 environment to support services and AIF

  - Developing with standard, custom, or system services

  - Troubleshooting all aspects of services and AIF

  - Moving from test to production

## If you are new to Services and AIF in Microsoft Dynamics AX

If you are new to using Services and AIF in Microsoft Dynamics AX and you want an introduction to the basics, see the following topics.

  - For an introduction and key concepts, see [Key concepts in AIF](key-concepts-in-aif.md).

  - For an overview of integration architecture, see [Services and AIF architecture](services-and-aif-architecture.md).

  - For information about security with Web services, see [Security architecture for Web services](security-architecture-for-web-services.md).

  - For an introduction to developing with the different types of services in Microsoft Dynamics AX, see [Developing with Services and AIF](developing-with-services-and-aif.md).

If you are new to using Services and AIF and you want to see a catalog of walkthroughs using services and AIF, see [Services and AIF Walkthroughs](services-and-aif-walkthroughs.md).

If you are new to programming with Services and AIF and you want to see samples that work, see the following topics.

  - For an example of a read request by using a document service and the NetTCP adapter, see [Walkthrough: Reading a Customer by Using the NetTCP Adapter](walkthrough-reading-a-customer-by-using-the-nettcp-adapter.md).

  - For an example of a read request by using an XML message and the file system adapter, see [Walkthrough: Reading a Customer by Using the File System Adapter](walkthrough-reading-a-customer-by-using-the-file-system-adapter.md).

  - For example code for an outbound transfer, see [Walkthrough: Deploying the Document Service in an Outbound Exchange](walkthrough-deploying-the-document-service-in-an-outbound-exchange.md).

  - For an example .NET assembly transform, see [Walkthrough: Creating a .NET Assembly Transform](walkthrough-creating-a-net-assembly-transform.md).

  - For an example of a custom service, see [Walkthrough: Exposing an X++ Class as a Data Contract](walkthrough-exposing-an-x-class-as-a-data-contract.md).

  - For an example that uses BizTalk Server, see [Exchanging documents between BizTalk Server and AIF](exchanging-documents-between-biztalk-server-and-aif.md).

## If you are familiar with an earlier version of Microsoft Dynamics AX

Implementing data transfers has changed significantly in Microsoft Dynamics AX 2012. For more information about these changes, see the following topics.

  - For information about What’s New in Microsoft Dynamics AX 2012 for system administrators, see [What's New: Services and AIF administration](https://technet.microsoft.com/library/gg751352\(v=ax.60\)).

  - For information about what’s new in Microsoft Dynamics AX 2012 for developers, see What's New: Services and AIF for Developers in Microsoft Dynamics AX 2012.

  - For information about new and see comment features in Microsoft Dynamics AX 2012, see [New, changed, and deprecated features for Microsoft Dynamics AX 2012](https://go.microsoft.com/fwlink/?linkid=212966).

In Microsoft Dynamics AX 2012, proprietary Microsoft Message Queuing (MSMQ) and BizTalk Server adapters used in the previous releases of Microsoft Dynamics AX are no longer available. For information about how to use Message Queuing and BizTalk Server with AIF in Microsoft Dynamics AX 2012, see the following topics:

  - [Walkthrough: Exchanging documents by using the MSMQ adapter](walkthrough-exchanging-documents-by-using-the-msmq-adapter.md)

  - [Exchanging documents between BizTalk Server and AIF](exchanging-documents-between-biztalk-server-and-aif.md)

### Upgrading from an earlier version

For information about how to upgrade from an earlier version of Microsoft Dynamics AX, see the following topics.

  - For information about supported upgrade paths to Microsoft Dynamics AX 2012, see [Supported upgrade paths](supported-upgrade-paths.md).

  - For the latest information about how to upgrade to Microsoft Dynamics AX 2012, see [Upgrade to Microsoft Dynamics AX 2012](upgrade-to-microsoft-dynamics-ax-2012.md).

  - For information specifically about how to upgrade services and AIF, see [Upgrade AIF code](upgrade-aif-code.md).

## Microsoft Dynamics AX 2012 operations in-depth

### Planning, installation, and deployment

To learn about how to plan, installing, and deploying services and AIF in MSDAX6, see the following topics.

  - For information about how to plan, including exchanging documents between BizTalk Server and AIF, see [Plan for integration](plan-for-integration.md).

  - For information about how to install Microsoft Dynamics AX 2012, see [Install Microsoft Dynamics AX 2012](install-microsoft-dynamics-ax-2012.md).

  - For information about registering services by using the **Installation checklist**, see [Set up Application Integration Framework](set-up-application-integration-framework.md) and the section “Register services” in [Customize service contracts](customize-service-contracts.md)..

  - For information about how to deploy services and AIF by using Message Queuing or web services and IIS, see [Deploy services and AIF](deploy-services-and-aif.md).

### Configuring services and AIF

In AIF, you set up and configure integration ports to manage message exchanges. For more information, see the following topics.

  - For conceptual information about integration ports, see [Integration ports](integration-ports.md).

  - For information about how to set up and configure integration ports, see [Managing integration ports](managing-integration-ports.md).

  - For information about how to set up security for services and AIF, see [Services and AIF security and protection](services-and-aif-security-and-protection.md).

  - For a simple procedure to set up an exchange that reads a sales order from Microsoft Dynamics AX, see [Walkthrough: Exchanging documents by using the NetTcp adapter](walkthrough-exchanging-documents-by-using-the-nettcp-adapter.md).

  - For information about batched messages, see [Processing batched messages in AIF](processing-batched-messages-in-aif.md).

  - For information about how to distribute AIF work among AOSes, see [Configuring network load balancing for services](configuring-network-load-balancing-for-services.md) and [Sequential and parallel processing in services and AIF](sequential-and-parallel-processing-in-services-and-aif.md).

  - For information about change tracking, see [Configuring AIF for change tracking](configuring-aif-for-change-tracking.md).

### Monitoring and troubleshooting services and AIF

Microsoft Dynamics AX lets you manage your document exchanges throughout their life cycle and troubleshoot any issues that affect data transfers.

  - For information about the maintenance and management of services and AIF exchanges, see [Monitoring services and AIF](monitoring-services-and-aif.md).

  - For information about how to troubleshoot issues with services and AIF, see [Troubleshoot services and AIF](troubleshoot-services-and-aif.md).

## Microsoft Dynamics AX 2012 programming in-depth

For a list of walkthroughs that show you how to work with services and AIF, see [Services and AIF Walkthroughs](services-and-aif-walkthroughs.md).

For an introduction to developing with the different types of services in Microsoft Dynamics AX, see [Developing with Services and AIF](developing-with-services-and-aif.md).

### Document Services

The following topics contain information about document services:

  - For information about reading data that uses document services, see [Walkthrough: Reading a Customer by Using the NetTCP Adapter](walkthrough-reading-a-customer-by-using-the-nettcp-adapter.md).

  - For information about coding an outbound exchange, see [Walkthrough: Deploying the Document Service in an Outbound Exchange](walkthrough-deploying-the-document-service-in-an-outbound-exchange.md).

  - For an example of sending a read request to an inbound port by using an XML message and the file system adapter, see [Walkthrough: Reading a Customer by Using the File System Adapter](walkthrough-reading-a-customer-by-using-the-file-system-adapter.md).

  - For information about the classes that make up document services, see [About Document Service Classes](about-document-service-classes.md).

  - You can use the AIF system services to enable clients to interact with and retrieve system information, including metadata, data returned in a query, and user session data.

### System Services

You can use the AIF system services to enable clients to interact with and retrieve system information, including metadata, data returned in a query, and user session data. For an introduction to the AIF system services, see [AIF System Services](aif-system-services.md).

The following topics introduce the capabilities of the AIF system services and provide walkthroughs of common scenarios.

  - For information about the metadata service, see [Metadata Service](metadata-service.md).

  - For an example that calls the metadata service, see [Walkthrough: Calling the Metadata Service](walkthrough-calling-the-metadata-service.md).

  - For information about the query service, see [Query Service](query-service.md).

  - For an example that calls the query service, see [Walkthrough: Calling the Query Service with a Static Query](walkthrough-calling-the-query-service-with-a-static-query.md).

  - For information about the user session service, see [User Session Service](user-session-service.md).

  - For an example that calls the user session service, see [Walkthrough: Calling the User Session Service](walkthrough-calling-the-user-session-service.md).

### Custom Services

The following topic contains a walkthrough for creating a custom service.

  - [Walkthrough: Exposing an X++ Class as a Data Contract](walkthrough-exposing-an-x-class-as-a-data-contract.md)

### Consuming External Web Services

The following topic contains a walkthrough for how to consume an external web service:

  - [Walkthrough: Calling an External Web Service from X++](walkthrough-calling-an-external-web-service-from-x.md)

## Troubleshooting

For information about how to troubleshoot issues with services and AIF, see [Troubleshoot services and AIF](troubleshoot-services-and-aif.md).

## Moving from test to production

When you move from a test environment into production, you can export and import your integration port configurations. For more information, see [Exporting and importing AIF integration port configurations](exporting-and-importing-aif-integration-port-configurations.md).


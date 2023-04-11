---
title: System architecture
TOCTitle: System architecture
ms:assetid: e4cbce28-2f87-4c12-8ea6-6e54d9570ce7
ms:mtpsurl: https://technet.microsoft.com/library/Dd362112(v=AX.60)
ms:contentKeyID: 35133118
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# System architecture 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you understand the internal architecture of Microsoft Dynamics AX, you can more effectively make decisions when you plan, customize, and deploy a system. This topic provides a high-level overview of the system architecture of Microsoft Dynamics AX.

## Microsoft Dynamics AX system architecture

The following diagram provides a high-level overview of the system architecture of Microsoft Dynamics AX. This diagram does not depict the system topology or physical infrastructure that are required for the deployment. Your infrastructure can consist of many Microsoft Dynamics AX components, and these components can be installed on either a single physical server or multiple physical servers. For factors that you must consider when you plan a deployment infrastructure, see [Plan system topology](plan-system-topology.md). For detailed information about Microsoft Dynamics AX components, see [Component architecture](component-architecture.md). For the current hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377) document that is available from the Microsoft Download Center.

![System architecture](images/Dd362112.AX6_sysdocs_Systemarchitecture(AX.60).gif "System architecture")

## Authentication and authorization

Microsoft Dynamics AX uses integrated Windows authentication to authenticate Active Directory Domain Services users. If you configure Microsoft Dynamics AX to use a different authentication provider, users are authenticated by that provider. Authorization for access to data, business functionality, and presentation elements, such as forms, menus, fields, and reports, is governed by Microsoft Dynamics AX security. Anonymous web users can access Enterprise Portal for Microsoft Dynamics AX. However, only limited functionality is available to these users.

For more information, see [Security architecture of the Microsoft Dynamics AX application](security-architecture-of-the-microsoft-dynamics-ax-application.md).

## Presentation tier (clients and external applications)

A client provides an interface to Microsoft Dynamics AX data and functionality. An external application is integrated with Microsoft Dynamics AX to programmatically integrate functionality or exchange data.

  - The Windows client for Microsoft Dynamics AX is a native 32-bit program that provides a rich user interface.

  - Supported web browsers provide access to Microsoft Dynamics AX functionality and data through Enterprise Portal.

  - External applications interact with Microsoft Dynamics AX via services and Application Integration Framework (AIF). Services and AIF provide an extensible framework for XML-based scenarios for enterprise application integration (EAI), business-to-business (B2B), and service-oriented architecture (SOA).


> [!NOTE]
> <P>Use services and AIF to interact with the Microsoft Dynamics AX application. We recommend that you not use .NET Business Connector for integration with the Microsoft Dynamics AX application.</P>



For more information about the architecture of the presentation tier, see the following topics:

  - [Client architecture](client-architecture.md)

  - [Enterprise Portal architecture](enterprise-portal-architecture.md)

  - [Services and AIF architecture](services-and-aif-architecture.md)

## Application tier

The application tier consists of one or more of the following Microsoft Dynamics AX components or computer roles.

## Active Directory domain controller

A domain controller for AD DS is a prerequisite for installing Microsoft Dynamics AX.

For more information, see [Security architecture of the Microsoft Dynamics AX application](security-architecture-of-the-microsoft-dynamics-ax-application.md).

## Application Object Server

Application Object Server (AOS) controls communication among Microsoft Dynamics AX clients, databases, and applications. AOS also hosts Microsoft Dynamics AX services and the workflow system. You can deploy AOS on a single computer or create a load-balanced cluster of multiple AOS instances. AOS is a Windows service that requires a Windows Server operating system. For the current hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377) document that is available from the Microsoft Download Center.

AOS uses libraries from the Microsoft .NET Framework version 4, such as Windows Communication Foundation and Windows Workflow Foundation.

For more information, see [AOS architecture](aos-architecture.md).

## Enterprise Portal

Microsoft Dynamics AX provides a set of websites that give you access to data. On these sites, you can also participate in business processes by using web-based forms. These sites are collectively called Enterprise Portal.

For more information, see [Enterprise Portal architecture](enterprise-portal-architecture.md).

## Enterprise Search

Enterprise Search in Microsoft Dynamics AX enables users to search through data, metadata, and documents that are attached to records by using either the Microsoft Dynamics AX client or Enterprise Portal. All aspects of crawling, indexing, and retrieving Microsoft Dynamics AX data and metadata for search are performed by one of the supported SharePoint 2010 Products.

For more information, see [Enterprise Search architecture](enterprise-search-architecture.md).

## Reporting

Microsoft SQL Server Reporting Services is the primary reporting platform for Microsoft Dynamics AX.

For more information, see [Reporting architecture](reporting-architecture.md).

## Analytics

Microsoft SQL Server Analysis Services is a server-based solution that provides functionality for online analytical processing (OLAP). OLAP reports help users analyze business data and identify trends that they might not discover if they view the data in traditional reports.

For more information, see [Analytics architecture](analytics-architecture.md).

## Workflow

Workflow is a system that is installed together with Microsoft Dynamics AX, and that runs on AOS. The workflow system provides functionality that you can use to create individual workflows, or business processes.

For more information, see [Workflow system architecture](workflow-system-architecture.md).

## Services and Application Integration Framework (AIF)

The capability to integrate Microsoft Dynamics AX with other systems inside and outside the enterprise is a common requirement. Services and AIF provide this capability by enabling the exchange of data through formatted XML.

For more information, see [Services and AIF architecture](services-and-aif-architecture.md).

## Help server

The Help system uses a client/server architecture. Help content is hosted on a dedicated server component, the Help server, which manages the storage and display of product documentation. The Help viewer, which is a component of the Microsoft Dynamics AX client, provides access to Help content from individual workstations.

For more information, see [Help system architecture](help-system-architecture.md).

## Microsoft Project Server integration

The integration of Microsoft Dynamics AX with Microsoft Project Server requires two integration components, the synchronization service for Project Server and synchronization proxy for Project Server. To use the Project Server functionality, you must install both components.

For more information, see [Project Server integration architecture](project-server-integration-architecture.md).

## Data tier

Microsoft Dynamics AX requires several database components.

## The Microsoft Dynamics AX database

The business database is a Microsoft SQL Server database that stores transaction and reference data. This database is functionally equivalent to the principal database in Microsoft Dynamics AX 4.0 and Microsoft Dynamics AX 2009.

For more information, see [Database components](database-components.md).

## The model store

The model store database stores all application elements for Microsoft Dynamics AX. These elements include customizations. Information about layers and models is an integral part of the store. AOS has access to the model store, handles layer flattening, and provides model data to all the Microsoft Dynamics AX subsystems. These subsystems include the subsystems for form rendering, report rendering, and X++ code. The model store replaces the Microsoft Dynamics AX Object Data (AOD) files that were used in earlier versions of Microsoft Dynamics AX.


> [!NOTE]
> <P>The model store has been moved to a separate database in Microsoft Dynamics AX 2012 R2.</P>



For more information, see [Model store architecture](model-store-architecture.md).

## Other databases

Enterprise Portal requires content and configuration databases for SharePoint 2010 products. Reporting Services requires a Reporting Services database. Support for OLAP cubes requires an Analysis Services database. Support for Enterprise Search requires a SharePoint Search Administration database, crawl database, and property database.

## See also

[Architecture and planning](architecture-and-planning.md)

  



---
title: Enterprise Search architecture
TOCTitle: Enterprise Search architecture
ms:assetid: 1bc490b8-fa42-4910-b3b7-6728e05d1dc0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751361(v=AX.60)
ms:contentKeyID: 35132568
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Enterprise Search architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the various concepts and components of Microsoft Dynamics AX Enterprise Search.

## The search experience

Enterprise Search in Microsoft Dynamics AX 2012 enables users to search through data, metadata, and documents that are attached to records by using either the Microsoft Dynamics AX client or Enterprise Portal. Users can search for common nouns such as 'customer' and 'cash flow report'. Users can also search for specific data, such as a customer name, a product ID, or a telephone number. The search box is prominently displayed, and users can view recent search terms in a drop-down list.

## The search engine

All aspects of crawling, indexing, and retrieving Microsoft Dynamics AX data and metadata for Search are performed by one of the following products:

  - Microsoft SharePoint Foundation 2010 or Microsoft SharePoint Server 2010

  - Microsoft Search Server 2010 or Microsoft Search Server Express 2010

  - Microsoft FAST Search Server 2010

  - Microsoft SharePoint Foundation 2013 or Microsoft SharePoint Server 2013

One of these products must be available in the computing environment before you can install Enterprise Search. For more information about Enterprise Search, see [Enterprise Search](enterprise-search.md).

## Installation and configuration overview

This section provides a high level overview of how an administrator installs and configures Microsoft Dynamics AX Enterprise Search.

## Install Enterprise Search

Microsoft Dynamics AX Enterprise Search is installed by using Setup. Setup installs the Microsoft Dynamics AX Search Service, which enables Microsoft Dynamics AX clients and Enterprise Portal to communicate with the SharePoint Search service. Setup also configures the Business Connector proxy account and the Enterprise Search account. After Setup finishes installing Search, the system publishes the out-of-box searchable queries and starts the full data and metadata crawl. For more information about how to install search, see [Install Microsoft Dynamics AX Enterprise Search](install-microsoft-dynamics-ax-enterprise-search.md).

## Specify searchable data and metadata

After you install Enterprise Search, you specify which data and metadata should be indexed for search by configuring Microsoft Dynamics AX queries. Specifically, in the **Queries** node of the Application Object Tree (AOT), you set the **Searchable** property to True for those queries that should be indexed for search. After you specify a query as searchable, you must check the best practices on the query to ensure it can be published to the Microsoft SharePoint Business Data Connectivity Service (BCS). Administrators must work closely with business decision makers to identify queries that should be searchable.

## Search Configuration wizard

After queries are identified as searchable, you publish those queries to the BCS by using the Search Configuration wizard. The Search Configuration wizard includes several screens that enable administrators to select which queries to publish, and which fields should be available in search results. For more information about how to use the Search Configuration wizard, see [Configure Enterprise Search by using the Search Configuration wizard](configure-enterprise-search-by-using-the-search-configuration-wizard.md). For information about related administrative tasks for deploying and configuring Enterprise Search, see [Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md).

## Crawling and indexing

After the queries have been published, the SharePoint Search service runs in the context of the Enterprise Search account to crawl the Microsoft Dynamics AX database. After the crawl is completed, users can view search results depending on their role assignments in Microsoft Dynamics AX. For information about the Enterprise Search account, see [Configure the Search Crawler account](configure-the-search-crawler-account.md).

## The Search Service

Setup installs the Microsoft Dynamics AX Enterprise Search service on the web server. The Microsoft Dynamics AX Enterprise Search service is a .NET DLL that enables Microsoft Dynamics AX clients and Enterprise Portal to communicate with SharePoint by using web services. The Microsoft Dynamics AX Enterprise Search service also enables communication between SharePoint and Application Object Server (AOS) services for crawling, indexing, and retrieving data from the Microsoft Dynamics AX database.

## Enterprise Search architecture

The following diagram provides a high-level overview of the Microsoft Dynamics AX Enterprise Search architecture.

![Enterprise Search Architecture](images/Gg751361.EnterpriseSearchArchitecture(AX.60).gif "Enterprise Search Architecture")

## See also

[System architecture](system-architecture.md)

[System requirements](http://go.microsoft.com/fwlink/?linkid=165377)

[Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: AIF System Services
TOCTitle: AIF System Services
ms:assetid: 9ac4d96b-d6de-4f31-8cd0-4de0d707392d
ms:mtpsurl: https://technet.microsoft.com/library/Gg879657(v=AX.60)
ms:contentKeyID: 35248154
author: Khairunj
ms.author: daxcpft
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# AIF System Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

System services are Windows Communication Foundation (WCF) services that are included with Microsoft Dynamics AX. These services enable clients to interact with and retrieve system information. The system services include the following:

  - [Metadata Service](metadata-service.md) – Enables you to retrieve information about elements in the AOT. You can retrieve metadata for labels, menus, menu items, tables, extended data types, data types, enums, queries, web menus, web menu items, info parts, cues, dimensions, form parts, web controls, service groups, and services. The metadata service should be used when you want to return information about the structures in Microsoft Dynamics AX to a client application. For example, if you want to return information about a table such as what indexes exist on that table, you can use the metadata service.

  - [Query Service](query-service.md) – Enables you to issue a query for data without using an Application Integration Framework (AIF) document service or creating a custom service. The query service returns data in a dataset and implements a paging mechanism so that you can manage queries that return large amounts of data.
    
    When you call the query service, you can specify the query to run in one of three different ways:
    
      - Static query – A query that is already defined in the AOT under the **Queries** node.
    
      - User-defined query – A query that is defined by using the QueryMetadata class which is found in the metadata service.
    
      - Dynamic query – A query that is defined in an X++ class that extends the AifQueryBuilder class. All query logic resides in the query builder class

  - [User Session Service](user-session-service.md) – Enables you to return information about the current Windows user. You can return information such as the user’s default language, default company, default company time zone, permissions to access-controlled items, and so on.

The system services are hosted by the Application Object Server (AOS). The system services are automatically installed as part of the setup process and are always available.


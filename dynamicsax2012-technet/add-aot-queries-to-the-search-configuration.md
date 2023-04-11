---
title: Add AOT queries to the Search configuration
TOCTitle: Add AOT queries to the Search configuration
ms:assetid: 1d4707eb-72d0-4d91-8432-eb5e5a4bbfb9
ms:mtpsurl: https://technet.microsoft.com/library/Hh500181(v=AX.60)
ms:contentKeyID: 37820245
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Add AOT queries to the Search configuration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to add a new query for the Microsoft Dynamics AX Application Object Tree (AOT) to the Search configuration. After you add one or more queries to the Search configuration, you can publish the configuration so that the underlying database tables are indexed for Search.

## Before you begin

Before you configure AOT queries for Search, read [Enterprise Search security and protection](enterprise-search-security-and-protection.md) to learn about restrictions for certain kinds of queries and database tables.

## Add a new query to Search

1.  In the AOT, expand the **Queries** node.

2.  Select a query to add to the Search configuration.

3.  In the **Properties** pane, click **Searchable**, and then click **Yes** in the list.

4.  Right-click the query, click **Add-ins**, and then click **Check best practices**. Verify that there are no best practice errors. If there are errors, the query might not be configurable for Search. Review the errors to learn more.

5.  After you have configured queries for Search, update caches so that the changes are available in the Search Configuration Wizard. In the AOT, click the **Tools** menu, click **Caches**, and then click **Refresh elements**.

## Update the Search Crawler role

When you install Enterprise Search, the domain account that is assigned the Search Crawler role in Microsoft Dynamics AX is configured to have read-only permissions for queries that are configured for Search. When you configure new queries for Search, you must reset the permissions of the Search Crawler role to read-only for all searchable entities.

1.  Click **System administration** \> **Setup** \> **Search** \> **Update search crawler role**.

2.  Click **OK**.

## Next steps

The queries that you configured for Search are now ready to be published to the SharePoint Business Data Connectivity service. To publish the queries, you use the Search Configuration Wizard. After the queries are published to SharePoint, they are indexed, so that users can view results when they search in the Microsoft Dynamics AX client or Enterprise Portal for Microsoft Dynamics AX. For information about how to publish queries to SharePoint, see [Configure Enterprise Search by using the Search Configuration wizard](configure-enterprise-search-by-using-the-search-configuration-wizard.md).

## See also

[Import Search configurations to an AOS](import-search-configurations-to-an-aos.md)

  



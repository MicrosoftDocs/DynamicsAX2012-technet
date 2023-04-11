---
title: Enterprise Search security and protection
TOCTitle: Enterprise Search security and protection
ms:assetid: 53d56eec-e274-4ac1-b89f-35ef10326145
ms:mtpsurl: https://technet.microsoft.com/library/Hh433510(v=AX.60)
ms:contentKeyID: 36941291
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Enterprise Search security and protection 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how Microsoft Dynamics AX restricts access to data, metadata, and documents in Enterprise Search results. If Search is installed by using Setup, users can search in the Microsoft Dynamics AX client or Enterprise Portal. After you install Search, the search box is available in the Microsoft Dynamics AX client. The data that is returned by Search is determined by queries that are listed in the Application Object Tree (AOT) and design features that trim data in Search results.


> [!NOTE]
> <P>In this topic, Search results that include data, metadata, and documents are referred to as <EM>data</EM>.</P>



## Application Object Tree queries

Data can only be crawled and indexed for Search if the database table is included in an AOT query in Microsoft Dynamics AX. After the table is specified in a query, the query must be configured for Search. You configure a query for Search by setting the **Searchable** property to **True** in the AOT. By default, only the following queries are configured for Search. These queries are automatically published and indexed after you install Enterprise Search:

  - BdcDocuRef

  - CustTableListPage

  - EcoResProductPerCompanySearch

  - HcmWorkerListPage

  - SecurityRoleAllTasks

  - smmBusinessRelations\_NoFilter

  - VendorEnterpriseSearch

If you configure queries for Search, you must publish the queries to the SharePoint Business Data Connectivity Service, so that the tables can be crawled and indexed for Microsoft Dynamics AX Enterprise Search. For information about how to publish Microsoft Dynamics AX queries for Search, see [Configure Enterprise Search by using the Search Configuration wizard](configure-enterprise-search-by-using-the-search-configuration-wizard.md).

## Design features that trim data in Search results

The following design features of Microsoft Dynamics AX Enterprise Search help trim data in Search results.

## Role-based security

Microsoft Dynamics AX restricts the data that is returned in Search results, based on each user’s role in Microsoft Dynamics AX. Role-based security trims data at the level of database tables, records, and fields.

  - **Tables** – When a user performs a search, Microsoft Dynamics AX verifies that members of the user’s role can view the tables that are listed in the AOT query. If the role does not have permission to view data from a table, Search trims the results. For example, an AOT query includes Table 1 and Table 2, but a user’s role only has permission to view data from Table 1. In this case, Search returns data from Table 1 but trims all data from Table 2.

  - **Records** – When a user performs a search, Microsoft Dynamics AX verifies that members of the user’s role can view the records that are contained in the tables in the AOT query. If the role does not have permission to view one or more records in a table, Search trims the results. For example, an AOT query includes Table 1, a user’s role has permission to view data from Table 1, but Table 1 has a record that the user’s role is not permitted to view. In this case, Search returns data from Table 1 but trims the data for the restricted record.

  - **Variable field access** – Microsoft Dynamics AX excludes a field from Search results if the field has different access permissions for different roles. For example, a record includes a field that is named **Employee Performance Score**. Role 1 can view the field, but Role 2 cannot view the field. In this case, the data in the field is excluded from all Search results. Therefore, **Employee Performance Score** is not displayed in the Search results, regardless of the user who performed the search, because the field is not indexed by Search. Fields that have variable access are not indexed and are therefore not discoverable in Search.

## Form references

Tables in the AOT include a **FormRef** property. This property specifies the form that is used in the Microsoft Dynamics AX client to enter data for a specific table. Tables also include a **SearchLinkRefName** property. This property specifies the form that is used in Enterprise Portal to enter data for a specific table. If either of these properties is empty, Search excludes results for form metadata for the corresponding client, the Microsoft Dynamics AX client or Enterprise Portal. For example, an AOT query includes Table 1, and the **FormRef** property is empty for Table 1. In this case, Search results do not include metadata links to the form.

## See also

[Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md)

[Enterprise Search architecture](enterprise-search-architecture.md)

  



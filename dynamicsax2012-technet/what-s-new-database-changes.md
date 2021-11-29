---
title: "What's new: Database changes"
TOCTitle: Database changes
ms:assetid: f018bd64-b86b-4ac7-b459-19694e06aaab
ms:mtpsurl: https://technet.microsoft.com/library/Gg732282(v=AX.60)
ms:contentKeyID: 35133227
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Database changes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information about changes in Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 R2 that affect databases.

## Database changes that affect system administrators

This section provides information about new features and enhancements in AX 2012 that affect system administrators.

## Microsoft SQL Server–based databases

In AX 2012 R2, you must create your Microsoft Dynamics AX business and model store database on SQL Server. You cannot create the Microsoft Dynamics AX database on an Oracle database server. All other databases, such as the databases that are used for Microsoft SharePoint 2010 products and Microsoft SQL Server Reporting Services, also require SQL Server.

## Application files are now stored in the model store database

In the previous version of Microsoft Dynamics AX, the application files, or AOD files, that contained Microsoft Dynamics AX metadata were stored on a file share. In this version, application objects are stored in the model store database and are managed as model files.

AX 2012 R2 has two databases. The business database contains transaction and master data. The model store database contains application objects, which are managed as model files. This database replaces the application file store (AOD) in previous versions. You can name the business database. The model store database has the same name as the business database, but \_model is appended. Both databases must be stored on the same instance of SQL Server.


> [!IMPORTANT]
> <P>Before AX 2012 R2, the model store was stored in the same database as business data. Starting in AX 2012 R2, the databases were separated.</P>



## Fixed schema

This version of Microsoft Dynamics AX has a fixed schema. In other words, tables and fields are no longer dropped and then added again when license or configuration keys are changed. This change applies to all tables and fields, except some that are used during upgrade (SysDeletedObjectsXX). These tables and fields are dropped when the relevant configuration keys are disabled in a production environment. This change was made to better support Microsoft SQL Server Analysis Services cubes on Role Centers.

## Full-text search

In this version, Microsoft Dynamics AX provides full-text search, which lets you search business data over a large volume of text data or documents. Full-text search also supports additional features, such as language-specific word breakers, stemmers, and extensible APIs. You can create a full-text index on tables that are associated with the **Main** or **Group** table type.


> [!NOTE]
> <P>You must configure the functionality for SQL Server full-text search before you can use this functionality in Microsoft Dynamics AX. For more information, see <A href="https://go.microsoft.com/fwlink/?linkid=216841">Full-Text Search (SQL Server)</A>.</P>



Like regular SQL Server indexes, full-text indexes can be updated automatically when data is modified in the associated tables. By default, this behavior is used for Microsoft Dynamics AX. In the Microsoft Dynamics AX Application Object Tree (AOT), developers can set the **ChangeTracking** property of a full-text index to either **Auto** or **Manual**. If **ChangeTracking** is set to **Auto**, SQL Server automatically updates the index when data is modified in the associated tables. If **ChangeTracking** is set to **Manual**, you must manually update the index at a specified interval. For more information, see [Getting Started with Full-Text Search](https://go.microsoft.com/fwlink/?linkid=216842). By default, the **ChangeTracking** property is set to **Auto** when a new full-text index is created. The **Auto** setting provides optimal response time and throughput for your program.

## TempDB temporary tables

A new type of temporary table that is created in the TempDB database is available in AX 2012. In the AOT properties for a table, the **TableType** property is now an enum. The **InMemory** enum value is the type of temporary table that was created on Microsoft Dynamics AX Application Object Server (AOS) or the client in earlier versions of Microsoft Dynamics AX. The **TempDb** enum value is the new type of temporary table that is created in the SQL Server TempDB database. TempDB temporary tables can be joined on the database tier with tables from the Microsoft Dynamics AX database. The use of TempDB temporary tables can improve performance and simplify the programming model. The domain account that you use for the Microsoft Dynamics AX service must have read and write access to the TempDB database.


> [!NOTE]
> <P>SQL Server creates TempDB at startup. Therefore, you must assign permissions to TempDB every time that SQL Server starts or restarts.</P>



## Support for SQL Server 2012 AlwaysOn availability groups

The AlwaysOn availability groups feature in SQL Server is a high-availability and disaster recovery solution that provides an enterprise-level alternative to database mirroring. AlwaysOn availability groups were introduced in SQL Server 2012 and maximize the availability of a set of user databases for an enterprise. An availability group supports a failover environment for a discrete set of user databases that fail over together. These databases are known as availability databases. An availability group supports a set of read-write primary databases and one to four sets of corresponding secondary databases. Optionally, secondary databases can be made available for read-only access and some backup operations. For more information, see [SQL Server topology recommendations for availability and performance](sql-server-topology-recommendations-for-availability-and-performance.md).

## Implementation considerations for new features

This section provides information about implementation considerations for the new features in AX 2012.

## Planning and architecture considerations

Planning the database infrastructure and storage is a critical requirement for optimal Microsoft Dynamics AX performance. For more information, see [Configure SQL Server and storage settings](configure-sql-server-and-storage-settings.md).

## Upgrade considerations

For information about how to upgrade from previous releases of Microsoft Dynamics AX, see [Upgrade to Microsoft Dynamics AX 2012](upgrade-to-microsoft-dynamics-ax-2012.md).

## Administration changes

Database administration activities, such as database backup, recovery, and data recovery planning, must incorporate the following enhancements in AX 2012:

  - The business database, model store database, and baseline model store databases

  - Full-text search

  - Support for SQL Server 2012 AlwaysOn availability groups to increase availability

## Database enhancements that affect developers

This section provides information about new features and enhancements in AX 2012 that affect developers.

## Table inheritance

Object-oriented programming languages, such as C\# and C++, support inheritance relationships between classes. A derived class inherits fields and methods from its base class. AX 2012 supports similar inheritance between tables in the AOT.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>All, especially those feature areas that query tables that are involved in inheritance relationships</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Technical decision makers</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Table inheritance provides better support than traditional foreign key relationships for customized extensions.

Table inheritance provides a rich type of metadata that describes the relationships between tables. Tools can use this metadata to provide better functionality.

## Special considerations

The following tables are some of the base tables that are involved in inheritance relationships:

  - AgreementHeader

  - AgreementLine

  - BankLC

  - BankLCLine

  - CaseDetailBase

  - CatProductReference

  - DirPartyTable

  - EcoResProduct

  - HRPDefaultLimit

  - IntercompanyActionPolicy

  - VendRequest

Because of inheritance relationships between tables, some fields in Microsoft Dynamics AX 2009 have been moved to different tables in AX 2012. Some legacy custom queries might have to be updated. This update requires the same amount of pre-upgrade work as any change to table schemas. In some cases, the size of an X++ SQL Select statement can decrease, and the statement can become simpler.

## Comparison with AX 2009

The application data framework has changed since AX 2009. AX 2012 includes changes to the following aspects:

  - AOT design time aspects

  - Query development aspects

## AOT design time aspects

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Capture rich metadata about the relationships between tables.</p></td>
<td><p>Foreign key relationships were supported. Inheritance relationships between tables could be managed only by custom code.</p></td>
<td><p>Inheritance relationships between tables can be captured and described by setting properties on the tables.</p></td>
<td><p>Developers can more fully express the relationships between certain entities.</p></td>
</tr>
</tbody>
</table>


## Query development aspects

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Access fields from various tables by using simpler code.</p></td>
<td><p>A query could take advantage of a foreign key relationship to obtain fields from a parent table by joining.</p></td>
<td><p>A query can take advantage of an inheritance relationship to obtain fields from a parent table without joining.</p></td>
<td><p>X++ SQL code and AOT queries take less developer time to create and maintain.</p></td>
</tr>
</tbody>
</table>


## Table relations

In AX 2009, table relations could be defined through extended data types (EDTs). In AX 2012, table relations are defined under the **Relations** node for each table in the AOT. Each relation has properties that can be set in the **Properties** window.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Technical decision makers</p>
<p>ISVs/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

The new format enables rich metadata to be stored about each table relation. The metadata can be used throughout the application to increase functionality.

**Examples**

  - In AX 2012, the system stores the cardinality of each relationship. Tools that generate diagrams of database entity relationships in Microsoft Visio 2010 can read the cardinality data to draw the diagram correctly.

  - The new **UnitOfWork** class simplifies transaction management for table relations that are defined under the **Relations** node for a table. However, the **UnitOfWork** class cannot take advantage of relations that are defined through EDTs.

## Special considerations

  - In AX 2012, table relations can no longer be created through EDTs.

  - Legacy custom table relations that were defined through EDTs continue to work in AX 2012.

## Comparison with AX 2009

Table relations are defined in a new way in AX 2012.

## AOT table relations

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Define a table relation by using the AOT.</p></td>
<td><p>Table relations were defined only through EDTs. This limitation was a problem if multiple relations were required between tables, or if relations involved composite keys.</p></td>
<td><p>EDT table relations are recognized, but relations are now defined under the <strong>Relations</strong> node for an individual table.</p></td>
<td><p>Relationship metadata can be stored. This feature supports other system features and future growth.</p></td>
</tr>
<tr class="even">
<td><p>Automatically migrate table relations to the AOT.</p></td>
<td><p>Not available</p></td>
<td><p>A tool is provided that converts legacy table relations from EDT nodes to table nodes in the AOT.</p></td>
<td><p>This automation can save the developer time and reduce the chance of errors.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about table relations, see the [EDT Relations Migration Tool](https://msdn.microsoft.com/library/da71a84d-1414-47ce-91d7-773f4a0d29bc\(ax.60\).aspx) topic on MSDN.

## Inactive tables remain

Sometimes, deactivating a configuration key affects a table in Microsoft Dynamics AX. In AX 2009 and earlier versions, the associated table was removed from the underlying SQL Server database. When queries were run on that table later, messages were displayed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>All, especially operations that issue SQL queries from outside Microsoft Dynamics AX</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Technical decision makers</p>
<p>ISVs/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Tables that are deactivated by a configuration key now remain available to external SQL queries. This functionality can provide a practical benefit, depending on the ongoing data changes that must be made to the tables.

## Special considerations

System administrators who deactivate a configuration key must inform users who issue external SQL queries that the data in the deactivated tables will no longer be updated, and that the data in those tables will become outdated. After a configuration key has been deactivated, messages are no longer displayed for external SQL queries.

## Comparison with AX 2009

The effects that deactivated configuration keys have on tables have changed since AX 2009. AX 2012 includes changes to the following aspects:

  - SQL queries on inactive tables

## SQL queries on inactive tables

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Run queries on inactive tables in Microsoft Dynamics AX.</p></td>
<td><p>Queries failed, and messages were displayed.</p></td>
<td><p>Queries on inactive tables continue to function, but data in the inactive tables is ignored.</p></td>
<td><p>Queries on the tables still function.</p></td>
</tr>
<tr class="even">
<td><p>Run external queries on tables from Microsoft Dynamics AX.</p></td>
<td><p>Queries failed, and messages were displayed.</p></td>
<td><p>Queries on inactive tables continue to function, but data from the inactive tables is outdated.</p></td>
<td><p>Queries on the SQL Server database still function.</p></td>
</tr>
</tbody>
</table>

  



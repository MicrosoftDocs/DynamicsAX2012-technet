---
title: Master Data Management in Microsoft Dynamics AX
TOCTitle: Master Data Management in Microsoft Dynamics AX
ms:assetid: c6c0d477-625d-445a-9afc-96f2ce7301b8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720451(v=AX.60)
ms:contentKeyID: 62224158
ms.date: 04/25/2014
mtps_version: v=AX.60
---

# Master Data Management in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Master Data Management (MDM) is a feature of Microsoft Dynamics AX 2012 R3 that lets you synchronize master data records across multiple instances of Microsoft Dynamics AX 2012. By creating and maintaining a single copy of master data, you can help guarantee the consistency of important information, such as customer and product data, that is shared across AX 2012 instances. Master data is stored in a central data store. This central store then synchronizes the data with each AX 2012 instance on a defined schedule. MDM uses Microsoft SQL Server Master Data Services (SQL MDS) as the central data store and AX 2012 Data Import/Export Framework entities as the unit for data synchronization. MDM is preconfigured to support synchronization of the Customers, Vendors, Employees, Global Address Book, and Product entities. You can also create customizations to support other Data Import/Export Framework entities in MDM.

## When to Use MDM

You should use MDM if you have multiple AX 2012 deployments that rely on the same reference data. MDM should be used only with reference data that is non-transactional and that tends not to change very often. This data includes people, products, and locations. Typically, transactional data is unique to a deployment and should not be used with MDM.

If you are using the [Intelligent Data Management Framework for Microsoft Dynamics AX](microsoft-dynamics-ax-intelligent-data-management-framework-idmf.md) to automatically purge data, you can still use MDM. However, you should plan ahead and decide how you want to handle purging data in subscribed entities. If this data is purged, the related records must be manually cleaned from the master data store and the other participating AX 2012 instances.

## Data Visibility

By default, all data in subscribed entities is visible to all spokes, regardless of the legal entity or partition. You can limit this visibility by configuring filtering in your MDM implementation. Use queries and views to constrain the datasets that are available for each spoke. For more information, see [Configure Master Data Management](configure-master-data-management.md).

## MDM Features

MDM provides several standard features that you can use to tune your MDM implementation:

  - **Single-master or multi-master record modification** – You can configure a single-master environment, where only one AX 2012 instance can push updated data to SQL MDS, and all other instances are read-only. Alternatively, you can configure a multi-master environment, where all AX 2012 instances can update master data records.

  - **Synchronization scheduling** – You can schedule entities to sync with the master database every hour, day, or week. Synchronization groups permit you to more easily schedule entities that you want to sync at the same time.

  - **Data filtering** – You can limit the records that are pulled from the master data store to a AX 2012 instance by defining a view that retrieves a specified subset of data. For example, if you have subsidiaries in multiple geographic locations, you might want the instance in each location to pull down only products that are sold in that region. You can also limit the records that are pushed to the master data store from a AX 2012 instance by defining a query that similarly narrows the data that is selected. For example, if your vendors must meet specific requirements before they can be used in all geographic locations, you might want to synchronize only vendor records that are approved for use across the company.

  - **Conflict identification and resolution** – When two instances make different updates to the same record, this conflict is recognized, and the conflicting records are flagged in the master data store. The conflict is reported to MDM so that you are alerted. You can then use the SQL Server Master Data Services Add-In for Microsoft Excel to manually resolve the conflict.

  - **Customization support** – You can extend your master data coverage by adding or customizing Data Import/Export Framework entities that are used with MDM.

## MDM Architecture

MDM uses the following components to provide functionality:

  - [SQL Server Master Data Services](http://go.microsoft.com/fwlink/?linkid=393133%26clcid=0x409) acts as the central data store, and provides change tracking and conflict detection on the master data records.

  - The AX 2012 Data Import/Export Framework handles the import and export of updated records between each AX 2012 instance and SQL MDS by using Data Import/Export Framework entities. For more information about the Data Import/Export Framework, see [Data import/export framework user guide (DIXF, DMF)](data-import-export-framework-user-guide-dixf-dmf.md).

  - The Master Data Management module identifies changed records that have to be synchronized. This module also schedules and runs the synchronization jobs between each AX 2012 instance and SQL MDS. Additionally, the module provides tools that let you perform the following tasks:
    
      - Provision AX 2012 entities so that they can be used in SQL MDS.
    
      - Configure each spoke to determine synchronization scheduling and other behavior.
    
      - Review conflicts in record data.

The SQL MDS database acts as a central hub, and each participating AX 2012 instance is a spoke. MDM pushes data from each spoke to send changes from that spoke to the master database. MDM then pulls data to get the canonical copy of the data back from the master database. Records are correlated across SQL MDS and the AX 2012 instances, based on a shared natural key or primary key. However, each record in each instance still has a unique record ID as well.

A typical workflow between the hub and a spoke is as follows:

1.  Changes are made in underlying tables that are encapsulated by an entity.

2.  Change tracking in the AX 2012 database identifies the changes. These changes are then extracted by an MDM job into a Data Import/Export Framework staging table.

3.  The changes are pushed out from the staging table to SQL MDS. There, the master data is updated with the new information if there are no conflicts. If there are conflicts, the conflicting records are set aside, and you are notified to manually resolve the conflicts.

4.  MDM queries SQL MDS and retrieves any updated master data. MDM pulls this data back to the AX 2012 instance and loads it into staging tables.

5.  A Data Import/Export Framework import job collects the data from the staging tables and performs inserts/updates to the appropriate target tables to bring them up to date.

The following illustration shows a typical workflow between SQL MDS and the AX 2012 MDM components.

![MDM components and the basic workflow between them](images/Dn720451.MDMtopology(AX.60).gif "MDM components and the basic workflow between them")

## See also

[Deploy Master Data Management](deploy-master-data-management.md)

[Configure Master Data Management](configure-master-data-management.md)

[Manage Master Data Management](manage-master-data-management.md)

[Add an Entity to Master Data Management](add-an-entity-to-master-data-management.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


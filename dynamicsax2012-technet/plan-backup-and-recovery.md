---
title: Plan backup and recovery
TOCTitle: Plan backup and recovery
ms:assetid: 91864f99-40c7-4f58-9947-02a7de0be946
ms:mtpsurl: https://technet.microsoft.com/library/Dd361990(v=AX.60)
ms:contentKeyID: 36584379
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Plan backup and recovery 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By carefully planning and implementing a backup and restore strategy, you can help protect your environment against data loss. In addition to the transaction data that is stored in the business databases, all models and customizations are now stored in the model store databases. Therefore, we recommend that you protect both the business databases and the model store databases in your Microsoft Dynamics AX environment. Develop a strategy, and regularly test your backup and recovery procedures to make sure that you are prepared to effectively respond to a failure or disaster.


> [!IMPORTANT]
> <P>Microsoft Dynamics AX does not include any built-in backup and recovery tools. We assume that you rely on Microsoft SQL Server or other tools that support backup and recovery. For example, Microsoft System Center Data Protection Manager can be used to protect Microsoft Dynamics AX. For more information, see <A href="protecting-microsoft-dynamics-ax-environments-with-system-center-2012-data-protection-manager-dpm.md">Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)</A> and <A href="https://go.microsoft.com/fwlink/?linkid=230427">How to Protect Microsoft Dynamics AX 2009 with System Center Data Protection Manager 2007 sp1</A>.</P>



## The importance of backups

A backup is a copy of a database that is used to restore and recover data after a system failure. By using appropriate backups, you can recover from many failures, such as the following kinds:

  - Media failures

  - User errors, such as a table that is dropped by mistake

  - Hardware failures, such as a damaged disk drive or permanent loss of a server

  - Natural disasters

Database backups are also useful for routine purposes. For example, you can use a database backup to copy the database from one server to another, set up database mirroring, or archive the database for governmental purposes. For information about how to select and implement a backup and recovery strategy, see your database documentation.

## Databases that must be backed up

Include all the databases in your Microsoft Dynamics AX system in your backup and restore strategy:

  - The SQL Server Microsoft Dynamics AX business database.

  - The Microsoft Dynamics AX model store database. The name of this database consists of the name of the business database plus **\_model**.

  - The Microsoft SharePoint Server 2010 databases that support Enterprise Portal for Microsoft Dynamics AX.

  - The SharePoint 2010 products databases that support Enterprise Search.

  - The Microsoft SQL Server Reporting Services database that supports ad hoc reporting.

  - The Microsoft SQL Server Analysis Services database that supports OLAP reporting.

  - The Microsoft BizTalk Server database, if BizTalk Server is deployed.

  - Databases that are used by any applications that are integrated with Microsoft Dynamics AX.

## Backup and recovery strategies

A well-designed backup and recovery strategy maximizes data availability and minimizes data loss. The actual amount of data that is available and the amount of data that is lost depend on your business requirements, environment, and resources. A backup and recovery strategy is based on service level agreements for recovery point objective (RPO) and recovery time objective (RTO).

  - A recovery point objective specifies the acceptable interval between backups, or how much data loss is acceptable.

  - A recovery time objective specifies the service level agreement for the time that a recovery takes.

A backup strategy defines the type and frequency of backups, the nature and speed of the hardware that is required for backups, and backup security. A backup strategy also defines how backups are tested, where backup media is stored, and how it is stored.

A recovery strategy defines how to restore databases to meet your goals for availability of the database and for minimizing data loss. A recovery strategy also defines who recovers the data.

We recommend that you document your backup and recovery procedures and that you keep a copy of the documentation in your operations manual.

Designing an effective backup and recovery strategy requires careful planning, implementation, and testing. Consider the following factors:

  - RPO and RTO

  - Availability requirements

  - Constraints on resources, such as hardware, personnel, space for storing backup media, and the physical security of the stored media

  - The use of each of your databases:
    
      - How often does the data in each database change?
    
      - Are some tables modified more often than others?
    
      - What are your critical time periods? What are the usage patterns during these periods?
    
      - When does the database experience heavy use that causes frequent inserts and updates? You may want to schedule differential or log backups during periods of heaviest use, and full backups during off-peak hours.
    
      - Does the database require additional protection, or can the information that it stores be re-created from other sources and still comply with your service level agreements?

## Next steps

For more information about how to implement a backup and recovery strategy for your environment, see the following documentation:

  - [Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)](protecting-microsoft-dynamics-ax-environments-with-system-center-2012-data-protection-manager-dpm.md)

  - [Back up and recover databases (SQL Server)](back-up-and-recover-databases-sql-server.md)

  - [Backing Up and Restoring Databases in SQL Server](https://go.microsoft.com/fwlink/?linkid=215815)

  - [High Availability and Disaster Recovery for SharePoint Server 2010](https://go.microsoft.com/fwlink/?linkid=215820)

  - [Backup and Restore Operations for a Reporting Services Installation](https://go.microsoft.com/fwlink/?linkid=215818)

  - [Managing Backing Up and Restoring (Analysis Services)](https://go.microsoft.com/fwlink/?linkid=215819)

  



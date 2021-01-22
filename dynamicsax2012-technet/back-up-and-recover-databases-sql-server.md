---
title: Back up and recover databases (SQL Server)
TOCTitle: Back up and recover databases (SQL Server)
ms:assetid: f63959d7-376c-4e69-afe9-0ed03ba13a1f
ms:mtpsurl: https://technet.microsoft.com/library/Dd362128(v=AX.60)
ms:contentKeyID: 36584408
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Back up and recover databases (SQL Server) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how back up or recover a Microsoft Dynamics AX business database or model store database, using the backup and recovery tools for Microsoft SQL Server. This topic provides links to instructions that describe how to use SQL Server Management Studio to back up and recover a Microsoft Dynamics AX database. Before you begin a backup, we recommend that you read [Plan backup and recovery](plan-backup-and-recovery.md).

If you have to recover a database to a different environment, you must complete additional steps.

## Back up the Microsoft Dynamics AX databases

Database backups can be resource-intensive and can cause the whole system to slow down. We recommend that you schedule backups during times when system use is low.

The account of the user who performs the backup must be a member of the **db\_backupoperator** fixed database role for SQL Server on the database server where each database is stored.

For detailed instructions, see [How to: Back up a database](https://go.microsoft.com/fwlink/?linkid=216758).

## Recover the Microsoft Dynamics AX databases

Before you recover the Microsoft Dynamics AX databases, you must close all connections and take all instances of Application Object Server (AOS) offline.

Backups must be restored in the order in which they were created. Before you can restore a particular backup, you must restore the previous backups.

Follow these steps to use SQL Server tools to restore a content database.

1.  If you can, back up the live transaction log of the content database. This backup helps protect any changes that were made after the most recent full or differential backup. For more information, see [How to: Back up a transaction log](https://go.microsoft.com/fwlink/?linkid=216754).

2.  Restore the most recent full database backup. For more information, see [How to: Restore a database backup](https://go.microsoft.com/fwlink/?linkid=216755).

3.  Restore the most recent differential database backup that occurred after the most recent full database backup. For more information, see [How to: Restore a differential backup](https://go.microsoft.com/fwlink/?linkid=216756).

4.  Restore all backups of the transaction log that occurred after the most recent full or differential database backup. For more information, see [How to: Restore a transaction log backup](https://go.microsoft.com/fwlink/?linkid=216757).

## See also

[Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)](protecting-microsoft-dynamics-ax-environments-with-system-center-2012-data-protection-manager-dpm.md)

  



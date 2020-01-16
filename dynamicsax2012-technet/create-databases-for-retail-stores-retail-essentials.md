---
title: Create databases for retail stores (Retail essentials)
TOCTitle: Create databases for retail stores (Retail essentials)
ms:assetid: d57a3d13-28da-441e-8a72-7ad5c764b8af
ms:mtpsurl: https://technet.microsoft.com/library/Dn736963(v=AX.60)
ms:contentKeyID: 62200441
author: Khairunj
ms.date: 12/17/2014
mtps_version: v=AX.60
f1_keywords:
- d57a3d13-28da-441e-8a72-7ad5c764b8af
- MsDynAx060.d57a3d13-28da-441e-8a72-7ad5c764b8af
---

# Create databases for retail stores (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create and update retail store databases by using the Retail Store Database Utility. A store database can be created on either a shared database server or a point-of-sale (POS) register for offline use.

**Prerequisites**

Before you can create or update retail store databases, you must do the following:

  - On each computer where you want to create a store database, use the Setup wizard for Retail essentials to install the Retail Channel Configuration Utility. For more information, see [Install the Retail Channel Configuration Utility (Retail Store Database Utility)](install-the-retail-channel-configuration-utility-retail-store-database-utility.md).
    
    The Retail Channel Configuration Utility can also be used to configure a basic POS register that does not have an offline database. For more information, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).

  - Install a supported version of Microsoft SQL Server on the computer where you plan to run the Retail Store Database Utility. For a list of supported operating systems and SQL Server versions, see [Microsoft Dynamics AX system requirements](http://go.microsoft.com/fwlink/?linkid=165377). For information about how to configure SQL Server for store and offline databases, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).

**Procedures in this topic**

This topic contains the following sections:

  - Create a store database on a database server

  - Distribute initial data to the store database

  - Create a POS register that has an offline database

  - Synchronize data between the store database and offline databases

  - Operate the POS when the store database is offline

  - Reconnect to the store database

## Create a store database on a database server

Use the following procedure to create a store database on a shared database server. You can create only one store database for a store.

1.  On a stand-alone computer that is running SQL Server, click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Retail Channel Configuration Utility** \> **Retail Channel Configuration Utility**.

2.  Select **Create channel database**, and complete the information in the following fields:
    
      - **Server name** – Enter the name of the server on which to create the store database. Typically, you install the database on the local computer, or **localhost**.
    
      - **Database name** – Enter a unique name for the store database.

3.  Optional: Test the connection.

4.  Click **Continue** to create the store database.

## Distribute initial data to the store database


> [!NOTE]
> <P>This procedure assumes that you are using the Retail Scheduler jobs that are included by default with Retail essentials. If you have modified those jobs or created additional jobs, you might have to modify those jobs accordingly.</P>



After you create a new store database, and before you create offline databases for registers, you must add data from Retail essentials to the new store database.

To send data to the store database, do the following:

  - When you set up a new store database, run the job **9999 Full sync**. This runs all jobs and ensures that all the data is sent to the stores. To avoid sending all data to all locations, you can temporarily modify the distribution schedule for the job, so that the data is sent only to the new location.

For more information about jobs, see [Configure jobs and subjobs in Retail Scheduler (Retail essentials)](configure-jobs-and-subjobs-in-retail-scheduler-retail-essentials.md) and [Schedule and run jobs in Retail Scheduler (Retail essentials)](schedule-and-run-jobs-in-retail-scheduler-retail-essentials.md).

## Create a POS register that has an offline database

**Prerequisite**: Before you can complete this procedure, you must create a store database and distribute initial data to it.

Use the following procedure to create an offline database on a point-of-sale (POS) register.

1.  On a POS computer, click **Start** \> **All Programs** \> **Microsoft Dynamics AX 2012** \> **Retail Channel Configuration Utility** \> **Retail Channel Configuration Utility**.

2.  Select **Create or reprovision the offline database**, and then complete the information in the following fields:
    
      - **Store ID** – Enter the store ID. This value must be the same as the value that was entered for the store in the **Name** field of the **Retail stores** form. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
    
      - Under **Channel database**, enter the following information:
        
          - **Server name** – The name of the SQL Server instance that is hosting the store database.
        
          - **Database name** – The name of the store database.
    
      - Under **Offline database**, enter the following information:
        
          - **Server name** – The name of the SQL Server instance that is hosting the offline database.
        
          - **Database name** – The name of the offline database to be created or reprovisioned.

3.  Optional: Test the connection.

4.  Click **Continue** to create and configure the offline database.

5.  On the POS computer, start the Offline Sync Service, so that the offline database can be synchronized with the shared store database.

6.  To confirm that the offline database was created correctly, and that synchronization is working, verify that tracking tables have been added to the store database. Tracking tables are copies of tables that have the suffix \_tracking. If tracking tables have been added, the store database has been provisioned for synchronization. To make sure that the synchronization service is running, see the RetailOfflineSyncLog table in the store database.

7.  When you troubleshoot database synchronization and offline databases, make sure that the user who creates and synchronizes databases has sufficient permissions on the store server and on the SQL Server instance where the offline database is created.

## Configure Retail POS and Retail Offline Sync Service

Before you can complete this procedure, you must create an offline database. The sync service is used to synchronize the offline database with the store database.

To configure Retail POS and Retail Offline Sync Service, follow these steps:

1.  On a POS computer, click **Start** \> **All Programs** \> **Microsoft Dynamics AX 2012** \> **Retail Channel Configuration Utility** \> **Retail Channel Configuration Utility**.

2.  Select **Configure Retail POS and Retail Offline Sync Service**, and then complete the information in the following fields:
    
      - **Store ID** – Type the store ID. This value must be the same as the value that was entered for the store in the **Name** field of the **Retail stores** form. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
    
      - **Register ID** – The ID of the local POS register that is being configured.
    
      - **Legal entity** – The legal entity that the store belongs to.
    
      - Under **Channel database**, enter the following information:
        
          - **Server name** – The name of the SQL Server instance that is hosting the store database.
        
          - **Database name** – The name of the store database.

3.  Optional: Test the connection.

4.  Click **Continue** to create and configure POS and the offline sync service.

5.  On the POS computer, start the Offline Sync Service, so that the offline database can be synchronized with the shared store database.

6.  To confirm that the offline database was created correctly, and that synchronization is working, verify that tracking tables have been added to the store database. Tracking tables are copies of tables that have the suffix \_tracking. If tracking tables have been added, the store database has been provisioned for synchronization. To make sure that the synchronization service is running, see the RetailOfflineSyncLog table in the store database.

7.  When you troubleshoot database synchronization and offline databases, make sure that the user who creates and synchronizes databases has sufficient permissions on the store server and on the SQL Server instance where the offline database is created.

## Synchronize data between the store database and offline databases

If the store database becomes unavailable, POS registers can connect to a local offline database and continue performing transactions. Therefore, offline databases on POS registers must be synchronized with the latest data from the store database.

Offline profiles define which data is synchronized from the store database to the offline databases on POS registers. Each offline profile consists of several offline scopes. The default scopes are modeled after the Retail Scheduler jobs that are used to synchronize data between Retail essentials and the stores. For example, the 1080 scheduler job pushes tax-related information from Retail essentials to the stores. The tables that are included in the 1080 scheduler job are also included in the offline scope that pushes tax-related information from the store database to the offline database.

For more information about offline scopes and offline profiles, see [Set up offline profiles (Retail essentials)](set-up-offline-profiles-retail-essentials.md).

## Operate the POS register when the store database is offline

The following sections describe the transactions that you can and can’t complete when a POS register is in offline mode.

## POS operations that can be completed when the store database is offline

If a POS register has an offline database, you can complete the following operations when the store database is offline:

  - Generate a sales transaction.

  - Recall an unfinished transaction, if the transaction was initiated during the current offline session.

  - Void an item.

  - Void a payment.

  - Void a transaction, if the transaction was initiated during the current offline session.

  - Perform blank operations.

  - Complete a return transaction, under specific circumstances. The following table shows when an offline return transaction can be completed.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Mode of database when the original transaction was generated</p></th>
    <th><p>Current mode of database</p></th>
    <th><p>Return allowed</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Offline</p></td>
    <td><p>Offline</p></td>
    <td><p>Yes, if the original transaction was completed during the current offline session</p></td>
    </tr>
    <tr class="even">
    <td><p>Offline</p></td>
    <td><p>Online</p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p>Online</p></td>
    <td><p>Offline</p></td>
    <td><p>No</p></td>
    </tr>
    <tr class="even">
    <td><p>Online</p></td>
    <td><p>Online</p></td>
    <td><p>Yes</p></td>
    </tr>
    </tbody>
    </table>


## POS operations that can’t be completed when the store database is offline

You can’t complete the following operations when the store database is offline:

  - Print an X report

  - Print a Z report

  - Close a shift

  - Blind-close a shift

  - View blind-closed shifts

  - Suspend a shift

## Reconnect to the store database

A register will go offline if the system is temporarily down or if the store database is unavailable. When the connection with the store database is lost, Retail POS automatically switches to the offline database. The connection status is displayed on the status bar.


> [!IMPORTANT]
> <P>If a transaction is in progress when the connection is lost, you must void the transaction, and then start a new transaction that uses the offline database.</P>



When the store database becomes available again, you must use the **Database connection status** operation in Retail POS to reestablish the connection with the store database.

## See also

[Setting up retail stores (Retail essentials)](setting-up-retail-stores-retail-essentials.md)

  



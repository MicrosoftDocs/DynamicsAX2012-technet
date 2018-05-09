---
title: Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)
TOCTitle: Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)
ms:assetid: 99ba8d75-d3ef-457d-a714-95dd894fccc5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679929(v=AX.60)
ms:contentKeyID: 49557912
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to create retail store databases and offline databases by using the Retail Store Database Utility.


> [!NOTE]
> <P>The information in this topic applies to AX 2012 R2 and AX 2012 Feature Pack. For information about how to complete these tasks in AX 2012 R3, see <A href="create-a-channel-database-or-an-offline-database-ax-2012-r3.md">Create a channel database or an offline database (AX 2012 R3)</A>.</P>



A store database may be created either on a shared database server or on a point of sale (POS) register for offline use.

Direct connections between the database on a POS register and the Microsoft Dynamics AX database are not prohibited, but this scenario is not supported.

On each computer where you want to create a database, you must use the Setup wizard for Microsoft Dynamics AX to install the Retail Store Database Utility. For more information, see [Install the Retail Channel Configuration Utility (Retail Store Database Utility)](install-the-retail-channel-configuration-utility-retail-store-database-utility.md).

The procedures in this topic assume that you have installed a supported version of Microsoft SQL Server on the computer where you plan to run the Retail Store Database Utility. For a list of supported operating systems and SQL Server versions, see the [Microsoft Dynamics AX system requirements](http://go.microsoft.com/fwlink/?linkid=165377). For information about how to configure SQL Server for channel and offline databases, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).

The Retail Store Database Utility can also be used to configure database connections for a POS register. For more information, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).

This topic contains the following sections:

  - Create a store database on a database server

  - Distribute initial data to the store database

  - Create a POS register that has an offline database

  - Synchronize data between the store database and offline databases

## Create a store database on a database server

Use the following procedure to create a store database on a shared database server. If you have installed an update, and a store database already exists, the database will be upgraded.


> [!NOTE]
> <P>Multiple store databases in a single store are not supported.</P>



1.  On a stand-alone SQL Server computer, click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Retail Database Utility** \> **Retail Database Utility** to open the **Retail POS configuration** form.

2.  In the **Database** section of the form, select **Configure store database**. Complete the information in the following fields:
    
      - **Store server name** – Select or type the name of the server on which to create the store database. Typically, you will install on the local computer, or **localhost**.
    
      - **Store database name** – Type a unique name for the store database.

3.  Optional: Test the connection.

4.  Click **Continue** to create and configure the store database.

## Distribute initial data to the store database

After you create a new store database, and before you create offline databases for registers, you must populate the store database with data from Microsoft Dynamics AX.


> [!NOTE]
> <P>This procedure assumes that you are using the Retail Scheduler jobs that are included by default with Microsoft Dynamics AX. If you have modified those jobs or created additional jobs, you might have to modify the following list accordingly.</P>



When you set up a new store database, you must run all A jobs for that location. In addition, run the following N jobs:

  - N-1000 – Currency

  - N-1010 – Customer

  - N-1030 – Reason code information, if reason codes are used

  - N-1050 – Loyalty, if loyalty discounts are given

  - N-1080 – Tax

  - N-1100 – Item and price parameters

  - N-1110 – Global configuration

  - N-1115 – Global address book reference data

To avoid sending all data to all locations, you can temporarily modify the distribution schedule for the job, so that the data is sent only to the new location.

For more information about jobs, see [Configure jobs and subjobs in Retail Scheduler](configure-jobs-and-subjobs-in-retail-scheduler.md) and [Schedule and run jobs in Retail Scheduler](schedule-and-run-jobs-in-retail-scheduler.md).

## Create a POS register that has an offline database

Use the following procedure to create an offline database on a POS register.


> [!IMPORTANT]
> <P>Before you can complete this procedure, you must create a store database and distribute initial data to the store database.</P>



1.  On a POS computer, click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Retail Database Utility** \> **Retail Database Utility** to open the **Retail POS configuration** form.

2.  In the **Identification** section of the form, complete the information in the following fields:
    
      - **Store ID** – Type the store ID. This value must be the same as the value that was entered for the store in the **Name** field of the **Retail stores** form. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
        

        > [!NOTE]
        > <P>The store record does not have to be created before you complete this step. However, the ID must match later when the record is created and the profile is linked. For more information, see <A href="setting-up-retail-stores.md">Setting up retail stores</A>.</P>

    
      - **Register ID** – Type a unique ID for the POS register.
        

        > [!NOTE]
        > <P>The POS register record does not have to be created before you complete this step. However, the ID must match later when the record is created and the profile is linked. For more information, see <A href="setting-up-retail-pos.md">Setting up Retail POS</A>.</P>

    
      - **Data area ID** – Type the applicable company code.

3.  In the **Database** section of the form, select **Configure offline database**. Complete the information in the following fields:
    
      - **Store server name** – Select the server where the store database is installed.
    
      - **Store database name** – Type the name of the store database.

4.  Optional: Test the connection.

5.  In the **Offline database** section of the form, complete the information in the following fields:
    
      - **Offline server name** – Type the name of the computer on which to create the offline database. Typically, you will install on the local computer, or **localhost**.
    
      - **Offline database name** – Type a unique name for the new offline database.

6.  Optional: Test the connection.

7.  Click **Continue** to create and configure the offline database.

8.  On the POS computer, start the Microsoft Dynamics AX for Retail Offline Sync Service, so that the offline database can be synchronized with the shared store database.

9.  To confirm that the offline database was created correctly, and that synchronization is working, verify that tracking tables have been added to the store database. Tracking tables are copies of Retail tables that have the suffix \_tracking. If tracking tables have been added, the store database has been provisioned for synchronization. To make sure that the synchronization service is running, see the RetailOfflineSyncLog table in the store database.
    

    > [!TIP]
    > <P>When you troubleshoot database synchronization and offline databases, make sure that the user who creates and synchronizes databases has sufficient permissions on the store server and on the SQL Server instance where the offline database is created.</P>



## Synchronize data between the store database and offline databases

If the store database becomes unavailable, POS registers can connect to a local offline database, so that transaction entry is not interrupted. Therefore, offline databases on POS registers must be synchronized with the latest data from the store database.

Offline profiles define which data is synchronized from the store database to the offline databases on POS registers. Each offline profile consists of several offline scopes. The default scopes are modeled after the Retail Scheduler jobs that are used to synchronize data between Microsoft Dynamics AX and the stores. For example, the A-1080 scheduler job pushes tax-related information from Microsoft Dynamics AX to the stores. The tables that are included in the A-1080 scheduler job are also included in the offline scope that pushes tax-related information from the store database to the offline database.

For more information about offline scopes and offline profiles, see [Set up offline profiles](set-up-offline-profiles.md).

## See also

[Use Retail POS in offline mode](use-retail-pos-in-offline-mode.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


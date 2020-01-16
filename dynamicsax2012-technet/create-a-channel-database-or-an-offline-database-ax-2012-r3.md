---
title: Create a channel database or an offline database (AX 2012 R3)
TOCTitle: Create a channel database or an offline database (AX 2012 R3)
ms:assetid: e12bd6ab-e41f-494e-8b34-98abcee0217a
ms:mtpsurl: https://technet.microsoft.com/library/Hh575256(v=AX.60)
ms:contentKeyID: 39555421
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Create a channel database or an offline database (AX 2012 R3) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create retail channel databases and offline databases by using the Retail Channel Configuration Utility.


> [!NOTE]
> <P>The information in this topic applies to AX 2012 R3. For information about how to complete these tasks in AX 2012 R2 or AX 2012 Feature Pack, see <A href="create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md">Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)</A>.</P>



Channel databases hold retail data for one or more retail channels, such as online stores or brick-and-mortar stores. The data for a channel can be included in more than one channel database. Create a channel database on a shared database server. Create an offline database on a point of sale (POS) device so that transactions can continue if the device loses connectivity with the channel database.

On each computer where you want to create a database, you must use the Microsoft Dynamics AX Setup wizard to install the Retail Channel Configuration Utility. For more information, see [Install the Retail Channel Configuration Utility (Retail Store Database Utility)](install-the-retail-channel-configuration-utility-retail-store-database-utility.md).


> [!NOTE]
> <P>You can also use the Setup wizard to create a channel database. For more information, see <A href="install-a-retail-channel-database.md">Install a Retail channel database</A>.</P>



The procedures in this topic assume that you have installed a supported version of Microsoft SQL Server on the computer where you plan to run the Retail Channel Configuration Utility. For a list of supported operating systems and SQL Server versions, see the [Microsoft Dynamics AX system requirements](http://go.microsoft.com/fwlink/?linkid=165377). For information about how to configure SQL Server for channel databases and offline databases, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).

The Retail Channel Configuration Utility can also be used to configure database connections for a POS register. For more information, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).

This topic contains the following sections:

  - Create a channel database on a database server

  - Distribute initial data to the channel database

  - Create or provision an offline database

  - Synchronize data between the channel database and offline databases

## Create a channel database on a database server

Use the following procedure to create a channel database on a shared database server. If you have installed an update, and a channel database already exists, the database will be upgraded.

1.  On a SQL Server computer, start the Retail Channel Configuration Utility.

2.  Select **Create channel database**.

3.  In the **Channel database** section of the form, select or type the name of the server on which to create the channel database. Typically, you will install on the local computer, or **localhost**. Type a unique name for the channel database.

4.  Optional: Test the connection.

5.  Click **Apply** to create and configure the channel database.

6.  On the computer where the channel database is installed, use SQL Server Management Studio to assign the local **RetailOfflineSyncUsers** group read and write permissions to the database.

## Distribute initial data to the channel database

After you create a new channel database, you must populate it with the data for the channel.

1.  Open the Microsoft Dynamics AX client.

2.  If necessary, create a channel data group for the database. (Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel data group**.) For more information, see [Create a channel data group](create-a-channel-data-group.md).

3.  Create a profile for the new channel database. (Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**.) For more information, see [Set up a channel database profile](set-up-a-channel-database-profile.md).

4.  Synchronize all data for the channel database. In the **Channel database** form, click **Full data sync** and then select the distribution schedule that is named **Full sync**.
    
    For more information about how to run jobs to distribute data, see [Schedule and run jobs in Retail Scheduler](schedule-and-run-jobs-in-retail-scheduler.md).

## Create or provision an offline database

Use the following procedure to create an offline database on a POS device.


> [!IMPORTANT]
> <P>Before you can complete this procedure, you must create a channel database and distribute initial data to the channel database. You must also run the <STRONG>Offline scopes</STRONG> job to at headquarters to synchronize offline scopes with the channel database.</P>



1.  On a POS register, start the Retail Channel Configuration Utility.

2.  Select **Create or reprovision offline database**.

3.  In the **Identification** section of the form, type the store ID. This value must be the same as the value that was entered in the **Name** field on the **Retail stores** form. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
    

    > [!NOTE]
    > <P>The store record does not have to be created before you complete this step. However, the ID must match later when the record is created and the profile is linked. For more information, see <A href="setting-up-retail-stores.md">Setting up retail stores</A>.</P>



4.  In the **Channel Database** section of the form, select the server where the channel database is installed, and type the name of the channel database.

5.  Optional: Test the connection.

6.  In the **Offline database** section of the form, type the name of the computer on which to create the offline database. Typically, you will install on the local computer, or **localhost**. Type a unique name for the new offline database.

7.  Optional: Test the connection.

8.  Click **Apply** to create and configure the offline database.

9.  On the POS device, start the Microsoft Dynamics AX for Retail Offline Sync Service, so that the offline database can be synchronized with the shared channel database.

10. To confirm that the offline database was created correctly, and that synchronization is working, verify that tracking tables have been added to the channel database. Tracking tables are copies of Retail tables that have the suffix \_tracking. If tracking tables have been added, the channel database has been provisioned for synchronization. To make sure that the synchronization service is running, see the RetailOfflineSyncLog table in the channel database.
    

    > [!TIP]
    > <P>When you troubleshoot database synchronization and offline databases, make sure that the user who creates and synchronizes databases has sufficient permissions on the database server and on the SQL Server instance where the offline database is created.</P>



## Synchronize data between the channel database and offline databases

If the channel database becomes unavailable, POS devices can connect to a local offline database, so that transaction entry is not interrupted. Therefore, offline databases on POS devices must be synchronized with the latest data from the channel database.

Offline profiles define which data is synchronized from the channel database to the offline databases on POS devices. Each offline profile consists of several offline scopes. The default scopes are modeled after the Retail Scheduler jobs that are used to synchronize data between Microsoft Dynamics AX and the channel. For example, the 1080 scheduler job pushes tax-related information from Microsoft Dynamics AX to the channel. The tables that are included in the 1080 scheduler job are also included in the offline scope that pushes tax-related information from the channel database to the offline database. For more information about offline scopes and offline profiles, see [Set up offline profiles](set-up-offline-profiles.md).


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, you can no longer switch to offline mode if the offline database has not been synchronized.</P>



## See also

[Use Retail POS in offline mode](use-retail-pos-in-offline-mode.md)

[Configure offline options for Retail Modern POS](configure-offline-options-for-retail-modern-pos.md)

  



---
title: Configure offline options for Retail Modern POS
TOCTitle: Configure offline options for Retail Modern POS
ms:assetid: ef15dc30-e1e3-4d70-8efb-53822768e66a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn879454(v=AX.60)
ms:contentKeyID: 63810526
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure offline options for Retail Modern POS 


This topic explains how to create offline databases for the Retail Modern POS by using the Retail Channel Configuration Utility.

Retail Modern POS can be configured to either to connect to a channel database through a Retail Server, or it can be configured to connect directly to the channel database. Offline mode is supported for both deployment options. For details about supported deployment topologies, see [Retail Modern POS architecture](retail-modern-pos-architecture.md).

On each computer where you want to create a database, you must use the Microsoft Dynamics AX Setup wizard to install the Retail Channel Configuration Utility. For more information, see [Install the Retail Channel Configuration Utility (Retail Store Database Utility)](install-the-retail-channel-configuration-utility-retail-store-database-utility.md).


> [!NOTE]
> <P>You can also use the Setup wizard to create a channel database. For more information, see <A href="install-a-retail-channel-database.md">Install a Retail channel database</A>.</P>



The procedures in this topic assume that you have installed a supported version of Microsoft SQL Server on the computer where you plan to run the Retail Channel Configuration Utility. For a list of supported operating systems and SQL Server versions, see the [Microsoft Dynamics AX system requirements](http://go.microsoft.com/fwlink/?linkid=165377). For information about how to configure SQL Server for channel databases and offline databases, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).

The Retail Channel Configuration Utility can also be used to configure database connections for a POS register. For more information, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).


> [!IMPORTANT]
> <P>You must install <A href="https://support.microsoft.com/kb/2703853">Microsoft Sync Framework hotfix 2703853</A> on all computers on which you install Retail Modern POS with an offline database.</P>
> <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



## Create an offline database for Retail Modern POS


> [!IMPORTANT]
> <P>Before you can complete this procedure, you must create a channel database and distribute initial data to the channel database. You must also run the <STRONG>Offline scopes</STRONG> job to at headquarters to synchronize offline scopes with the channel database.</P>



1.  Install [Microsoft Sync Framework hotfix 2703853](https://support.microsoft.com/kb/2703853) on the POS register.

2.  On a POS register, start the Retail Channel Configuration Utility.

3.  Select **Create or reprovision offline database**.
    
    1.  In the **Identification** section of the form, type the store ID. This value must be the same as the value that was entered in the **Name** field on the **Retail stores** form. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
        

        > [!NOTE]
        > <P>The store record does not have to be created before you complete this step. However, the ID must match later when the record is created and the profile is linked. For more information, see <A href="setting-up-retail-stores.md">Setting up retail stores</A>.</P>

    
    2.  Optional: Test the connection.
    
    3.  In the **Offline database** section of the form, type the name of the computer on which to create the offline database. Typically, you will install on the local computer, or **localhost**. Type a unique name for the new offline database.
    
    4.  Click **Apply** to create the offline database.

4.  Select **Configure Retail Modern POS**.
    
    1.  In the **Identification** section of the form, enter the register ID.
    
    2.  Select **Configure offline database**.
    
    3.  In the **Retail Offline Sync Service Configuration** section of the form, enter the user name and password of the Windows account used by the Retail Offline Sync Service. For more information, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).
        

        > [!NOTE]
        > <P>This account must be a member of the POS user group. For more information, see <A href="set-up-user-accounts-and-the-pos-user-group.md">Set up user accounts and the POS user group</A>.</P>



5.  Start the Microsoft Dynamics AX for Retail Offline Sync Service, so that the offline database can be synchronized with the channel database.

## Synchronize data between the channel database and offline databases

If the channel database becomes unavailable, Retail Modern POS devices can connect to a local offline database, so that transaction entry is not interrupted. Therefore, offline databases on Retail Modern POS devices must be synchronized with the latest data from the channel database.

Offline profiles define which data is synchronized from the channel database to the offline databases on POS devices. Each offline profile consists of several offline scopes. The default scopes are modeled after the Retail Scheduler jobs that are used to synchronize data between Microsoft Dynamics AX and the channel. For example, the 1080 scheduler job pushes tax-related information from Microsoft Dynamics AX to the channel. The tables that are included in the 1080 scheduler job are also included in the offline scope that pushes tax-related information from the channel database to the offline database. For more information about offline scopes and offline profiles, see [Set up offline profiles](set-up-offline-profiles.md).

## See also

[Use Retail POS in offline mode](use-retail-pos-in-offline-mode.md)

[Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


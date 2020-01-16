---
title: Deploy updates in a retail environment
TOCTitle: Deploy updates in a retail environment
ms:assetid: eaecf1b3-93dd-4211-97e3-6552441ef014
ms:mtpsurl: https://technet.microsoft.com/library/Dn305851(v=AX.60)
ms:contentKeyID: 54911460
author: Khairunj
ms.date: 03/09/2016
mtps_version: v=AX.60
---

# Deploy updates in a retail environment 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For more information, see the section later in this topic.</P>



If you are running a retail environment, there are additional steps that you must perform to deploy updates and hotfixes to computers that are running Retail POS, Commerce Data Exchange components, or a store database. Retail software at the store can be updated in any order or at the same time.

Updates for retail environments may be either binary or application updates. Application updates are installed like other Microsoft Dynamics AX application updates, by installing to a database server, and then recompiling. Only binary updates require additional steps.

We recommend that you first perform these steps in a test environment local to your headquarters, validate that all fixes perform as expected, and then roll them out to your stores. These steps are in addition to the processes described in the topics [Apply updates and hotfixes](apply-updates-and-hotfixes.md) and [Apply updates to database, AOS, and clients](apply-updates-to-database-aos-and-clients.md).


> [!IMPORTANT]
> <P>Updates included in a hotfix should be applied to all computers that host the updated components. For example, you should run the same version of Commerce Data Exchange: Synch Service at all stores and at headquarters. Environments that run different versions of the same Retail component are not supported. In some cases, deployed fixes will not be fully available until all components included in the hotfix have been updated. For example, a Commerce Data Exchange: Real-time Service update might also require a code change at headquarters.</P>




> [!IMPORTANT]
> <P>If you apply a binary hotfix that was released after AX 2012 R3 CU8 to a Retail environment in which the channels are running a later version of the software than the head office (N+1), you must update all components offered in the update wizard EXCEPT the Real-time Service.</P>
> <P>You should update the Real-time Service only if the Microsoft Dynamics AX application code has been upgraded to AX 2012 R3 CU8 (6.3.1000.309).</P>
> <P>In AX 2012 R3 CU8, the Real-time Service was modified to reference AX methods that are available only after you are running AX 2012 R3 CU8.</P>



## General guidance

The following guidance applies to any update that affects retail components.

## Before you begin

Before you deploy updates to Retail components, you must complete the following tasks.

1.  At the store, install [Microsoft Sync Framework hotfix 2703853](https://support.microsoft.com/kb/2703853) on all computers on which you have installed Retail POS or Retail Modern POS.
    

    > [!IMPORTANT]
    > <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



2.  At the store, bring offline registers online and make sure that offline transactions have been synchronized with the store database.
    

    > [!WARNING]
    > <P>If you skip this step, severe data damage and possible financial losses can occur. After you upgrade the store database, you can no longer synchronize transactions from existing offline databases.</P>



3.  At headquarters, run P jobs to synchronize store transactions with headquarters. For more information, see [Schedule and run jobs in Retail Scheduler](schedule-and-run-jobs-in-retail-scheduler.md).

4.  Back up the store database by using Microsoft SQL Server Management Studio or another tool.

## Merge any existing code changes with POS and redeploy

When updates are applied to POS, they may overwrite your customized assemblies. If you have customized Retail POS, you must re-merge your code changes to services and triggers, compile, and then re-deploy the customized assemblies. For more information about how to handle customizations in an update, see the blog post [AX for Retail: Managing and Maintaining POS Customizations](http://blogs.msdn.com/b/axsupport/archive/2013/07/08/ax-for-retail-managing-and-maintaining-pos-customizations.aspx) from the Microsoft Dynamics AX Support team.

## Update the Retail Channel Configuration Utility (Retail Store Database Utility) on one computer

If a retail database update is included in the update that you are applying, an updated version of the Retail Channel Configuration Utility is included in the update.


> [!NOTE]
> <P>In AX 2012 R2 and AX 2012 Feature Pack, the Retail Channel Configuration Utility is called the Retail Store Database Utility.</P>



At the store, start by updating the Retail Channel Configuration Utility on one computer. If other Retail software is installed on this computer, you can also update that software.

1.  Browse to the location where you extracted the files for the update, and then double-click **AxUpdate.exe**.

2.  Install updates.

## Upgrade the store database by using the Retail Channel Configuration Utility (Retail Store Database Utility)

If an update includes a schema change, the updated version of Retail POS will not run until the store database has been upgraded.

To upgrade retail databases, you must run an updated version of the Retail Channel Configuration Utility. Upgrade the store database before you upgrade offline databases on POS registers.

1.  Start the Retail Channel Configuration Utility.

2.  Enter the information for the store database and then click **Apply** or **Continue**.
    
    Database upgrade scripts are executed. If there is an offline database on the computer where the utility is installed and run, you are prompted to provision again, and then the offline database is also upgraded.

## Apply updates on remaining computers and upgrade offline databases

After the store database has been updated, you can upgrade offline databases and update all other retail software at the store.


> [!WARNING]
> <P>It can take several hours to upgrade offline databases. Offline mode is not available until the store database has been provisioned and an offline database has been created on at least one register. If your environment relies heavily on offline mode, consider these factors when you plan the update.</P>



1.  On each computer in the environment, including POS registers, update all Retail components that are offered in the hotfix installer. This makes sure that the local copy of the Retail Channel Configuration Utility is updated with the latest offline database schema.

2.  On each computer where offline mode will be available, run the Retail Channel Configuration Utility to upgrade offline databases.
    
    For more information, see [Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md) or [Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md).

## Edit and resave all category hierarchies

In order to uptake features from AX 2012 R3, you must open, change, and save all category hierarchies. Changes can be as small as adding a space to a description. For more information, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

## Move from AX 2012 R3 to AX 2012 R3 cumulative update 8

This section lists issues to consider before applying AX 2012 R3 CU8 and describes how to update retail components.

## Plan to move to AX 2012 R3 CU8

Most retail organizations are not able to update all their channel locations and the head office on the same day. This means that you must have a plan for updating to AX 2012 R3 CU8 in a staggered manner. Microsoft Dynamics AX supports the following two scenarios:

  - Update the head office first (N-1)

  - Update some or all channels first (N+1)

For both of these scenarios, there are special considerations for offline mode.


> [!IMPORTANT]
> <P>We strongly recommend completing any previous upgrade before moving to AX 2012 R3 CU8. All channel deployments should be running AX 2012 R3 RTM or AX 2012 R3 CU8.</P>



## If you plan to update the head office first (N-1)

In this scenario, components at the head office are updated to AX 2012 R3 CU8 before any updates tasks are deployed for your channels (stores and online stores). We call this scenario N-1. The most important considerations for this scenario are communication with your channels and offline mode.


> [!IMPORTANT]
> <P>When you apply AX 2012 R3 CU8 to the head office environment, you should upgrade all Retail components, including head office components such as Async Server and Real-time Service.</P>



## Communication with channels

After AX 2012 R3 is updated to AX 2012 R3 CU8, you **must** reinitialize Retail in order to update the Retail scheduler jobs that you use to communicate with channel databases. Reinitializing Retail ensures that your system has the latest, improved and updated seed data.


> [!NOTE]
> <P>In general, reinitializing Retail does not cause data loss. Your customized receipt formats, layouts, and so on will not be affected when you reinitialize. Similarly, any custom fields that you have added to out-of-the-box subjobs and your custom subjobs will not be modified. However, if you have customized the table distribution, that customization will need to be preserved.</P>



After you reinitialize, channels that are still running an earlier release can no longer communicate with the AX 2012 R3 CU8 business database by using existing Retail scheduler jobs.


> [!IMPORTANT]
> <P>This includes channels that are running the RTM release of AX 2012 R3.</P>



To resume communications, you must deploy head-office support for the previous schema, set up a new data group or groups, and run upgrade classes to create a new set of N-1 jobs for the AX 2012 R3 RTM schema. For more information, see Update the head office later in this article.

## Offline mode in N-1 scenarios

In AX 2012 R3 CU8, we have added support for maintaining multiple offline profiles. After updating to AX 2012 R3 CU8, you can choose to maintain offline profiles for both the AX 2012 R3 CU8 and RTM releases of Retail POS.

To help you take advantage of this new support, as part of AX 2012 R3 CU8, we set up two offline profiles for you:

  - **Default pr** – This is the offline profile for AX 2012 R3 RTM. It is preserved during upgrade (even if it has been customized).

  - **AX6 CU8** – This is the new offline profile for AX 2012 R3 CU8. This profile includes all scopes from the AX 2012 R3 RTM profile (including custom scopes) plus scopes for the new tables added in AX 2012 R3 CU8. The 1095 job sends offline profile and scope information to channel databases. The job can be run for all locations, regardless of the target release of the channel database in each location; each channel database receives its assigned offline profile.


> [!NOTE]
> <P>Support for multiple offline profiles is applicable only for AX 2012 R3 releases (RTM or CU8).</P>
> <P>In releases prior to AX 2012 R3 CU8, you cannot add the same offline scope to more than one profile.</P>



## If you plan to update channels first (N+1)

In this scenario, components at some or all channels are updated to AX 2012 R3 CU8 before the head office components are updated to AX 2012 R3 CU8. We call this scenario N+1. The most important considerations for this scenario are channel data and functionality, update of the Retail SDK, and offline mode.


> [!IMPORTANT]
> <P>In the N+1 scenario, you must update all components offered in the update wizard EXCEPT the Real-time Service.</P>
> <P>You should update the Real-time Service only if the Microsoft Dynamics AX application code has been upgraded to AX 2012 R3 CU8 (6.3.1000.309).</P>
> <P>This is required, because in AX 2012 R3 CU8, the Real-time Service was modified to reference AX methods that are available only after you are running AX 2012 R3 CU8.</P>



## Channel data and functionality

When you update a channel database to AX 2012 R3 CU8, the database is modified to include additional tables, additional columns, and new or modified stored procedures, views, and more. These changes are in support of AX 2012 R3 CU8 functionality. Some of this functionality will be available to you immediately, and some is not yet available (since data in support of that functionality does not yet exist). As part of channel database update, new tables and columns are populated with default values that keep your functionality virtually the same as it was before update. You can take advantage of new features in AX 2012 R3 CU8 after you have updated your head office components and have completed distribution of your new data (when needed to enable new functionality) to the respective channels.

## Updating Retail SDK and merging customizations

When you update the Retail SDK to AX 2012 R3 CU8, the existing SDK files on the computer are not modified. Instead, the updated Retail SDK is installed to a folder named Retail SDK CU8 and is located in the Documents folder of the user who ran the original install. Your customizations need to be merged into this new code.

## Offline mode

In the N+1 scenario, because the head office has not been updated and reinitialized, the offline profile in the channel database remains the same (AX 2012 R3 RTM version), even after re-provisioning. This means that only the tables and columns that existed prior to the upgrade are present and synchronized in the AX 2012 R3 CU8 offline channel database. As a result, any new AX 2012 R3 CU8 functionality that relies on new data being defined in the head office will not be available.

## How to update retail components

The process for updating most Retail components to AX 2012 R3 CU8 is similar to the update process for other components in AX 2012 R3. This section describes the differences and additional requirements for those Retail components that have special considerations or steps for updating to AX 2012 R3 CU8.


> [!IMPORTANT]
> <P>We strongly recommend completing any previous upgrade prior to updating to AX 2012 R3 CU8. All channel deployments should be running AX 2012 R3 RTM or AX 2012 R3 CU8.</P>



You can update the following Retail components completely by running AxUpdate.exe.

  - Commerce Data Exchange: Async Client

  - Commerce Data Exchange: Real-time Service

  - Retail Server

  - Retail Hardware Station

  - Retail mass deployment toolkit

As always, AxUpdate.exe will only update the default instance of each component configured using AxSetup.exe and will not update components that have been manually installed (such as through Windows PowerShell scripts).

## Update the head office

This section describes the special considerations for updating the head office with AX 2012 R3 CU8.


> [!IMPORTANT]
> <P>We strongly recommend completing any previous upgrade prior to updating to AX 2012 R3 CU8. All channel deployments should be running AX 2012 R3 RTM or AX 2012 R3 CU8.</P>



## Reinitialize Retail

Open the **Retail parameters** form, and click **Initialize** (**Retail** \> **Setup** \> **Retail parameters**). For more information about what this step does and why it is required, see Plan to move to AX 2012 R3 CU8.

## Configure N-1 support

If needed, you can set up N-1 support for channels that are still using previous releases of AX 2012, including the RTM release of AX 2012 R3. For more information, see the following documentation:

  - [Support for Previous POS Versions White Paper for Microsoft Dynamics AX 2012 R2](https://mbs.microsoft.com/customersource/northamerica/ax/learning/documentation/white-papers/ax2012_supportforpreviousposversions)

  - Plan to move to AX 2012 R3 CU8


> [!NOTE]
> <P>You can skip this step if all your channels have already been updated to AX 2012 R3 CU8, of if you have any new channels that you want to deploy with AX 2012 R3 CU8 versions of the Retail components.</P>



## Update the Retail online channel (eCommerce)

When you update the Retail online channel by using AxUpdate.exe wizard, only the installation binaries are updated. The update will not redeploy the online storefront to SharePoint. The steps in redeploying to SharePoint include:

1.  Uninstall the online store. For details, see the Uninstall section in the [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md) topic.

2.  Uninstall the online channel web applications. For details, see the section Uninstall an online channel.

3.  Reinstall the online channel. For details, see the topic [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md).

Plan the timing for updating your online store based on the availability requirements and customizations in the existing system.


> [!NOTE]
> <P>The recommended topology is to separate the computer running the head office components and the online channel components. In a topology that has head office components and Online Channel Components on the same computer, the Commerce Runtime and SharePoint DLLs in the Global Assembly Cache (GAC) must be the latest version of the DLLs. The assembly version of the DLLs for AX 2012 R3 RTM and AX 2012 R3 CU8 are the same and will require that you remove the existing DLLs from the GAC before AXUpdate.exe is run.</P>
> <P>For more information, see <A href="http://msdn.microsoft.com/en-us/library/aa559881.aspx">How to Uninstall an Assembly from the GAC</A>.</P>
> <P>The assembly versions for the AX 2012 R2 and AX 2012 R3 releases are different and can co-exist.</P>



Other topology options include setting up a new AX 2012 R3 CU8 channel database connected to an existing online channel. Such a topology can use Commerce Data Exchange to publish (distribution schedule changes) only to the new channel and bring back orders from both channels. This method requires installing the online store. For more information see [Install the online store](https://technet.microsoft.com/library/jj677412\(v=ax.60\)).

## Uninstall an online channel

The following procedure describes how to uninstall the Retail Online Channel. You must be a Farm administrator in SharePoint.

1.  In SharePoint Central Administration go to **System Settings** \> **Manage Farm features**.

2.  Deactivate the following features, if they are present:
    
      - Claims provider
    
      - Logging service
    
      - Publishing job
    
    Site level features will be automatically uninstalled when the parent solutions are removed.

3.  Under **Manage Farm features**, retract the following solutions immediately, and click **OK**.
    
      - PublisherJob
    
      - StoreFront
    
      - CommonGlobalModules
        
        This package is shared across all instances of storefront. Removing it triggers an IIS reset, so the Central Administration site may not be available. Wait and try again.
    
      - After all of the solutions have been retracted (undeployed), remove the entry for each solution.

4.  In SharePoint Central Administration **Manage Web applications**, delete the retail web applications.
    

    > [!NOTE]
    > <P>You must delete the content database and the IIS web site for each web application.</P>
    > <P>This step may take a long time to process.</P>



## Update the Retail SDK

To update the Retail SDK, select it in AxUpdate.exe.

This update does not modify the SDK files that are already installed on your system. Instead, a new deployment of the Retail SDK is created, in a folder named **Retail SKD CU8**. You must merge your customizations into this new code. See the section [Deploy updates in a retail environment](deploy-updates-in-a-retail-environment.md).

## Update Retail POS and Retail Channel Configuration Utility

To update the store server or a register computer, select the Retail POS and the Retail Channel Configuration Utility components in AxUpdate.exe.

After the installation is completed, follow these steps:

  - On the store server, run the Retail Channel Configuration utility to complete the update of the channel database.

  - On each register computer, either run the Retail Channel Configuration utility or run the Retail POS application as an administrator. This will update the Retail POS configuration file to add the new elements that are required for AX 2012 R3 CU8.

For more information about how to run the Retail Channel Configuration utility, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).


> [!IMPORTANT]
> <P>After any update of the channel database, you must follow these steps:</P>
> <OL>
> <LI>
> <P>Reprovision the channel database for offline mode.</P>
> <LI>
> <P>Create a new offline database for each register.</P>
> <LI>
> <P>Configure Retail POS to update the offline configuration to reference the new offline database details.</P>
> <LI>
> <P>Wait for the offline synchronization process to finish.</P></LI></OL>
> <P>While this work is in progress, offline mode is not available in the store. You can resume use of offline mode on a register after that register’s offline database is created and synchronized. For more information, see the section Apply updates on remaining computers and upgrade offline databases.</P>



## Update Retail Modern POS

AX 2012 R3 CU8 includes the RTM release of Retail Modern POS. This is the first supported release of this application. For more information about Retail Modern POS, see [Retail Modern Point of Sale](retail-modern-point-of-sale.md).

## Uninstall pre-release versions of Modern POS

If you installed a pre-release copy of Retail Modern POS, you must uninstall the pre-release application before installing the RTM version. You can do this either by running AxSetup.exe and selecting the component for removal, or by uninstalling it from **Control Panel** \> **Add or Remove Programs**.

If multiple Windows users have been using an installation of Retail Modern POS, we recommend that you start with a reimaged computer whenever possible.

To uninstall, you must explicitly remove the application for every user who logged onto the computer. Have each user right-click the application on the Start screen, and then click **Remove**. After you have removed all instances, you can remove the installer from **Control Panel** \> **Add or Remove Programs**.

## Install the CU8 version of Retail Modern POS


> [!NOTE]
> <P>The prerequisites for Retail Modern POS have changed. To install the RTM release of Retail Modern POS, you must be running Windows 8.1 Update 1.</P>



Install Retail Modern POS by slipstreaming AX 2012 R3 CU8 with AxSetup.exe. For more information about slipstream installation of Microsoft Dynamics AX components, see [Include cumulative updates and hotfixes in a new installation (slipstreaming)](include-cumulative-updates-and-hotfixes-in-a-new-installation-slipstreaming.md).

## See also

[Mass deploy retail updates and customizations by using System Center Configuration Manager](mass-deploy-retail-updates-and-customizations-by-using-system-center-configuration-manager.md)

[Synchronize a new table or field with retail databases](synchronize-a-new-table-or-field-with-retail-databases.md)

  



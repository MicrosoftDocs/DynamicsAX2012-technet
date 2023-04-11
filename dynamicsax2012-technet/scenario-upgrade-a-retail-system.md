---
title: 'Scenario: Upgrade a Retail system'
TOCTitle: 'Scenario: Upgrade a Retail system'
ms:assetid: 82b5489f-750d-4bde-a5c7-ab1cc8798c57
ms:mtpsurl: https://technet.microsoft.com/library/JJ721717(v=AX.60)
ms:contentKeyID: 49732800
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- xml
---

# Scenario: Upgrade a Retail system 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The upgrade process for Retail installations of Microsoft Dynamics AX 2012 is based on the Microsoft Dynamics AX 2012 upgrade framework, and uses procedures that are common to both Retail and non-Retail deployments. Before administrators attempt an upgrade, they must be familiar with the [Microsoft Dynamics AX 2012 Upgrade Guide](https://go.microsoft.com/fwlink/?linkid=163798) and the regularly updated upgrade documentation on TechNet.

### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Supported Retail upgrade paths

Retail upgrade paths are a subset of general Microsoft Dynamics AX 2012 upgrade paths. For a complete list of these upgrade paths, see [Supported upgrade paths](supported-upgrade-paths.md).

Microsoft Dynamics AX supports several direct upgrade paths for Retail customers who want to upgrade to Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, or Microsoft Dynamics AX 2012 Feature Pack from previous versions. The following diagram shows these direct upgrade paths.

![Retail upgrade paths](images/JJ721717.Retailupgradepathsin62(en-us,AX.60).png "Retail upgrade paths")

The terms *source* and *target* refer to stages of the AX 2012 upgrade framework. The goal of the upgrade framework is to reduce the downtime that is required during code and data upgrade. Upgrade administrators and business application experts can prepare data upgrade fixes on the existing production system, or source system, without interrupting business operations. While this work is in progress, the AX 2012 system, or target system, is installed and configured on a separate computer. Code upgrade is performed on the target system while that system is still offline. Finally, during a relatively brief downtime window, prepared data is copied from the source system and upgraded on the target system.

The term *in-place* describes upgrades that take place on a single computer system. Upgrades between subreleases of AX 2012 use an in-place upgrade model.


> [!IMPORTANT]
> <P>Direct upgrade of retail systems from AX 2009 for Retail is not supported. Customers who want to perform this upgrade must first upgrade to AX 2009 for Retail (R2 Refresh), the supported source. For information about how to perform this preliminary upgrade, see the upgrade section of the <A href="https://mbs.microsoft.com/customersource/downloads/servicepacks/microsoftdynamicsaxforretailcs.htm?printpage=false&amp;sid=sv1zlv0gdopipwyrz22i0zez&amp;stext=ax%20for%20retail">Deployment and installation Guide: Microsoft Dynamics AX [2009] for Retail</A>.</P>



### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Retail upgrade cases

Each of the following cases provides a simplified workflow of the phases that are involved in the upgrade of a Microsoft Dynamics AX Retail system. Only one of these cases will apply to your own upgrade.

For complete, step-by-step documentation of the AX 2012 upgrade process, see the [Microsoft Dynamics AX 2012 Upgrade Guide](https://go.microsoft.com/fwlink/?linkid=163798), or see the latest [Upgrade to Microsoft Dynamics AX 2012](upgrade-to-microsoft-dynamics-ax-2012.md) on TechNet.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Case 1: Upgrade AX 2009 for Retail (R2 Refresh) to AX 2012 Feature Pack

The AX 2012 source-to-target upgrade model defines the phases of a Retail module upgrade from AX 2009 for Retail (R2 Refresh). The following diagram illustrates the workflow that is involved in this version of a source-to-target scenario.

![Retail upgrade scenario 1](images/JJ721717.Retailupgradescenario1(en-us,AX.60).png "Retail upgrade scenario 1")

For documentation about the core Microsoft Dynamics AX source-to-target upgrade process for this case and step-by-step procedures for successfully completing it, see [Scenario: Upgrade AX 4.0 or AX 2009 to AX 2012 (all versions)](scenario-upgrade-ax-4-0-or-ax-2009-to-ax-2012-all-versions.md).

For documentation about setting up stores and installing POS registers, see the section “Deploy Retail POS for AX 2012 R2 or AX 2012 Feature Pack,” later in this topic.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Case 2: Upgrade AX 2009 for Retail (R2 Refresh) to AX 2012 R2 or AX 2012 R3

The Microsoft Dynamics AX 2012 source-to-target upgrade model defines the phases of a Retail module upgrade from Microsoft Dynamics AX 2009 for Retail (R2 Refresh). The following diagram illustrates the workflow that is involved in this version of a source-to-target scenario.

![Retail upgrade scenario 2](images/JJ721717.Retailupgradescenario2(en-us,AX.60).png "Retail upgrade scenario 2")

For documentation about the core Microsoft Dynamics AX source-to-target upgrade process for this case and step-by-step procedures for successfully completing it, see [Scenario: Upgrade AX 4.0 or AX 2009 to AX 2012 (all versions)](scenario-upgrade-ax-4-0-or-ax-2009-to-ax-2012-all-versions.md).

AX 2012 R2 and AX 2012 R3 support up to two versions of POS software across multiple stores. Therefore, administrators have the flexibility to upgrade one store at a time instead of all stores at one time. For information about how to configure the Retail module for multiversion POS installations, see the appropriate section later in this topic, either “Deploy Retail POS for AX 2012 R2 or AX 2012 Feature Pack” or “Deploy Retail POS for AX 2012 R3.”

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Case 3: Upgrade AX 2012 to AX 2012 Feature Pack

This case describes an in-place upgrade from a non-Retail AX 2012 version to a Retail installation of AX 2012 Feature Pack. Since this will be a new Retail system, all stores will be set up with latest-version components. The following diagram illustrates the workflow that is involved in this version of an in-place upgrade scenario.

![Retail upgrade scenerio 3](images/JJ721717.Retailupgradescenario3(en-us,AX.60).png "Retail upgrade scenerio 3")

The upgrade installs a new model, OneFPK, onto the existing system to supply the framework and applications that support Retail functionality.

For documentation about the core Microsoft Dynamics AX in-place upgrade process for this case and step-by-step procedures for successfully completing it, see [Scenario: Perform in-place upgrade to AX 2012 Feature Pack](scenario-perform-in-place-upgrade-to-ax-2012-feature-pack.md).

For documentation about setting up stores and installing POS registers, see the section “Deploy Retail POS for AX 2012 R2 or AX 2012 Feature Pack.”

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Case 4: Upgrade AX 2012 to AX 2012 R2 or AX 2012 R3

This case describes an in-place upgrade from a non-Retail Microsoft Dynamics AX 2012 version to a Retail installation of Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3. Since this will be a new Retail system, all stores will be set up with latest-version components. The following diagram illustrates the workflow that is involved in this version of an in-place upgrade scenario.

![Retail upgrade scenario 4](images/JJ721717.Retailupgradescenario4(en-us,AX.60).png "Retail upgrade scenario 4")

For documentation about the core Microsoft Dynamics AX in-place upgrade process for this case and step-by-step procedures for successfully completing it, see [Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3](scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md).

AX 2012 R2 and AX 2012 R3 support up to two versions of POS software across multiple stores. Therefore, administrators have the flexibility to upgrade one store at a time instead of all stores at one time. For information about how to configure the Retail module for multiversion POS installations, see the appropriate section later in this topic, either “Deploy Retail POS for AX 2012 R2 or AX 2012 Feature Pack” or “Deploy Retail POS for AX 2012 R3.”

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Case 5: Upgrade AX 2012 Feature Pack to AX 2012 R2 or AX 2012 R3

This case describes an in-place upgrade from a Retail installation of Microsoft Dynamics AX 2012 Feature Pack to a Retail installation of Microsoft Dynamics AX 2012 R2. The following diagram illustrates the workflow that is involved in this version of an in-place upgrade scenario.

![Retail upgrade scenario 5](images/JJ721717.Retailupgradescenario5(en-us,AX.60).png "Retail upgrade scenario 5")

For documentation of the core Microsoft Dynamics AX in-place upgrade process for this case and step-by-step procedures for successfully completing it, see [Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3](scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md).

AX 2012 R2 and AX 2012 R3 support up to two versions of POS software across multiple stores. Therefore, administrators have the flexibility to upgrade one store at a time instead of all stores at once. For information about how to configure the Retail module for multiversion POS installations, see the appropriate section below, either “Deploy Retail POS for AX 2012 R2 or AX 2012 Feature Pack” or “Deploy Retail POS for AX 2012 R3.”

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Case 6: Upgrade AX 2012 R2 to AX 2012 R3

This case describes an in-place upgrade from a Retail installation of Microsoft Dynamics AX 2012 R2 to a Retail installation of Microsoft Dynamics AX 2012 R3. The following diagram illustrates the workflow that is involved in this version of an in-place upgrade scenario.

![R2 to R3](images/JJ721717.Retailupgradescenario6(en-us,AX.60).png "R2 to R3")

For documentation about the core Microsoft Dynamics AX in-place upgrade process for this case and step-by-step procedures for successfully completing it, see [Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3](scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md).

AX 2012 R3 supports up to two versions of POS software across multiple stores. Therefore, administrators have the flexibility to upgrade one store at a time instead of all stores at one time. For information about how to configure the Retail module for multiversion POS installations, see the section “Deploy Retail POS for AX 2012 R3,” later in this topic.

## Deploy POS registers when upgrading to AX 2012 R3

Starting with AX 2012 Feature Pack, there is no longer an in-store upgrade process for Retail POS. Instead, you must uninstall the previous version, back up the Retail POS database, and then install AX 2012 R3 Retail POS and create a new database.

For information about installing AX 2012 R3 Retail POS, see [Point of Sale](point-of-sale.md).

Upgrade-related deployment of POS registers differs in one respect from other deployments: You will probably want to set seed values for receipts at existing stores in order to maintain sequential receipt numbers. To do this, open the **Retail POS redeployment** form at **Retail** \> **Periodic** \> **Retail POS redeployment** and specify the appropriate seed values.

To download all required data to an upgraded store, run a full data sync for the store’s channel database. Open the **Channel database** form at **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**. On the **Action Pane**, click **Full data sync** and select distribution schedule 9999.

At the store, install [Microsoft Sync Framework hotfix 2703853](https://support.microsoft.com/kb/2703853) on all computers on which you plan to install Retail POS.


> [!IMPORTANT]
> <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Support for multiple versions of Retail POS

A retail upgrade to AX 2012 Feature Pack required you to upgrade all of your POS register across all of your stores immediately after upgrading the Microsoft Dynamics AX headquarters system. Otherwise data connectivity with the registers would be lost when Microsoft Dynamics AX was stopped for upgrade, and any sales transactions processed after the start of the upgrade had to be manually imported for posting. AX 2012 R2 introduced new functionality that let a previous register version communicate with AX 2012 R2 after the upgrade. This functionality has been enhanced in AX 2012 R3 to support all of the earlier register versions:

  - AX 2009 for Retail (R2 Refresh)

  - AX 2012 Feature Pack

  - AX 2012 R2

Previous-version support depends on the following prerequisites:

  - The Foundation upgrade model must be installed.

  - The **Keep update objects** license configuration key for the appropriate version must be enabled.

  - The **Keep retail objects** license configuration key must be enabled.

  - The **Retail Commerce Data Exchange backward compatibility** license configuration key must be enabled.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Configure AX 2012 R3 to support AX 2009 registers

AX 2012 R3 makes several changes to the configuration of data distribution to enable support for previous POS register versions. The retail channel schema identifies the register version that the scheduler job is configured for and specifies the version-specific data-processing and translation classes. The following diagram shows the resulting service topology.

![R3/2009 support](images/JJ721717.Retail_N-1_A(en-us,AX.60).png "R3/2009 support")

**Service topology to support AX 2009 for Retail (R2 Refresh) registers on an AX 2012 R3 system.**

After the headquarters system has been upgraded to AX 2012 R3, apply the following settings to support use of AX 2009 for Retail (R2 Refresh) POS registers in some stores and AX 2012 R3 POS registers in others.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Distribution location

In AX 2009 for Retail (R2 Refresh), the recommended configuration was to have one database for each register. This configuration is no longer supported, and instead one store database supports all registers in a store.

In AX 2009 for Retail (R2 Refresh), creating a store or register would create a corresponding distribution location with the same location number as the store or register number. In the recommended deployment, each register distribution location had a database profile assigned to it. When a register was assigned to a store, the register distribution location was also added to the distribution subgroup of the same name. Including the register distribution location in the store distribution subgroup ensured that data was sent to all registers in the store.

In AX 2012 R3, a store is mapped to a channel database that replaces the database profile. After the headquarters upgrade, complete the following actions:

1.  Create a new channel data group for each store using the **Channel data group** form at **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel data group**. Set the **Retail channel schema** to **AX 2009 POS**.

2.  Create a new channel database for each store using the **Channel database** form at **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**. On the **Async server (previous version)** FastTab, specify the correct settings for the store database in the **Database name** field and for the legacy synchronization service in the **Async Server (previous version) profile** field.

The contrasting distribution topologies are represented in the following diagram.

![Version compatibility for distribution location](images/JJ721717.Retail_N-1_B(en-us,AX.60).png "Version compatibility for distribution location")

**AX 2012 R3 introduces a simplified distribution topology relying on a single database per store.**

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Scheduler jobs

All Retail installations of Microsoft Dynamics AX use scheduler jobs to define the data mapping between the headquarters Microsoft Dynamics AX database and Retail POS tables. Complete the following steps to configure the version-specific scheduler jobs.

1.  First, create the default configuration for AX 2012 R3. In the **Retail parameters** form at **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**, click **Initialize**.

2.  To create the default scheduler definitions for AX 2009 for Retail (R2 Refresh), open the Microsoft Dynamics AX Application Object Tree (AOT), expand the **Classes** node, double-click **RetailCDXSeedData\_AX5**, and click **Go** to generate the scheduler jobs and subjobs.

3.  For any customizations that were made in AX 2009 for Retail (R2 Refresh), corresponding changes to the scheduler job definitions must also be made.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Data translation

The database schema has substantially changed between AX 2009 and AX 2012. AX 2012 R3 provides a translation class that maps AX 2012 data elements to the expected format in AX 2009 for Retail (R2 Refresh) POS. The translation class RetailCDXDataTranslatorAX63\_AX5 transforms the data for each scheduler job. Customizations that affect data tables will require the addition of appropriate translation logic to this class. . Another option is to create a new class that inherits from the base class RetailCDXDataTranslator. If you use this approach, specify the derived class as the data translation class for the retail schema.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Distribution schedule

Generating seed data (as described in the “Scheduler jobs” section earlier in this topic) created the version-specific default distribution schedules. Names and descriptions of these, such as 1000\_AX5 / Currency\_AX5, can be viewed in the **Distribution schedule** form at **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

Use the **Data groups** FastTab in this form to add the appropriate channel data groups to the distribution schedules.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Commerce Data Exchange: Real-time Service


> [!NOTE]
> <P>Commerce Data Exchange: Real-time Service is the new name for Transaction Service as of AX 2012 R2.</P>



Setup for AX 2012 R3 will install the previous versions of Commerce Data Exchange: Real-time Service and also create the default Windows services. Configure the settings in RetailTransactionService.exe.config for version 5.1. The file can be found under \<Microsoft Dynamics AX installation folder\>\\CDX\\Real-time Services\\5.1\\Bin. Configure and start the service named **Microsoft Dynamics AX Commerce Data Exchange: Real-time Service 5.1**. The Commerce Data Exchange: Real-time Service profile has several properties that were not present in the Transaction service, but with the exception of Version, these can be ignored when configuring prior-version stores. The relevant configuration options are as follows:

  - **Server**: The name or IP address of the computer on which Commerce Data Exchange: Real-time Service is running.

  - **Port:** The TCP port on which Real-time Service is listening. The default port is 1239.
    

    > [!NOTE]
    > <P>This value must match the value that is specified in the RetailTransactionService.exe.config file.</P>



  - **Passphrase:** The token that is used by the POS register to authenticate itself.

  - **Language**: The language that is used by the .NET Business Connector to log into Microsoft Dynamics AX. This determines the language that is used for any error messages sent from Microsoft Dynamics AX headquarters to Retail POS.

  - **Real-time Service version**: Select **AX 2009** for the required data translation.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Known issues with AX 2009 register support

  - Both the database profile and the Commerce Data Exchange: Synch Service (formerly Store Connect) profile provide an option to test the configured connection. This functionality will not work if the profile represents a Retail POS 2009 database or Store Connect 2009

  - The configuration of discounts in AX 2009 for Retail (R2 Refresh) used priorities to determine which discount offers would apply in Retail POS. AX 2012 R2 replaced the priority settings with concurrency rules. As part of the data translation, the priority of the discounts is based on the time of creation, meaning that the newest discount offer will have the highest priority and the oldest discount offer will have the lowest priority.

  - AX 2009 for Retail (R2 Refresh) supported a fixed retail hierarchy of four levels. This hierarchy was replaced in AX 2012 Feature Pack by the category framework that supports unlimited levels. We recommend against changing the product hierarchy until all Retail POS registers have been upgraded to AX 2012 R2 or AX 2012 R3. Otherwise, the product hierarchy will be truncated to four levels during data translation, which could result in errors during transaction processing at Retail POS.

  - To delete a record in the Retail POS data through an A-job, the primary key for the table is used. For the following Retail POS tables, AX 2012 uses the RecId as primary key but Retail POS 2009 does not, which means records will not be deleted when running the corresponding distribution schedule:
    
    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p>RBOCUSTTABLE</p></td>
    </tr>
    <tr class="even">
    <td><p>INVENTDIM</p></td>
    </tr>
    <tr class="odd">
    <td><p>CONFIGTABLE</p></td>
    </tr>
    <tr class="even">
    <td><p>INVENTCOLOR</p></td>
    </tr>
    <tr class="odd">
    <td><p>INVENTSIZE</p></td>
    </tr>
    <tr class="even">
    <td><p>RBOINVENTSTYLE</p></td>
    </tr>
    <tr class="odd">
    <td><p>RBOCOLORS</p></td>
    </tr>
    <tr class="even">
    <td><p>RBOSIZES</p></td>
    </tr>
    <tr class="odd">
    <td><p>UNIT</p></td>
    </tr>
    <tr class="even">
    <td><p>COMPANYINFO</p></td>
    </tr>
    <tr class="odd">
    <td><p>TAXTABLE</p></td>
    </tr>
    <tr class="even">
    <td><p>POSTRANSACTIONSERVICEPROFILE</p></td>
    </tr>
    <tr class="odd">
    <td><p>RBOSUPPORTEDCOUNTRYREGION</p></td>
    </tr>
    <tr class="even">
    <td><p>RBOPARAMETERS</p></td>
    </tr>
    <tr class="odd">
    <td><p>RBOSTORETABLE</p></td>
    </tr>
    <tr class="even">
    <td><p>RBODISCOUNTOFFERLINE</p></td>
    </tr>
    </tbody>
    </table>


  - Downloading updated Synch Service upload options to a Store Connect 2009 instance is not supported.

  - In AX 2012, only customers that are included in the store’s customer address book are available at Retail POS. However, Retail POS 2009 has no address-book support, which means that removing a customer from the address book will not delete this record in the Retail POS 2009 database and that the customer will still be available in Retail POS.

  - If a product for which the product number (EcoResProdcut.DisplayProductNumber) and item Id (InventTable.ItemId) are different is included in a loyalty scheme, Retail POS 2009 will not calculate the loyalty points.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Configure AX 2012 R3 to support AX 2012 Feature Pack registers

After the headquarters system has been upgraded to AX 2012 R3, apply the following settings to support use of AX 2012 Feature Pack POS registers in some stores and AX 2012 R3 POS registers in others. The diagram below shows the resulting service topology.

![R3/FP sync compatibility](images/JJ721717.Retail_N-1_C(en-us,AX.60).png "R3/FP sync compatibility")

**Service topology to support AX 2012 Feature Pack registers on an AX 2012 R3 system.**

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Distribution location

The distribution locations for the stores and database profiles will be upgraded to a corresponding channel database and channel data group as part of headquarters upgrade. After upgrade is complete, perform the following actions:

1.  Create a new channel data group for each store by using the **Channel data group** form at **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel data group**. Set the **Retail channel schema** to **AX 2012 Feature Pack POS**.

2.  Open the **Channel database** form at **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**. On the **Async server (previous version)** FastTab, specify the correct settings for the store database in the **Database name** field and for the legacy synchronization service in the **Async Server (previous version) profile** field.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Scheduler jobs

Scheduler jobs are used to define the data mapping between the headquarters AX 2012 R3 database and Retail POS tables. Complete the following steps.

1.  First, create the default configuration for AX 2012 R3. In the **Retail parameters** form at **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**, click **Initialize**.

2.  To create the default scheduler definitions for AX 2012 Feature Pack, open the AOT, expand the **Classes** node, double-click **RetailCDXSeedData\_AX61**, and click **Go** to generate the scheduler jobs and subjobs.

3.  For any customizations that were made in AX 2012 Feature Pack, corresponding changes to the scheduler job definitions must also be made.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Data translation

There were minor changes to the database schema between AX 2012 Feature Pack and AX 2012 R3. AX 2012 R3 provides a translation class that maps AX 2012 R3 data elements to the expected format in Retail POS 2012 FP. The translation class RetailCDXDataTranslatorAX63\_AX61 transforms the data for each scheduler job. Customizations that affect data tables will require the addition of appropriate translation logic to this class. Another option is to create a new class that inherits from the base class RetailCDXDataTranslator. If you use this approach, specify the derived class as the data translation class for the retail schema.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Commerce Data Exchange: Real-time Service


> [!NOTE]
> <P>Commerce Data Exchange: Real-time Service is the new name for Transaction Service as of AX 2012 R2.</P>



Setup for AX 2012 R3 will install the previous versions of Commerce Data Exchange: Real-time Service and also create the default Windows services. Configure the settings in RetailTransactionService.exe.config for version 6.1. The file can be found under \<Microsoft Dynamics AX installation folder\>\\CDX\\Real-time Services\\6.1\\Bin. Configure and start the Windows service named **Microsoft Dynamics AX Commerce Data Exchange: Real-time Service 6.1**. The Commerce Data Exchange: Real-time Service profile has several properties that were not present in the Transaction service, but with the exception of Version, these can be ignored when configuring AX 2012 Feature Pack registers. The relevant configuration options are:

  - **Server**: The name or IP address of the computer on which the Real-time Service is running.

  - **Port:** The TCP port on which Real-time Service is listening. The default port is 1239.
    

    > [!NOTE]
    > <P>This value must match the value that is specified in the RetailTransactionService.exe.config file.</P>



  - **Passphrase:** The token that is used by the POS register to authenticate itself.

  - **Language**: The language that is used by the .NET Business Connector to log into Microsoft Dynamics AX. This determines the language that is used for any error messages sent from Microsoft Dynamics AX headquarters to Retail POS.

  - **Real-time Service version**: Select **AX 2012 Feature Pack** for the required data translation.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Known issues with AX 2012 Feature Pack register support

  - The provisioning of the offline database in Retail POS 2012 Feature Pack after upgrading to AX 2012 R3 is not supported.

  - If Retail POS 2012 Feature Pack creates a new customer, Commerce Data Exchange: Real-time Service returns the telephone number but not the email address. The customer’s email address becomes available at the registers after the 1010 distribution schedule runs.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Configure AX 2012 R3 to support AX 2012 R2 registers

After the headquarters system has been upgraded to Microsoft Dynamics AX 2012 R3, apply the following settings to support use of Microsoft Dynamics AX 2012 R2 POS registers in some stores and Microsoft Dynamics AX 2012 R3 POS registers in others. The diagram below shows the resulting service topology.

![R3/R2 sync compatibility](images/JJ721717.Retail_N-1_D(en-us,AX.60).png "R3/R2 sync compatibility")

**Service topology to support AX 2012 R2 registers on an AX 2012 R3 system.**

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Distribution location

The distribution locations for the stores and database profiles will be upgraded to a corresponding channel database and channel data group. After the headquarters upgrade, complete the following actions

1.  Create a new channel data group for each store by using the **Channel data group** form at **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel data group**. Set the **Retail channel schema** field to **AX 2012 R2 POS**. By default, one data group per store is generated, but if stores receive the same data, they can be grouped into one data group for better performance of data transfers.

2.  Create a new channel database for each store by using the **Channel database** form at **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**. On the **Async server (previous version)** FastTab, specify the correct settings for the store database in the **Database name** field and for the legacy synchronization service in the **Async Server (previous version) profile** field.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Scheduler jobs

Scheduler jobs are used to define the data mapping between the headquarters AX 2012 R3 database and Retail POS tables. Complete the following steps.

1.  First, create the default configuration for AX 2012 R3. In the **Retail parameters** form at **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**, click **Initialize**.

2.  To create the default scheduler definitions for AX 2012 R2, open the AOT, expand the **Classes** node, double-click **RetailCDXSeedData\_AX62**, and click **Go** to generate the scheduler jobs and subjobs.

3.  For any customizations that were made in AX 2012 R2, corresponding changes to the scheduler job definitions must also be made.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Data translation

There were minor changes to the database schema between AX 2012 R2 and AX 2012 R3. AX 2012 R3 provides a translation class that maps AX 2012 R3 data elements to the expected format in Retail POS 2012 R2. The translation class RetailCDXDataTranslatorAX63\_AX62 transforms the data for each Scheduler job. Customizations that affect data tables will require the addition of appropriate translation logic to this class. Another option is to create a new class that inherits from the base class RetailCDXDataTranslator. If you use this approach, specify the derived class as the data translation class for the retail schema.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Commerce Data Exchange: Real-time Service


> [!IMPORTANT]
> <P>There were changes to the binding configuration in Real-time Service between AX 2012 R2 and AX 2012 R3 that will not work with AX 2012 R2 POS registers. To support use of AX 2012 R2, you must run an instance of Real-time Service in a separate website with a binding configuration of <STRONG>StreamedTCPBinding</STRONG>.</P>



We recommend that you do not delete the existing Real-time Service web application and website so that it can still be used for AX 2012 R2. Instead, follow the steps below to install and configure a new instance of Real-time Service for AX 2012 R3.

1.  Run Setup in AX 2012 R3 to install a new instance of Real-time Service. Setup in AX 2012 R3 will uninstall the previous version binary files for Real-time Service, but will not remove the existing Real-time Service web application and website for AX 2012 R2.

2.  Configure the new instance of Real-time Service for AX 2012 R3 to a new website and port so you do not upgrade or overwrite the existing web application and website. The relevant properties to configure a new instance are listed below:
    
      - **Application name** – The name of the web application that hosts Real-time Service.
    
      - **Website name** – The name of the website that hosts Real-time Service.
    
      - **App pool name** – The name of the application pool that Real-time Service runs in.
    
      - **HTTPS port** – The port on which Real-time Service receives secure HTTP requests. You can specify any available port.
    
      - **TCP port** – The port on which Real-time Service receives TCP requests. You can specify any available port.

For more information about how to install and configure Real-time Service for AX 2012 R3 by using Setup, see [Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)](install-commerce-data-exchange-real-time-service-retail-transaction-service.md).

If you delete the existing web application and website that hosts Real-time Service before you run Setup in AX 2012 R3, or upgrade over the top of it during Setup, you must manually install and deploy a second instance of Real-time Service for AX 2012 R3 and modify it to support use of AX 2012 R2. Follow the steps below to manually install and deploy a second instance:

1.  Run Windows PowerShell to manually install and configure Real-time Service. For information about how to manually install and configure Real-time Service for AX 2012 R3, see [Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)](install-commerce-data-exchange-real-time-service-retail-transaction-service.md).

2.  Modify the binding configuration for the Real-time Service that you manually installed by changing the web.config file. By default, the file is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\ \\Real-time Services\\6.3\\web.config.
    
    1.  Locate the **services** element. The following XML example shows the services element from a web.config file.
        
        ``` xml
           <services>
              <service behaviorConfiguration="ReleaseBehavior" name="Microsoft.Dynamics.Retail.TransactionServices.TransactionService">
                <endpoint address="Common" binding="netTcpBinding" bindingConfiguration="BufferedTCPBinding" name="Common" contract="Microsoft.Dynamics.Retail.TransactionServices.Contracts.ITransactionService" />
                <endpoint address="SCMonitoring" binding="netTcpBinding" bindingConfiguration="BufferedTCPBinding" name="SCMonitoring" contract="Microsoft.Dynamics.Retail.TransactionServices.Contracts.IStoreConnectMonitoring" />
            ...
              </service>
           </services>
        ```
    
    2.  Change the bindingConfiguration to StreamedTCPBinding for the Common and SCMonitoring endpoint address where binding=”netTCPBinding”. The following XML example shows the services element after changing to StreamedTCPBinding.
        
        ``` xml
                       <services>
              <service behaviorConfiguration="ReleaseBehavior" name="Microsoft.Dynamics.Retail.TransactionServices.TransactionService">
                <endpoint address="Common" binding="netTcpBinding" bindingConfiguration="StreamedTCPBinding" name="Common" contract="Microsoft.Dynamics.Retail.TransactionServices.Contracts.ITransactionService" />
                <endpoint address="SCMonitoring" binding="netTcpBinding" bindingConfiguration="StreamedTCPBinding" name="SCMonitoring" contract="Microsoft.Dynamics.Retail.TransactionServices.Contracts.IStoreConnectMonitoring" />
            ...
              </service>
            </services>
        ```
    
    3.  Save your changes to the web.config file. For more information on how to change the web.config file for Real-time Service, see [Configure settings for Real-time Service](configure-settings-for-real-time-service.md).

3.  At the command prompt, type IISReset, and then press ENTER.

4.  Run Retail scheduler jobs 1070\_AX62 and 1090\_AX62. For more information on how to run scheduler jobs, see [Schedule and run jobs in Retail Scheduler](schedule-and-run-jobs-in-retail-scheduler.md).

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Known issues with AX 2012 R2 register support

The provisioning of the offline database in Retail POS 2012 R2 after upgrading to AX 2012 R3 is not supported.

## Deploy POS registers when upgrading to AX 2012 R2 or AX 2012 Feature Pack


> [!IMPORTANT]
> <P>This section contains legacy documentation for Retail customers who want to upgrade to a version of Microsoft Dynamics AX 2012 prior to Microsoft Dynamics AX 2012 R3 on the headquarters system. If you are upgrading to AX 2012 R3, follow the procedures described in the “Deploy POS registers when upgrading to AX 2012 R3” section earlier in this topic.</P>



Deployment of point of sale (POS) registers is performed on the AX 2012 system at the head office, where the **Retail** module is installed. Deployment of registers after an upgrade of the Retail module is sometimes referred to as *redeployment*. However, the steps are the same for both the initial deployment of the software and redeployment after an upgrade.

### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Before you begin


> [!IMPORTANT]
> <P>Install <A href="https://support.microsoft.com/kb/2703853">Microsoft Sync Framework hotfix 2703853</A> on all computers on which you plan to install Microsoft Dynamics AX for Retail POS.</P>
> <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



Complete the following procedure to prepare for deployment of Retail POS. You must configure both the system at the head office and the individual point-of-sale (POS) registers. This procedure assumes that you have previously installed Retail POS on registers by using the procedures in [Install Retail POS](install-retail-pos.md). If you are upgrading, make sure that you have completed the **Data upgrade checklist** on the AX 2012 system.


> [!NOTE]
> <P>Installation of the AX 2012 version of Retail POS on a system where an older version of POS is installed may fail. We recommend that you remove the older POS version before you try a new installation.</P>



Complete the following steps to prepare for Retail POS deployment.

1.  To enable data transfers between the head office and the POS registers, configure a default distribution setup. For more information, see [Set up or modify table distributions](set-up-or-modify-table-distributions.md).

2.  Initialize configuration data for the head office, and create POS operations. These operations include both legacy operations, such as tender transaction, return item, search item, and set quantity, and operations that are new in AX 2012, such as end shift and suspend shift. New jobs are also created. For more information, see [Retail parameters (form)](https://technet.microsoft.com/library/hh597194\(v=ax.60\)).

3.  At the stores, use the Retail Database Utility to create and configure the databases that you require. For more information, see [Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md).

### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Complete the Retail POS redeployment checklist

The **Retail POS redeployment checklist** contains the tasks that are required for deployment or redeployment, as described in the following procedure. You can use the checklist to deploy all stores at the same time, or you can deploy some stores now and return to the checklist later to deploy additional stores.


> [!NOTE]
> <P>Click <STRONG>System administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Checklists</STRONG> &gt; <STRONG>Retail POS redeployment checklist</STRONG> to open the checklist. Then complete the following procedures.</P>



#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Select stores to redeploy

Click the **Retail POS redeployment checklist** task to open the **Retail stores to deploy** form. When the form is first opened, it displays any existing stores. In an upgrade scenario, stores from the previous installation of AX 2009 or AX 2012 are displayed.


> [!TIP]
> <P>If you are upgrading to AX 2012 R2, you can stagger store redeployments to suit your business requirements. Stores and registers that run the previous version of Microsoft Dynamics AX for Retail POS can run side-by-side with stores and registers that run AX 2012 R2. As you upgrade additional stores and registers, you can run this procedure again to assign initial transaction values.</P>



For each store and POS register, configure the following settings to set initial transaction values.

1.  In the **Store number** field, select a store.

2.  In the **Receipt sale** field, select a POS register.

3.  Upgrade only: Click **Calculate POS number sequences** to automatically populate the fields for number sequences with initial transaction values. You can manually override the values that are generated.

4.  If you are deploying stores after a Retail module upgrade, values for transaction IDs should be initialized based on the values that were stored for each POS register before the upgrade. Because existing transaction data is not downloaded to POS registers after an upgrade, registers that are redeployed must be assigned appropriate initial values. The Retail module calculates suggested initial values based on the last transactions that were posted before the upgrade.
    
    Repeat steps 1 through 3 until initial transaction values have been assigned to all registers in all stores.

5.  By default, transaction values for a new POS register are set to 0 (zero). If you want to specify initial values manually, or to override the calculated values, click **Set up the retail parameters for product creation** to unlock the following fields for operation IDs, so that the fields can be modified:
    
      - **Receipt default**
    
      - **Receipt sale**
    
      - **Receipt return**
    
      - **Receipt sales order**
    
      - **Receipt sales invoice**
    
      - **Receipt payment**
    
      - **Shift ID**
    
      - **Transaction ID**
    
    For more information about these fields, see [Retail POS redeployment (form)](https://technet.microsoft.com/library/jj735277\(v=ax.60\)).

When you have finished configuring initial transaction values, click **Close**.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Reset replication counters


> [!NOTE]
> <P>As part of Microsoft Dynamics AX upgrade and POS redeployment, all data has to be initially replicated (via P-jobs) to the stores. If you are not upgrading, this action is optional.</P>



To trigger P-jobs on the new stores, click the **Reset replication counters** task to reset all data replication counters to 0 (zero), matching the values in the store database. A value of 0 means that all data will be copied from the head office to the stores when the first batch job runs.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Create preactions

A preaction is a data record that indicates which entity was changed, when the entity was changed, and who made the change. Click the **Create pre-actions** task to create the change records that are required.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Convert preactions to action jobs

To send data that has changed to stores, you must convert preactions to actions. Click the **Convert pre-actions to action jobs** task to create the actions that are used to push data to specific stores.

Actions are created based on the dependency hierarchy that is accessible in the **Table distribution** form. The table distribution defines the relation between stores and actual data, in a manner that resembles a SQL join statement.


> [!NOTE]
> <P>This task may take a relatively long time to be completed.</P>



#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Schedule batch jobs

After you have completed the configuration procedures, batch jobs must be scheduled to download required data to the store databases, and to set the initial transaction count on the POS registers. Click the **Schedule batch job** task to open the **Schedule redeployment** form.

The data replication that is involved in POS deployment can be controlled by using the Microsoft Dynamics AX batch framework. In the **Schedule redeployment** form, on the **Batch** tab, select a batch group. You can select a batch group only after a batch server is assigned to the group. In upgrade scenarios, you can optionally select the DATAUPDATE batch group. This batch group is created by the upgrade framework and starts to run before the upgrade is even completed.

#### ![JJ721717.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ721717.collapse_all(en-us,AX.60).gif")Cleanup tasks

Click the **Cleanup tasks** task to delete the setup data that was created by the previous checklist tasks. This cleanup is required before you can deploy additional stores. For example, you schedule and run batch jobs to deploy stores A and B. You then have to perform this task before you can deploy store C, because this deployment requires different setup values.

Even though this task is labeled “Required,” you can postpone it until all batch jobs for the current store deployment are completed successfully.

  



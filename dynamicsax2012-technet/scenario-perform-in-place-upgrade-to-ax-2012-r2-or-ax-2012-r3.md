---
title: 'Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3'
TOCTitle: 'Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3'
ms:assetid: eb8193f4-0318-427f-bcc9-2919f47afb8f
ms:mtpsurl: https://technet.microsoft.com/library/JJ733502(v=AX.60)
ms:contentKeyID: 49685466
author: tonyafehr
ms.date: 07/29/2015
mtps_version: v=AX.60
---

# Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An upgrade from one version of Microsoft Dynamics AX 2012 to another is known as a minor version or in-place upgrade. This type of upgrade requires no source-to-target workflow of the kind that is used when you upgrade from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009. Instead, the upgrade operations are performed on a copy of your production system. This topic describes the method that Microsoft recommends for an in-place upgrade to either Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3 from a previous Microsoft Dynamics AX 2012 version.


> [!NOTE]
> <P>An upgrade to AX 2012 R2 is almost the same as an upgrade to AX 2012 R3 from a version prior to AX 2012 R2. Throughout this topic, with a few exceptions, only the AX 2012 R3 upgrade scenario is explicitly described.</P>



The recommended topology for this in-place upgrade scenario requires three Microsoft Dynamics AX systems:

  - **Production** – The existing system that you are upgrading.

  - **Test** – A copy of your production system that is used to upgrade the database architecture, test new components, and test the data upgrade.

  - **Development** – A copy of your test system, where you upgrade your customized code and other metadata.

The following diagram summarizes the workflow across the three systems.

![process overview](images/JJ733502.Upgrade_inplace_0000(AX.60).png "process overview")

**Figure 1. Phases of an in-place upgrade.**

By upgrading in the recommended manner, you achieve several goals:

  - Your data and customized code are safely backed up at all times.

  - Operations on the production system that cause downtime are kept to a minimum.

  - You avoid potential conflicts of object IDs in your data and customized code.

## Before you begin

For all versions of Microsoft Dynamics AX, follow these steps before you start an in-place upgrade.

  - Freeze development and the application of hotfixes on the production system for at least two weeks before you copy it to the test system. Track any subsequent changes to the production system, and plan to perform a final delta code upgrade after you complete the main code upgrade on the development system.

  - Delete all earlier upgrade models from all layers of the production environment, and then synchronize the database. Upgrade models contain the word "Upgrade" in the name. For more information, see [How to: Remove (Uninstall) a Model](how-to-remove-uninstall-a-model.md).
    

    > [!IMPORTANT]
    > <P>When you delete upgrade models and synchronize the database, all the DEL_ upgrade tables and fields are removed from the database. If you have a project that you are still upgrading to or AX 2012 R2, complete that project before you upgrade to AX 2012 R3.</P>



  - Before you make a copy of your production database, so that you can use the copy to create the test environment, make sure that no batch jobs are running. Jobs must have the status **Withhold** or **Ended**. Batch jobs should not have the status **Waiting**. For more information, see [View or change batch job status](view-or-change-batch-job-status.md).

  - Make sure that the environment where you are performing the code upgrade has at least 8 GB of RAM. We strongly recommend that the environment have 16 GB of RAM.

  - Any modifications to the core system classes (Application, Global, Info, SysSetupForm, and Session) should be removed from the system before you run the AX 2012 R3 setup steps. You can add these modifications back later, as part of the code upgrade for the layer where the modifications previously existed. Failure to remove these modifications can lead to a state where Microsoft Dynamics AX Application Object Server (AOS) is unable to start or upgrade the database and stored procedures to the correct AX 2012 R3 state.

  - If you have installed any version of the Data Import/Export Framework from InformationSource, you must fully uninstall it before upgrading. This includes removing all binary files by using Add/Remove Programs, and then uninstalling any model that begins with DMF from the FPK layer. For more information see [How to: Remove (Uninstall) a Model](how-to-remove-uninstall-a-model.md).
    
    You do not need to remove installations of the Data Import/Export Framework that were installed as part of cumulative update 7 for AX 2012 R2.

  - Make sure that your production Microsoft Dynamics AX database is in a fully synchronized state. If you removed the upgrade models in a previous step and completed the **Model upgrade checklist** that appeared after you deleted the models, no further action is required. However, if there were no upgrade models, you should not run AX 2012 R3 Setup until you complete one of the following tasks:
    
      - Verify that the Microsoft Dynamics AX Application Object Tree (AOT) and database are correctly synchronized.
    
      - Synchronize the database from the AOT by using the existing (pre-R3) client and AOS instance.
    
    Failure to synchronize the database might cause synchronization issues in the AX 2012 R3 environment and prevent AOS from starting.

  - An upgrade from AX 2012 R2 to AX 2012 R3 does not require a new user license. If you are upgrading to AX 2012 R3 from a pre-R2 version, make sure that you have your new license available during the procedures that follow.

  - Back up your production system data and metadata.

## Starting state

Your production system has one of two possible database architectures, depending on its AX 2012 version.

![Pre-upgrade production system](images/JJ733502.Upgrade_inplace_01(AX.60).png "Pre-upgrade production system")

**Figure 2. The Microsoft Dynamics AX systems that are shown have either a single database for metadata and business data (left), or a separate database for each (right). When the upgrade is completed, the AX 2012 R3 system has a two-database architecture.**

Because of the dual-database architecture that is introduced in AX 2012 R2, this in-place upgrade scenario has two variations. If you are upgrading from Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack, the single database that contains both the model store and business data is split when you run AX 2012 R2 or AX 2012 R3 Setup. If you are upgrading from AX 2012 R2 to AX 2012 R3, the model store and business data are already in separate databases, and no split is necessary.

## Create a test system and prepare for upgrade

The following diagram shows the two possible architectures of a test system.

![Test system](images/JJ733502.Upgrade_inplace_01_5(AX.60).png "Test system")

**Figure 3. Your test system will be a somewhat simplified copy of your production system that includes all components and databases.**

Your test system will be a somewhat simplified copy of your production system that includes the AX components and databases. We recommend a test-system topology in which the AOS instance and the database are on the same computer. If these components are on different computers, the permissions on the two SQL Server databases that are created during upgrade might not be set correctly. In this case, you have to set the permissions manually by using AxUtil grant \<arguments\>

For the sake of simplicity, the diagrams that depict the test and development systems in this topic assume a one-computer system that contains the database, a single AOS instance, a single client, and the debugger (not shown).

## Create a test system

To create a test system, follow these steps:

1.  Install a clean Windows Server system on the computers that will serve as your test environment.

2.  Install Microsoft SQL Server and any other software that is required for your current Microsoft Dynamics AX system.

3.  Install the version of AX 2012 that you are currently using in production.

4.  Restore a copy of your production system Microsoft Dynamics AX databases into SQL Server on the test system.
    
    For tips that can help you restore or copy a Microsoft Dynamics AX system for testing or development purposes, see [Moving between Microsoft Dynamics AX 2012 Environments](https://blogs.msdn.com/b/axsupport/archive/2011/11/07/moving-between-microsoft-dynamics-ax-2012-environments.aspx).
    
    For system requirements, see [Microsoft Dynamics AX 2012 System Requirements](https://www.microsoft.com/en-us/download/details.aspx?id=11094).

## Import customized Web Parts and reports into the AOT

If your current deployment contains customized reports or Enterprise Portal for Microsoft Dynamics AX Web Parts that are not contained in the AOT, you must make sure that these customizations are preserved during upgrade by importing the customized code into the AOT before you install AX 2012 R3 components. Otherwise, the customizations are lost. During code upgrade, the imported reports and Web Parts are handled together with the rest of the customer-layer models. After all other server-based upgrade procedures have been completed, you can redeploy the customizations on their respective servers.

1.  Import reports into the AOT. For information about how to import a report into the AOT, see [How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md).

2.  Import Web Parts into the AOT. For information about how to import a Web Part into the AOT, see [How to: Import Pages into the AOT](how-to-import-pages-into-the-aot.md).

## Uninstall AX components

**Upgrading from AX 2012 or AX 2012 Feature Pack**

Before you run AX 2012 R3 Setup on the test system, follow these steps:

  - Go to **Control Panel** \> **Programs and Features**, and uninstall all Microsoft Dynamics AX components except the AOS instance.
    

    > [!IMPORTANT]
    > <P>The pre-R2 or R3 AOS instance is required to perform the database split during AX 2012 R3 Setup.</P>



  - Make sure that you run Setup as a user who has full permissions to the database.

  - Make sure that you have at least 60GB of free disk space for the installation of temporary files.

**Upgrading from AX 2012 R2**

Before you run AX 2012 R3 Setup on the test system, follow these steps:

  - Go to **Control Panel** \> **Programs and Features**, and uninstall all Microsoft Dynamics AX components.
    

    > [!NOTE]
    > <P>A database split is not necessary when upgrading from AX 2012 R2, so uninstall the AX 2012 R2 AOS instance.</P>



  - Make sure that you run Setup as a user who has full permissions to the database.

  - Make sure that you have at least 60GB of free disk space for the installation of temporary files.

## Run AX 2012 R3 on the test system


> [!NOTE]
> <P>This procedure assumes knowledge of AX 2012 R3 installation. For installation guidance, see <A href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</A>.</P>



**Case 1: Upgrade from AX 2012 or AX 2012 Feature Pack**

![Run setup on single database test system](images/JJ733502.Upgrade_inplace_03(AX.60).png "Run setup on single database test system")

**Figure 6. Run Setup on the test system to (1) split the database, (2) install the new Microsoft models, and (3) upgrade the AOS instance and the client.**

**Case 2: Upgrade from AX 2012 R2**

![Run setup on split database test system](images/JJ733502.Upgrade_inplace_04(AX.60).png "Run setup on split database test system")

**Figure 7. Run Setup on the test system to (1) install the new Microsoft models, and (2) upgrade the AOS instance and the client.**

In this procedure, you run AX 2012 R3 Setup several times on the test system to install updated versions of the AOS instance, client, and debugger, install the models that are required for your deployment, and restructure the database.


> [!IMPORTANT]
> <P>It is very important that you follow the detailed steps that are presented here, because this installation differs in important ways from other installation scenarios.</P>



In both AX 2012 and AX 2012 Feature Pack, a single database contained data and metadata. Beginning with AX 2012 R2, the model store and the business data reside in separate databases to simplify maintenance and backup. Setup automatically splits the single database into the two databases that are used by AX 2012 R2 and AX 2012 R3.

Next, follow these steps by using AX 2012 R3 Setup.

1.  Start Microsoft Dynamics AX Setup on the computer that hosts the AOS instance. Advance through the Setup wizard to the **Select components** page, and select **Databases**. Note that no other components should be selected during this run of Setup. Advance through the Setup wizard to the **Select databases** page, and select **Configure existing databases**.

2.  On the **Connect to the databases** page, in the **Database name** field, select your existing Microsoft Dynamics AX business database.
    

    > [!NOTE]
    > <P>The <STRONG>Baseline database name</STRONG> field should be left blank during this procedure.</P>



3.  On the **Select additional models** page, select the Foundation model, Foundation Upgrade model, and any other models that you require for your deployment. If you are using country/region-specific features, also select the Foundation Labels model.

4.  On the **Select file location** page, select **Specify a temporary file location**, and then enter or browse to an appropriate location in which to store the temporary model files and the SQL Server log file. We recommend that you provide 60 GB of disk capacity for this purpose. Make sure that your current administrative user has full access to this storage location.
    

    > [!NOTE]
    > <P>You will be notified that you are on an older AOS version if you are upgrading from AX 2012 or AX 2012 Feature Pack , and have not uninstalled the AOS instance. Continue and go to the next step.</P>



5.  Confirm your selections, and install the models.
    

    > [!NOTE]
    > <P>After the models are installed, the AOS instance restarts automatically. This restart might take longer than a typical AOS restart. If this process times out and causes an error, restart Setup to continue</P>

    
    After this step is completed, the test system contains two databases, one that contains the business data and one that contains the model store. The model store now consists of the following components:
    
      - Upgraded AX 2012 R3 models in the SYS, GLS, FPK, and SLN layers.
    
      - Non-upgraded customer models in the ISV, VAR, CUS, and USR layers.

6.  To prepare for AOS install, open the AX 2012 Server Configuration Utility (**Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**). Record the values of the following settings on the **Application Object Server** tab:
    
      - TCP/IP port
    
      - Services WSDL port
    
    Record the values of the following settings on the **Database Connection** tab:
    
      - Server name
    
      - Database name
    
    Keep this information available, so that you can provide it to Setup when you are prompted.

7.  Manually uninstall the remaining AOS instance by using **Control Panel** \> **Programs and Features**.
    

    > [!NOTE]
    > <P>This step is only valid when upgrading from AX 2012 or AX 2012 Feature Pack, and the pre-R2 AOS instance exists.</P>

    

    > [!TIP]
    > <P>If you do not manually remove the old AOS instance before you install the new AX 2012 R3 AOS instance, you might encounter multiple errors in subsequent steps. You can return the system to a stable condition in two ways.</P>
    > <P><STRONG>Edit the Windows registry</STRONG></P>
    > <P>If you have to preserve your AOS configuration settings, you can modify the registry. At each of the following registry locations, create a new key that has the name “split_modeldb” and a value of “1”:</P>
    > <UL>
    > <LI>
    > <P>HKEY_CURRENT_USER\Software\Microsoft\Dynamics\6.0\Configuration</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\Software\Microsoft\Dynamics\6.0\Configuration</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\services\Dynamic Server\6.0\</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\services\Dynamic Server\6.0\</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\services\Dynamic Server\6.0\</P>
    > <LI>
    > <P>HKEY_USERS\[your SID]\Software\Microsoft\Dynamics\6.0\</P></LI></UL>
    > <P><STRONG>Uninstall/reinstall AOS</STRONG></P>
    > <P>If you are willing to lose your current AOS configuration, you can restore the system relatively easily by following these steps.</P>
    > <OL>
    > <LI>
    > <P>Uninstall the AX 2012 R3 AOS instance by using <STRONG>Control Panel</STRONG> &gt; <STRONG>Programs and Features</STRONG>.</P>
    > <LI>
    > <P>Use Setup.exe to reinstall the AX 2012 R3 AOS instance and configure it to use the upgraded database.</P></LI></OL>



8.  Start Microsoft Dynamics AX Setup on the computer that hosts the AOS instance. Run Setup, and confirm that an upgrade is being performed. Advanced through the Setup wizard to the **Add or modify components** page, and select **Application Object Server (AOS)**. When you are prompted, provide the AOS and database configuration values that you recorded earlier.

9.  After the installation is completed, make sure that the AOS instance starts successfully. If the restart takes more than 10 minutes, cancel it and try again.

10. Run Setup a third time on the computer that hosts the AOS instance, and also on any other computers if you are using a multi-computer configuration. On the **Add or modify components** page, select and install the following components:
    
    1.  **Client**
    
    2.  **Debugger**
    
    3.  **Management utilities**
    
    After you have successfully split the database (if upgrading from AX 2012 or AX 2012 Feature Pack), installed the models, and installed the other core components, exit Setup, and then follow these steps: steps:

<!-- end list -->

1.  Stop the AOS instance.

2.  **If you are installing cumulative update 6 for Microsoft Dynamics AX 2012 R2 during upgrade:** Follow the procedure in [Fix Element IDs (SQL patch script for AX 2012 R2 + CU6 upgrade scenarios)](fix-element-ids-sql-patch-script-for-ax-2012-r2-cu6-upgrade-scenarios.md).

3.  Start the AOS instance.

4.  Perform a full kernel compilation:
    
      - **If you are upgrading to AX 2012 R3:** Use the following command:
        
        axbuild xppcompileall
        

        > [!NOTE]
        > <P>Whenever you compile the whole AOT during an upgrade to AX 2012 R3, use axbuild.</P>

    
      - **If you are upgrading to AX 2012 R2:** Use the following command:
        
        Ax32.exe -startupcmd=kernelcompileall
        

        > [!NOTE]
        > <P>This compilation can take five hours or more. The minimum RAM that is required for this operation is 8 GB, but we recommend 16 GB or more.</P>



5.  Manually restart the AOS instance.

## Back up the test system model store and business database

![Back up model store for use in code upgrade](images/JJ733502.Upgrade_inplace_05(AX.60).png "Back up model store for use in code upgrade")

**Figure 8. Export the model store that contains the upgraded Microsoft models to a file.**

To create a backup of the model store and Microsoft Dynamics AX business database, follow these steps:

  - Create a file backup of the model store. This backup is used during code upgrade of the models in the customer layers.

  - To export the model store to a file by using AxUtil, use the following command:
    
    AxUtil.exe exportstore /file:\[full path of file and file name\]
    
    This operation exports the model store as a single file that has the .axmodelstore file name extension. For more information about how to export and import complete model stores, see [How to: Export and Import a Model Store](how-to-export-and-import-a-model-store.md). Alternatively, to save time when you copy large amounts of metadata, you can export and work with individual models in subsequent steps. For more information, see [How to: Export and Import a Model](how-to-export-and-import-a-model.md).
    

    > [!IMPORTANT]
    > <P>In many cases, you can also use backup and restore operations for SQL Server to work with the model store. However, Microsoft Dynamics AX Setup can accept only model store files.</P>



  - Create a backup of the Microsoft Dynamics AX business database.

## Duplicate the test system and perform code upgrade

![Copy test system to development system](images/JJ733502.Upgrade_inplace_06(AX.60).png "Copy test system to development system")

**Figure 9. Create a copy of your test system for development use.**

Duplicate the AX 2012 R3 test system to create the development system, which is used to upgrade customer models. In its initial state, the development system contains the standard Microsoft models for AX 2012 R3 and also any customer models that exist on the legacy system.

## Create a development system

To create a development system, follow these steps:

1.  Install a clean Windows Server system on the computers that will serve as your test environment.

2.  Install Microsoft SQL Server and any other software that is required for AX 2012 R3.

3.  Install AX 2012 R3 on the development system.
    

    > [!WARNING]
    > <P>You have to run AX 2012 R3 Setup on the AOS instance to make sure that stored procedures are updated in the development environment.</P>



4.  Restore a copy of your test system Microsoft Dynamics AX databases into SQL Server on the development system.
    
    For tips that can help you restore or copy a Microsoft Dynamics AX system for testing or development purposes, see [Moving between Microsoft Dynamics AX 2012 Environments](https://blogs.msdn.com/b/axsupport/archive/2011/11/07/moving-between-microsoft-dynamics-ax-2012-environments.aspx).
    
    For system requirements, see [Microsoft Dynamics AX 2012 System Requirements](https://www.microsoft.com/en-us/download/details.aspx?id=11094).

## Prepare development system for code upgrade

Prepare for code upgrade by following these steps on the newly created development system.

1.  On the computer that hosts the AOS instance, open the server configuration utility (**Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**).

2.  If no existing configuration can be modified, create a new configuration.

3.  If you are upgrading to AX 2012 R2, open the **Database Connection** tab and set the baseline database name so that it is the same as the database name in the **Database Connection** tab. This step preserves the pre-R2 model store when Setup splits the original database into separate databases for data and metadata.
    

    > [!WARNING]
    > <P>This step is unnecessary if you are upgrading to AX 2012 R3, which creates the baseline database automatically.</P>



4.  Restart the AOS instance.

5.  Start the client, press CTRL+D to open the AOT, right-click **Data Dictionary**, and then click **Synchronize**.

## Import ISV-provided models into the development system

If an independent software vendor (ISV) has supplied you with upgraded models that are ready for import, import these models into their layers now. Start at the lowest layer, and work up. Model import must be performed as follows to preserve legacy object IDs.

1.  List the models that are installed, and display their IDs, by using the following command:
    
    AxUtil.exe list

2.  Import the models, but preserve the legacy IDs, by using the following command:
    
    AxUtil.exe import /file:\[full path of file and file name\] /replace:\[ID of legacy model\]

For more information about how to import a model from a file, see [How to: Export and Import a Model](how-to-export-and-import-a-model.md).

## Assign the working layer on the development system and delete all higher models

![Remove models from higher-level layers](images/JJ733502.Upgrade_inplace_07(AX.60).png "Remove models from higher-level layers")

**Figure 10. Work on one layer at a time, and remove the models above it.**


> [!NOTE]
> <P>Also delete all the higher models in the baseline model store.</P>



Customer models belong to one of the customer layers. In ascending order, these layers include the ISV, VAR, CUS, and USR layers. Code upgrade is performed by layer. In other words, each customer layer is upgraded separately, starting at the lowest layer and working up through the higher layers. The lowest layer is the layer that is closest to the SYS layer. All models in a layer are upgraded as part of code upgrade in that layer. For more information, see [Layers](https://technet.microsoft.com/library/aa851164\(v=ax.60\)).


> [!IMPORTANT]
> <P>For simplicity, <STRONG>Figure 10</STRONG> does not display patch layers (VAP, CUP, and so on). If patches are installed on your system, you have to take them into account when you plan for code upgrade. You can merge the patches either before upgrade or during the code upgrade process.</P>



As shown in **Step 1** in **Figure 10**, you first determine the lowest non-upgraded customized layer. Use the Microsoft Dynamics AX Configuration Utility to assign this layer as the working layer. Restart the Microsoft Dynamics AX client to make this change take effect. In **Figure 10**, the VAR layer has been set as the working layer and is shown in yellow. In this example, we assume that the ISV layer has already been upgraded as described in the section “Import ISV-provided models into the development system,” earlier in this topic. For more information about how to set the working layer, see [How to: Set the Layer](https://technet.microsoft.com/library/aa673975\(v=ax.60\)).

Next, as shown in **Step 2**, use AxUtil to delete the models in layers that are higher than the lowest non-upgraded customized layer. For more information about how to remove models by using AxUtil, see [How to: Remove (Uninstall) a Model](how-to-remove-uninstall-a-model.md).

## Upgrade code on the development system and export the upgraded models

![Export upgraded models](images/JJ733502.Upgrade_inplace_08(AX.60).png "Export upgraded models")

**Figure 11. Upgrade code and export models.**

In **Figure 11**, the models in the VAR layer are being upgraded. As shown in **Step 1**, you must complete the tasks on the **Code upgrade checklist for in-place upgrade**. All tasks on the checklist must be completed for each layer that contains models that require upgrade.


> [!NOTE]
> <P>If you plan to compare your pre-upgrade code to your new AX 2012 R3 code, you must configure a baseline database before you start the checklist. When a baseline database is configured, you can compare differences in code versions between the old and new Microsoft code, and between your old and new customizations. If a baseline database is not configured, you can only compare your old customizations (which were designed against the AX 2012, AX 2012 R2, or Feature Pack codebase) to the default AX 2012 R3 code.</P>
> <P>Follow these steps to configure the baseline database.</P>
> <OL>
> <LI>
> <P>Close the Microsoft Dynamics AX client.</P>
> <LI>
> <P>Open the AX 2012 Server Configuration utility (<STRONG>Start</STRONG> &gt; <STRONG>Administrative Tools</STRONG> &gt; <STRONG>Microsoft Dynamics AX 2012 Server Configuration</STRONG>).</P>
> <LI>
> <P>If no existing configuration can be modified, create a new configuration.</P>
> <LI>
> <P>On the <STRONG>Database Connection</STRONG> tab, set the <STRONG>Baseline database name</STRONG> value so that it is the same as the <STRONG>Database name</STRONG> value.</P>
> <LI>
> <P>Restart the AOS instance.</P>
> <LI>
> <P>Reopen the Microsoft Dynamics AX client, and continue with the upgrade.</P></LI></OL>
> <P>At any time while you complete the checklist, if you find that you do not have the basis that is required for code comparison, you can stop the client and configure the baseline database by using this procedure.</P>



After the checklist tasks have been completed, export the upgraded models as shown in **Step 2** of the previous diagram. These models are re-imported during a later procedure. For information about how to export a model to a file, see [How to: Export and Import a Model](how-to-export-and-import-a-model.md).

The **Code upgrade checklist for in-place upgrade** contains the following tasks.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Code upgrade white papers</strong></p></td>
<td><p>For information, see the downloadable <a href="https://go.microsoft.com/fwlink/?linkid=215083">code upgrade white papers</a>. Additionally, see <em>Inside Microsoft Dynamics AX 2009</em>, Chapter 18: “Code upgrade,” pp. 623–644.</p></td>
</tr>
<tr class="even">
<td><p><strong>Remove higher model layers</strong></p></td>
<td><p>See the section “Assign the working layer on the development system and delete all higher models” in this topic.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Restart Application Object Server</strong></p></td>
<td><p>For information, see <a href="restart-application-object-server.md">Restart Application Object Server</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Compile application</strong></p></td>
<td><p>For information, see <a href="compile-application.md">Compile application</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Compile into .NET Framework CIL</strong></p></td>
<td><p>For information, see <a href="compile-into-net-framework-cil.md">Compile into .NET Framework CIL</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Provide license information</strong></p></td>
<td><p>For information, see <a href="provide-license-information.md">Provide license information</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Synchronize database</strong></p></td>
<td><p>For information, see <a href="synchronize-the-database.md">Synchronize the database</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Set up Application Integration Framework</strong></p></td>
<td><p>Services and Microsoft Dynamics AX Application Integration Framework (AIF) require that you register new adapters, services, and basic ports any time that you change the AOT. Click this checklist task before you configure integration ports for the first time after upgrade.</p>
<p>This task initializes all services that are available in AX 2012 R3 and deploys service groups that are automatically deployed. Service groups that are not automatically deployed and enhanced ports can be deployed after this task has run.</p>
<p>Registration of new adapters, services, and ports can take several minutes.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Automatically merge enums</strong></p></td>
<td><p>For information, see <a href="automatically-merge-enums.md">Automatically merge enums</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Update SSRS project references</strong></p></td>
<td><p>Automatically update references for Microsoft SQL Server Reporting Services projects, so that the references compile correctly against the upgraded application. For more information, see <a href="development-tasks-for-reporting.md">Development Tasks for Reporting</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Identify SSRS Reports without a Visual Studio Model Project</strong></p></td>
<td><p>Create a Visual Studio project that contains all reports that do not have a Visual Studio model project. For more information, see <a href="development-tasks-for-reporting.md">Development Tasks for Reporting</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Compile application</strong></p></td>
<td><p>For information, see <a href="compile-application.md">Compile application</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Detect code upgrade conflicts</strong></p></td>
<td><p>For information, see <a href="detect-code-upgrade-conflicts.md">Detect code upgrade conflicts</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Upgrade your metadata</strong></p></td>
<td><p>For information, see <a href="upgrade-your-metadata.md">Upgrade your metadata</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Restart Application Object Server</strong></p></td>
<td><p>For information, see <a href="restart-application-object-server.md">Restart Application Object Server</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Compile into .NET Framework CIL</strong></p></td>
<td><p>For information, see <a href="compile-into-net-framework-cil.md">Compile into .NET Framework CIL</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Export upgraded models</strong></p></td>
<td><p>See earlier in this section, and see also <strong>Step 2</strong> in <strong>Figure 11</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Export upgraded model store</strong></p></td>
<td><p>See the section “Back up the upgraded model store” in this topic.</p></td>
</tr>
</tbody>
</table>


## Import the model store backup into the development system

![Restore customer models from backup](images/JJ733502.Upgrade_inplace_09(AX.60).png "Restore customer models from backup")

**Figure 12. Import the test system model store.**

After you complete the upgrade for a layer, you have to manually rebuild the model store before you can continue to the next layer. On the development system, import the backup of the model store that you made in the section “Back up the test system model store.” To complete this task by using AxUtil, use the following command:

AxUtil.exe importstore /file:\[full path of file and file name\] /idconflict:overwrite

This operation overwrites the upgraded layers, which are the ISV and VAR layers in this example, and also the other layers. Therefore, the upgraded models must be re-imported in the next step.


> [!WARNING]
> <P>The /idconflict:overwrite parameter that is used in this operation deviates from best practices and should be used only in the upgrade scenario that is described here. In other circumstances, this parameter causes the model store to be corrupted.</P>



## Import upgraded models into their layers on the development system

![Import upgraded models](images/JJ733502.Upgrade_inplace_10(AX.60).png "Import upgraded models")

**Figure 13. Import the upgraded model files.**

Import the upgraded model or models into the appropriate customer layers. Start with models from the lowest layer, and then work up through the higher layers. In this example, upgraded customer models are being imported into the ISV and VAR layers, in that order. Model import must be performed by using the following command to preserve legacy object IDs:

AxUtil.exe import /file:\[full path of file and file name\] /replace:\[ID of legacy model\]

For more information about how to import a model from a file, see [How to: Export and Import a Model](how-to-export-and-import-a-model.md).

## Repeat code upgrade for each layer

![Repeat the upgrade process through all layers](images/JJ733502.Upgrade_inplace_11(AX.60).png "Repeat the upgrade process through all layers")

**Figure 14. Repeat the procedure for all layers that require upgrade.**

For each remaining layer that contains customized models, repeat the upgrade procedure, moving from the lowest remaining layer to the highest layer. As shown in **Figure 14**, cycle through the following steps until the models in all layers have been upgraded:

**Step 1**: Assign the working layer.

**Step 2**: Delete models in higher layers.

**Step 3**: Perform the tasks on the code upgrade checklist.

**Step 4**: Export the upgraded models.

**Step 5**: Restore the backup of the model store.

**Step 6**: Import the upgraded models into their respective layers.

## Perform code upgrade on the production system delta

During the time that has elapsed since you copied the production system to create the test system, updates and hotfixes might have been applied to the production system. Before you complete the development steps, you must export any changed models on the production system and merge the changes into the upgraded model store. This requires that you run an additional code upgrade cycle for each affected layer.


> [!IMPORTANT]
> <P>The production system should remain in a complete code freeze from this point until the upgrade is completed.</P>



## Export the upgraded model store

![Back up the upgraded model store](images/JJ733502.Upgrade_inplace_12(AX.60).png "Back up the upgraded model store")

**Figure 15. Export the upgraded model store so that it can be used on the test and production systems.**

Export the fully upgraded model store that you have created on the development system to a file. This file acts as the source of the upgraded customer models that are used to prepare for data upgrade first on the test system and later on the production system.

Before you export the model store, run the following AxUtil command:

AxUtil.exe set /installmode


> [!WARNING]
> <P>If the /installmode flag is not set before export, you will not be able to start your AX 2012 R3 AOS when you try the data upgrade.</P>



The model store can now be exported by using the following command:

AxUtil.exe exportstore /file:\[full path of file and file name\]

This operation exports the model store as a single file that has the .axmodelstore file name extension. For more information about how to export and import complete model stores, see [How to: Export and Import a Model Store](how-to-export-and-import-a-model-store.md).

## Perform data upgrade on test system

## Import the upgraded model store into the test system

![Import upgraded model store into test system](images/JJ733502.Upgrade_inplace_13(AX.60).png "Import upgraded model store into test system")

**Figure 16. Prepare the test system for data upgrade by importing the upgraded model store.**

On the test system, import the model store file that you created in the section “Export the upgraded model store.” To complete this task by using AxUtil, use the following command:

AxUtil.exe importstore /file:\[full path of file and file name\] /idconflict:overwrite

For more information about how to export or import a complete model store, see [How to: Export and Import a Model Store](how-to-export-and-import-a-model-store.md).

The test system now contains the standard AX 2012 R3 models, the upgraded customer models, and a snapshot of the business data.


> [!WARNING]
> <P>Do not synchronize the database at this point, even if you are prompted to do this.</P>




> [!TIP]
> <P>We recommend that you create a backup of both Microsoft Dynamics AX databases at this point. If you experience an error during the data upgrade procedure, you must revert to this earlier state, resolve the underlying issue, and try the data upgrade again.</P>



## Perform data upgrade on the test system

![Run data upgrade checklist on test system](images/JJ733502.Upgrade_inplace_14(AX.60).png "Run data upgrade checklist on test system")

**Figure 17. Complete the tasks on the data upgrade checklist.**


> [!IMPORTANT]
> <P>Before you start the data upgrade, set the SQL Server logging model to <STRONG>Simple</STRONG>. Additionally, confirm that the AOS instance is set up as a batch server, and that it can process the DataUpgrade batch group.</P>



You can now perform the data upgrade by following these steps:

1.  Open the **Data upgrade checklist for in-place upgrade** by clicking **System administration** \> **Setup** \> **Checklists** \> **Data upgrade checklist for in-place upgrade**.

2.  Complete the tasks on the checklist. This iteration of data upgrade acts as a test and also provides a platform for user acceptance testing (UAT) before the production system is upgraded.

The **Data upgrade checklist for in-place upgrade** contains the following tasks.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Import upgraded model store</strong></p></td>
<td><p>See the section “Restore the upgraded model store to the test system,” earlier in this topic.</p></td>
</tr>
<tr class="even">
<td><p><strong>Restart Application Object Server</strong></p></td>
<td><p>For information, see <a href="restart-application-object-server.md">Restart Application Object Server</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Compile into .NET Framework CIL</strong></p></td>
<td><p>For information, see <a href="compile-into-net-framework-cil.md">Compile into .NET Framework CIL</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Provide license information</strong></p></td>
<td><p>For information, see <a href="provide-license-information.md">Provide license information</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Disable SQL Server change tracking</strong></p></td>
<td><p>Turn off change tracking in SQL Server. Database synchronization cannot be completed without errors unless change tracking is disabled.</p>
<div class="alert">

> [!NOTE]
> <P>If the customer requires that change tracking be enabled, you can manually re-enable SQL Server change tracking after data upgrade is completed.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Detect update scripts</strong></p></td>
<td><p>After you click this task, you cannot modify your upgrade scripts. If you encounter an error that is caused by an issue in a script or in your data, you must follow these steps.</p>
<ol>
<li><p>Revert to the state that is described in the previous section, “Restore the upgraded model store to the test system.”</p></li>
<li><p>Resolve the issue that is causing the error.</p></li>
<li><p>Try to upgrade your data again.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p><strong>Presynchronize</strong></p></td>
<td><p>For information, see <a href="presynchronize-upgrade.md">Presynchronize (upgrade)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Synchronize database</strong></p></td>
<td><p>This initial database synchronization can take up to six times as long as a typical synchronization. For more information, see <a href="synchronize-the-database.md">Synchronize the database</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Launch data upgrade</strong></p></td>
<td><p>For information, see <a href="launch-data-upgrade.md">Launch data upgrade</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Upgrade additional features</strong></p></td>
<td><p>For information, see <a href="upgrade-additional-features.md">Upgrade additional features</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Restructure database schema for inherited tables</strong></p></td>
<td><p>This task flattens the legacy table hierarchy to improve performance. Follow the steps in the Infolog window that the task opens. For more information, see the <a href="https://go.microsoft.com/fwlink/?linkid=238709">Upgrade best practices</a> white paper.</p></td>
</tr>
<tr class="even">
<td><p><strong>Restart Application Object Server</strong></p></td>
<td><p>For information, see <a href="restart-application-object-server.md">Restart Application Object Server</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Synchronize database</strong></p></td>
<td><p>For information, see <a href="synchronize-the-database.md">Synchronize the database</a>.</p>
<div class="alert">

> [!IMPORTANT]
> <P>Because of a known issue, this checklist task might already appear to be checked as completed. Regardless of its apparent status, the task must be run at this point.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Set up Application Integration Framework</strong></p></td>
<td><p>Services and AIF require that you register new adapters, services, and basic ports any time that you change the AOT. Click this checklist task before you configure integration ports for the first time after upgrade</p>
<p>This task initializes all services that are available in AX 2012 R3 and deploys service groups that are automatically deployed. Service groups that are not automatically deployed and enhanced ports can be deployed after this task has run.</p>
<p>Registration of new adapters, services, and ports can take several minutes.</p></td>
</tr>
</tbody>
</table>


## Redeploy Web Parts and reports

![Redeploy reports and Web Parts](images/JJ733502.Upgrade_inplace_14_5(AX.60).png "Redeploy reports and Web Parts")

**Figure 18. Redeploy the customized Web Parts and reports that you imported into the AOT in the section “Import customized Web Parts and reports into the AOT.”**

**Redeploy a Reporting Services report**

Follow these steps to redeploy a report after upgrade.

1.  In the AOT, expand the **SSRS Reports** node, and then expand the **Reports** node.

2.  Right-click the **\<Report name\>** node for the layer that contains the customization, such as **\<Report name\>(usr)**. Then click **Deploy**.

3.  Review any messages that were logged during the deployment process, and then close the Infolog window.

For more information, see [Walkthrough: Customizing existing Microsoft Dynamics AX Reports](walkthrough-customizing-existing-microsoft-dynamics-ax-reports.md).

**Redeploy an Enterprise Portal Web Part**

This procedure assumes that you have completed the upgrade of the Enterprise Portal server. Follow these steps to redeploy a Web Part after upgrade.

1.  Open a Command Prompt window, and navigate to C:\\Program Files\\Microsoft Dynamics AX\\60\\Setup.

2.  Run the Enterprise Portal update utility by entering the following command:
    
    AxUpdatePortal -updateall -iisreset -verbose \> "C:\\EPUpdate.log"

## Enter single-user mode on the production system


> [!IMPORTANT]
> <P>Before you start the upgrade on your production system, make a final backup of the database.</P>




> [!TIP]
> <P>This procedure does not support rollback of an upgrade in the production environment. If you want to be able to roll back an upgrade, we strongly recommend that you install a new production environment, except the database, on different equipment. You can then restore the backup of the model store that you created in the development environment to the production environment, and then continue with the data upgrade.</P>



![Enter single-user mode on production system](images/JJ733502.Upgrade_inplace_15(AX.60).png "Enter single-user mode on production system")

**Figure 19. Take the production system out of service to prepare for upgrade. (Only a single-database installation is shown. The procedure is the same if you are upgrading from AX 2012 R2.)**

On the production system, enter single-user mode. All client users except the administrator are disconnected from the Microsoft Dynamics AX system. This action starts the downtime window during which new business transactions cannot be processed. For more information, see [Enter into single-user mode](enter-into-single-user-mode.md).

## Prepare the production system for upgrade

Upgrade on the production system requires that you run AX 2012 R3 Setup on each computer in your deployment. Components of the deployment must be upgraded in the order that is shown in the following procedures.

Follow these steps to prepare the production system.

  - Use **Control Panel** \> **Programs and Features** to uninstall all Microsoft Dynamics AX components except the AOS instance that you are upgrading.

  - Make sure that you run Setup as a user who has full permissions to the database.

  - Make sure that you have at least 60 GB of free disk space for the installation of temporary files.

## Upgrade the production databases

Follow these database upgrade steps as required for your version of AX 2012. *It is very important that you follow the detailed steps that are presented here, because this installation differs in important ways from other installation scenarios.*

**Upgrade a single database**

The following diagram shows the operations that AX 2012 R3 Setup performs when it upgrades a single-database system.

![Equivalent database architectures](images/JJ733502.Upgrade_inplace_18(AX.60).png "Equivalent database architectures")

**Figure 20. Upgrade the database architecture. (1) Remove all Microsoft Dynamics AX components except a single AOS instance. (2) Designate the existing Microsoft Dynamics AX database as the business data database. (3) Create a new database to contain the model store. (4) Import the backup file that contains the upgraded model store into the new database.**

Follow these steps to split and upgrade the single-database system.

1.  Run AX 2012 R3 Setup on your database server.

2.  On the **Add or modify components** page, select **Databases** only.

3.  On the **Select databases** page, select **Configure existing databases**.

4.  On the **Connect to the databases** page, in the **Database name** field, select your existing Microsoft Dynamics AX database.
    

    > [!WARNING]
    > <P>The <STRONG>Baseline database name</STRONG> field should be ignored during this procedure.</P>



5.  On the **Select additional models** page, select the Foundation Upgrade model and any other models that you require for your deployment. If you are using country/region-specific features, also select the Foundation Labels model.
    

    > [!WARNING]
    > <P>If your system has an upgrade model that is left over from a previous upgrade, you must remove that upgrade model. Run the following console command from your server\bin folder:</P>
    > <P>AxUtil delete /model:[model id]</P>



6.  On the **Select file location** page, select **Import an upgraded model store file**, and then enter or browse to the location of the model store backup that you made in the section “Export the upgraded model store.”

7.  Confirm your selections, and install the model store.
    

    > [!WARNING]
    > <P>As shown in <STRONG>Figure 20</STRONG>, the legacy model store tables persist alongside the business data but are not used. These tables should not be deleted, because they act as an archive of your pre-upgrade code customizations.</P>



**Upgrade split databases**

The following diagram shows the operations that AX 2012 R3 Setup performs when it upgrades a system that has two databases.

![Run Setup on a split database installation](images/JJ733502.Upgrade_inplace_18_5(AX.60).png "Run Setup on a split database installation")

**Figure 21. Upgrade the databases. (1) Remove all Microsoft Dynamics AX components except a single AOS instance, and designate the business database and model store. (2) Delete the existing models. (3) Import the backup file that contains the upgraded models into the model store.**

Follow these steps to split and upgrade the single-database system.

1.  Run AX 2012 R3 Setup on your database server.

2.  On the **Add or modify components** page, select **Databases** only.

3.  On the **Select databases** page, select **Configure existing databases**.

4.  On the **Connect to the databases** page, designate your existing Microsoft Dynamics AX databases.

5.  On the **Select additional models** page, select the Foundation Upgrade model and any other models that you require for your deployment. If you are using country/region-specific features, also select the Foundation Labels model.
    

    > [!WARNING]
    > <P>If your system has an upgrade model that is left over from a previous upgrade, you must remove that upgrade model. Run the following console command from your server\bin folder:</P>
    > <P>AxUtil delete /model:[model id]</P>



6.  On the **Select file location** page, select **Import an upgraded model store file**, and then enter or browse to the location of the model store backup that you made in the section “Back up the upgraded model store.”

7.  Confirm your selections, and install the model store.

**Upgrade AOS and other core components**

![Install new components on production system](images/JJ733502.Upgrade_inplace_19(AX.60).png "Install new components on production system")

**Figure 22. Run Setup on the production system to upgrade the core server and client components.**

As shown in **Figure 22**, you now have to run Setup on the computer that hosts the AOS instance to install (that is, upgrade) the following components:

  - AOS

  - Client

  - Debugger

  - Management utilities


> [!WARNING]
> <P>As when you created the test system, make sure that you remove the legacy AOS instance before you install the AX 2012 R3 AOS instance.</P>



Follow these steps to upgrade the core components.

1.  To prepare for AOS upgrade, open the Microsoft Dynamics AX 2012 Server Configuration Utility (**Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**). Record the values of the following settings on the **Application Object Server** tab:
    
      - TCP/IP port
    
      - Services WSDL port
    
    Record the values of the following settings on the **Database Connection** tab:
    
      - Server name
    
      - Database name
    
    Keep this information available so that you can provide it to Setup when you are prompted.

2.  Manually remove the remaining AOS instance by using **Control Panel** \> **Programs and Features**.
    

    > [!TIP]
    > <P>If you do not manually remove the old AOS instance before you install the new AX 2012 R3 AOS instance, you might encounter multiple errors in subsequent steps. You can return the system to a stable condition in two ways.</P>
    > <P><STRONG>Edit the Windows registry</STRONG></P>
    > <P>If you have to preserve your AOS configuration settings, you can modify the registry. At each of the following registry locations, create a new key that has the name “split_modeldb” and a value of “1”:</P>
    > <UL>
    > <LI>
    > <P>HKEY_CURRENT_USER\Software\Microsoft\Dynamics\6.0\Configuration</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\Software\Microsoft\Dynamics\6.0\Configuration</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\services\Dynamic Server\6.0\</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\services\Dynamic Server\6.0\</P>
    > <LI>
    > <P>HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\services\Dynamic Server\6.0\</P>
    > <LI>
    > <P>HKEY_USERS\[your SID]\Software\Microsoft\Dynamics\6.0\</P></LI></UL>
    > <P><STRONG>Uninstall/reinstall AOS</STRONG></P>
    > <P>If you are willing to lose your current AOS configuration, you can restore the system relatively easily by following these steps.</P>
    > <OL>
    > <LI>
    > <P>Uninstall the AX 2012 R3 AOS instance by using <STRONG>Control Panel</STRONG> &gt; <STRONG>Programs and Features</STRONG>.</P>
    > <LI>
    > <P>Use Setup.exe to reinstall the AX 2012 R3 AOS instance and configure it to use the upgraded database.</P></LI></OL>



3.  Run Setup, and confirm that an upgrade is being performed. On the **Add or modify components** page, select **Application Object Server (AOS)**. When you are prompted, provide the AOS and database configuration values that you recorded earlier.

4.  When installation is completed, use the AX 2012 Server Configuration utility to point the AOS instance at the upgraded model store and the business database, which is not yet upgraded.

5.  Use the AX 2012 Configuration utility to point the client at the new AOS instance.

6.  Run Setup again, and install the client, debugger, and management utilities on the AOS computer.

7.  Run Setup on the computer that hosts the Help server. Select **Help Server** for installation, and also select any non-default languages that you want to install. When installation is completed, provide the AOS instance with the address of the Help server. For more information, see [Deployment of the Help server](deployment-of-the-help-server.md).

## Perform data upgrade on the production system

![Run data upgrade checklist on production system](images/JJ733502.Upgrade_inplace_20(AX.60).png "Run data upgrade checklist on production system")

**Figure 23. Complete the tasks on the data upgrade checklist.**

When you start the client after you change the model store, a **The model store has been modified.** dialog box should open automatically. Select **Start the data upgrade checklist for in-place upgrade**, and then click **OK**.

If the dialog box does not open automatically, open the **Data upgrade checklist for in-place upgrade** by clicking **System administration** \> **Setup** \> **Checklists** \> **Data upgrade checklist for in-place upgrade**.

Complete the tasks on the checklist as described in the section “Perform data upgrade on the test system,” earlier in this topic.

## Upgrade additional server components

![Upgrade of additional server components](images/JJ733502.Upgrade_inplace_21(AX.60).png "Upgrade of additional server components")

**Figure 24. Run Setup on the additional server computers.**

When data upgrade is completed, you can complete the upgrade of server components. As shown in **Figure 24**, run Setup on the computers that host Enterprise Portal, Reporting Services, and Microsoft SQL Server Analysis Services, and select the appropriate component for each. When installation is completed, validate these services against the upgraded Microsoft Dynamics AX data. For more information, see [Deploy Enterprise Portal and Role Centers](deploy-enterprise-portal-and-role-centers.md) and [Deployment of reporting](deployment-of-reporting.md).

## Redeploy reports and Web Parts

![Redeploy reports and Web Parts](images/JJ733502.Upgrade_inplace_21_5(AX.60).png "Redeploy reports and Web Parts")

**Figure 25. Redeploy the customized reports and Web Parts that you imported into the AOT in the section “Import customized Web Parts and reports into the AOT.”**

**Redeploy Reporting Services reports**

Follow these steps to redeploy a report after upgrade.

1.  In the AOT, expand the **SSRS Reports** node, and then expand the **Reports** node.

2.  Right-click the **\<Report name\>** node for the layer that contains the customization, such as **\<Report name\>(usr)**. Then click **Deploy**.

3.  Review any messages that were logged during the deployment process, and then close the Infolog window.

For more information, see [Walkthrough: Customizing existing Microsoft Dynamics AX Reports](walkthrough-customizing-existing-microsoft-dynamics-ax-reports.md).

**Redeploy Enterprise Portal Web Parts**

This procedure assumes that you have completed the upgrade of the Enterprise Portal server. Follow these steps to redeploy a Web Part after upgrade.

1.  Open a Command Prompt window, and navigate to C:\\Program Files\\Microsoft Dynamics AX\\60\\Setup.

2.  Run the Enterprise Portal update utility by entering the following command:
    
    AxUpdatePortal -updateall -iisreset -verbose \> "C:\\EPUpdate.log"

## Upgrade additional clients

![Install additional clients](images/JJ733502.Upgrade_inplace_22(AX.60).png "Install additional clients")

**Figure 26. Run Setup on the additional client computers.**

As shown in **Figure 26**, run Setup on your additional Microsoft Dynamics AX client systems to upgrade the client software. Select the following components for installation:

  - Client

  - Management utilities

For large deployments, you might want to perform a silent installation. For more information, see [Install Microsoft Dynamics AX in silent mode](install-microsoft-dynamics-ax-in-silent-mode.md).

## Troubleshoot an in-place upgrade

This section describes common issues that you might encounter during an in-place upgrade.

## While running checklist tasks, you encounter numerous SQL errors reporting a missing “PARTITION” column

It is normal to see partition-related Infolog errors between the time you finish running Setup and the first database synchronization. However, if you see large numbers of system-table partition errors in the setup logs after an AOS startup (which should trigger synchronization), it is possible that the core system tables were not synchronized correctly. If this occurs, contact customer support for assistance.

## The database reported invalid column name “PARTITIONKEY”

This error occurs when batch jobs are still running against the database that is being upgraded.

**Resolution:** Stop the batch jobs that are running against the database, and then start the data upgrade process again.

## Upgrade cannot uninstall a component of Microsoft Dynamics AX

This error occurs when the AX 2012 R3 installer cannot find hotfixes that were applied after the original installation.

**Resolution:** Uninstall the component by using the Control Panel and then install the AX 2012 R3 version of the component.

## AOS fails to start

Starting the new version of the AOS for the first time (in an AX 2012 RTM to R3 in-place upgrade) will fail during synchronization if Management Reporter is installed with change tracking enabled. You may also see failures during the synchronization step of the In-place Upgrade Checklist if change tracking is enabled. If you are testing the upgrade and you have already failed to start the AOS for the first time, then you may need to redo this step again by going back to the previous version and following the steps below and disabling change tracking prior to starting the AOS for the first time.

**Resolution:** Complete the following steps:

1.  Create a backup of the Microsoft Dynamics AX database.

2.  Open SQL Server Management Studio and open a new query window targeted at the Microsoft Dynamics AX database.

3.  Run the following query to create a temporary table and populate it with all tables currently configured for change tracking.
    
    SELECT Distinct T1.NAME AS TABLENAME into \#\#Name FROM SYSOBJECTS T1, sys.change\_tracking\_tables T2 WHERE T1.ID = T2.object\_id ORDER BY T1.NAME

4.  Set the query window to return results as text.

5.  Remove the prior query, and run the following statement.  This query will not disable change tracking, but will generate the commands needed to do so.
    
    SELECT 'ALTER TABLE ' + TableName + ' DISABLE CHANGE\_TRACKING' from \#\#Name

6.  Copy the results to a new query window or Notepad for use later.  Do not run them at this time.

7.  In the first query window, change the SQL statement to the following and run it (results to text).
    
    SELECT 'ALTER TABLE ' + TableName + ' ENABLE CHANGE\_TRACKING' from \#\#Name

8.  Again, copy the results to a new query window or Notepad for later use.

9.  Execute the scripts generated during step 5 to disable change tracking on all tables in the database.

10. Start the AOS instance.

11. After the synchronization step is complete in the In-place Upgrade Checklist, execute the scripts generated during step 7. This will enable change tracking on the tables in the Microsoft Dynamics AX database.
    
    For Management Reporter related objects you could also turn change tracking on again by using the Management Reporter configuration tool.

## See also

[Back up and recover databases (SQL Server)](back-up-and-recover-databases-sql-server.md)

[Drain users from an AOS](drain-users-from-an-aos.md)

[Configure an AOS to access a different database](configure-an-aos-to-access-a-different-database.md)

  



---
title: Synchronize a new table or field with retail databases
TOCTitle: Synchronize a new table or field with retail databases
ms:assetid: 690885db-8cb6-43e2-aed6-fcaa72d5735d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn282391(v=AX.60)
ms:contentKeyID: 54906854
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- xml
---

# Synchronize a new table or field with retail databases 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use the procedures in this topic if you have custom tables for which you want to synchronize data with Retail POS databases. This topic assumes that the tables that you plan to replicate are in Microsoft Dynamics AX and that the appropriate database profiles have been configured.


> [!NOTE]
> <P>Tables that are synchronized through Offline Sync Service can have primary keys with multiple columns. However, the primary key on the table cannot include an identity column. In addition, the clustered index on the table must be defined on the primary key only.</P>



## Add the custom table to the offline synchronization profile

Before you can synchronize data between the store database and the offline database, you must create the new table in the offline synchronization profile by using the following procedure. Tables can also be added to the database manually, if necessary.

1.  In Microsoft Dynamics AX, open a development workspace.

2.  In the AOT, expand **Data Dictionary** \> **Tables**, and then select **RetailOfflineTable**.

3.  Right-click **RetailOfflineTable** to open the **Table browser** form. Create a new line and then add the name of your custom table.

4.  In the Microsoft Dynamics AX client workspace, click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Offline profile**.
    
    We recommend that you create a new offline profile that includes the custom tables. For more information about offline profiles, see [Set up offline profiles](set-up-offline-profiles.md).

5.  In the **Offline profile** form, select a profile and then click **Offline scope**.

6.  On the **Line details** FastTab, click **Add**. In the **Offline table name** field, select the new table.
    

    > [!IMPORTANT]
    > <P>Don’t synchronize the updated offline synchronization profile with channel databases yet. First, you must create the new table in channel databases and offline databases. We recommend that you do not assign the new offline profile to a channel until after you have upgraded the channel database by using the procedures later in this topic.</P>



## Create the custom table in existing channel databases and offline databases

After you have added the new table to the Microsoft Dynamics AX database and the offline synchronization profile, you must modify and run the Retail Channel Configuration Utility for each database. (In releases before AX 2012 R3, the Retail Channel Configuration Utility was called the Retail Store Database Utility.) When you run the modified Retail Channel Configuration Utility, channel databases and offline databases are upgraded to include the new table.

If redeploying the channel database is feasible, you may want to start with a new channel database, set up synchronization with the offline database, and then deploy data to the new channel database.

In either case, you must first modify the Retail Channel Configuration Utility to include the new field.

### ![Dn282391.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn282391.collapse_all(en-us,AX.60).gif")Modify the Retail Channel Configuration Utility

To modify the Retail Channel Configuration Utility, you’ll need to use the Retail SDK. For information about how to install the Retail SDK, see [Install Retail SDK (Retail POS Plug-ins)](install-retail-sdk-retail-pos-plug-ins.md).

1.  Go to the folder where you installed the Retail SDK and open the Microsoft Dynamics AX for Retail POS Plug-ins folder. Open the **Services** folder and double-click the **Services** Visual Studio solution file.

2.  Expand the **CreateDatabase** project and then expand the **Upgrades** node. You will see an existing upgrade SQL script. The name of the script reflects the version of Microsoft Dynamics AX that is installed, for example, Upgrade6.3.0.0.sql. Add a script to the project and increment the version number in the script title. For example, you could name your script Upgrade6.3.0.1.sql.
    

    > [!NOTE]
    > <P>If there is any database-specific information in the new script, remove it.</P>

    
    Right-click the new script and select **Properties** . Set the **Build Action** property to **Embedded Resource**.

3.  Under the **Upgrades** node in the project, double-click the **POSISUPGRADES.xml** file. Near the bottom of the file, you will see version information that matches the original Upgrade.6.3.0.0.sql script, as shown here:
    
    ``` xml
    <!--  Upgrade Id : AppMajor.AppMinor.DbVersion.ReservedForPartners -->
        <POSISUPGRADES>
            <UPGRADEVERSION>6.3.0.0</UPGRADEVERSION>
            <UPGRADESCRIPT>Upgrade6.3.0.0.sql</UPGRADESCRIPT>
        </POSISUPGRADES>
    ```
    
    Add your updated version information underneath the existing information. See the following example.
    
    ``` xml
    <!--  Upgrade Id : AppMajor.AppMinor.DbVersion.ReservedForPartners -->
        <POSISUPGRADES>
            <UPGRADEVERSION>6.3.0.0</UPGRADEVERSION>
            <UPGRADESCRIPT>Upgrade6.3.0.0.sql</UPGRADESCRIPT>
        </POSISUPGRADES>
    <!--  Upgrade Id : AppMajor.AppMinor.DbVersion.ReservedForPartners -->
        <POSISUPGRADES>
            <UPGRADEVERSION>6.3.0.1</UPGRADEVERSION>
            <UPGRADESCRIPT>Upgrade6.3.0.1.sql</UPGRADESCRIPT>
        </POSISUPGRADES>
    ```

4.  Build the **CreateDatabase** project.

5.  Place the new CreateDatabase.dll file in the Services folder of the Retail Channel Configuration Utility.
    
      - In AX 2012 R3, the Retail Channel Configuration Utility is typically located at \<root\>\\Program Files\\Microsoft Dynamics AX\\60\\Retail Database Utility.
    
      - In AX 2012 R2 and AX 2012 Feature Pack, the Retail Store Database Utility is typically located at \<root\>\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail POS\\Services.

### ![Dn282391.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn282391.collapse_all(en-us,AX.60).gif")Run the Retail Channel Configuration Utility

After you have modified the Retail Channel Configuration Utility, you must run it for each channel. If a channel database already exists, the database will be upgraded to include the new field. If a channel database does not yet exist, one will be deployed.

#### ![Dn282391.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn282391.collapse_all(en-us,AX.60).gif")Run the Retail Channel Configuration Utility in AX 2012 R3

1.  Start the Retail Channel Configuration Utility.

2.  Click **Create channel database**.

3.  Specify the name of the SQL Server and the name of the channel database.

4.  Click **Apply**. After the table is created, you will see a dialog that says, “Channel database creation was successful.”

5.  Now you can transfer data from the new table to channel databases.

For more information about how to create databases with the Retail Channel Configuration Utility, see [Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md).

#### ![Dn282391.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn282391.collapse_all(en-us,AX.60).gif")Run the Retail Store Database Utility in AX 2012 R2 or AX 2012 Feature Pack

1.  Start the Retail Store Database Utility. Set the following values, depending on your setup:
    
      - Store ID
    
      - Register ID
    
      - Data area ID
    
      - Store server name
    
      - Store database name
    
    You must also specify whether you are configuring a store database or an offline database.

2.  When you are ready, click **Continue**. After the table is created, you will see a dialog that says, “Store database creation was successful.”

3.  Now you can transfer data from the new table to store databases.

For more information about how to create databases with the Retail Store Database Utility, see [Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md).

## Enable action filtering on the custom table (AX 2012 R2 or AX 2012 Feature Pack)

If you’re using AX 2012 R2 or AX 2012 Feature Pack, you must set up action filters to use A jobs with the new table. Action filters work by tracking the changes that are made to the data in a table. If a user creates, modifies, or deletes a record in a table that is monitored, the action filter automatically collects the information that changed. Change tracking is enabled by default on many tables that are included in Microsoft Dynamics AX for Retail. For information about how to enable change tracking on a custom table, and for example code, see [Walkthrough: Adding an Image to Product Search Results](walkthrough-adding-an-image-to-product-search-results.md).

For more information about action filters and A jobs, see [Set up action filters for Retail data](set-up-action-filters-for-retail-data.md).

## Set up data distribution for the custom table

Next, set up data distribution for the new table. Data is transferred between Microsoft Dynamics AX and Retail POS through Commerce Data Exchange. Retail scheduler jobs in Microsoft Dynamics AX handle the data transfer.

### ![Dn282391.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn282391.collapse_all(en-us,AX.60).gif")Set up data distribution in AX 2012 R3

In AX 2012 R3, the channel schema includes the table distribution, which is used to specify the tables that contain data to transfer to retail channels.

1.  Add the new table to the table distribution by using the **Retail channel schema** form. (Click **Retail** \> **Setup** \> **Retail scheduler** \> **Retail channel schema**.)

2.  Add the new table to an existing subjob or create a new subjob. If you create a new subjob, add the subjob to the appropriate A job. For more information, see [Configure jobs and subjobs in Retail Scheduler](configure-jobs-and-subjobs-in-retail-scheduler.md).

### ![Dn282391.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn282391.collapse_all(en-us,AX.60).gif")Set up data distribution in AX 2012 R2 or AX 2012 Feature Pack

In AX 2012 R2 and AX 2012 Feature Pack, the table distribution tree defines which tables contain data to transfer to retail channels. For instance, if a product is available only at specific stores, that product’s information will be sent only to those stores.

Complete the following procedures to set up data distribution for the new table.

1.  Add the new table to the table distribution. For more information, see [Set up action filters for Retail data](set-up-action-filters-for-retail-data.md) and [Set up or modify table distributions](set-up-or-modify-table-distributions.md).
    

    > [!IMPORTANT]
    > <P>Setting up table distribution is a complex task. We recommend that this task be completed only by a person who is experienced in Microsoft SQL Server administration, and who also has detailed knowledge of the tables and fields in the Microsoft Dynamics AX database.</P>



2.  If you selected a distribution type of **Same as parent distribution**, set up table links. For more information, see [Set up table links](set-up-table-links.md).

3.  Add the new table to an existing subjob or create a new subjob. If you create a new subjob, add the subjob to the appropriate A job. For more information, see [Configure jobs and subjobs in Retail Scheduler](configure-jobs-and-subjobs-in-retail-scheduler.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


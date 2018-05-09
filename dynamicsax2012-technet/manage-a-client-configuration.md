---
title: Manage a client configuration
TOCTitle: Manage a client configuration
ms:assetid: 813ed1c9-aec5-47f5-9c1f-94e934fda5d3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569651(v=AX.60)
ms:contentKeyID: 35949323
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Manage a client configuration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you are a member of the Administrators group on the local computer, you can manage configurations for Microsoft Dynamics AX clients by using the Microsoft Dynamics AX 2012 Configuration utility. For information about how to use a shared configuration file to manage Microsoft Dynamics AX clients, see [Configure clients to use a shared configuration](configure-clients-to-use-a-shared-configuration.md). For information about how to manage configurations for .NET Business Connector, see [Create a configuration for .NET Business Connector](create-a-configuration-for-net-business-connector.md). This topic includes the following sections.

  - Create a new configuration

  - Copy a configuration

  - Rename a configuration

  - Load a configuration

  - Load a configuration from the registry

  - Import a configuration file

  - Save or export a configuration

  - Save a configuration to the registry

  - Export a configuration to a file

  - Export all configurations to a file

  - Save a configuration file that uses a new name

  - Specify a shared configuration file for a client

  - Delete a configuration

## Create a new configuration

You cannot modify the original configuration of a system. To change a configuration, you must create and modify a new configuration. For information about configuring client access to a partition, see [Configure clients to access data in a partition](configure-clients-to-access-data-in-a-partition.md).


> [!IMPORTANT]
> <P>By default, changes that are made to configurations are stored in the registry for each user.</P>



1.  Open the configuration utility. Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  In the **Configuration target** list, select **Local client**.

3.  Click **Manage**, and then click **Create configuration**.

4.  In the **Create configuration** dialog box, in the **Name** box, type a name.

5.  You can copy settings from either the active configuration or the original configuration, which is the default configuration. Select the configuration that you want to copy settings from, and then click **OK**.
    

    > [!NOTE]
    > <P>You cannot delete or rename the original configuration. You can only rename or delete configurations that you create.</P>



## Copy a configuration

1.  In the **Configuration** list, select the configuration that you want to create a copy of.

2.  Click **Manage**, and then click **Create configuration**.

3.  In the **Create configuration** dialog box, in the **Name** box, type a name.

4.  Click **Copy settings from the active configuration**, and then click **OK**.

## Rename a configuration

1.  In the **Configuration** list, select the configuration that you want to rename.

2.  Click **Manage**, and then click **Rename configuration**.

3.  In the **Rename** **configuration** dialog box, in the **New name** box, type a name, and then click **OK**.

## Load a configuration

You can either load a configuration that is stored in the local registry or import a configuration file. Although you can use the **Open** command to view a configuration file that has been saved, Microsoft Dynamics AX does not store the settings from the file in the registry. To store the settings in the registry, you must use the **Import** command.

## Load a configuration from the registry

  - In the **Configuration** list, select the configuration that you want to open.

## Import a configuration file

1.  Click **Manage**, and then click **Import**.

2.  Browse to the configuration file that you want to use, and open the file. Configuration files have the **.axc** extension.

## Save or export a configuration

You can save the startup settings for a client or an instance of .NET Business Connector as a configuration that is stored in the registry. Alternatively, you can save the startup settings as a configuration file. You can use startup settings that are saved to complete the following tasks:

  - Tune Microsoft Dynamics AX. Change settings, and then tune the system by comparing the performance with the performance of saved configurations.

  - Move a configuration from one client to another.

## Save a configuration to the registry

1.  Verify that the configuration that you want to save is selected.

2.  Make any changes that you want to make to the selected configuration.

3.  Click **Apply**, and then click **OK**.

## Export a configuration to a file

Use this procedure if you want to copy a configuration to a client on another computer.

1.  Verify that the configuration that you want to save is selected.

2.  Click **Manage**, and then click **Export configuration to a file**. Enter a location and name for the configuration file, and then click **Save**. The file is saved as an **.axc** file.

## Export all configurations to a file

Use this procedure if you want to copy all configurations from one client.

1.  Verify that the configuration that you want to save is selected.

2.  Click **Manage**, and then click **Export All**. Enter a location and name for the configuration file, and then click **Save**. The file is saved as an **.axc** file.

## Save a configuration file that uses a new name

Use this procedure if you want to create a copy of the configuration file that you have been using.

1.  Import or open a configuration file.

2.  Change the settings in the configuration file.

3.  Click **Manage**, and then click **Save configuration file as**. Enter a location and name for the configuration file, and then click **Save**.

## Specify a shared configuration file for a client

If you saved or exported a configuration file to a network share, use this procedure to specify the shared configuration file that a client uses. For more information about how to use a shared configuration file to manage Microsoft Dynamics AX clients, see [Configure clients to use a shared configuration](configure-clients-to-use-a-shared-configuration.md).

1.  Click **Manage**, and then click **Set Configuration Store**.

2.  Enter the path of the shared configuration file, and then click **OK**.


> [!NOTE]
> <P>After you enter the path of a shared configuration file, you may want a client to use configuration settings that are stored in the registry of the local computer. Click <STRONG>Set Configuration Store</STRONG>, and then delete the path in the <STRONG>Configuration File Path</STRONG> box.</P>



## Delete a configuration

1.  Verify that the configuration that you want to delete is selected.

2.  Click **Manage**, and then click **Delete configuration**.

## See also

[Configure clients to access data in a partition](configure-clients-to-access-data-in-a-partition.md)

[Client configuration commands](client-configuration-commands.md)

[Connect a client to a different Application Object Server instance](connect-a-client-to-a-different-application-object-server-instance.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


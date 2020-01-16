---
title: Manage an AOS configuration
TOCTitle: Manage an AOS configuration
ms:assetid: 4aab5e81-921d-4f7f-b379-adffcb8febce
ms:mtpsurl: https://technet.microsoft.com/library/Aa569618(v=AX.60)
ms:contentKeyID: 35949290
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Manage an AOS configuration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A configuration is a group of startup, connection, performance, and developer settings for an instance of Microsoft Dynamics AX Application Object Server (AOS). Administrators and developers create new AOS configurations to complete the following tasks:

  - **To move an AOS instance from a development environment to a production environment** – The administrator or developer changes the database that an AOS instance points to, and specifies whether the instance enables debugging.

  - **To tune Microsoft Dynamics AX** – The administrator or developer saves a configuration that includes the default values, and then changes various settings, one at a time, to evaluate performance.

This topic includes the following procedures:

1.  Create a new configuration

2.  Save a configuration

3.  Export a configuration

4.  Load a configuration

5.  Import a configuration


> [!WARNING]
> <P>The procedures in this topic are performed by using the Microsoft Dynamics AX 2012 Server Configuration utility. After you make changes in the server configuration utility, the system prompts you to restart the AOS instance. The restart affects all client and database connections to the AOS instance. If you must perform one or more of these procedures on a production server, we recommend that you perform the procedures during off-peak hours to prevent dropped connections for clients and databases.</P>



## Create a new configuration

You cannot modify the original configuration of a system. Therefore, all the fields in the original configuration are unavailable. To change AOS settings, you must create and modify a new configuration.

1.  Open the server configuration utility. Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  In the **Application Object Server instance** list, select the AOS instance that you want to modify.

3.  Click **Manage**, and then click **Create configuration**.

4.  Enter a name for the configuration.

5.  In the **Copy configurations from** section, click **Active configuration** if you loaded a custom configuration and want the new configuration to use the same settings. If you want the new configuration to use the default settings that were configured when the AOS instance was installed, click **Original configuration**. Click **OK**.

You can now make changes in the server configuration utility. All changes apply to the AOS instance that is selected in the **Application Object Server instance** list.

## Save a configuration

After you create a configuration, you can save the changes that you made to that configuration to either the registry or a file. By saving a configuration so that it uses a new name, or so that it is a new file, you can iterate changes over time. The server configuration utility includes the following options for saving a configuration:

  - **If you created a new configuration that is based on the original, or if you loaded a configuration that is already stored in the registry** – To save your changes to the registry, click **Apply** or **OK** in the server configuration utility. To save your changes to a new file, click **Manage** \> **Save configuration as file**, and then click **Apply** or **OK**. The system prompts you to restart the AOS instance to implement the changes.

  - **If you opened a configuration file** – To save your changes to the file that you opened, click **Manage** \> **Save configuration file**. To save your changes to a new file, click **Manage** \> **Save configuration as file**, and then click **Apply** or **OK**. The system prompts you to restart the AOS instance to implement the changes. To save your changes to the registry, import the configuration by using the procedure that is described later in this topic.

## Export a configuration

Use this procedure if you want to copy a configuration to an AOS instance on another computer.

1.  In the server configuration utility, verify that the AOS instance and the configuration that you want to save are selected.

2.  Click **Manage** \> **Export configuration to file**. Enter a location and name for the configuration file, and then click **Save**. The file is saved as an .axc file.

If you created multiple configurations for an AOS instance, you can export all the configurations by clicking **Manage** \> **Export all**. The system informs you of the number of configurations that were exported.

## Load a configuration

1.  In the server configuration utility, in the **Application Object Server instance** list, select the AOS instance that you want to modify.

2.  In the **Configuration** list, select the configuration that you want to load.

3.  Click **Apply**.

## Import a configuration

You can open a configuration file by using the **Open configuration file** command. However, Microsoft Dynamics AX does not store settings from configuration files in the registry. To store settings from configuration files in the registry, you must use the **Import configuration from file** command. Importing a configuration has the following effects:

  - After the configuration is imported, it becomes the active configuration, and the system prompts you to restart the AOS instance.

  - If you imported a configuration file that contains multiple configurations, the first configuration in the file becomes the active configuration.

<!-- end list -->

1.  In the server configuration utility, in the **Application Object Server instance** list, select the AOS instance that you want to modify.

2.  Click **Manage** \> **Import configuration from file**.

3.  Browse to the configuration file that you want to use, and then click **Open**. Configuration files have the **.axc** extension.

## See also

[Install an AOS instance](install-an-aos-instance.md)

[Microsoft Dynamics AX 2012 Server Configuration (form)](https://technet.microsoft.com/library/aa569635\(v=ax.60\))

[Manage AOS performance and availability](manage-aos-performance-and-availability.md)

[Maintain an AOS](maintain-an-aos.md)

  



---
title: Install a Retail channel database
TOCTitle: Install a Retail channel database
ms:assetid: 6c7f96f3-1fc2-4cc5-9c48-2d3876e91856
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741218(v=AX.60)
ms:contentKeyID: 62219106
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Install a Retail channel database 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create a retail channel database by using Setup or Windows PowerShell. Channel databases hold retail data for one or more retail channels, such as online stores or brick-and-mortar stores. Typically, there is one channel database per retail store location that uses Retail POS or Modern POS, or per e-commerce installation. The channel database for a Retail POS is typically located at a brick-and-mortar store, whereas the channel databases for Modern POS or e-commerce installations are typically located at the head office. The data for a channel can be included in more than one channel database.

You can also use the Retail Channel Configuration Utility to create a channel database. For more information, see [Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md).


> [!NOTE]
> <P>Channel databases are used only with Microsoft Dynamics AX 2012 R3. In earlier versions of Microsoft Dynamics AX, the store database provided the functionality now provided by the channel database.</P>



To deploy channel databases from a central location, use the Retail mass deployment toolkit together with System Center Configuration Manager. For more information, see [Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md).

## Before you install a retail channel database

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).
    

    > [!NOTE]
    > <P>Regardless of the version of Microsoft SQL Server that you are installing on, the prerequisite validation utility requires that you install the SQL Server 2008 R2 version of SQL Server Shared Management Objects (SMO). From the location that is provided in the prerequisite details, install the package that is appropriate for your architecture (either x86 or x64).</P>



  - Make sure that Microsoft SQL Server is set up correctly for Microsoft Dynamics AX 2012 for Retail databases. For more information, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).

  - We recommend that you install Commerce Data Exchange: Async Server and Commerce Data Exchange: Real-time Service in the environment before you install channel databases.

## Option 1: Install a retail channel database by using Setup

Use this procedure to install a retail channel database by using the Setup wizard. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Retail channel database**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Create a channel database** page, select the **Configure Retail Channel database** option to configure a channel database by using Setup. If you clear this option, the application files are installed, but a channel database is not configured.
    
    If you’re configuring a channel database, enter the name of the server on which to create the database and the name of the database.
    

    > [!NOTE]
    > <P>If you’re using a named instance of SQL Server, enter the server name in the format <EM>ServerName</EM>\<EM>InstanceName</EM>.</P>



9.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

10. On the **Ready to install** page, click **Install**.

11. After the installation is completed, click **Finish** to close the wizard.

## Option 2: Install a retail channel database by using Windows PowerShell

Use this procedure to install a retail channel database manually by using Windows PowerShell. Manual installations are often performed by businesses and organizations that automate deployments by using scripts.

### ![Dn741218.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741218.collapse_all(en-us,AX.60).gif")Extract installation files

Use Microsoft Dynamics AX Setup to extract the files that are required for manual installation.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  On the **Modify Microsoft Dynamics AX installation** page, click **Add or modify components**, and then click **Next**.

3.  On the **Add or modify components** page, select **Retail channel database**, and then click **Next**.

4.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

5.  On the **Create a channel database** page, clear the **Configure retail channel database** option.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Ready to install** page, click **Install**.

8.  After the installation is completed, click **Finish** to close the wizard.

### ![Dn741218.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741218.collapse_all(en-us,AX.60).gif")Configure settings in the channeldb-settings.xml file

After you extract the installation files by using Setup, you must configure settings in the channeldb-settings.xml file.

1.  Open the folder where the installation files are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Channel Database\\Tools.

2.  Create a copy of the channeldb-settings.xml file for each channel database that you are deploying. We recommend that you not change the original file.

3.  Open your copy of the channeldb-settings.xml file in Microsoft Visual Studio or a text editor, such as Notepad.

4.  Enter a value for the following parameters.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Parameter</p></th>
    <th><p>Enter this value</p></th>
    <th><p>Default value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>ChannelDatabaseServerName</strong></p></td>
    <td><p>The name of the server that hosts the channel database. The script is case-sensitive. For example, enter <strong>value=“DatabaseServer” /&gt;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ChannelDatabaseServerNamedInstanceName</strong></p></td>
    <td><p>The name of the SQL Server instance that hosts the channel database.</p>
    <div class="alert">
    <div class="mtps-table">
    <div class="mtps-row">
    <img src="images/Dn527205.alert_note(AX.60).gif" title="Note" alt="Note" class="note" /><strong>Note</strong>
    </div>
    <div class="mtps-row">
    The format for a SQL Server instance name is either the server name or the full instance name. For example, valid names are <strong>localhost</strong>, <strong>localhost\instance2</strong>, <strong>server1</strong>, and <strong>server1\instance2</strong>.
    </div>
    </div>
    </div></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ChannelDatabaseName</strong></p></td>
    <td><p>The name of the channel database.</p></td>
    <td><p>None</p></td>
    </tr>
    </tbody>
    </table>


5.  Save your changes.

### ![Dn741218.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741218.collapse_all(en-us,AX.60).gif")Run Windows PowerShell scripts to configure a channel database

After you configure the parameters in the channeldb-settings.xml file, you can run the Windows PowerShell scripts that configure a channel database.


> [!NOTE]
> <P>Windows PowerShell includes a security setting called the execution policy that determines how scripts are run. By default, the execution policy is set to <STRONG>Restricted</STRONG>, which prevents any scripts from running. To run the installation scripts for Microsoft Dynamics AX components, we recommend that you set the execution policy to <STRONG>RemoteSigned</STRONG> by using Set-ExecutionPolicy cmdlet. This setting allows you to run scripts that you’ve written and scripts that have been signed by a trusted publisher.</P>



1.  On the server where you want to run the script, open Windows PowerShell to the folder where the scripts are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Channel Database\\Tools.
    
      - If you’re using Windows Server 2012 or a later operating system, use Windows Explorer to open the folder where the scripts are installed, and then click **File** \> **Open Windows PowerShell** \> **Open Windows PowerShell as administrator**.
    
      - If you’re using Windows Server 2008 R2 or an earlier operating system, start Windows PowerShell as the administrator, and then change the directory by using the following command: CD "\<Path to directory\>".

2.  Run the following command to create the channel database:
    
    ``` powershell
    .\Deploy-Databases.ps1 -SettingsXmlFilePath .\channeldb-settings-updated.xml -TopologyXmlFilePath .\channeldb-topology.xml –Verbose $true
    ```
    
    Example:
    
    .\\DeployDatabases.ps1 -SettingsXmlFilePath “C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Channel Database\\Tools \\channeldb-settings-updated.xml” -TopologyXmlFilePath “C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Channel Database\\Tools\\channeldb-topology.xml” –Verbose $true

## After you install a retail channel database

After you install a channel database, you must complete the following tasks.

  - Set up a Retail scheduler profile for the database. For more information, see [Set up a channel database profile](set-up-a-channel-database-profile.md).

  - On each register where you install Retail POS, configure Retail POS to use the channel database by using the Retail Channel Configuration Utility. For more information, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).

  - Optional: Add the database to a data group. For more information, see [Create a channel data group](create-a-channel-data-group.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


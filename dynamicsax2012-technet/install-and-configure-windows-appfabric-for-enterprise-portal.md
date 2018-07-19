---
title: Install and configure Windows AppFabric for Enterprise Portal
TOCTitle: Install and configure Windows AppFabric for Enterprise Portal
ms:assetid: b9a24873-27cb-456e-893e-b79ee90512f7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn473937(v=AX.60)
ms:contentKeyID: 59371890
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Install and configure Windows AppFabric for Enterprise Portal 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic provides sample configurations and settings for installing [Windows Server AppFabric](http://go.microsoft.com/fwlink/?linkid=324716) with Enterprise Portal for Microsoft Dynamics AX. AppFabric is required to run Enterprise Portal in a web farm with Microsoft Dynamics AX 2012 R2. AppFabric is not required for single-server Enterprise Portal deployments.

Windows Server AppFabric is a set of integrated technologies that make it easier to build, scale and manage Web and composite applications that run on Internet Information Services (IIS). AppFabric extends Windows Server to provide enhanced hosting, management, and caching capabilities for Web applications and middle-tier services. Enterprise Portal uses the AppFabric distributed, in-memory caching services to improve the performance and scalability of the application.


> [!IMPORTANT]
> <P>This document includes sample settings and configurations to help you install AppFabric for Enterprise Portal. Depending on your hardware, software, and computing environment, you might select different settings and configurations from those specified in this document.</P>



This topic includes the following sections

  - Install Windows Server AppFabric on a single server

  - Install Windows Server AppFabric in a cluster


> [!NOTE]
> <P>Previous versions of Windows Server AppFabric were called Velocity Server. This document includes code blocks that make reference to “Velocity”.</P>



## Install and configure Windows Server AppFabric on a single server

Use the following procedures to install Windows Server AppFabric single server and then run the configuration wizard. To install AppFabric in a cluster, see **Install Windows Server AppFabric in a cluster** in this document. The installation program provides the following functionality:

  - Enables you to select specific features to install.

  - Validates the operating system to make sure that the product is not installed in an unsupported state, and indicates which prerequisites have to be installed.

  - Installs AppFabric.

  - Enables you to remove specific AppFabric features or AppFabric as a whole. This makes sure that the computer can be left in a state in which the features or AppFabric can be reinstalled.

  - Creates the AppFabric Caching Service. Sets the services to a startup type of manual and a status of stopped.

The AppFabric Setup program sets configuration settings in the root (server level) Web.config file, the machine.config file, and the applicationHost.config file. You can configure AppFabric either immediately after installation, or in a separate process. Installing and configuring Windows Server AppFabric on a single server requires that you:

1.  Run Setup

2.  Run the configuration wizard

3.  Configure cache settings with PowerShell

4.  Install and configure the cache client

5.  Validate deployment

Each of these processes is described in this topic.

## Run Setup

1.  Run one of the following Setup applications on the Enterprise Portal server:
    
    For AppFabric 1.0, [download](http://go.microsoft.com/fwlink/?linkid=324596) and run the WindowsServerAppFabricSetup\_x64\_6.1.
    
    For AppFabric 1.1, [download](http://go.microsoft.com/fwlink/?linkid=386334) and run the WindowsServerAppFabricSetup\_x64.

2.  On the **Accept License Terms** page, read the license terms, and then accept the terms and then click **Next** to continue, or do not accept the terms and then exit the setup wizard.

3.  On the **Customer Experience Improvement Program** page, select **Yes** to participate in the Customer Experience Improvement program, or **No** not to participate, and then click **Next**.

4.  Clear the **Yes, download and install critical updates** option.

5.  On the **Feature Selection** page, select **Caching Services** and **Cache Administration**, and then click **Next**.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p>Caching Services</p></td>
    <td><p>The distributed Caching Service and related components that enable you to prepare this host as a Caching Service, turning the server into the node of a cluster. You can create a new cluster or join this host to an existing cluster by using the Caching Service.</p></td>
    </tr>
    <tr class="even">
    <td><p>Cache Administration</p></td>
    <td><p>Components that enable you to administer a cache cluster. You can select Cache Administration as an independent component, without other features selected. In that instance, you could use administration tools to administer the Caching Service installed on a separate computer.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If prerequisite software has to be installed, the setup wizard will display the <STRONG>Platform Validation</STRONG> page after the <STRONG>Feature Selection</STRONG> page. You must install the missing prerequisites manually. If all prerequisites have already been installed, the setup wizard will continue to the <STRONG>Confirm Installation Selections</STRONG> page.</P>



6.  On the **Platform Validation** page, review the information and download any prerequisite software. Click the link for a component or a configuration issue for more information. After installing components and resolving issues, click **Refresh** to verify that the problem has been fixed and then click **Next** to continue with the setup wizard.

7.  The **Confirm Installation Selections** page will display a list of the features that were selected in the **Feature Selection** page, and will be installed. It displays a list of the required Windows components and the AppFabric features that will be installed. Verify that the lists are correct, and then click **Install** to begin installation.
    

    > [!NOTE]
    > <P>The Application Server role is required for AppFabric. This role will be included in the list of the required Windows components even if it is already installed, and the installation wizard will verify that it has been installed.</P>



8.  On the **Installation Progress** page, you can monitor the progress of the installation.

9.  On the **Installation Results** page, verify that the installation has succeeded. To display a list of recommended updates that you can install, click the **Recommended Updates** link. To run the configuration wizard, select the **Launch configuration tool** check box, and then click **Finish** to complete the installation wizard. Click **Detailed Installation report** to display a log of setup events.

## Run the configuration wizard

This section describes recommended settings for Windows Server AppFabric with Enterprise Portal. The following table lists settings as they appear in the Windows Server AppFabric Configuration Wizard. For more information about the options or settings in the configuration wizard, see [Configure Windows Server AppFabric](http://go.microsoft.com/fwlink/?linkid=324774).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Configuring Caching service parameters</p></th>
<th><p>Suggested settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set Caching Service configuration</p></td>
<td><p>Select this option</p></td>
</tr>
<tr class="even">
<td><p>Caching Service configuration provider</p></td>
<td><p>XML</p></td>
</tr>
<tr class="odd">
<td><p>File share (UNC server share required: \\server\share)</p></td>
<td><p>Create a file share on the C drive of the Enterprise Portal server. Configure permissions for the share as follows:</p>
<ul>
<li><p>Grant read access for the account under which the Enterprise Portal application pool is running in IIS (This is also the .NET Business Connector proxy account).</p></li>
<li><p>Grant read access for the application caching account.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>New cluster</p></td>
<td><p>Select this option</p></td>
</tr>
<tr class="odd">
<td><p>Cluster size</p></td>
<td><p>Select Small (1-5 computers)</p></td>
</tr>
</tbody>
</table>


Click **Next** to view the next page of the wizard.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Configure AppFabric Cache Node</p></th>
<th><p>Suggested settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Node ports</p></td>
<td><p>Retain default settings</p></td>
</tr>
<tr class="even">
<td><p>Windows firewall exceptions</p></td>
<td><p>Select Windows Server AppFabric: AppFabric Caching Service</p></td>
</tr>
</tbody>
</table>


Click **Finish**. When prompted, click **Yes**.

## Configure cache settings with PowerShell

The procedure in this section uses PowerShell Cmdlts to configure cache settings. For more information, about these cmdlts, see [AppFabric Caching PowerShell Cmdlts](http://go.microsoft.com/fwlink/?linkid=324842) on MSDN.

1.  Open the Caching Administration Windows PowerShell command prompt as an administrator.

2.  Execute the [Use-CacheCluster](http://go.microsoft.com/fwlink/?linkid=324847) command to set the context of your PowerShell session to a particular cache cluster.

3.  Execute the [New-Cache](http://go.microsoft.com/fwlink/?linkid=324848) command to create a new named cache. Make a note of the name you specified. You will enter this cache name in the next procedure.

4.  Execute the [Grant-CacheAllowedClientAccount](http://go.microsoft.com/fwlink/?linkid=324849) command and specify the .NET Business Connector proxy (the account that is used by the Enterprise Portal application pool).

5.  Execute the [Start-CacheCluster](http://go.microsoft.com/fwlink/?linkid=324850) command to start the cache.

## Install and configure the cache client

1.  Run the WindowsServerAppFabricSetup\_x64\_6.1.exe file on the Enterprise Portal server.

2.  On the **Feature Selection** page, select **Cache Client** and clear all other options. Click **Next**.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p>Cache Client</p></td>
    <td><p>The client libraries that enable you to use cache functionality in your applications during development or run time. You can install this component even if you are not installing the Caching Services.</p></td>
    </tr>
    </tbody>
    </table>


3.  Complete the setup wizard.

4.  In Windows explorer, open the c:\\inetpub\\wwwroot\\\<Enterprise Portal web app\> folder. Locate the web.config file and create a backup of this file in a different location.

5.  Open the web.config file.

6.  Locate the \<configSections\>. Add the following section tag:
    
        <section name="dataCacheClient" type="Microsoft.ApplicationServer.Caching.DataCacheClientSection, Microsoft.ApplicationServer.Caching.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35" allowLocation="true" allowDefinition="Everywhere" />

7.  Add the following AppFabric cache client tags to the web.config file *after* the \</configSections\>. Replace “Host\_server\_name” with the name of the name of the server where you installed Windows Server AppFabric. Replace “default” with the name specified when you executed the New-Cache command.
    
        <!-- velocity -->
        <dataCacheClient>
            <localCache isEnabled="false" />
        <hosts>
        <!--List of hosts -->
        <!-- Replace Host_server_name with velocity server name -->
        <host name="Host_server_name" cachePort="22233" />
        </hosts>
        </dataCacheClient>
        <Microsoft.Dynamics>
        <AppFabricCaching CacheName="default" />
        </Microsoft.Dynamics>
        <!-- velocity -->

## Required configurations for AppFabric 1.1

If you installed AppFabric 1.1, you must choose Option 1 or Option 2 in this section and perform the procedures for that option. If you installed AppFabric 1.0, you can skip this section.

You must choose one of these options because AppFabric 1.1 DLLs are not stored in the Global Assembly Cache (GAC). If you run Enterprise Portal in an AppFabric 1.1 environment without performing the procedures for Option 1 or Option 2, Enterprise Portal returns an error.

**Option 1: Add AppFabric codeBase tags to the web.config file** This option is more complex than Option 2, but it reduces overall administration time and troubleshooting because you only have to perform the procedure one time.

**Option 2: Copy AppFabric DLLs to the bin folder** This option is a simple copy/paste, but if the AppFabric DLLs are ever updated, you must repeat this procedure with the updated AppFabric DLLs. Updated DLLs can include AppFabric hotfixes, updates, or version releases. If you do not repeat this procedure whenever AppFabric DLLs are updated, you might receive errors in Enterprise Portal.

## Option 1: Add AppFabric codeBase tags to the web.config file

Use the procedures in this section to add tags to the Enterprise Portal web.config file.

1.  Open the web.config file in Microsoft Visual Studio or a text editor, such as Notepad. By default, the file is located in the following directory on the Enterprise Portal server: C:\\inetpub\\wwwroot\\wss\\VirtualDirectories\\80\\web.config

2.  Add the codebase tag for the following AppFabric DLLs:
    
    Microsoft.ApplicationServer.Caching.Core.dll
    
    Microsoft.ApplicationServer.Caching.Client.dll
    
    Microsoft.WindowsFabric.Common.dll
    
    Microsoft.WindowsFabric.Data.Common.dll
    

    > [!IMPORTANT]
    > <P>The href attribute for the codeBase tag must specify the location of the AppFabric DLLs. By default, the DLLs are located in the following directory: C:\Program Files\AppFabric 1.1 for Windows Server\.</P>

    
        <runtime>
            <assemblyBinding xmlns="urn:schemas-microsoft-com:asm.v1">
        …
        <!-- velocity -->
              <dependentAssembly>
                <assemblyIdentity name="Microsoft.ApplicationServer.Caching.Core" publicKeyToken="31bf3856ad364e35" culture="neutral" />        
                <codeBase version="1.0.0.0" href="C:\Program Files\AppFabric 1.1 for Windows Server\Microsoft.ApplicationServer.Caching.Core.dll"/>
              </dependentAssembly>
              <dependentAssembly>
                <assemblyIdentity name="Microsoft.ApplicationServer.Caching.Client" publicKeyToken="31bf3856ad364e35" culture="neutral" />
                <codeBase version="1.0.0.0" href="C:\Program Files\AppFabric 1.1 for Windows Server\Microsoft.ApplicationServer.Caching.Client.dll"/>
              </dependentAssembly>
              <dependentAssembly>
                <assemblyIdentity name="Microsoft.WindowsFabric.Common" publicKeyToken="31bf3856ad364e35" culture="neutral" />
                <codeBase version="1.0.0.0" href="C:\Program Files\AppFabric 1.1 for Windows Server\Microsoft.WindowsFabric.Common.dll"/>
              </dependentAssembly>
              <dependentAssembly>
                <assemblyIdentity name="Microsoft.WindowsFabric.Data.Common" publicKeyToken="31bf3856ad364e35" culture="neutral" />
                <codeBase version="1.0.0.0" href="C:\Program Files\AppFabric 1.1 for Windows Server\Microsoft.WindowsFabric.Data.Common.dll"/>
              </dependentAssembly>
        <!-- velocity -->
        …
            </assemblyBinding>
          </runtime>

3.  Search the web.config file for the following tag:
    
        <system.web>
        <securityPolicy>
        <trustLevel name="WSS_Medium" policyFile="C:\Program Files\Common Files\Microsoft Shared\Web Server Extensions\14\config\wss_mediumtrust.config" />

4.  Open the directory specified in the trustLevel \> policyFile section of this tag. For example: C:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\config\\

5.  Make a copy of the wss\_mediumtrust.config file in this directory. Rename the copy as wss\_mediumtrust\_appfabric.config.

6.  Open the wss\_mediumtrust\_appfabric.config file.

7.  Search the file for the following tag: class="FirstMatchCodeGroup"

8.  Add the UnionCodeGroup section in a new \<CodeGroup section beneath the “FirstMatchCodeGroup” section. Be sure to add it down to the first closing \</CodeGroup\> tag. The closing tag is not included in the following example:
    
        <CodeGroup 
        class="FirstMatchCodeGroup"
        version="1"
        PermissionSetName="Nothing">
        <IMembershipCondition 
        class="AllMembershipCondition"
        version="1"
        />
        <CodeGroup
        class="UnionCodeGroup"
        version="1"
        PermissionSetName="FullTrust">
        <IMembershipCondition
        class="UrlMembershipCondition"
        version="1"
        Url="file:///C:/Program Files/AppFabric 1.1 for Windows Server/*"
        />

9.  In the web.config file, search for the \<system.web\> tag.

10. Add the following tag in the \<securityPolicy\> section:
    
        <trustLevel name="WSS_Medium_Custom" policyFile="C:\Program Files\Common Files\Microsoft Shared\Web Server Extensions\14\config\wss_mediumtrust_appfabric.config" />

11. Search the file for the \<trust originUrl="" level="WSS\_Medium" /\> tag.

12. Change the trust level to “WSS\_Medium\_Custom”. For example:
    
        <trust originUrl="" level="WSS_Medium_Custom" />

13. Save your changes in the file.

14. From the Run dialog, type iisreset to restart the web service.

## Option 2: Copy AppFabric DLLs to the bin folder

1.  Copy the following files from the C:\\Program Files\\AppFabric 1.1 for Windows Server directory:
    
    1.  Microsoft.ApplicationServer.Caching.Core.dll
    
    2.  Microsoft.ApplicationServer.Caching.Client.dll
    
    3.  Microsoft.WindowsFabric.Common.dll
    
    4.  Microsoft.WindowsFabric.Data.Common.dll

2.  Paste these files into the following directory: C:\\inetpub\\wwwroot\\wss\\VirtualDirectories\\80\\\_app\_bin

3.  From the Run dialog, type iisreset and press Enter.


> [!WARNING]
> <P>If the AppFabric 1.1 DLLs are ever updated, for example if AppFabric 1.2 or 2.0 is released, then you must repeat this procedure with the updated DLLs.</P>



## Validate deployment

Use the following procedure to verify that the AppFabric cache stores Enterprise Portal session on the server.

1.  On the AppFabric server, verify in the Windows Services console that AppFabricCachingService is running.

2.  Open a Windows PowerShell command prompt as an administrator.

3.  Execute the [Get-CacheStatistics](http://go.microsoft.com/fwlink/?linkid=324868) default command. The results should display all zeros.

4.  Open Enterprise Portal and submit an Expense report.

5.  Execute the [Get-CacheStatistics](http://go.microsoft.com/fwlink/?linkid=324868) default command again and verify that the cache displays values. This indicates that cache distribution is working.

## Install and configure Windows Server AppFabric in a cluster

Use the following procedures to install Windows Server AppFabric in a cluster and then run the configuration wizard. The installation program provides the following functionality:

  - Enables you to select specific features to install.

  - Validates the operating system to make sure that the product is not installed in an unsupported state, and indicates which prerequisites must be installed.

  - Installs AppFabric.

  - Enables you to remove specific AppFabric features or AppFabric as a whole, making sure that the computer can be left in a state in which the features or AppFabric can be reinstalled.

  - Creates the AppFabric Caching Service. Sets the services to a startup type of manual and a status of stopped.

The AppFabric Setup program sets configuration settings in the root (server level) Web.config file, the machine.config file, and the applicationHost.config file. You can configure AppFabric either immediately after installation, or in a separate process. Installing and configuring Windows Server AppFabric on a single server requires that you:

1.  Run Setup

2.  Run the configuration wizard

3.  Configure additional servers in the AppFabric cluster

4.  Configure the cluster cache settings with PowerShell

5.  Install and configure the cache client

6.  Validate deployment

Each of these processes is described in this topic.

## Run Setup

1.  [Download](http://go.microsoft.com/fwlink/?linkid=324596) and run the WindowsServerAppFabricSetup\_x64\_6.1.exe file on the host server in the cluster.

2.  On the **Accept License Terms** page, read the license terms, and then accept the terms and then click **Next** to continue, or do not accept the terms and then exit the setup wizard.

3.  On the **Customer Experience Improvement Program** page, select **Yes** to participate in the Customer Experience Improvement program, or **No** not to participate, and then click **Next**.

4.  Clear the **Yes, download and install critical updates** option.

5.  On the **Feature Selection** page, select **Caching Services** and **Cache Administration**, and then click **Next**.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p>Caching Services</p></td>
    <td><p>The distributed Caching Service and related components that enable you to prepare this host as a Caching Service, turning the server into the node of a cluster. You can create a new cluster or join this host to an existing cluster by using the Caching Service.</p></td>
    </tr>
    <tr class="even">
    <td><p>Cache Administration</p></td>
    <td><p>Components that enable you to administer a cache cluster. You can select Cache Administration as an independent component, without other features selected. In that instance, you could use administration tools to administer the Caching Service installed on a separate computer.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If prerequisite software must be installed, the setup wizard will display the <STRONG>Platform Validation</STRONG> page after the <STRONG>Feature Selection</STRONG> page. You must install the missing prerequisites manually. If all prerequisites have already been installed, the setup wizard will continue to the <STRONG>Confirm Installation Selections</STRONG> page.</P>



6.  On the **Platform Validation** page, review the information and download any prerequisite software. Click the link for a component or a configuration issue for more information. After installing components and resolving issues, click **Refresh** to verify that the problem has been fixed and then click **Next** to continue with the setup wizard.

7.  The **Confirm Installation Selections** page will display a list of the features that were selected in the **Feature Selection** page, and will be installed. It displays a list of the required Windows components and the AppFabric features that will be installed. Verify that the lists are correct, and then click **Install** to begin installation.
    

    > [!NOTE]
    > <P>The Application Server role is required for AppFabric. This role will be included in the list of the required Windows components even if it is already installed, and the installation wizard will verify that it has been installed.</P>



8.  On the **Installation Progress** page, you can monitor the progress of the installation.

9.  On the **Installation Results** page, verify that the installation has succeeded. To display a list of recommended updates that you can install, click the **Recommended Updates** link. To run the configuration wizard, select the **Launch configuration tool** check box, and then click **Finish** to complete the installation wizard. Click **Detailed Installation report** to display a log of setup events.

## Run the configuration wizard

This section describes recommended settings for Windows Server AppFabric with Enterprise Portal. The following table lists settings as they appear in the Windows Server AppFabric Configuration Wizard. For more information about the options or settings in the configuration wizard, see [Configure Windows Server AppFabric](http://go.microsoft.com/fwlink/?linkid=324774).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Configuring Caching service parameters</p></th>
<th><p>Suggested settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set Caching Service configuration</p></td>
<td><p>Select this option</p></td>
</tr>
<tr class="even">
<td><p>Caching Service configuration provider</p></td>
<td><p>SQL Server AppFabric Caching Service Configuration Store Provider</p></td>
</tr>
<tr class="odd">
<td><p>New cluster</p></td>
<td><p>Select this option</p></td>
</tr>
<tr class="even">
<td><p>Cluster size</p></td>
<td><p>Select an option</p></td>
</tr>
</tbody>
</table>


Click **Next** to view the next page of the wizard.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Specify settings to create and register an AppFabric Caching Service configuration database that uses the Microsoft SQL Server provider</p></th>
<th><p>Suggested settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Register AppFabric Caching Service configuration database</p></td>
<td><p>Select this option</p></td>
</tr>
<tr class="even">
<td><p>Create AppFabric Caching Service configuration database</p></td>
<td><p>Select this option</p></td>
</tr>
</tbody>
</table>


Enter required information in the **Server** and **Database** fields and then click **OK**.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Configure AppFabric Cache Node</p></th>
<th><p>Suggested settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Node ports</p></td>
<td><p>Retain default settings</p></td>
</tr>
<tr class="even">
<td><p>Windows firewall exceptions</p></td>
<td><p>Select Windows Server AppFabric: AppFabric Caching Service</p></td>
</tr>
</tbody>
</table>


When prompted, click **Yes**.

## Configure additional servers in the AppFabric cluster

On each server in the cluster, repeat the procedures that are described in this section for running Setup and running the configuration wizard. In the configuration wizard, you must select the following options

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Configuring Caching service parameters</p></th>
<th><p>Suggested settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set Caching Service configuration</p></td>
<td><p>Select this option</p></td>
</tr>
<tr class="even">
<td><p>Caching Service configuration provider</p></td>
<td><p>SQL Server AppFabric Caching Service Configuration Store Provider</p></td>
</tr>
<tr class="odd">
<td><p>Join cluster</p></td>
<td><p>Select this option</p></td>
</tr>
</tbody>
</table>


Click **Next** to view the next page of the wizard.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Specify settings to create and register an AppFabric Caching Service configuration database that uses the Microsoft SQL Server provider</p></th>
<th><p>Suggested settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Register AppFabric Caching Service configuration database</p></td>
<td><p>Select this option</p></td>
</tr>
<tr class="even">
<td><p>Create AppFabric Caching Service configuration database</p></td>
<td><p>Clear this option</p></td>
</tr>
</tbody>
</table>


Enter the same information that you previously specified in the **Server** and **Database** fields and then click **OK**.

## Configure the cluster cache settings with PowerShell

The procedure in this section uses PowerShell Cmdlts to complete the process of configuring the cache. For more information, about these cmdlts, see [AppFabric Caching PowerShell Cmdlts](http://go.microsoft.com/fwlink/?linkid=324842) on MSDN.

1.  Open a Windows PowerShell command prompt as an administrator.

2.  Execute the [Use-CacheCluster](http://go.microsoft.com/fwlink/?linkid=324847) command to set the context of your PowerShell session to a particular cache cluster.

3.  Execute the [New-Cache](http://go.microsoft.com/fwlink/?linkid=324848) command to create a new named cache. Make a note of the name you specified. You will enter this cache name in the next procedure.

4.  Execute the [Grant-CacheAllowedClientAccount](http://go.microsoft.com/fwlink/?linkid=324849) command and specify the .NET Business Connector proxy (the account that is used by the Enterprise Portal application pool).

5.  Execute the [Set-CacheConfig](http://go.microsoft.com/fwlink/?linkid=324878) command and specify –Secondaries parameter

6.  Export the configuration with this command: Export-CacheClusterConfig and specify a name for the file.

7.  Open the file that you just created and add the following configuration to the \<advancedProperties\> section:
    
    \<transportProperties maxBufferSize="1000000000" /\>

8.  Import the configuration with this command: Import-CacheClusterConfig

9.  Execute the [Start-CacheCluster](http://go.microsoft.com/fwlink/?linkid=324850) command to start the cache.

## Install and configure the cache client

1.  Run the WindowsServerAppFabricSetup\_x64\_6.1.exe file on the Enterprise Portal server.

2.  On the **Feature Selection** page, select **Cache Client** and clear all other options. Click **Next**.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p>Cache Client</p></td>
    <td><p>The client libraries that enable you to use cache functionality in your applications during development or run time. You can install this component even if you are not installing the Caching Services.</p></td>
    </tr>
    </tbody>
    </table>


3.  Complete the setup wizard.

4.  In Windows explorer, open the $\\inetpub\\wwwroot\\ folder. Locate the web.config file and create a backup of this file in a different location.

5.  Open the web.config file.

6.  Locate the \<configSections\>. Add the following section tag:
    
        <configSections>
        <!-- velocity -->
        <section name="dataCacheClient" type="Microsoft.ApplicationServer.Caching.DataCacheClientSection; Microsoft.ApplicationServer.Caching.Core, Version=1.0.0.0; Culture=neutral, PublicKeyToken=31bf3856ad364e35" allowLocation="true" allowDefinition="Everywhere" />
        <sectionGroup name="Microsoft.Dynamics">
        <section name="Session" type="System.Configuration.SingleTagSectionHandler, System, Version=1.0.5000.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" />
        <section name="ServerState" type="System.Configuration.SingleTagSectionHandler, System, Version=1.0.5000.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" />
        <section name="AppFabricCaching" type="System.Configuration.SingleTagSectionHandler, System, Version=1.0.5000.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" />
        </sectionGroup>
        <!-- velocity -->

7.  Add the following dataCacheClient tag to the web.config file *after* the \</configSections\>. Replace each instance of “Host\_server\_name” with the name of a server. Replace “default” with the name specified when you executed the New-Cache command.
    
        <!-- velocity -->
          <dataCacheClient>
            <localCache isEnabled="false" />
            <hosts>
              <!--List of hosts -->
          <!-- Replace Host_server_name with velocity server name -->
              <host name="Host_server_name1" cachePort="22233" />   
             <host name="Host_server_name2" cachePort="22233" />   
             <host name="Host_server_name3" cachePort="22233" />   
            </hosts>
          </dataCacheClient>
          <Microsoft.Dynamics>
            <AppFabricCaching CacheName="default" />
          </Microsoft.Dynamics>
          <!-- velocity -->

## Validate deployment

Use the following procedure to verify that the AppFabric cache stores Enterprise Portal session on the server.

1.  On the AppFabric server, verify in the Windows Services console that AppFabricCachingService is running.

2.  Open a Windows PowerShell command prompt as an administrator.

3.  Execute the [Get-CacheStatistics](http://go.microsoft.com/fwlink/?linkid=324868) default command. The results should display all zeros.

4.  Restart the web service on the Enterprise Portal server.

5.  Open Enterprise Portal and submit an Expense report.

6.  Execute the [Get-CacheStatistics](http://go.microsoft.com/fwlink/?linkid=324868) default command again and verify that the cache displays values. This indicates that cache distribution is working.

## See also

[Install Enterprise Portal in a Web farm](install-enterprise-portal-in-a-web-farm.md)

  



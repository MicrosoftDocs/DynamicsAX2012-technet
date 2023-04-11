---
title: Install Retail Server
TOCTitle: Install Retail Server
ms:assetid: 15458480-7197-4909-bdab-0999b2fb5b43
ms:mtpsurl: https://technet.microsoft.com/library/Dn741428(v=AX.60)
ms:contentKeyID: 62219706
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install Retail Server 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Retail Server provides services and business logic for Retail Modern POS (point of sale) clients. To deploy Retail Server on multiple computers in a cluster, you can run Setup on each computer or you can manually copy the web application to each computer. Alternatively, you can use Retail mass deployment toolkit with System Center Configuration Manager to deploy Retail Server from a central location. For more information, see [Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md).

This topic includes the following sections.

  - Before you install Retail Server

  - Install Retail Server by using Setup

  - Install Retail Server by using Windows PowerShell


> [!NOTE]
> <P>Retail Server is available only with Microsoft Dynamics AX 2012 R3.</P>



## Before you install Retail Server

  - Be aware that you do not have to install Retail Server in a domain. You can install it as part of a work group on a single computer.

  - Create a service account. This service account is used for the identity of the application pool for Retail Server. This account does not have to be a domain account. It can be a work group account. For more information, see [Create service accounts](create-service-accounts.md).

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - 
    
    Because this component uses Secure Sockets Layer (SSL) encryption, you must install a server certificate that was issued by a trusted certification authority. (For test environments, you can create a self-signed certificate in IIS.) When you run Setup, you will need to enter the thumbprint for the certificate. To view the thumbprint in IIS Manager, double-click the certificate and click the **Details** tab.

## Option 1: Install Retail Server by using Setup

Use this procedure to install Retail Server. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

5.  On the **Select components** page, select **Retail Server**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Configure Retail Server** page, enter the following information about the web site where Retail Server will run.
    
      - **Configure Retail Server** – On the **Configure Retail Server** page, select the check box to configure Retail Server by using Setup. If you clear this option, the application files are installed, but Retail Server is not configured. If you’re configuring Retail Server, enter the following information:
    
      - **Application name** – The name of an existing web application in your server environment or the name of an application that you want Setup to create.
    
      - **Website name** – The name of an existing web site in your server environment or the name of a site that you want Setup to create.
    
      - **App pool name** – The name of an existing web application pool in your server environment or the name of an application pool that you want Setup to create.
    
      - **User name** and **Password** – The credentials for the application pool identity. The user does not have to be a domain account. It can be a member of a work group on the local computer.
    
      - **HTTP port** and **HTTPS port** – You can specify any available ports. Verify that these ports are open in Windows firewall. Also, make a note of these port numbers. The port is used to create the URL for Retail Server in the format: https://\<ServerName\>:Port/\<WebApplicationName\>. This URL is required to activate Retail Modern POS devices that connect to Retail Server.
        

        > [!IMPORTANT]
        > <P>We strongly recommend that you use an HTTPS port for Retail Server.</P>

        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **SSL certificate thumbprint** – The thumbprint for your Secure Sockets Layer (SSL) encryption certificate.

8.  On the **Select a database to use with Retail Server** page, select an existing database. To create a new channel database you must install the Retail channel database component.

9.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

10. On the **Ready to install** page, click **Install**.

11. After the installation is completed, click **Finish** to close the wizard.

## Option 2: Install Retail Server by using Windows PowerShell

Use this procedure to install Retail Server manually by using Windows PowerShell. Manual installations are often performed by businesses and organizations that automate deployments by using scripts.

### ![Dn741428.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741428.collapse_all(en-us,AX.60).gif")Extract installation files

Use Microsoft Dynamics AX Setup to extract the files that are needed for manual installation.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

3.  On the **Select components** page, select **Retail Server**, and then click **Next**.

4.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

5.  On the **Configure Retail Server** page, clear the **Configure Retail Server** option.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Ready to install** page, click **Install**.

8.  After the installation is completed, click **Finish** to close the wizard.

### ![Dn741428.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741428.collapse_all(en-us,AX.60).gif")Configure settings in the rs-settings.xml file

After you extract the installation files by using Setup, you must configure settings in the rs-settings.xml file.

1.  Open the folder where the installation files are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Server\\Tools.

2.  Create a copy of the rs-settings.xml file. We recommend that you do not change the original file.

3.  Open the rs-settings.xml file in Microsoft Visual Studio or a text editor, such as Notepad.

4.  Enter a value for the following parameters:
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Parameter</p></th>
    <th><p>What to enter</p></th>
    <th><p>Default value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>ChannelDatabaseServerName</strong></p></td>
    <td><p>The name of the server that hosts the channel database. The script is case-sensitive. For example, <strong>value=&quot;DatabaseServer&quot; /&gt;</strong></p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ChannelDatabaseServerNamedInstanceName</strong></p></td>
    <td><p>The name of the SQL Server instance that hosts the channel database. The format for a SQL Server instance name is either the server name or the full instance name. For example, valid names are &quot;localhost&quot;, &quot;localhost\instance2&quot;, &quot;server1&quot;, and &quot;server1\instance2”.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ChannelDatabaseName</strong></p></td>
    <td><p>The name of the channel database.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailServerWebAppPoolName</strong></p></td>
    <td><p>The name of an existing web application or the name of an application that you want Setup to create.</p></td>
    <td><p>RetailServerAppPool</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerWebSiteName</strong></p></td>
    <td><p>The name of an existing web site or the name of a site that you want Setup to create.</p></td>
    <td><p>RetailServerWebsite</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailServerWebSiteHttpPort</strong></p></td>
    <td><p>You can specify any available port. Verify that the port is open in Windows firewall. Also, note the port number. The port is used to create the URL for Retail Server in the format: https://&lt;server name&gt;:port/&lt;web application name&gt;. This URL is required to activate Retail Modern POS devices that connect to Retail Server.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerWebSiteHttpsPort</strong></p></td>
    <td><p>You can specify any available port. Verify that the port is open in Windows firewall. Also, note the port number. The port is used to create the URL for Retail Server in the format: https://&lt;server name&gt;:port/&lt;web application name&gt;. This URL is required to activate Retail Modern POS devices that connect to Retail Server.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailServerWebApplicationName</strong></p></td>
    <td><p>The name of an existing web application or the name of an application that you want Setup to create.</p></td>
    <td><p>RetailServer</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerWebSiteSSLCertificateStore</strong></p></td>
    <td><p>The Certificates store specified when the certificate was created or imported.</p></td>
    <td><p>My</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailServerWebSiteSSLCertificateRootStore</strong></p></td>
    <td><p>The server where the certificate is stored.</p></td>
    <td><p>LocalMachine</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerWebSiteWorkingFolder</strong></p></td>
    <td><p>The folder where you want PowerShell to create a new IIS virtual directory.</p></td>
    <td><p>%SystemDrive%\inetpub\wwwroot</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailServerWebAppPoolUser</strong></p></td>
    <td><p>Enter a domain account for the application pool. Enter the account in the form <strong>value=&quot;Domain\User&quot;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerWebSiteSSLCertificateThumbprint</strong></p></td>
    <td><p>The thumbprint for your Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.</p>
    <p></p>
    <p>Because this component uses Secure Sockets Layer (SSL) encryption, you must install a server certificate that was issued by a trusted certification authority. (For test environments, you can create a self-signed certificate in IIS.) You will need to paste the thumbprint for the certificate into the settings file. To view the thumbprint in IIS Manager, double-click the certificate and click the <strong>Details</strong> tab. We recommend that you paste the thumbprint into a text file and remove all spaces before you paste it into the settings file.</p>
    <div class="alert">
    <div class="mtps-table">
    <div class="mtps-row">
    <img src="images/Gg732282.alert_caution(AX.60).gif" title="Caution note" alt="Caution note" class="note" /><strong>Caution</strong>
    </div>
    <div class="mtps-row">
    A thumbprint can contain hidden characters at the beginning of the thumbprint value. You must delete these extra characters before you paste the thumbprint into the settings file.
    </div>
    </div>
    </div></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailServerWebApplicationServiceBinarySourceFolder</strong></p></td>
    <td><p>This folder contains required files for deploying Retail ServerBy default this folder is:</p>
    <p>C:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Server\Package folder</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerWebApplicationWorkingFolder</strong></p></td>
    <td><p>The folder from where the web service will run. You can specify the RetailServerWebApplicationServiceBinarySourceFolder or any available folder.</p></td>
    <td><p>[RetailServerWebSiteWorkingFolder]\[RetailServerWebApplicationName]</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailServerAllownAnonymousMetadata</strong></p></td>
    <td><p>This setting controls OData $metadata accessibility for anonymous users.</p>
    <p>In a developer environment, we recommend setting this parameter to true. Setting this to true enables the system to reference the OData $metadata service to generate client proxy code.</p>
    <p>In a production environment, this setting should be false.</p></td>
    <td><p>False</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerRequireSSL</strong></p></td>
    <td><p>This option can be used to bypass the SSL requirement in a demonstration environment. In a production environment, you must set the option to true and specify values for the other SSL properties in the configuration file.</p></td>
    <td><p>True</p></td>
    </tr>
    </tbody>
    </table>


5.  Save your changes.


> [!IMPORTANT]
> <P>If you deployed Retail Server in a web farm with a load balancer, you must specify a machine key to ensure that client connections retain session. For more information, see <A href="https://go.microsoft.com/fwlink/?linkid=397516">WIF and Web Farms</A>.</P>



### ![Dn741428.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741428.collapse_all(en-us,AX.60).gif")Run PowerShell scripts to deploy and configure Retail Server

After you configure the parameters in the rs-settings.xml file, you can run the Windows PowerShell scripts that deploy and configure Retail Server.

1.  On the server where you want to run the script, open the folder where the PowerShell scripts are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Server\\Tools

2.  If you’re using Windows Server 2012 or a later operating system, use Windows Explorer to open the folder where the scripts are installed. Then click File \> Open Windows PowerShell \> Open Windows PowerShell as administrator.
    
    If you’re using Windows Server 2008 R2 or an earlier operating system, start Windows PowerShell as the administrator. Then, change the directory by using the following command: CD “\<Path to directory\>”.

3.  In the Windows PowerShell console, run the following command to create a credential object in Active Directory for the service account. Replace ‘domain\\useraccount’ and ‘password’ with credentials that have permission to create sites in IIS:
    
        $Cred = @((New-Object System.Management.Automation.PSCredential(‘domain\useraccount',(ConvertTo-SecureString 'password' -AsPlainText -Force))))

4.  Run the following command to deploy and configure Retail Server:
    
        .\DeployRetailServer.ps1 -SettingsXmlFilePath .\rs-settings.xml -TopologyXmlFilePath .\rs-topology.xml -Credentials $Cred –Verbose $true
    
    For example:
    
    .\\DeployRetailServer.ps1 -SettingsXmlFilePath "C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Server\\Tools\\rs-settings.xml" -TopologyXmlFilePath "C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Server\\Tools\\rs-topology.xml" -Credentials $Cred –Verbose $true

## After you install Retail Server

You must create a channel profile and a channel database profile for Retail Server in the Microsoft Dynamics AX client. For more information, see [Set up a channel profile](set-up-a-channel-profile.md) and [Set up a channel database profile](set-up-a-channel-database-profile.md).

After you create the channel and channel database profiles, you can verify Retail Server configurations by opening a store in the **Retail channels** \> **Retail stores** form. In the **Profiles** section, verify that the **Channel profile** and the **Live channel database** fields display the correct channel profile values.

After Retail Server is deployed and configured, you can deploy Microsoft Dynamics AX Retail Modern POS on supported clients. For more information, see [Install Retail Modern POS](install-retail-modern-pos.md).

## See also

[Install Retail Hardware Station](install-retail-hardware-station.md)

  



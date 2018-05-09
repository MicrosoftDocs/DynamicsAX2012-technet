---
title: 'Install Commerce Data Exchange: Async Server'
TOCTitle: 'Install Commerce Data Exchange: Async Server'
ms:assetid: 70b699fc-909d-47af-9c4e-09d9a75ccd57
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741219(v=AX.60)
ms:contentKeyID: 62219107
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Install Commerce Data Exchange: Async Server 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Commerce Data Exchange: Async Server is part of the asynchronous system that shares data between the Microsoft Dynamics AX database and channel databases. Async Server is installed at headquarters and communicates with Microsoft Dynamics AX. In addition to Async Server, Commerce Data Exchange includes Commerce Data Exchange: Async Client, which is installed at channels and communicates with the channel database.

When you install Async Server, the Retail Salt Utility is also installed. The Retail Salt Utility provides extra encryption for the passwords and credentials that are associated with the Microsoft Dynamics AX 2012 for Retail system.


> [!NOTE]
> <P>Async Server is available only with Microsoft Dynamics AX 2012 R3.</P>



To deploy Async Server on multiple computers in a cluster, you can run Setup on each computer. Alternatively, you can use the Retail mass deployment toolkit to deploy Async Server from a central location. For information about how to set up an Internet Information Services (IIS) cluster, see the [Network Load Balancing Deployment Guide](http://technet.microsoft.com/en-us/library/cc754833\(v=ws.10\).aspx). For information about how to use the mass deployment toolkit, see [Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md).

The following sections are included in this topic:

  - Before you install Async Server

  - Install Async Server by using Setup

  - Install Async Server by using Windows PowerShell

  - After you install AsyncServer

## Before you install Async Server

  - Determine how many instances of Async Server you want to install, and on which computers.
    
    In a basic deployment of Retail, one instance of Async Server is installed at headquarters. Operations in a large organization might scale more efficiently if you install multiple Async Server instances, either on a single server or on multiple servers. For more information, see [Deployment topologies for Retail](deployment-topologies-for-retail.md).
    

    > [!WARNING]
    > <P>Although a single instance of Async Server can manage all communications for the organization, excessive load or network latency might decrease performance.</P>



  - Select a service account to run the application pool for Async Server. For information about the requirements for this account, see [Create service accounts](create-service-accounts.md).

  - 
    
    Because this component uses Secure Sockets Layer (SSL) encryption, you must install a server certificate that was issued by a trusted certification authority. (For test environments, you can create a self-signed certificate in IIS.) When you run Setup, you will need to enter the thumbprint for the certificate. To view the thumbprint in IIS Manager, double-click the certificate and click the **Details** tab.
    
    If you deploy Async Server with a self-signed certificate, this certificate must be trusted by the computer running the corresponding Async Client component

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - The SQLCMD utility is required to install Async Server. This utility is typically installed with Microsoft SQL Server. If a version of SQL Server is not installed on the computer where you install Async Server, you can download and install [Microsoft Command Line Utilities 11 for SQL Server](http://www.microsoft.com/en-us/download/details.aspx?id=36433) to meet this requirement.

## Option 1: Install Async Server by using Setup

Use this procedure to install Async Server by using the Setup wizard. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Async Server**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Configure Async Server** page, select the check box to configure Async Server by using Setup. If you clear this check box, the application files are installed, but Async Server is not configured.
    
    If you’re configuring Async Server, enter the following information:
    
      - **Application name** – The name of the web application that hosts Async Server.
    
      - **App pool name** – The name of the application pool that the web application runs under.
        
        We recommend that you specify separate application pools if multiple Retail components are installed on the same computer. Multiple web applications can share an application pool if resources on the computer are limited. However, if the shared application pool fails, all of the applications that use it will stop responding. In addition, if one application is heavily used, it can negatively affect the performance of the other applications in the pool.
    
      - **Website name** – The name of the website that Async Server runs on.
    
      - **User name** and **Password**– The credentials for the application pool identity.
    
      - **HTTPS port** – The port on which Async Server receives HTTPS requests. You can specify any available port. Verify that the port is open in Windows Firewall, and record the port number. The port is used to create the URL for Async Server in the following format: https://\<server name\>:port/\<web application name\>. This URL is required when you configure instances of Async Client that connect to this instance of Async Server.
        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **TCP port (optional)** – The port on which Async Server receives TCP requests. Specify a TCP port if your environment uses high-performance data synchronization. You can specify any available port. Verify that the port is open in Windows Firewall.
    
      - **AOS service user** – The user account that the instance of Microsoft Dynamics AX Application Object Server (AOS) runs as.
    
      - **SSL certificate thumbprint** – The thumbprint for the Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.

9.  On the **Select a database to use with Async Server** page, create a new message database for Async Server. If you install a subsequent instance of Async Server for load balancing, you must select the same message database.
    

    > [!NOTE]
    > <P>You must set up a separate message database for each partition in Microsoft Dynamics AX.</P>



10. On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

11. On the **Ready to install** page, click **Install**.

12. After the installation is completed, click **Finish** to close the wizard.

## Option 2: Install Async Server by using Windows PowerShell

Use this procedure to install Async Server manually by using Windows PowerShell. To install multiple instances of Async Server on the same computer, you must use a manual installation. Manual installations are often performed by businesses and organizations that automate deployments by using scripts.

### ![Dn741219.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741219.collapse_all(en-us,AX.60).gif")Extract installation files

Use Microsoft Dynamics AX Setup to extract the files that are required for manual installation.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  On the **Modify Microsoft Dynamics AX installation** page, click **Add or modify components**, and then click **Next**.

3.  On the **Add or modify components** page, select **Async Server**, and then click **Next**.

4.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

5.  On the **Configure Async Server** page, clear the **Configure Async Server** option.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Ready to install** page, click **Install**.

8.  After the installation is completed, click **Finish** to close the wizard.

### ![Dn741219.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741219.collapse_all(en-us,AX.60).gif")Configure settings in the ss-settings.xml file

After you extract the installation files by using Setup, you must configure settings in the ss-settings.xml file.

1.  Open the folder where the Windows PowerShell scripts are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Async Server\\Tools.

2.  Create a copy of the ss-settings.xml file for each instance of Async Server that you plan to deploy. We recommend that you not change the original file.

3.  Open your copy of the ss-settings.xml file in Microsoft Visual Studio or a text editor, such as Notepad.

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
    <td><p><strong>HQMessageDatabaseServerName</strong></p></td>
    <td><p>The name of the server that hosts the message database for Async Server. The script is case sensitive. For example, enter <strong>value=“DatabaseServer” /&gt;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>HQMessageDatabaseServerNamedInstanceName</strong></p></td>
    <td><p>The name of the Microsoft SQL Server instance that hosts the message database.</p>
    <p>The format for a SQL Server instance name is either the server name or the full instance name. For example, valid formats are <strong>localhost</strong>, <strong>localhost\instance2</strong>, <strong>server1</strong>, and <strong>server1\instance2</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>HQMessageDatabase</strong></p></td>
    <td><p>The name of the message database.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>HQMessageDatabaseServerOverride</strong></p></td>
    <td><p>(Optional) The name of the database server that is used to connect to the message database. By default, the computer name that was used to deploy the database is used.</p></td>
    <td><p>[HQMessageDatabaseServerName]</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteName</strong></p></td>
    <td><p>The name of the website that hosts Async Server.</p></td>
    <td><p>AsyncServerSite</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AppPoolName</strong></p></td>
    <td><p>The name of the application pool for the Async Server web application.</p></td>
    <td><p>AsyncServer</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AppPoolUser</strong></p></td>
    <td><p>The credentials for the application pool identity.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AOSServiceUser</strong></p></td>
    <td><p>The user account that the AOS instance runs as.</p></td>
    <td><p>NT Authority\Network Service</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebApplicationName</strong></p></td>
    <td><p>The name of the web application that hosts Async Server.</p></td>
    <td><p>AsyncServer</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebApplicationServiceBinarySourceFolder</strong></p></td>
    <td><p>The location where the installer copied binary components. By default, the files are located at C:\Program Files (x86)\Microsoft Dynamics AX\60\CDX\Async Server\6.3.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteHttpsPort</strong></p></td>
    <td><p>The port on which Async Server receives HTTPS requests.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteTcpPort</strong></p></td>
    <td><p>The port on which Async Server receives TCP requests. Specify a TCP port if your environment uses high-performance data synchronization.</p></td>
    <td><p>808</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteSSLCertificateThumbprint</strong></p></td>
    <td><p>The thumbprint for the SSL encryption certificate. You must obtain a valid, registered certificate from a provider.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteSSLCertificateRootStore</strong></p></td>
    <td><p>The name of the root store where the SSL certificate that is used to help secure the website is installed.</p></td>
    <td><p>LocalMachine</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteSSLCertificateStore</strong></p></td>
    <td><p>Enter the name of the certificate store where the SSL certificate that is used to help secure the website is installed.</p></td>
    <td><p>My</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteWorkingFolder</strong></p></td>
    <td><p>The path of the physical folder where website files are stored.</p></td>
    <td><p>%SystemDrive%\inetpub\AsyncServerSite</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebApplicationWorkingFolder</strong></p></td>
    <td><p>The path of the physical folder where web application files are stored.</p></td>
    <td><p>[WebSiteWorkingFolder]\[WebApplicationName]</p></td>
    </tr>
    </tbody>
    </table>


5.  Save your changes.

### ![Dn741219.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741219.collapse_all(en-us,AX.60).gif")Run Windows PowerShell scripts to configure Async Server

After you configure the parameters in the ss-settings.xml file, you can run the Windows PowerShell scripts that configure Async Server.


> [!NOTE]
> <P>Windows PowerShell includes a security setting called the execution policy that determines how scripts are run. By default, the execution policy is set to <STRONG>Restricted</STRONG>, which prevents any scripts from running. To run the installation scripts for Microsoft Dynamics AX components, we recommend that you set the execution policy to <STRONG>RemoteSigned</STRONG> by using Set-ExecutionPolicy cmdlet. This setting allows you to run scripts that you’ve written and scripts that have been signed by a trusted publisher.</P>



1.  On the server where you want to run the script, open Windows PowerShell to the folder where the scripts are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Async Server\\Tools.
    
      - If you’re using Windows Server 2012 or a later operating system, use Windows Explorer to open the folder where the scripts are installed. Then click **File** \> **Open Windows PowerShell** \> **Open Windows PowerShell as administrator**.
    
      - If you’re using Windows Server 2008 R2 or an earlier operating system, start Windows PowerShell as the administrator. Then change the directory by using the following command: CD "\<Path to directory\>".

2.  In the Windows PowerShell console, run the following command to create a secure credential object for the application pool identity.
    
    ``` powershell
    $Cred = @((New-Object System.Management.Automation.PSCredential('domain\user', (ConvertTo-SecureString 'password' -AsPlainText -Force))))
    ```

3.  Run the following command to deploy Async Server.
    
    ``` powershell
    .\DeployAsyncServer.ps1 -TopologyXmlFilePath $topologyFileName -SettingsXmlFilePath $updatedSettingsFileName -Credentials $Cred
    ```
    
    Example:
    
    .\\DeployAsyncServer.ps1 -SettingsXmlFilePath “C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Async Server\\Tools\\ss-settings.xml” -TopologyXmlFilePath “C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Async Server\\Tools\\ss-topology.xml” -Credentials $Cred –Verbose $true

## After you install Async Server

After you install Async Server, you must complete the following tasks.

  - Set message database information in the **Retail scheduler parameters** form. Then click the **Sync metadata** button. For more information, see [Enter parameters for Retail Scheduler](enter-parameters-for-retail-scheduler.md).

  - Create a scheduler profile for Async Server. For more information, see [Set up a profile for Async Server](set-up-a-profile-for-async-server.md).

  - Set up working folders. For more information, see [Specify working folders for Commerce Data Exchange](specify-working-folders-for-commerce-data-exchange.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


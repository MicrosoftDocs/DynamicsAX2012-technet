---
title: Install Retail Hardware Station
TOCTitle: Install Retail Hardware Station
ms:assetid: 43c7b127-15c6-4dcc-9eb2-9af2ae14af6d
ms:mtpsurl: https://technet.microsoft.com/library/Dn741431(v=AX.60)
ms:contentKeyID: 62219707
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install Retail Hardware Station 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Microsoft Dynamics AX Retail Hardware Station provides services for Microsoft Dynamics AX Retail Retail Modern POS (point of sale) clients and peripherals such as printers, cash drawers, or payment devices that enable these devices to communicate with Microsoft Dynamics AX Retail Server. This section includes the following information about how to install and configure Hardware Station.

  - Before you begin

  - Install Hardware Station by using Setup

  - Install Hardware Station by using Windows PowerShell


> [!NOTE]
> <P>Hardware Station is available only with Microsoft Dynamics AX 2012 R3.</P>



## Before you begin

  - Be aware that you do not have to install Hardware Station in a domain. You can install it as part of a work group on a single computer.

  - Create a service account. This service account is used for the identity of the application pool for Hardware Station. This account does not have to be a domain account. It can be a work group account. For more information, see [Create service accounts](create-service-accounts.md).

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - 
    
    Because this component uses Secure Sockets Layer (SSL) encryption, you must install a server certificate that was issued by a trusted certification authority. (For test environments, you can create a self-signed certificate in IIS.) When you run Setup, you will need to enter the thumbprint for the certificate. To view the thumbprint in IIS Manager, double-click the certificate and click the **Details** tab.

## Option 1: Install Hardware Station by using Setup

Use this procedure to install Hardware Station. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

5.  On the **Select components** page, select **Retail Hardware Station**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Configure Retail Hardware Station** page, enter the following information about the web site where Hardware Station will run.
    
      - **Configure Hardware Station**: On the **Configure Hardware Station** page, select the check box to configure Hardware Station by using Setup. If you clear this option, the application files are installed, but Hardware Station is not configured. If you’re configuring Hardware Station, enter the following information:
    
      - **Application name** – The name of an existing web application or the name of an application that you want Setup to create.
    
      - **Website name** – The name of an existing web site or the name of a site that you want Setup to create.
    
      - **App pool name** – The name of an existing web application pool in your server environment or the name of an application pool that you want Setup to create.
    
      - **User name** and **Password** – The credentials for the application pool identity. The user does not have to be a domain account. It can be a member of a work group on the local computer.
    
      - **HTTP port** and **HTTPS port** – You can specify any available ports. Verify that these ports are open in Windows firewall.
        

        > [!IMPORTANT]
        > <P>We strongly recommend that you use an HTTPS port for Hardware Station.</P>

        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **SSL certificate thumbprint** – The thumbprint for your Secure Sockets Layer (SSL) encryption certificate.
    
      - **Retail Server URL** – The URL specified when Retail Server was installed. By default, the URL is created by using the following parameters:
        
        https://\<Fully Qualified Server Name\>:Port/\<WebApplicationName\>/v1

8.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is completed, click **Finish** to close the wizard.

## Option 2: Install Hardware Station by using Windows PowerShell

Use this procedure to install Hardware Station manually by using Windows PowerShell. Manual installations are often performed by businesses and organizations that automate deployments by using scripts.

### ![Dn741431.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741431.collapse_all(en-us,AX.60).gif")Extract installation files

Use Microsoft Dynamics AX Setup to extract the files that are needed for manual installation.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

3.  On the **Select components** page, select **Retail Hardware Station**, and then click **Next**.

4.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

5.  On the **Configure Retail Hardware Station** page, clear the **Configure Retail Server** option.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Ready to install** page, click **Install**.

8.  After the installation is completed, click **Finish** to close the wizard.

### ![Dn741431.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741431.collapse_all(en-us,AX.60).gif")Configure settings in the hs-settings.xml file

After you extract the installation files by using Setup, you must configure settings in the hs-settings.xml file.

1.  Open the folder where the installation files are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\HardwareStation\\Tools.

2.  Create a copy of the hs-settings.xml file. We recommend that you do not change the original file.

3.  Open the hs-settings.xml file in Microsoft Visual Studio or a text editor, such as Notepad.

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
    <td><p><strong>WebAppPoolName</strong></p></td>
    <td><p>The name of an existing web application or the name of an application that you want Setup to create.</p></td>
    <td><p>HardwareStationAppPool</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteName</strong></p></td>
    <td><p>The name of an existing web site or the name of a site that you want Setup to create.</p></td>
    <td><p>HardwareStationWebsite</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteHttpPort</strong></p></td>
    <td><p>You can specify any available port. Verify that the port is open in Windows firewall. Also, note the port number. The port is used to create the URL for Retail Server in the format: https://&lt;server name&gt;:port/&lt;web application name&gt;. This URL is required to activate Retail Modern POS devices that connect to Retail Server.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteHttpsPort</strong></p></td>
    <td><p>You can specify any available port. Verify that the port is open in Windows firewall. Also, note the port number. The port is used to create the URL for Retail Server in the format: https://&lt;server name&gt;:port/&lt;web application name&gt;. This URL is required to activate Retail Modern POS devices that connect to Retail Server.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebApplicationName</strong></p></td>
    <td><p>The name of an existing web application or the name of an application that you want Setup to create.</p></td>
    <td><p>HardwareStation</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteSSLCertificateStore</strong></p></td>
    <td><p>The Certificates store specified when the certificate was created or imported.</p></td>
    <td><p>My</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteSSLCertificateRootStore</strong></p></td>
    <td><p>The server where the certificate is stored.</p></td>
    <td><p>LocalMachine</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteWorkingFolder</strong></p></td>
    <td><p>The folder where you want PowerShell to create a new IIS virtual directory.</p></td>
    <td><p>%SystemDrive%\inetpub\HardwareStation</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebAppPoolUser</strong></p></td>
    <td><p>Enter a domain account for the application pool. Enter the account in the form <strong>value=&quot;Domain\User&quot;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteSSLCertificateThumbprint</strong></p></td>
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
    <tr class="odd">
    <td><p><strong>WebApplicationServiceBinarySourceFolder</strong></p></td>
    <td><p>By default, this folder is:</p>
    <p>C:\Program Files (x86)\Microsoft Dynamics AX\60\HardwareStation\Package folder</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebApplicationWorkingFolder</strong></p></td>
    <td><p>The folder from where the web service will run. You can specify the WebApplicationServiceBinarySourceFolder or any available folder.</p></td>
    <td><p>[RetailServerWebSiteWorkingFolder]\[RetailServerWebApplicationName]</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>RetailServerURL</strong></p></td>
    <td><p>The URL specified when Retail Server was installed. By default, the URL uses the following format:</p>
    <p>https://&lt;ServerName&gt;:Port/&lt;WebApplicationName&gt;</p></td>
    <td><p>None</p></td>
    </tr>
    </tbody>
    </table>


5.  Save your changes .

### ![Dn741431.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741431.collapse_all(en-us,AX.60).gif")Run PowerShell scripts to deploy and configure Hardware Station

After you configure the parameters in the hs-settings.xml file, you can run the Windows PowerShell scripts that deploy and configure Hardware Station.

1.  On the server where you want to run the script, open the folder where the PowerShell scripts are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\HardwareStation\\Tools

2.  If you’re using Windows Server 2012 or a later operating system, use Windows Explorer to open the folder where the scripts are installed. Then click File \> Open Windows PowerShell \> Open Windows PowerShell as administrator.
    
    If you’re using Windows Server 2008 R2 or an earlier operating system, start Windows PowerShell as the administrator. Then, change the directory by using the following command: CD “\<Path to directory\>”.

3.  In the Windows PowerShell console, run the following command to create a credential object in Active Directory for the service account. Replace ‘domain\\useraccount’ and ‘password’ with credentials that have permission to create sites in IIS:
    
        $Cred = @((New-Object System.Management.Automation.PSCredential(‘domain\useraccount',(ConvertTo-SecureString 'password' -AsPlainText -Force))))

4.  Run the following command to deploy and configure Hardware Station:
    
        .\DeployHardwareStation.ps1 -SettingsXmlFilePath .\hs-settings.xml -TopologyXmlFilePath .\hs-topology.xml -Credentials $Cred –Verbose $true
    
    For example:
    
    .\\DeployHardwareStation.ps1 -SettingsXmlFilePath "C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\HardwareStation\\Tools\\hs-settings.xml" -TopologyXmlFilePath "C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\HardwareStation\\Tools\\hs-topology.xml" -Credentials $Cred –Verbose $true

## After you install Hardware Station

For information about how to install Modern POS, see [Install Retail Modern POS](install-retail-modern-pos.md). To install Retail Server, see [Install Retail Server](install-retail-server.md).

## See also

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  



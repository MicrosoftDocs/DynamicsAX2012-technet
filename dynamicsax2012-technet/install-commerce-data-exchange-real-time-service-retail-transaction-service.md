---
title: 'Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)'
TOCTitle: 'Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)'
ms:assetid: 8144c227-ebc2-4c24-8a61-62f52d61e95d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh575229(v=AX.60)
ms:contentKeyID: 39555376
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Install Commerce Data Exchange: Real-time Service (Retail Transaction Service) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to install Commerce Data Exchange: Real-time Service. Real-time Service is an integrated service that provides real-time communication between Microsoft Dynamics AX and retail channels. Real-time Service enables individual point of sale (POS) computers and online stores to retrieve specific data from Microsoft Dynamics AX in real time.


> [!NOTE]
> <P>Components of Microsoft Dynamics AX 2012 for Retail are available with Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 Feature Pack.</P>



At the head office, install Real-time Service on the communications server. Deployment steps vary, depending on the version that you are installing:

  - In AX 2012 R3 and AX 2012 R2, Real-time Service is a Windows Communication Foundation (WCF) service that must be installed on a website in Internet Information Services (IIS).

  - In AX 2012 Feature Pack, Real-time Service is a Windows service that is called Retail Transaction Service.

When you install this component, the Retail Salt Utility is also installed. The Retail Salt Utility provides extra encryption for the passwords and credentials that are associated with the Retail system.

The following sections are included in this topic:

  - Before you install Real-time Service

  - Install Real-time Service by using Setup (AX 2012 R3)

  - Install Real-time Service by using Windows PowerShell (AX 2012 R3)

  - Install Real-time Service (AX 2012 Feature Pack or AX 2012 R2)

  - Deploy Real-time Service (required for AX 2012 R2 only)

  - After you install and deploy Real-time Service

## Before you install Real-time Service

  - Create the service account that will be used as the application pool identity for the Real-time Service website. In AX 2012 Feature Pack, this account is used as the identity for the Windows service. For more information about the requirements for this account, see [Create service accounts](create-service-accounts.md).

  - 
    
    Because this component uses Secure Sockets Layer (SSL) encryption, you must install a server certificate that was issued by a trusted certification authority. (For test environments, you can create a self-signed certificate in IIS.) When you run Setup, you will need to enter the thumbprint for the certificate. To view the thumbprint in IIS Manager, double-click the certificate and click the **Details** tab.

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - Real-time Service requires .NET Business Connector. The .NET Business Connector enables Real-time Service to interact with instances of Microsoft Dynamics AX Application Object Server (AOS). If .NET Business Connector is not already installed, it is selected automatically when you select to install Real-time Service.

## Option 1: Install Real-time Service by using Setup (AX 2012 R3)

Use this procedure to install Real-time Service for AX 2012 R3. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

To deploy Real-time Service on multiple computers in a cluster, you can run Setup on each computer. Alternatively, you can use the Retail mass deployment toolkit to deploy Real-time Service from a central location. For information about how to set up an IIS cluster, see the [Network Load Balancing Deployment Guide](http://technet.microsoft.com/en-us/library/cc754833\(v=ws.10\).aspx). For more information about mass deployment, see [Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md).

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select an installation option** page, click **Microsoft Dynamics AX**, and then click **Next**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Real-time Service**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location in which to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Select a display language** page, select the language in which to run Microsoft Dynamics AX for the first time.
    

    > [!NOTE]
    > <P>.NET Business Connector is a kind of Microsoft Dynamics AX client. Therefore, if .NET Business Connector is the first client that you install on a computer, Setup requires that you set the display language.</P>



10. On the **Specify a location for configuration settings** page, specify whether you want .NET Business Connector to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file. Click **Next**.

11. On the **Connect to AOS instance** page, enter the name of the computer that runs the instance of AOS to connect to. You can optionally specify the name of the AOS instance and the TCP/IP port number. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



12. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by .NET Business Connector. Click **Next**.

13. On the **Configure Real-time Service** page, select the check box to configure Real-time Service by using Setup. If you clear this check box, the application files are installed, but Real-time Service is not configured.
    
    If you’re configuring Real-time Service, enter the following information:
    
      - **Application name** – The name of the web application that hosts Real-time Service.
    
      - **Website name** – The name of the website that hosts Real-time Service.
    
      - **App pool name** – The name of the application pool that Real-time Service runs in.
        
        We recommend that you specify separate application pools if multiple Retail components are installed on the same computer. Multiple web applications can share an application pool if resources on the computer are limited. However, if the shared application pool fails, all of the applications that use it will stop responding. In addition, if one application is heavily used, it can negatively affect the performance of the other applications in the pool.
    
      - **User name** and **Password** – The credentials for the application pool identity.
    
      - **HTTPS port** – The port on which Real-time Service receives secure HTTP requests. You can specify any available port. Verify that the port is open in Windows Firewall.
        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **TCP port** – The port on which Real-time Service receives TCP requests. You can specify any available port. Verify that the port is open in Windows Firewall.
    
      - **SSL certificate thumbprint** – The thumbprint for your Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.

14. On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

15. On the **Ready to install** page, click **Install**.

16. After the installation is completed, click **Finish** to close the wizard.

## Option 2: Install Real-time Service by using Windows PowerShell (AX 2012 R3)

Use this procedure to manually install Real-time Service for AX 2012 R3 by using Windows PowerShell. To install multiple instances of Real-time Service on the same computer, you must use a manual installation. Manual installations are often performed by businesses and organizations that automate deployments by using scripts.

### ![Hh575229.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh575229.collapse_all(en-us,AX.60).gif")Extract installation files

Use Microsoft Dynamics AX Setup to extract the files that are required for manual installation.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  On the **Modify Microsoft Dynamics AX installation** page, click **Add or modify components**, and then click **Next**.

3.  On the **Add or modify components** page, select **Real-time Service**, and then click **Next**.

4.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

5.  On the **Configure Real-time Service** page, clear the **Configure Real-time Service** option.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Ready to install** page, click **Install**.

8.  After the installation is completed, click **Finish** to close the wizard.

### ![Hh575229.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh575229.collapse_all(en-us,AX.60).gif")Configure settings in the rts-settings.xml file

After you extract the installation files by using Setup, you must configure settings in the rts-settings.xml file.

1.  Open the folder where the Windows PowerShell scripts are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Real-time Services\\Tools.

2.  Create a copy of the rts-settings.xml file for each instance of Real-time Service that you plan to deploy. We recommend that you not change the original file.

3.  Open your copy of the rts-settings.xml file in Microsoft Visual Studio or a text editor, such as Notepad.

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
    <td><p><strong>WebAppPoolName</strong></p></td>
    <td><p>The name of the application pool that hosts the Real-time Service web application.</p></td>
    <td><p>CDXRealtimeServiceAppPool</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteName</strong></p></td>
    <td><p>The name of the website that hosts Real-time Service.</p></td>
    <td><p>CDXRealtimeServiceWebsite</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteHttpsPort</strong></p></td>
    <td><p>The port on which Real-time Service receives secure HTTP requests. You can specify any available port. Verify that the port is open in Windows Firewall.</p>
    <p></p>
    <div class="alert">
    > [!Caution]  
	> To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443). A nonstandard port number also helps make the website more secure.

    </div></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteTcpPort</strong></p></td>
    <td><p>The port on which Real-time Service receives TCP requests. You can specify any available port. Verify that the port is open in Windows Firewall.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebApplicationName</strong></p></td>
    <td><p>The name of the web application that hosts Real-time Service.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebAppPoolUser</strong></p></td>
    <td><p>The user name for the account that is used as the application pool identity.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteSSLCertificateThumbprint</strong></p></td>
    <td><p>The thumbprint for your SSL encryption certificate. You must obtain a valid, registered certificate from a provider.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteSSLCertificateRootStore</strong></p></td>
    <td><p>The name of the root store where the SSL certificate that is used to help secure the website is installed.</p></td>
    <td><p>LocalMachine</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebSiteSSLCertificateStore</strong></p></td>
    <td><p>The name of the certificate store where the SSL certificate that is used to help secure the website is installed.</p></td>
    <td><p>My</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebApplicationServiceBinarySourceFolder</strong></p></td>
    <td><p>The location where the installer copied binary components. By default, the files are located at C:\Program Files (x86)\Microsoft Dynamics AX\60\CDX\Real-time Services\6.3.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>WebApplicationAOSServer</strong></p></td>
    <td><p>Not applicable</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebSiteWorkingFolder</strong></p></td>
    <td><p>The path of the physical folder where website files are stored.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>EnableMetadataExchange</strong></p></td>
    <td><p>A value that indicates whether the WCF service returns debugging information. In a production environment, this option should be set to <strong>false</strong>.</p></td>
    <td><p>false</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WebApplicationWorkingFolder</strong></p></td>
    <td><p>The path of the physical folder where web application files are stored.</p></td>
    <td><p>[WebSiteWorkingFolder]\[WebApplicationName]</p></td>
    </tr>
    </tbody>
    </table>


5.  Save your changes.

### ![Hh575229.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh575229.collapse_all(en-us,AX.60).gif")Run Windows PowerShell scripts to configure Real-time Service

After you configure the parameters in the rts-settings.xml file, you can run the Windows PowerShell scripts that configure Real-time Service.


> [!NOTE]
> <P>Windows PowerShell includes a security setting called the execution policy that determines how scripts are run. By default, the execution policy is set to <STRONG>Restricted</STRONG>, which prevents any scripts from running. To run the installation scripts for Microsoft Dynamics AX components, we recommend that you set the execution policy to <STRONG>RemoteSigned</STRONG> by using Set-ExecutionPolicy cmdlet. This setting allows you to run scripts that you’ve written and scripts that have been signed by a trusted publisher.</P>



1.  On the server where you want to run the script, open Windows PowerShell to the folder where the scripts are installed. By default, the files are located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Real-time Services\\Tools.
    
      - If you’re using Windows Server 2012 or a later operating system, use Windows Explorer to open the folder where the scripts are installed. Then click **File** \> **Open Windows PowerShell** \> **Open Windows PowerShell as administrator**.
    
      - If you’re using Windows Server 2008 R2 or an earlier operating system, start Windows PowerShell as the administrator. Then, change the directory by using the following command: CD "\<Path to directory\>".

2.  In the Windows PowerShell console, run the following command to create a credential object for the application pool identity.
    
    ``` powershell
    $Cred = @((New-Object System.Management.Automation.PSCredential('domain\user',(ConvertTo-SecureString 'password' -AsPlainText -Force))))
    ```

3.  Run the following command to configure Real-time Service.
    
    ``` powershell
    .\DeployRealtimeService.ps1 -SettingsXmlFilePath .\rts-settings.xml -TopologyXmlFilePath .\rts-topology.xml -Credentials $Cred –Verbose $true
    ```
    
    Example:
    
    .\\DeployRealtimeService.ps1 -SettingsXmlFilePath “C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Real-time Services\\Tools\\rts-settings.xml” -TopologyXmlFilePath “C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\CDX\\Real-time Services\\Tools\\rts-topology.xml” -Credentials $Cred -Verbose $true

## Install Real-time Service (AX 2012 Feature Pack or AX 2012 R2)

Use this procedure to install Real-time Service for AX 2012 Feature Pack or AX 2012 R2. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

5.  On the **Select components** page, select **Real-time Service**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location in which to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

8.  On the **Select a display language** page, select the language in which to run Microsoft Dynamics AX for the first time.
    

    > [!NOTE]
    > <P>.NET Business Connector is a kind of Microsoft Dynamics AX client. Therefore, if .NET Business Connector is the first client that you install on a computer, Setup requires that you set the display language.</P>



9.  On the **Specify a location for configuration settings** page, specify whether you want .NET Business Connector to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that runs the instance of AOS to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



11. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by .NET Business Connector. Click **Next**.

12. On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

13. On the **Ready to install** page, click **Install**.

14. After the installation is completed, click **Finish** to close the wizard.

## Deploy Real-time Service (required for AX 2012 R2 only)

After you install Real-time Service for Microsoft Dynamics AX 2012 R2, you must deploy and configure the web service.


> [!NOTE]
> <P>If you are not using AX 2012 R2, you can skip this procedure. In AX 2012 Feature Pack, Real-time Service is not a web service. In AX 2012 R3, Setup performs these steps for you.</P>



When you install Real-time Service for AX 2012 R2 by using the Setup wizard, the following resources are installed:

  - A folder that contains the binaries and configuration files for the WCF service

  - A folder that contains sample Windows PowerShell scripts

Use these resources to manually deploy and configure the WCF service that is used by Real-time Service.

### ![Hh575229.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh575229.collapse_all(en-us,AX.60).gif")Request and install a server certificate for the website

Because this component uses SSL encryption, you must install a server certificate that was issued by a trusted certification authority. (For test environments, you can create a self-signed certificate in IIS.) When you run the script to install Real-time Service, you have to enter the thumbprint for the certificate. To view the thumbprint in IIS Manager, double-click the certificate, and then click the **Details** tab. We recommend that you first copy the thumbprint, paste it into a text file, and remove all spaces. Then copy the reformatted thumbprint, and paste it into Windows PowerShell.


> [!WARNING]
> <P>The beginning of the thumbprint value can contain hidden characters. You must delete these extra characters before you paste the thumbprint.</P>



#### ![Hh575229.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh575229.collapse_all(en-us,AX.60).gif")Install a certificate by using Windows PowerShell

If you have already received a certificate from your provider, or if you are migrating a certificate from a different server, the file might be in .pfx format. In this case, you can use a sample Windows PowerShell script to install the certificate.

1.  Open a Windows PowerShell session that has Administrator permissions.

2.  At the Windows PowerShell command prompt, run the InstallServerCertificate.ps1 script. For example, enter the following command.
    
    ``` powershell
    & "C:\Program Files (x86)\Microsoft Dynamics AX\60\Commerce Data Exchange\Real-time Services\6.2\Sample Deployment Scripts\InstallServerCertificate.ps1"
    ```

3.  When you are prompted, enter the path of the .pfx file and the private key password.

### ![Hh575229.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh575229.collapse_all(en-us,AX.60).gif")Deploy the web service by using Windows PowerShell

A sample Windows PowerShell script is provided to help you deploy the WCF service for Real-time Service.

1.  Open a Windows PowerShell session that has Administrator permissions.

2.  At the Windows PowerShell command prompt, run the InstallCommerceDataExchangeRealtimeService.ps1 script. For example, enter the following command.
    
    ``` powershell
    & "C:\Program Files (x86)\Microsoft Dynamics AX\60\Commerce Data Exchange\Real-time Services\6.2\Sample Deployment Scripts\ InstallCommerceDataExchangeRealtimeService.ps1"
    ```

3.  When you are prompted, enter the following information:
    
      - **User account** – The user account to run the service as. Enter the user account in the following format: domain\\user. This user account must be a Microsoft Dynamics AX user who has the appropriate permissions.
    
      - **Password** – The password for the user account.
    
      - **Service binary source folder path** – The location of the .dll files for Real-time Service. By default, the path is “C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Commerce Data Exchange\\Real-time Services\\6.2\\.”. The .dll files are copied to the website that is created.
        

        > [!TIP]
        > <P>Do not include the bin subfolder in the path.</P>

    
      - **Server certificate thumbprint** – The thumbprint of the certificate that is installed on the IIS server. Enter only the characters that are included in the thumbprint value. Omit all spaces.
        
        To obtain the thumbprint, in IIS Manager, double-click **IIS**, and then click **Server Certificates**. Double-click the certificate, and then select **Details**.

### ![Hh575229.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh575229.collapse_all(en-us,AX.60).gif")Test and troubleshoot Real-time Service

For more information about how to configure, test, and troubleshoot the installation of Real-time Service, see the following posts on the AX Support Blog:

  - [AX for Retail 2012 R2: Installing the Real-time Service](http://blogs.msdn.com/b/axsupport/archive/2012/12/18/ax-for-retail-2012-r2-installing-the-real-time-service.aspx)

  - [AX for Retail 2012 R2: Troubleshooting the Real-time Service](http://blogs.msdn.com/b/axsupport/archive/2012/12/31/ax-for-retail-2012-r2-troubleshooting-the-real-time-service.aspx)

## After you install and deploy Real-time Service

Next, set up profiles for Real-time Service, and assign the profiles to channels. For more information, see [Set up a Real-time Service profile](set-up-a-real-time-service-profile.md).

  



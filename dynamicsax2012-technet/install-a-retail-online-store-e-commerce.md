---
title: Install a Retail online store (e-commerce)
TOCTitle: Install an online store (e-commerce)
ms:assetid: fc2c4afa-99e3-4333-9c46-e06b80f6aa37
ms:mtpsurl: https://technet.microsoft.com/library/JJ991927(v=AX.60)
ms:contentKeyID: 51595730
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install a Retail online store (e-commerce) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to install a Microsoft Dynamics AX Retail online store. The Retail online store is also called the Microsoft Dynamics AX e-commerce store. This topic includes procedures for single server and server farm deployments. You can install the online store by using Setup.exe or by using Windows PowerShell scripts. Both options are described in this topic. After you complete the installation procedures described in this topic, a *starter* store is deployed in your computing environment. You can then configure, customize, and rebrand the starter store to meet your needs.

This topic includes the following sections.

  - Before you begin

  - Install the Retail online store by using Setup

  - Deploy the Retail online store by using Windows PowerShell

  - Next steps for developers

  - Uninstall an online store

## Before you begin

You must complete the following tasks before you deploy the Microsoft Dynamics AX Retail online store.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify that your computing environment meets all system requirements</p></td>
<td><ul>
<li><p>Verify that the SharePoint server(s) that will host the Retail online store meet the following requirements: 16 GB of RAM recommended; 10 GB of RAM and 4 processors, minimum.</p></li>
<li><p>Verify that the SQL server is not running SQL Express. The retail online store is not supported with SQL Express.</p></li>
</ul>
<p>For more information about system requirements, see <a href="hardware-and-software-requirements.md">Hardware and software requirements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Install URL Rewrite</p></td>
<td><p>Verify that you installed the <a href="https://go.microsoft.com/fwlink/?linkid=277134&amp;clcid=0x409">URL Rewrite Module 2.0</a> (64-bit) on each SharePoint server.</p></td>
</tr>
<tr class="odd">
<td><p>Deploy and configure SharePoint</p></td>
<td><ul>
<li><p>Deploy and configure SharePoint Server 2013 Service Pack 1 or later (Enterprise edition). For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=286388">Overview of SharePoint 2013 installation and configuration</a></p></li>
<li><p>Download and install all cumulative updates for SharePoint Server 2013. To improve update installation times, use the PowerShell script described in this <a href="https://go.microsoft.com/fwlink/?linkid=393181">MSDN blog</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Verify that Microsoft Dynamics AX and all updates are installed in your computing environment</p></td>
<td><ul>
<li><p><a href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</a></p></li>
<li><p><a href="apply-updates-and-hotfixes.md">Apply updates and hotfixes</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Verify that Microsoft Dynamics AX Retail features are installed in your computing environment</p></td>
<td><p>You must install the following Retail features:</p>
<ul>
<li><p>Retail headquarters</p></li>
<li><p>Commerce Data Exchange components</p></li>
<li><p>Retail SDK</p></li>
<li><p>Retail channel database</p></li>
</ul>
<p>For more information, see <a href="install-retail-components.md">Install retail components</a></p></td>
</tr>
<tr class="even">
<td><p>Prepare the developer environment</p></td>
<td><p>Set up the development environment for a Retail online store</p></td>
</tr>
<tr class="odd">
<td><p>Verify that SharePoint application pools are running in IIS</p></td>
<td><p>Verify that all SharePoint application pools are running in IIS Manager.</p>
<div class="alert">
<div class="mtps-table">
<div class="mtps-row">
<img src="images/Gg732282.alert_caution(AX.60).gif" title="Important" alt="Important" class="note" /><strong>Important</strong>
</div>
<div class="mtps-row">
If the SharePoint Web Services Root application pool is stopped, you must start it.
</div>
</div>
</div></td>
</tr>
<tr class="even">
<td><p>Verify that required SharePoint services are running</p></td>
<td><p>In SharePoint Central Administration, click <strong>Application Management</strong> &gt; <strong>Service Applications</strong> &gt; <strong>Manage Services on Server</strong> and verify that, at a minimum, the following services are running:</p>
<ul>
<li><p>Central Administration</p></li>
<li><p>Managed Metadata Web Service</p></li>
<li><p>Microsoft SharePoint Foundation Workflow Timer Service</p></li>
<li><p>Microsoft SharePoint Foundation Web Application</p></li>
<li><p>Search Host Controller Service</p></li>
<li><p>Search Query and Site Settings Service</p></li>
<li><p>SharePoint Server Search</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Verify role requirements</p></td>
<td><ul>
<li><p>If you did not install and configure Microsoft Dynamics AX, verify that you are a member of the system administrator role in Microsoft Dynamics AX.</p></li>
<li><p>If you did not install and configure SharePoint, verify that you are a member of the farm administrator role in SharePoint and that you have administrator access to each site collection in the farm.</p></li>
<li><p>If you did not install and configure Microsoft SQL Server, Microsoft Dynamics AX, or SharePoint, verify that you are a member of the sysadmin role on the Microsoft Dynamics AX databases and all SharePoint databases.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Create domain user accounts</p></td>
<td><p>Verify or create the following domain accounts. You will specify these accounts when you deploy the Retail online store later in this topic.</p>
<ul>
<li><p><strong>Product Catalog Web App Pool User</strong>: This account must be a member of the SharePoint Farm Administrators group so that it can edit properties in the root web site. This account will be specified later in this topic.</p></li>
<li><p><strong>StoreFront Web App Pool User</strong>: This account must be a member of the SharePoint Farm Administrators group so that it can edit properties in the root web site. This account will be specified later in this topic.</p></li>
<li><p><strong>STS Web App Pool User</strong>: This account must be a member of the SharePoint Farm Administrators group so that it can edit properties in the root web site. This account was specified when you installed SharePoint. It is the account under which the Security Token Service application pool runs in IIS Manager.</p></li>
<li><p><strong>Retail Job User</strong>: This account was specified when you installed SharePoint. It is the account under which the SharePoint Timer Service runs.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Acquire Secure Sockets Layer (SSL) certificates</p></td>
<td><p><strong>Encryption settings:</strong> The Retail store publishing portal uses SSL encryption. For production environments, you must register your domain and obtain a valid, registered SSL certificate from a provider. For developer and evaluation environments, you can use a <a href="https://go.microsoft.com/fwlink/?linkid=235235">self-signed certificate</a>. For information about how to work with certificates see <a href="https://go.microsoft.com/fwlink/?linkid=282620">Certificate Overview</a>.</p></td>
</tr>
<tr class="even">
<td><p>Verify SQLCMD utility</p></td>
<td><p>The SQLCMD utility is required to install the Retail online store. This utility is typically installed with Microsoft SQL Server. If a version of SQL Server is not installed on the computer where you install the online store, you can download and install <a href="https://www.microsoft.com/en-us/download/details.aspx?id=36433">Microsoft Command Line Utilities 11 for SQL Server</a> to meet this requirement.</p></td>
</tr>
<tr class="odd">
<td><p>Verify warehouse requirement</p></td>
<td><p>You cannot configure a Microsoft Dynamics AX Retail store (online store or brick-and-mortar store) to use a warehouse that is managed by the Warehouse Management module. The module was introduced in AX 2012 R3. You can configure a Retail online store to use a warehouse that is managed by the Inventory Management module.</p></td>
</tr>
</tbody>
</table>


### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Verify SharePoint Managed Metadata connection properties

You must verify that the SharePoint Managed Metadata connection required options are enabled.

1.  In SharePoint Central Administration, under **Application Management**, click **Manage service applications**.

2.  Highlight the **Managed Metadata Service Connection** row and then click **Properties**.
    
    ![SharePoint Managed Metadata application](images/JJ991927.SPMetadata1(en-us,AX.60).gif "SharePoint Managed Metadata application")

3.  Verify that the following options are selected.
    
    ![SharePoint Managed Metadata properties](images/JJ991927.SPMetadata2(en-us,AX.60).gif "SharePoint Managed Metadata properties")

4.  Save your changes.

5.  If you are installing Microsoft Dynamics AX 2012 R3 Cumulative Update 8, you must also complete the following steps:
    
    1.  In Central Administration, under **Application Management**, click **Manage Service Applications**.
    
    2.  Click **Managed Metadata Service**.
    
    3.  In the Term Store Management tool, add the user name in the Term Store Administrators field. Ensure that the user name is the same as the service account for SharePoint Timer Service.
    
    4.  Click **Check Names**, and then click **Save**.

### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Prepare your developer environment for signing updated source code

After you install the online store as described in this topic, you will be ready to customize the store you deployed. The process of customizing the Retail online store requires that you recompile the source code in the Visual Studio projects. After you recompile, the fully-qualified name of the rebuilt assemblies will be different than the assemblies originally provide by Microsoft. Before you can recompile the assemblies, you must provide a code signing key file (also called a strong name key file) to sign the customized code. If your business has a code signing key file (.snk file), you can reuse this file. If you do not have a code signing key file, Visual Studio can create one for you. You must create a new project and enable code signing. Then, create a second project that references the .dll of the output of the first project. You can locate the thumbprint in the assembly reference of the .csproj file in the second project. When you have the .snk file, you must do the following:

1.  Save the file in the Retail SDK folder and give it a name *Name*.snk.

2.  Edit the UpdateAssemblyIdentities.ps1 file in the Retail SDK folder. You must update the version number and the thumbprint of the key file (lines 97, 98).

3.  Update the source code to use the strong name certificate by executing the UpdateAssemblyIdentities.ps1 script. This script can take several minutes to complete.

Additional steps and recommendations for developers are described in the Next steps for developers section in this topic.

## Option 1: Install the Retail online store by using Setup

You can install the Retail online store by using Microsoft Dynamics AX Setup or by using Windows PowerShell scripts. If you prefer to install the Retail online store manually, see “Install the Retail online store by using Windows PowerShell” in this topic.

If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

5.  On the **Select components** page, select **Retail online channel**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Configure a Microsoft Dynamics AX Retail online store** page, enter the following information about the web site where the online store will run.
    
      - On the **Configure the Retail online channel** page, select the check box to configure online store by using Setup. If you clear this option, the application files are installed, but the online store is not deployed or configured.
        
        If you’re configuring the online store, enter the following information:
    
      - **Storefront to deploy**: Select a Retail starter store to deploy. The Contoso starter store is modeled after an online electronics retailer. The Fabrikam starter store is modeled after an online clothing retailer.
    
      - **Database server**: The name of the server that will host the Retail online store databases
    
      - **Channel database name**: The name of the Retail channel database. If this database does not exist, you must cancel Setup and install a Retail channel database.
    
      - **User name** and **Password**: The credentials for a domain account that has permission to create web applications and execute PowerShell scripts in SharePoint.
    
      - **Pfx file path**: The path to the Pfx file for the SSL certificate.
    
      - **Password**: The password for the Pfx file.
    
      - **Channel operating unit number**: A channel operating unit number is specified when you create an online channel in the Microsoft Dynamics AX client. You must create the channel before you deploy the Retail online store. To locate this operating unit number, click **Retail** \> **Retail channels** \> **Online Stores**.

8.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is completed, click **Finish** to close the wizard.

If the deployment succeeded, proceed to the Verify deployment section in this document. If the deployment failed check the Microsoft Dynamics AX log file and the Windows event logs for information. For additional troubleshooting support, see the “Troubleshooting deployment issues” section in [Troubleshoot installation issues for a Retail online store](troubleshoot-installation-issues-for-a-retail-online-store.md).

## Option 2: Deploy the Retail online store by using Windows PowerShell

Use this procedure to install the Retail online store manually by using Windows PowerShell. Manual installations are often performed by businesses and organizations that automate deployments by using scripts.

### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Extract installation files

Use Microsoft Dynamics AX Setup to extract the files that are needed for manual installation. Perform this procedure on the SharePoint server that will host the online store.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

5.  On the **Select components** page, select **Retail online channel**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Configure a Microsoft Dynamics AX Retail online store** page, clear the **Configure Retail online store** option. Click **Next**.

8.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is completed, click **Finish** to close the wizard. Setup extracts files and creates the following folder on the local server:
    
    C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel

### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Configure settings in the Retail online store xml file

After you extract the installation files by using Setup, you must configure settings in the oob-settings.xml file.

#### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Before you begin

If you deployed SharePoint on Windows Server 2012, then you must complete the following procedure to ensure that the Microsoft.Web.Administration.dll is not overwritten in the global assembly cache when you execute deployment scripts later in this topic. You do not need to perform this procedure on Windows Server 2008 R2.

1.  Open the manifest.xml file in the following directory on the SharePoint server:
    
    C:\\...\\Retail Online Channel\\StoreFront\\SP

2.  Delete the following line of code from the manifest.xml file:
    
    \<Assembly Location="Microsoft.Web.Administration.dll" DeploymentTarget="GlobalAssemblyCache" /\>

3.  Save and close the file.

The Microsoft.Web.Administration.dll in the global assembly cache will not be overwritten when you execute PowerShell commands later in this topic.

#### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Configure settings in the oob-settings.xml file

This section describes how to configure settings in the oob-settings.xml file.

1.  Open the following directory:
    
    C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools

2.  Open the oob-settings.xml file in Microsoft Visual Studio or a text editor, such as Notepad.

3.  Enter a value for the following parameters.
    
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
    <th><p>Default</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>StoreFront_Name</strong></p></td>
    <td><p>Enter the name of the online store to deploy. You must enter either Contoso or Fabrikam.</p></td>
    <td><p>Contoso</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFront_Design</strong></p></td>
    <td><p>Microsoft Dynamics AX uses this value to determine which customizations to apply to the publishing portal. Change this value if, for example, a developer creates a new design template.</p></td>
    <td><p>Default</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFront_CountryCode</strong></p></td>
    <td><p>Enter an ISO country code. This code displays the country string, for example, when a customer places an order. Customers of your site do not see this code. This value is not published.</p></td>
    <td><p>USA</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFront_CountryName</strong></p></td>
    <td><p>Enter the name of the country. Customers of your site do not see this code. This value is not published.</p></td>
    <td><p>United States</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFront_CurrencyTemplate</strong></p></td>
    <td><p>Enter a currency template. This template determines how currency amounts are displayed in the online store.</p></td>
    <td><p>${0}</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>SharepointPackageInstanceIdentifier</strong></p></td>
    <td><p>Enter any alphanumeric value to uniquely identify this deployment. This value must be unique across all Retail online store deployments in the server farm.</p></td>
    <td><p>None, but we recommend a value of 1.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFront_ItemAvailabilityThreshold</strong></p></td>
    <td><p>Enter a threshold value for the number of items in stock for any product. If the number of items in stock for a specific product is below this value, the system could display a banner to the customer that lets them know how many items are left in stock. A developer would need to customize the store to create a banner.</p></td>
    <td><p>10</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFront_ShoppingCartExpiryTerm</strong></p></td>
    <td><p>Enter the number of days to retain a shopping cart. If no value is entered, the store deletes the shopping cart after 24 hours.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFront_LanguageId</strong></p></td>
    <td><p>Enter a language code identifier (LCID). This ID must match the language pack for your SharePoint deployment. For more information about deploying the online store in multiple languages, see <a href="install-multiple-microsoft-dynamics-ax-retail-online-stores.md">Install multiple Microsoft Dynamics AX Retail online stores</a>.</p></td>
    <td><p>1033</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFront_DeviceChannelsListName</strong></p></td>
    <td><p>This value is the name of a SharePoint Design Manager list that stores device channels. For more information about device channel lists, see <a href="https://go.microsoft.com/fwlink/?linkid=394743">SharePoint 2013 Design Manager device channels</a>. The name of this value varies based on locale. For example, if you are deploying the online store by using the en-US locale then the name should be Device Channels. If you are deploying for an online store for fr-FR (French) locale then this name should be Canaux des appareils.</p>
    <div class="alert">
    <div class="mtps-table">
    <div class="mtps-row">
    <img src="images/Dn527205.alert_note(AX.60).gif" title="Note" alt="Note" class="note" /><strong>Note</strong>
    </div>
    <div class="mtps-row">
    The value of this property and the value of the previous property (StoreFront_DeviceChannelsListName) work together. For example, an en-US online store uses the 1033, Device Channels values and an fr-FR online store uses the 1036, Canaux des appareils values.
    </div>
    </div>
    </div></td>
    <td><p>Device Channels</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>LoggingServiceName</strong></p></td>
    <td><p>The name of the logging service for this deployment as it appears in SharePoint Central Administration. You can change the default string value (Dynamics AX Retail Logging Service) if you want. However, we recommend that you do not change the place holder value ([SharepointPackageInstanceIdentifier]) unless you are a developer and understand the repercussions of making a change.</p></td>
    <td><p>Dynamics AX Retail Logging Service [SharepointPackageInstanceIdentifier]</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>LoggingCategoryName</strong></p></td>
    <td><p>The SharePoint diagnostics logging category where events for this deployment will be logged. We recommend that you do not change the place holder value ([SharepointPackageInstanceIdentifier]) unless you are a developer and understand the repercussions of making a change.</p></td>
    <td><p>General Logging [SharepointPackageInstanceIdentifier]</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>MonitoringEventLogSourceName</strong></p></td>
    <td><p>For events logged in the Windows NT Event Viewer, this parameter identifies the source of the event. You can change the string value (Dynamics AX Retail Monitoring) if you want. However, we recommend that you do not change the place holder value ([SharepointPackageInstanceIdentifier]) unless you are a developer and understand the repercussions of making a change.</p></td>
    <td><p>Dynamics AX Retail Monitoring [SharepointPackageInstanceIdentifier]</p></td>
    </tr>
    <tr class="even">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p>PORTS and URLS</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontUrlPort_Public</strong></p></td>
    <td><p><strong>The port for the public online store site</strong>: You can specify any available port.</p></td>
    <td><p>40002</p>
    <p>50002 for the Fabrikam starter store</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFrontUrlPort_SSL_Public</strong></p></td>
    <td><p><strong>The port for the public online store site for encrypted communications</strong>: You can specify any available port.</p></td>
    <td><p>40004</p>
    <p>50004 for the Fabrikam starter store</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontUrlPort_Internal</strong></p></td>
    <td><p><strong>The port for the internal online store site</strong>: You can specify any available port. This URL is only accessed by domain users with permission to make changes to the site collection by using SharePoint site settings. It is not required, but you can change this port value if you want the internal online store to use a different port.</p></td>
    <td><p>40003</p>
    <p>50003 for the Fabrikam starter store</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ProductCatalogUrlPort_Internal</strong></p></td>
    <td><p><strong>The port for the internal product catalog site</strong>: You can specify any available port. This URL is only accessed by domain users with permission to make changes to the site collection by using SharePoint site settings. It is not required, but you can change this port value if you want the internal product catalog to use a different port.</p></td>
    <td><p>40001</p>
    <p>50001 for the Fabrikam starter store</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ResetSearchIndex</strong></p></td>
    <td><p>Setting this parameter to true clears the SharePoint index cache and initiates a full crawl across the farm.</p></td>
    <td><p>False</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFrontSiteCollectionRootUrl_FormsAuth</strong></p></td>
    <td><p>The local web address of the Retail online store (as opposed to a public address like www.contoso.com.) Enter a valid server name and remove the % signs. We recommend that you do not change the place holder value ([StoreFrontUrlPort_Public]) unless you are a developer and understand the repercussions of making a change.</p></td>
    <td><p>http://%COMPUTERNAME%:[StoreFrontUrlPort_Public]</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontSiteCollectionRootUrl_WindowsAuth</strong></p></td>
    <td><p>The local web address of the 40003 site. Enter a valid server name and remove the % signs. We recommend that you do not change the place holder value ([StoreFrontUrlPort_Internal]) unless you are a developer and understand the repercussions of making a change.</p></td>
    <td><p>http://%COMPUTERNAME%:[StoreFrontUrlPort_Internal]</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFrontSiteCollectionRootUrl_FormsAuth_Public</strong></p></td>
    <td><p>This is the customer facing URL. For example with a port 80 site, it could be http://www.contoso.com. With a port 3000 site it could be http://www.contoso.com:3000.</p></td>
    <td><p>http://www.[StoreFront_Name].com:[StoreFrontUrlPort_Public]</p></td>
    </tr>
    <tr class="odd">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p>SSL</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFrontSiteCollectionRootUrl_SSL_FormsAuth</strong></p></td>
    <td><p><strong>The internal URL for the online store encrypted communications site</strong>: Enter a valid server name and remove the % signs. We recommend that you do not change the place holder value ([StoreFrontUrlPort_SSL_Public]) unless you are a developer and understand the repercussions of making a change.</p></td>
    <td><p>https://%COMPUTERNAME%:[StoreFrontUrlPort_SSL_Public]</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontSiteCollectionRootUrl_SSL_FormsAuth_Public</strong></p></td>
    <td><p><strong>The public URL for the online store encrypted communications site</strong>: The https site customers use for secure transactions and processing.</p></td>
    <td><p>https://www.[StoreFront_Name].com:[StoreFrontUrlPort_SSL_Public]</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>PublishingPortalRelativePath</strong></p></td>
    <td><p>This relative path is combined with URLs specified earlier to create a complete path for the publishing portal. We recommend that you do not leave this blank and use a format similar to “/sites/XYZ”. Leaving this field blank would require customizations to the oob-topology.xml file, and should be attempted by advanced users only.</p></td>
    <td><p>/sites/RetailPublishingPortal</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontPublicSSLCertThumbprint</strong></p></td>
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
    <td><p><strong>StoreFrontPublicSSLCertDirectory</strong></p></td>
    <td><p>The source directory where Microsoft Dynamics AX retrieves the .pfx file for the SSL certificate. This value can be a network share.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontPublicSSLCertLocalDirectory</strong></p></td>
    <td><p>The destination folder where Microsoft Dynamics AX stores a local copy of the certificate. This location <strong>cannot</strong> be the same as the <strong>StoreFrontPublicSSLCertDirectory</strong> value.</p>
    <div class="alert">
    <div class="mtps-table">
    <div class="mtps-row">
    <img src="images/Gg732282.alert_caution(AX.60).gif" title="Important" alt="Important" class="note" /><strong>Important</strong>
    </div>
    <div class="mtps-row">
    This path cannot contain any special characters. If the path contains a special character deployment fails.
    </div>
    </div>
    </div></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>StoreFrontPublicSSLCertPfxFileName</strong></p></td>
    <td><p>Enter the file name and extension. By default the extension is .pfx.</p>
    <p>To create a .pfx file for a self-signed certificate, you must export the certificate from IIS Manager. To do this, right-click the certificate, click <strong>Export</strong>, and then complete the export wizard. You must then import the .pfx file into the local certificate store. Right-click the .pfx file in the directory where you just created it, click <strong>Import</strong>, and then complete the import wizard.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontPublicSSLCertPfxPassword</strong></p></td>
    <td><p>Enter the password of the .pfx file. This password cannot contain any restricted XML characters such as the following: exclamation point (!), greater than sign (&lt;), less than sign (&gt;), ampersand (&amp;), apostrophe (‘), or a quotation mark (“).</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p>DOMAIN ACCOUNTS and MISCELLANEOUS</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>StoreFrontWebAppPoolUser</strong></p></td>
    <td><p>Enter a domain account for the application pool of the online store. Enter the account in the form <strong>value=&quot;Domain\User&quot;</strong>. This account must be a member of the SharePoint Farm Administrators group because it must edit properties in the root web site.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ProductCatalogSiteCollectionRootUrl_WindowsAuth</strong></p></td>
    <td><p>The local web address of the product catalog. Enter a valid server name and remove the % signs. We recommend that you do not change the place holder value ([ProductCatalogUrlPort_Internal]) unless you are a developer and understand the repercussions of making a change.</p></td>
    <td><p>http://%COMPUTERNAME%:[ProductCatalogUrlPort_Internal]</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ProductCatalogWebAppPoolUser</strong></p></td>
    <td><p>Enter a domain account for the application pool of the catalog site. Enter the account in the form <strong>value=&quot;Domain\User&quot;</strong>. This account must be a member of the SharePoint Farm Administrators group because it must edit properties in the root web site.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ProductCatalogName</strong></p></td>
    <td><p>Enter any name for the product catalog. This value is not displayed to customers.</p></td>
    <td><p>Retail Product Catalog</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>STSWebAppPoolUser</strong></p></td>
    <td><p>This account must be a member of the SharePoint Farm Administrators group. Also, this is the domain account used by the Security Token Service Application Pool. You specified this account when you installed SharePoint. To locate the account in IIS Manager, click <strong>Application Pools</strong>, right-click <strong>SecurityTokenServiceApplicationPool</strong>, and then click <strong>Advanced Settings</strong>. The account for this application pool is listed under <strong>Process Model</strong> &gt; <strong>Identity</strong>. Enter the account in the form <strong>value=&quot;Domain\User&quot;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>RetailJobUser</strong></p></td>
    <td><p>This account must be a member of the SharePoint Farm Administrators group. Also, this is the account used by the SharePoint Timer service. You specified this account when you installed SharePoint. Enter the account in the form <strong>value=&quot;Domain\User&quot;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ChannelOperatingUnitNumber</strong></p></td>
    <td><p>A channel operating unit number is specified when you create an online channel in the Microsoft Dynamics AX client. You must create the channel before you deploy the Retail online store. To locate this operating unit number, click <strong>Retail</strong> &gt; <strong>Retail channels</strong> &gt; <strong>Online Stores</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>DestinationId</strong></p></td>
    <td><p>A value that uniquely identifies an endpoint to Commerce Runtime (CRT). This value must be a GUID. If necessary, create a GUID by using Visual Studio.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>PublishingConnectorServiceInstanceServers</strong></p></td>
    <td><p>A comma-separated list of servers where the Retail online store publishing job must run. The PowerShell script is case sensitive. For example, <strong>value=&quot;RetailTestOne, RetailTestTwo&quot; /&gt;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>FarmAdministratorAlias</strong></p></td>
    <td><p>Enter a domain account and alias of a SharePoint farm administrator. Enter the account in the form <strong>value=&quot;Domain\User&quot;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>FarmAdministratorEmail</strong></p></td>
    <td><p>Enter the e-mail address of a SharePoint farm administrator. Enter the address in the form <strong>value=&quot;Username@</strong> <em>YourDomain</em> <strong>.com&quot;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>SharePointRelyPartyUrl</strong></p></td>
    <td><p></p></td>
    <td><p>https://www.[StoreFront_Name].com:[StoreFrontUrlPort_SSL_Public]/_trust/</p></td>
    </tr>
    <tr class="odd">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p>DATABASE DETAILS</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p>--------------------</p></td>
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ChannelDatabaseServerName</strong></p></td>
    <td><p>If you have not already done so, use Microsoft Dynamics AX Setup.exe to deploy a Retail channel database. For this parameter, enter the server name. The PowerShell script is case sensitive. For example, <strong>value=&quot;RetailTestOne&quot; /&gt;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ChannelDatabaseServerNamedInstanceName</strong></p></td>
    <td><p>If you installed the retail channel database as part of a SQL named instance, enter the named instance. This parameter cannot be empty. The format for a SQL instance name is either the server name or the full instance name. For example, valid names are: &quot;localhost&quot;, &quot;localhost\instance2&quot;, &quot;server1&quot;, &quot;server1\instance2&quot;.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ChannelDatabaseName</strong></p></td>
    <td><p>If you have not already done so, use Microsoft Dynamics AX Setup.exe to deploy a Retail channel database. For this parameter, enter the database name.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>IdentityProviderDatabaseServerName</strong></p></td>
    <td><p>The identity provider database is used for authentication and authorization of online store registered users. If there are multiple Retail online store deployments in the same farm, then the IdentityProviderDatabase and CustomClaimsProviderDatabase must be the same for all Retail online store deployments in the farm. Enter a server name. The PowerShell script is case sensitive. For example, <strong>value=&quot;RetailTestOne&quot; /&gt;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>IdentityProviderDatabaseServerNamedInstanceName</strong></p></td>
    <td><p>If you installed the identity provider database as part of a SQL named instance, enter the named instance. This parameter cannot be empty. The format for a SQL instance name is either the server name or the full instance name. For example, valid names are: &quot;localhost&quot;, &quot;localhost\instance2&quot;, &quot;server1&quot;, &quot;server1\instance2&quot;.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>CustomClaimsProviderDatabaseServerName</strong></p></td>
    <td><p>The custom claims provider database is used for authentication and authorization of online store registered users. If there are multiple Retail online store deployments in the same farm, then the IdentityProviderDatabase and CustomClaimsProviderDatabase must be the same for all Retail online store deployments in the farm. Enter a server name. The PowerShell script is case sensitive. For example, <strong>value=&quot;RetailTestOne&quot; /&gt;</strong>.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>CustomClaimsProviderDatabaseServerNamedInstanceName</strong></p></td>
    <td><p>If you installed the custom claims provider database as part of a SQL named instance, enter the named instance. You can leave this parameter empty if the database is not part of a named instance.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>BingMapsId</strong></p></td>
    <td><p>If you want your Retail online store to work with Bing Maps, then you must register with Bing Maps. Specify the Bing Maps ID here.</p></td>
    <td><p>None</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ShowDebugErrorMessages</strong></p></td>
    <td><p>For a testing environment, set this value to True to see detailed error messages in the online store. For production sites set the value to False.</p></td>
    <td><p>None</p></td>
    </tr>
    </tbody>
    </table>



> [!IMPORTANT]
> <P>To keep a record of the settings and parameters you specified, we recommend that you make a copy of the oob-settings.xml file after you finished entering parameters.</P>



#### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Configure Facebook integration

The Retail online store can authenticate users who sign in to your site by using their Facebook credentials. This section describes how to configure your environment for Facebook authentication.


> [!IMPORTANT]
> <P>Facebook integration is optional. However, if you do not want to use Facebook authentication, then you must disable this feature in the oob-topology.xml file. If you do not disable it, the deployment scripts fail. For more information, see <STRONG>Disable Facebook</STRONG> integration later in this topic.</P>



**Create a Facebook application:** Use the following procedure to create a Facebook application that enables Facebook logon to your site.

1.  Logon to the [Facebook developer site](https://developers.facebook.com/apps)

2.  Register as a developer on the Facebook developer site.

3.  Click **Create New App** and then follow the prompts to create a new application.

4.  In the **Select how your application integrates with Facebook** section, click the **Website with Facebook Login** option and specify the Site URL.

5.  Click **Save Changes**.

6.  On the applications landing page, select the application that you just created.

7.  In the oob-settings.xml file, search for **FacebookApplicationId**. Replace the value with the Facebook ID. Retain the quotation marks.

8.  In the oob-settings.xml file, search for **FacebookApplicationSecret**. Replace the value with the secret you created for your Facebook application. Retain the quotation marks.

9.  Save your changes in the oob-settings.xml file.

**Certificates:** Use the following procedure to create certificates for Facebook authentication. For production environments, you must register your domain and obtain a valid, registered SSL certificate from a provider. For developer and evaluation environments, you can use a [self-signed certificate](https://go.microsoft.com/fwlink/?linkid=235235). For information about how to work with certificates see [Certificate Overview](https://go.microsoft.com/fwlink/?linkid=282620).

1.  Search in the oob-settings.xml file for the parameters listed in the following table. Enter a value for each parameter. For each value, retain quotation marks (“”) but remove percent signs (%).
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Parameter</p></th>
    <th><p>What to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>FacebookApplicationId</strong></p></td>
    <td><p>The ID created when you registered a Facebook application.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>FacebookApplicationSecret</strong></p></td>
    <td><p>The secret specified when you registered a Facebook application.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>FacebookCertificateDirectory</strong></p></td>
    <td><p>The source directory where Microsoft Dynamics AX retrieves the .pfx file for the SSL certificate. This value can be a network share.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>FacebookCertificateLocalCopyDirectory</strong></p></td>
    <td><p>The destination folder where Microsoft Dynamics AX stores a local copy of the certificate. This location cannot be the same as the StoreFrontPublicSSLCertDirectory value.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>FacebookSigningCertificateCerFileName</strong></p></td>
    <td><p>Enter a value with the name of the certificate .cer file in the form <strong>value=&quot;</strong> <em>CertificateName</em> <strong>.cer&quot;</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>FacebookSigningCertificatePfxFileName</strong></p></td>
    <td><p>Enter a value with the name of the certificate .pfx file in the form <strong>value=&quot;</strong> <em>CertificateName</em> <strong>.pfx&quot;</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>FacebookSigningCertificatePfxPassword</strong></p></td>
    <td><p>This is a password for a test certificate. For production environments, do not enter a password here. It will be prompted during deployment. This password cannot contain any restricted XML characters such as the following: exclamation point (!), greater than sign (&lt;), less than sign (&gt;), ampersand (&amp;), apostrophe (‘), or a quotation mark (“).</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>FacebookSigningCertificateThumbprint</strong></p></td>
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
    </tr>
    <tr class="odd">
    <td><p><strong>FacebookSignInUrl</strong></p></td>
    <td><p>The page that will contact Facebook to authenticate users. For example: http://www.[StoreFront_Name].com:[StoreFrontUrlPort_Public][PublishingPortalRelativePath]/pages/Login.aspx</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>FacebookSslCertificateAuthorityCerFileName</strong></p></td>
    <td><p>Enter the file name.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>FacebookSslCertificateAuthorityThumbprint</strong></p></td>
    <td><p>Enter the thumbprint. Remove all spaces.</p></td>
    </tr>
    </tbody>
    </table>


2.  Save your changes in the oob-settings.xml file.


> [!NOTE]
> <P>You can enable Facebook integration in developer environments that are not using a fully registered domain name (for example, www.<EM>DomainName</EM>.com). To do this, you must create host file entries on each computer that will browse the online store. The URL for host file entries must be in the form: http://www.<EM>DomainName</EM>.com/sites/RetailPublishingPortal.</P>



**Update the prerequisite script for Facebook**

A known issue in this version of the Microsoft Dynamics AX Retail online store can cause an installation to fail if you configure Facebook as an identity provider. If you plan to use Facebook as an identity provider, perform the following procedure before you install the online store. If you do not plan to use Facebook as an identity provider, you can skip this procedure.

1.  Open the following folder:
    
    C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Online Channel\\tools

2.  Open the Install-Prerequistes.ps1 file in Microsoft Visual Studio.

3.  Search for line 155:
    
    RoboCopy $trustedIdentityTokenIssuerConfig.CertificateDirectory $certificateLocalCopyDirectory $trustedIdentityTokenIssuerConfig.SigningCertificateCerFileName $trustedIdentityTokenIssuerConfig.SigningCertificatePfxFileName

4.  Replace that line with the following:
    
    RoboCopy $trustedIdentityTokenIssuerConfig.CertificateDirectory $certificateLocalCopyDirectory $trustedIdentityTokenIssuerConfig.SigningCertificateCerFileName $trustedIdentityTokenIssuerConfig.SigningCertificatePfxFileName $trustedIdentityTokenIssuerConfig.SslCertificateAuthorityCerFileName

5.  Save your changes.

**Disable Facebook integration**

If you do not want to enable Facebook authentication for your Retail online store you must disable it, as described in the following procedure. If you previously enabled and configured Facebook authentication you can also use this procedure to disable it.

1.  Open the oob-topology.xml file in Microsoft Visual Studio or a text editor, such as Notepad.

2.  Search in the oob-topology.xml file for the parameter listed in the following table. Enter a value for each parameter. For each value, retain quotation marks (“”) but remove percent signs (%).
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Search for</p></th>
    <th><p>Enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>&lt;TrustedIdentityTokenIssuer id=&quot;Facebook&quot; install=&quot;true&quot; deleteifexists=&quot;true&quot;&gt;</strong></p></td>
    <td><p>Change both flags to “false”. For example:</p>
    <p><strong>&lt;TrustedIdentityTokenIssuer id=&quot;Facebook&quot; install=&quot;false&quot; deleteifexists=&quot;false&quot;&gt;</strong></p></td>
    </tr>
    </tbody>
    </table>


3.  Save your changes in the oob-topology.xml file.

### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Run Windows PowerShell scripts to create and configure the online store

After you configure the parameters in the oob-settings.xml file, you can run the Windows PowerShell scripts that deploy and configure the online store.

In this section, you will execute the following scripts to create and configure the online store.

  - InstallPrereqs-SPFarm

  - Generate-WSP

  - Deploy-FarmSolutions

**Toggling options if re-running scripts**

If you re-run the PowerShell deployment scripts in this section, by default, existing databases, web applications, features, and settings are deleted. You can, however, toggle different parameters in the oob-topology.xml file to preserve databases, web applications, features, and settings. Preserving an object means that you change a “true” flag to “false”. For example, in the oob-topology file, in the \<Channel\> section, the Database is configured as follows.

\<Database install="true" dropifexists="true"\>

By changing each flag to “false” the deployment scripts preserve the existing databases.

#### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")InstallPrereqs-SPFarm.ps1

This script performs the following actions on the server.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Area</p></th>
<th><p>Actions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Database actions performed by this script</strong></p>
<p>If you re-run the PowerShell deployment scripts in this section, by default, existing Retail online store databases, web applications, features, and settings are deleted. You can, however, toggle different parameters in the oob-topology.xml file to preserve databases, web applications, features, and settings, as described earlier in this topic.</p></td>
<td><ul>
<li><p>Create Windows NT user groups</p></li>
<li><p>Add process users to Windows NT user groups</p></li>
<li><p>Create SQL Server logins for Windows NT user groups</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>SharePoint Server actions performed by this script</strong></p></td>
<td><ul>
<li><p>Creates trusted identity token issuer for Facebook integration (on every web front-end server, when executed in a server farm)</p></li>
<li><p>Creates SharePoint web applications</p></li>
<li><p>Creates SSL binding (on every web front-end server, when executed in a server farm)</p></li>
<li><p>Creates SharePoint sites</p></li>
<li><p>Configures sites and web application properties</p></li>
<li><p>Disables versioning of the Retail Online Store Publishing Portal web application</p></li>
<li><p>Configures site URLS (for different zones)</p></li>
<li><p>Enables trusted authentication providers for Facebook (if option was configured)</p></li>
</ul>
<p>If you re-run this script, the system performs the following actions before creating or configuring SharePoint. You can, however, toggle options to preserve settings, as described earlier in this document.</p>
<ul>
<li><p>Deactivates Retail online store features</p></li>
<li><p>Removes WSP solution files, if installed</p></li>
<li><p>Deletes Retail online store sites</p></li>
<li><p>Removes SSL bindings (on every web front-end server, when executed in a server farm)</p></li>
<li><p>Deletes Retail online store web applications</p></li>
<li><p>Deletes trusted identity token issuer (on every web front-end server, when executed in a server farm)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Other actions performed by the script</strong></p>
<p>The script performs the following pre-deployment checks, by default. You can customize which checks are performed.</p></td>
<td><ul>
<li><p>Verifies that the folders and files referenced in the oob-topology.xml and oob-settings.xml files exist</p></li>
<li><p>Verifies that the configured database server can be pinged.</p></li>
<li><p>Verifies that the SharePoint server names configured for the publishing job are correct and that they are joined to the current SharePoint farm.</p></li>
<li><p>Verifies that the SharePoint installation is of the correct version. SharePoint 2013 is required.</p></li>
<li><p>Verifies that every SharePoint server that acts as an application server has the URL Rewrite module installed.</p></li>
<li><p>Verifies that any ports are not already used by web applications with different names.</p></li>
</ul></td>
</tr>
</tbody>
</table>


If any of these checks fail, the script will not perform the installation.

**Run InstallPrereqs-SPFarm.ps1:** Use the following procedures to run this script.


> [!WARNING]
> <P>SQL Server work-around for cumulative update 1</P>
> <P>Cumulative update 1 has a known issue where the InstallPrereqs-SPFarm.ps1 script fails if SQL Server is not installed on the server where you are running this script. If SQL Server is not installed on the server and if you do not intend to install any databases, complete the following steps before you run the InstallPrereqs-SPFarm.ps1 script.</P>
> <OL>
> <LI>
> <P>Open the following folder:</P>
> <P>C:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Online Channel\tools</P>
> <LI>
> <P>Open the Custom-Scripts.ps1 file in Microsoft Visual Studio or a text editor, such as Notepad.</P>
> <LI>
> <P>Search for and delete the following line of code:</P>
> <P>(if((Test-Connection $value -Count 1 -Quiet) -ne $True))</P>
> <LI>
> <P>Save your changes.</P></LI></OL>



**Run the script**


> [!NOTE]
> <P>Windows PowerShell includes a security setting called the execution policy that determines how scripts are run. By default, the execution policy is set to <STRONG>Restricted</STRONG>, which prevents any scripts from running. To run the installation scripts for Microsoft Dynamics AX components, we recommend that you set the execution policy to <STRONG>RemoteSigned</STRONG> by using Set-ExecutionPolicy cmdlet. This setting allows you to run scripts that you’ve written and scripts that have been signed by a trusted publisher.</P>



1.  On the server where you want to run the script, open the tools folder where the PowerShell scripts are installed.

2.  If you’re using Windows Server 2012 or a later operating system, use Windows Explorer to open the folder where the scripts are installed. Then click File \> Open Windows PowerShell \> Open Windows PowerShell as administrator.
    
    If you’re using Windows Server 2008 R2 or an earlier operating system, start pw\_wps as the administrator. Then, change the directory by using the following command: CD “\<Path to directory\>”.

3.  Run the following command to verify and install prerequisites for the online store:
    
        .\InstallPrereqs-SPFarm.ps1 oob-topology.xml oob-settings.xml

When the system finishes the operation, you can run the next script.

#### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Generate-WSP.ps1

This script creates a SharePoint solution package (.WSP file) for your computing environment. The solution package includes properties such as connection strings, URLS, and ports from the oob-topology.xml and oob-settings.xml files. The solution package also includes binaries and static web files that were deployed by Microsoft Dynamics AX Setup to the Retail Online Channel directory.

**Run Generate-WSP.ps1:**

In the Windows PowerShell console, run the following command to generate the WSP file for the online store:

    .\Generate-WSP.ps1 oob-topology.xml oob-settings.xml


> [!IMPORTANT]
> <P>Due to a known issue, the following script can fail with a file access error. If the script fails, re-run it. It should finish successfully the second time.</P>



When the system finishes the operation, you can execute the next script.

#### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Deploy-FarmSolutions.ps1

This script performs the following actions on the server.

  - Deploys the new SharePoint solution package

  - Activates features

  - Runs post-deployment custom scripts (deploy mode)

If you re-run this script, the system performs the following actions before deploying the solution package or activating features. You can toggle options to preserve settings, as described earlier in this document.

1.  Deactivates features

2.  Uninstalls solution packages

3.  Runs post-deployment custom scripts (retract mode)

**Run Deploy-FarmSolutions.ps1:**

In the Windows PowerShell console, run the following command to deploy the solution to SharePoint.

    .\Deploy-FarmSolutions.ps1 oob-topology.xml oob-settings.xml

When the system finishes the operation, you can verify the deployment.

### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Verify deployment

If all deployment scripts completed without errors, use this section to help verify the online store deployment. If the deployment scripts returned errors, see [Troubleshoot installation issues for a Retail online store](troubleshoot-installation-issues-for-a-retail-online-store.md).

**Verify that the Connector Service is running**: After a successful deployment, the **Retail Publishing Connector Service 1** is running in SharePoint Central Administration. At this point, the service displays an error “No channel configuration could be found in the database,” which means that the channel has not been configured in Microsoft Dynamics AX yet. For information about configuring a channel, see the section titled *Set up the online store in Microsoft Dynamics AX* in the [Online Store](online-store.md)

Use the following procedure to verify that the **Dynamics AX Publishing Connector** service is running.

1.  In SharePoint Central Administration under **System Settings**, click **Manage services on server**.

2.  Verify that the **Retail Publishing Connector Service 1** is running.

3.  In SharePoint Central Administration, click **Monitoring**, and then click **Check job status**.

4.  Verify that you see jobs listed for the **C1 Application for Retail Store Front – Internal** and the **Out of box Store front – Public**.

**Verify that site collections exist and can be browsed**: After a successful deployment, you can view the Retail online store web applications and site collections in SharePoint Central Administration. If you specified different URLs for your web applications, you must adjust the URLS below accordingly.


> [!NOTE]
> <P>If you installed the Fabrikam starter store, change port values below from the 40,000 range to the 50,000 range. For example: The Contoso starter store product catalog site is http://ServerName:40001/sites/RetailProductCatalog. The Fabrikam starter store product catalog site is http://ServerName:50001/sites/RetailProductCatalog.</P>



1.  In SharePoint Central Administration, click **Application Management**, and then click **View all site collections**.

2.  On the **C1 Application for Retail Store Front – Internal** web application, copy the http://*ServerName*:40001/sites/RetailProductCatalog URL and paste it into a browser. Verify that the **Welcome to your product catalog site displays**.

3.  In SharePoint Central Administration, click the **Web application** drop-down list and then click **Change web application**.

4.  Click the **Out of box Store front – Public** web application.

5.  In the **URL** section, verify that you see the following URLs:
    
    http://*ServerName*:40002/sites/RetailPublishingPortal
    
    http://*ServerName*:40002

6.  Copy and paste each URL into a browser. Verify that you see the **Contoso electronic superstore** site and the **Contoso electronic superstore sign-in** site. If the sign-in site displays a certificate warning, click **Continue to this web site**. This warning appears if you used a self-signed certificate.

**Verify that you can create and sign-in with a new forms-based user account**: You should be able to register a new user account and logon from the public URL. By completing the sign-up process you verify SQL Server connectivity, SSL port settings, and SSL certificate bindings.

1.  Paste the public URL into a browser and press Enter. For example: http://*ServerName*:40002/sites/RetailPublishingPortal

2.  Click **Register a new account**.

3.  Enter an email address and a strong password in the required fields and then click **Create account**. Note that if you see more than one email and password field on the page, it means that you executed the Deploy-FarmSolutions.ps1 script multiple times on this server. This is a known issue. To create the forms-based user account, you must enter the email address and strong password in each field. Also note that you receive an error after you register the account because the online channel has not been configured in Microsoft Dynamics AX.

4.  Browse the public portal site again (http:// *ServerName*:40002/sites/RetailPublishingPortal).

5.  Click the **Sign In** link and enter the information for the account that you just created. The system logs you onto the Contoso electronics site as a registered user.

**Verify that you can browse the public URL**: If you registered a domain, you should be able to browse the web address for your site. For example, you should be able to browse http://www.\<your\_domain\>.com/sites/RetailPublishingPortal. If you have not yet registered the domain then you must create a hosts file entry and disable proxy settings in your browser (if applicable) before you attempt to browse the web address.

## Next steps for developers

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step</p></th>
<th><p>Detail</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Review the quick guide for customizing the online store.</p></td>
<td><p>See <a href="quick-guide-how-to-customize-a-microsoft-dynamics-ax-for-retail-online-store.md">Quick Guide: How to customize a Microsoft Dynamics AX for Retail online store</a>.</p></td>
</tr>
<tr class="even">
<td><p>Set up the online channel</p></td>
<td><p>After you deploy the Microsoft Dynamics AX Retail online store, you must setup the online channel in Microsoft Dynamics AX. See the <strong>Online store setup checklist</strong>. The checklist is available in the Microsoft Dynamics AX client: <strong>Retail</strong> &gt; <strong>Setup</strong> &gt; <strong>Online store setup checklist</strong>.</p>
<div class="alert">
<div class="mtps-table">
<div class="mtps-row">
<img src="images/Dn527205.alert_note(AX.60).gif" title="Note" alt="Note" class="note" /><strong>Note</strong>
</div>
<div class="mtps-row">
If the online channel has already been set up in Microsoft Dynamics AX then you only need to publish the channel and publish a catalog. For information, see <em>Publish an online store</em> in <a href="set-up-an-online-store.md">Set up an online store</a> and <em>Publish a catalog</em> in <a href="key-tasks-create-retail-product-catalogs.md">Key tasks: Create retail product catalogs</a>.
</div>
</div>
</div></td>
</tr>
<tr class="odd">
<td><p>Customize and rebrand the starter store</p></td>
<td><p>See the Extend section of the <a href="online-store.md">Online Store</a>.</p></td>
</tr>
<tr class="even">
<td><p>Deploy a second online store</p></td>
<td><p><a href="install-multiple-microsoft-dynamics-ax-retail-online-stores.md">Install multiple Microsoft Dynamics AX Retail online stores</a></p></td>
</tr>
<tr class="odd">
<td><p>Deploy to production</p></td>
<td><p>See <em>Deploy your solution to a production environment</em> in <a href="quick-guide-how-to-customize-a-microsoft-dynamics-ax-for-retail-online-store.md">Quick Guide: How to customize a Microsoft Dynamics AX for Retail online store</a>.</p></td>
</tr>
</tbody>
</table>


## Uninstall an online store

The method that you use to uninstall an online store varies depending on the method you used to install the store.


> [!WARNING]
> <P>Before you uninstall, we strongly recommend that you back up your SharePoint farm. If you don't follow the instructions completely, your content database may be corrupted.</P>



### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Uninstall if you used Setup to install

If you installed an online store by using Setup, then you can either run Setup again to remove it, or use Control Panel \> Add or Remove Programs.

### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Uninstall if you installed with Windows PowerShell

If you used settings and topology files to configure the online store, then run the undeploy script from the Microsoft Dynamics Windows PowerShell prompt. The following example removes the default instance deployed by Setup.

    C:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Online Channel\Tools\UnDeployRetailOnlineChannel.ps1 -TopologyXmlFilePath oob-topology-updated.xml -SettingsXmlFilePath oob-settings-updated.xml

To remove a non-default instance, change the name of the XML file in the parameters to the appropriate file.

    C:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Online Channel\Tools\UnDeployRetailOnlineChannel.ps1  -TopologyXmlFilePath oob-topology-updatedFabrikam.xml   -SettingsXmlFilePath oob-settings-updatedFabrikam.xml


> [!NOTE]
> <P>If you have multiple online channels, you must run the script with the appropriate settings and topology file for each online channel.</P>



### ![JJ991927.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ991927.collapse_all(en-us,AX.60).gif")Uninstall if you installed with Windows PowerShell, and no longer have the original settings and topologies file

Use the following procedure if you installed with a settings file, but no longer have the file.

1.  In **SharePoint Central Administration**, under **System Settings**, click **Manage Farm Features**.

2.  Clear **Claims Provider**, **Logging Service**, and **Publishing Job**. If these features are not present, skip this step.
    

    > [!NOTE]
    > <P>Site level features will be automatically uninstalled when you uninstall the parent solutions.</P>



3.  In **Central Administration**, under **System Settings**, click **Manage Farm Solutions**. For each of the following solutions, choose to retract immediately, and then click **OK**.
    
      - Publisher Job
    
      - StoreFront
    
      - Common Global Modules
        

        > [!NOTE]
        > <P>This package is shared across all instances of storefront.</P>

    

    > [!NOTE]
    > <P>While you complete these steps, an IIS reset will occur, and Central Administration might become unavailable. If so, wait and try again.</P>



4.  After all the solutions have been retracted, remove the solution for each entry.
    
    1.  In **Central Administration**, under **Manage Web Applications**, delete all of the web applications by clicking **Delete**, and then clicking **Delete Web Application**.
    
    2.  Click **Yes** when you are prompted to delete content databases and to delete IIS websites. This step can take some time to complete.

## See also

[Online Store](online-store.md)

  



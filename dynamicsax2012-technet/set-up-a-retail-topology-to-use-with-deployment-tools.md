---
title: Set up a Retail topology to use with deployment tools
TOCTitle: Set up a Retail topology to use with deployment tools
ms:assetid: 5820dee2-ddaf-4a32-a891-94587706d3e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn858394(v=AX.60)
ms:contentKeyID: 63417188
ms.date: 11/09/2016
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCDXClientProfile
- Forms.RetailCDXHeadOfficeProfile
- Forms.RetailDeploymentBusinessConnectorProfile
- Forms.RetailDeploymentHierarchyForm
- Forms.RetailChannelDatabaseProfiles
- Forms.RetailDeploymentPOSRegisterProfiles
- Forms.RetailServerServiceProfile
- Forms.RetailDeploymentRTSProfiles
- Forms.RetailModernPOSProfile
- Forms.RetailMachineClusters
- MsDynAx060.Forms.RetailChannelDatabaseProfiles
- MsDynAx060.Forms.RetailCDXHeadOfficeProfile
- MsDynAx060.Forms.RetailCDXClientProfile
- Forms.RetailMachineTableListPage
- MsDynAx060.Forms.RetailServerServiceProfile
- MsDynAx060.Forms.RetailDeploymentHierarchyForm
- MsDynAx060.Forms.RetailDeploymentPOSRegisterProfiles
- MsDynAx060.Forms.RetailMachineClusters
- MsDynAx060.Forms.RetailDeploymentBusinessConnectorProfile
- MsDynAx060.Forms.RetailModernPOSProfile
- MsDynAx060.Forms.RetailDeploymentRTSProfiles
- MsDynAx060.Forms.RetailMachineTableListPage
---

# Set up a Retail topology to use with deployment tools [AX 2012]


Before you can use deployment tools to mass deploy retail components, you must enter information about the topology of the retail environment in Microsoft Dynamics AX. You’ll also specify settings for each component that will be deployed.

> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R3.</P>

This topic contains the following sections:

  - Step 1: Import or enter computer information in Microsoft Dynamics AX

  - Step 2: Set up a deployment plan in Microsoft Dynamics AX

  - Step 3: Export the retail deployment plan from Microsoft Dynamics AX

## Step 1: Import or enter computer information in Microsoft Dynamics AX

First, specify the computers to include in the deployment. You can use two methods to create the list of computers in Microsoft Dynamics AX. We recommend that you bulk import computer entities from Microsoft System Center Configuration Manager. If Configuration Manager isn’t available, you can manually enter information about individual computers in Microsoft Dynamics AX.

> [!NOTE]
> <P>Computer entities that you define in Microsoft Dynamics AX must already be discovered in Configuration Manager before you import the topology to Configuration Manager.</P>

## Bulk import computer entities from Configuration Manager (recommended)

If your environment includes System Center Configuration Manager, you can use the following procedure to import computer information into Microsoft Dynamics AX. Office Add-ins for Microsoft Dynamics AX, the Retail mass deployment toolkit, and the Configuration Manager console must be installed to complete this procedure.

For information about how to install the toolkit, see [Install the Retail mass deployment toolkit](install-the-retail-mass-deployment-toolkit.md). For information about how to install Office Add-ins, see [Install Office Add-ins](install-office-add-ins.md).

1.  Open a Command Prompt window, and change the directory to the folder where RetailConfigMgrToolkit.exe is located. By default, the file is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\ConfigManagerToolKit.

2.  Run the following command to export discovered computers to a CSV file:
    
    **RetailConfigMgrToolkit.exe -o ExportMachines -f \<file name.csv\>**
    
    All computers discovered by Configuration Manager are exported to the CSV file.

3.  Open the Microsoft Dynamics AX client.

4.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Target computers** \> **Computers**.

5.  On the ribbon, click **Export to Microsoft Excel**. A new Microsoft Excel document opens, in which the column names correspond to the fields in the form.

6.  In Excel, open the CSV file that you created earlier.

7.  Copy the records from the CSV file, and paste them into the Excel file.

8.  In Excel, on the ribbon, on the **Dynamics AX** tab, click **Publish** to publish the new records to Microsoft Dynamics AX. Computer records are created in the **Computers** form.

## Define security credentials

To set up and secure communication among the various Retail components, you must provide credentials and obtain certificates. During deployment, you need a way to provide this information without allowing too many people access to it. You can do this by saving credentials and certificate information in a clear-text xml file that is stored on a secure file share at headquarters. This type of file is called a security file. By allowing only deployment tools and a limited number of users access to security files, you help make your credentials and certificates more secure.


> [!NOTE]
> <P>The deployment tools for Retail components support security files starting in Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



A security file is required when you use mass deployment tools to deploy the following components.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Requires a certificate</p></th>
<th><p>Requires credentials</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Channel database</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Real-time Service</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Async Client</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Async Server</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Retail POS</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Retail Server</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Retail Hardware Station</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


For information about how to create and connect to a security file, see: [Create a security file for Retail deployment](create-a-security-file-for-retail-deployment.md).

## Optional. Manually enter log and computer information in Microsoft Dynamics AX

Use the following procedure to enter individual computer records in Microsoft Dynamics AX.

1.      

> [!NOTE]
> <P>This step is only available on AX 2012 R3 CU8.</P>

Under **Retail Mass-deployment** \> **Security** \> **Retail deployment log shares**, enter a location to store log files.

2.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Target computers** \> **Computers**.

3.  Click **Retail computer** to add a new record.

4.  Enter a unique name to identify the computer record in Microsoft Dynamics AX.

5.  Enter identifying information about the computer, such as the computer name, and the domain or workgroup that the computer belongs to.
    
    If you are creating a topology for AX 2012 R3 CU8 and have defined a log share, you can also select it for each **Retail computer**.

## Set up retail computer clusters

Create one or more clusters of retail computers. Each cluster can contain one or more computers. You use a cluster to deploy a component to a group of servers for load balancing.

Clusters are used only to deploy components to web servers.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Target computers** \> **Retail computer clusters**.

2.  Enter a name and description for the cluster.

3.  Add retail computers to the cluster.

## Step 2: Set up a deployment plan in Microsoft Dynamics AX

After you have identified the computers to include in the deployment, you must specify the deployment settings for each Retail component that you want to deploy.


> [!TIP]
> <p>Avoid the use of spaces in configuration parameters when completing forms.</p>

## Create a deployment profile for a channel database

Define a deployment profile for each channel database that you plan to deploy.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Channel database deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Channel database</strong></p></td>
    <td><p>Select a channel database profile to use with this deployment profile.</p>
    <p>A channel database profile defines the retail channels that use a particular channel database. For more information about channel database profiles, see <a href="set-up-a-channel-database-profile.md">Set up a channel database profile</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Computer name</strong></p></td>
    <td><p>Select the computer where the channel database will be created.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Database server instance</strong></p></td>
    <td><p>Enter the name of the Microsoft SQL Server instance that will host the channel database.</p>
    <p>If you are using the default instance of SQL Server, you can leave this field blank.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Database name</strong></p></td>
    <td><p>Enter the name of the channel database.</p></td>
    </tr>
    </tbody>
    </table>


## Create a deployment profile for Real-time Service

Define a deployment profile for each computer cluster where you plan to deploy Real-time Service.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Real-time Service deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Web application name</strong></p></td>
    <td><p>Enter the name of the web application that hosts Real-time Service.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Website name</strong></p></td>
    <td><p>Enter the name of the website that hosts Real-time Service.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retail computer cluster</strong></p></td>
    <td><p>Select the cluster of retail computers where Real-time Service will be deployed. A cluster contains one or more retail computers.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Application pool name</strong></p></td>
    <td><p>Enter the name of the application pool for the Real-time Service web application.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>HTTPS port</strong></p></td>
    <td><p>Enter the port that the website uses for Secure Sockets Layer (SSL) communication.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Business Connector deployment profile</strong></p></td>
    <td><p>Select the Business Connector deployment profile to use with this deployment profile.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Website install folder</strong></p></td>
    <td><p>Enter the path of the physical folder where website files are stored.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>TCP port</strong></p></td>
    <td><p>Enter the port that the website uses for TCP/IP communication.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Service Credential ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the credential ID and security file location to use when Real-time Service is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Certificate ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the certificate ID and security file location to use when Real-time Service is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p>
    <p>If you’re using a version of AX 2012 R3 that is earlier than AX 2012 R3 CU8, enter certificate information in the <strong>Certificate root store</strong>, <strong>Certificate store</strong>, and <strong>Certificate thumbprint</strong> fields instead.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Certificate root store</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the name of the root store where the SSL certificate that is used to help secure the website is installed. By default, the root store is set to <strong>LocalMachine</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Certificate store</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the name of the certificate store where the SSL certificate that is used to help secure the website is installed. By default, the certificate store is set to <strong>My</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Certificate thumbprint</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the thumbprint for the SSL certificate that is used to help secure the website.</p>
    
    > [!NOTE]
    > <P>The certificate must be installed on the target computer before you attempt to deploy this component.</P>

    </td>
    </tr>
    </tbody>
    </table>


## Create a deployment profile for Async Client

Define one or more deployment profiles for Async Client.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Async Client deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Async Server deployment</strong></p></td>
    <td><p>Select the Async Server deployment profile to use with this deployment profile.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Channel database deployment</strong></p></td>
    <td><p>Select the channel database deployment profile to use with this deployment profile.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Channel database credential ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the credential ID and security file location for the channel database credentials.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sync interval (in minutes)</strong></p></td>
    <td><p>Enter the interval at which Async Client will look for updates from Async Server.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Working folder</strong></p></td>
    <td><p>Enter the path of the working folder where data packages are stored and picked up by Async Client.</p>
   
    > [!NOTE]
    > <P>We recommend that you use a folder on the computer where Async Client is being installed, instead of a remote shared location.</P>

    </td>
    </tr>
    <tr class="even">
    <td><p><strong>Service Credential ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the credential ID and security file location to use when Async Client is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Computer name</strong></p></td>
    <td><p>Enter the name of the server that will host the message database for Async Client.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Database server instance</strong></p></td>
    <td><p>Enter the name of the SQL Server instance that will host the message database for Async Client.</p>
    <p>If you are using the default instance of SQL Server, you can leave this field blank.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Database name</strong></p></td>
    <td><p>Enter the name of the database where Async Client messages are stored.</p></td>
    </tr>
    </tbody>
    </table>


## Create a deployment profile for Async Server

Define a deployment profile for each computer cluster where you plan to deploy Async Server.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Async Server deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Web application name</strong></p></td>
    <td><p>Enter the name of the web application that hosts Async Server.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Website name</strong></p></td>
    <td><p>Enter the name of the website that hosts Async Server.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Application pool name</strong></p></td>
    <td><p>Enter the name of the application pool for the Async Server web application.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>HTTPS port</strong></p></td>
    <td><p>Enter the port that the website uses for SSL communication.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>TCP port</strong></p></td>
    <td><p>Enter the port that the website uses for TCP/IP communication.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>File storage provider</strong></p></td>
    <td><p>Select a set of working folders where data packages will be stored. For more information, see <a href="specify-working-folders-for-commerce-data-exchange.md">Specify working folders for Commerce Data Exchange</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retail computer cluster</strong></p></td>
    <td><p>Select the cluster of retail computers where Async Server will be deployed. A cluster contains one or more retail computers.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Website install folder</strong></p></td>
    <td><p>Enter the path of the physical folder where website files are stored.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Service Credential ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the credential ID and security file location to use when Async Server is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base URL</strong></p></td>
    <td><p>Enter the URL that Async Client uses to contact Async Server.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Computer name</strong></p></td>
    <td><p>Enter the name of the server that will host the message database.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Database server instance</strong></p></td>
    <td><p>Enter the name of the SQL Server instance that will host the message database.</p>
    <p>If you are using the default instance of SQL Server, you can leave this field blank.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Database name</strong></p></td>
    <td><p>Enter the name of the database where Async Server messages are stored.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Certificate ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the certificate ID and security file location to use when Async Server is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p>
    <p>If you’re using a version of AX 2012 R3 that is earlier than to AX 2012 R3 CU8, enter certificate information in the <strong>Certificate root store</strong>, <strong>Certificate store</strong>, and <strong>Certificate thumbprint</strong> fields instead.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Certificate root store</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the name of the root store where the SSL certificate that is used to help secure the website is installed. By default, the root store is set to <strong>LocalMachine</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Certificate store</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the name of the certificate store where the SSL certificate that is used to help secure the website is installed. By default, the certificate store is set to <strong>My</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Certificate thumbprint</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the thumbprint for the certificate that is used to help secure the website.</p>
    
    > [!NOTE]
    > <P>The certificate must be installed on the target computer before you attempt to deploy this component.</P>

    </td>
    </tr>
    <tr class="even">
    <td><p><strong>Database server</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Optionally, enter the name of the database server that is used to connect to the message database. By default, the computer name that was used to deploy the database is used.</p></td>
    </tr>
    </tbody>
    </table>


## Create a deployment profile for Retail POS

Define a deployment profile for each device where you plan to deploy Retail POS.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Retail POS deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Computer name</strong></p></td>
    <td><p>Select the computer where Retail POS will be deployed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Register number</strong></p></td>
    <td><p>Select a register number for the selected computer.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Channel database deployment</strong></p></td>
    <td><p>Select the channel database deployment profile to use with this deployment profile.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Real-time Service deployment</strong></p></td>
    <td><p>Select the Real-time Service deployment profile to use with this deployment profile.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Database server instance</strong></p></td>
    <td><p>Enter the name of the SQL Server instance that will host the offline database.</p>
    <p>If you are using the default instance of SQL Server, you can leave this field blank.</p>
    
    > [!NOTE]
    > <P>The Builtin\Administrators group must belong to the sysadmin server role on the SQL Server instance where the offline database is deployed.</P>

    </td>
    </tr>
    <tr class="even">
    <td><p><strong>Database name</strong></p></td>
    <td><p>Enter the name of the offline database.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Credential ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the credential ID and security file location to use when Retail POS is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Database server</strong></p></td>
    <td><p>Optionally, enter the name of the database server that is used to connect to the offline database. By default, the computer name that was used to deploy the database is used.</p></td>
    </tr>
    </tbody>
    </table>


## Create a deployment profile for Retail Modern POS

Define a deployment profile for each device where you plan to deploy Retail Modern POS.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Modern POS deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Register number</strong></p></td>
    <td><p>Select a register number.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Computer name</strong></p></td>
    <td><p>Select the computer or device where Retail Modern POS will be deployed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retail Server deployment</strong></p></td>
    <td><p>Select a Retail Server deployment profile to use with this deployment profile. The Retail Modern POS client will connect to the Retail Server that is specified in the profile.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Side loading key</strong></p></td>
    <td><p>Enter a sideloading key.</p>
    <p>Apps that aren't signed by Windows Store can be installed only on devices that are enabled for sideloading. To enable sideloading on a computer, you must use a sideloading product activation key. For more information about how to sideload apps, see <a href="http://technet.microsoft.com/en-us/windows/jj874388.aspx">Try It Out: Sideload Windows Store Apps</a>.</p></td>
    </tr>
    </tbody>
    </table>


## Create a deployment profile for Retail Server

Define a deployment profile for each computer cluster where you plan to deploy Retail Server.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Retail Server deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Web application name</strong></p></td>
    <td><p>Enter the name of the web application that hosts Retail Server.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Website name</strong></p></td>
    <td><p>Enter the name of the website that hosts Retail Server.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retail computer cluster</strong></p></td>
    <td><p>Select the cluster of retail computers where Retail Server will be deployed. A cluster contains one or more retail computers.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Application pool name</strong></p></td>
    <td><p>Enter the name of the application pool for the Retail Server web application.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>HTTP port</strong></p></td>
    <td><p>Enter the port that the website uses for HTTP communication.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>HTTPS port</strong></p></td>
    <td><p>Enter the port that the website uses for SSL communication.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Real-time Service deployment</strong></p></td>
    <td><p>Select the Real-time Service deployment profile to use with this deployment profile.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Channel database deployment</strong></p></td>
    <td><p>Select the channel database deployment profile to use with this deployment profile.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Website install folder</strong></p></td>
    <td><p>Enter the path of the physical folder where website files are stored.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Service Credential ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the credential ID and security file location to use when Retail Server is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Base URL</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Enter the URL that Retail Modern POS clients use to contact Retail Server.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Certificate ID</strong></p>
    <p>This field is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the certificate ID and security file location to use when Retail Server is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p>
    <p>If you’re using a version of AX 2012 R3 that is earlier than AX 2012 R3 CU8, enter certificate information in the <strong>Certificate root store</strong>, <strong>Certificate store</strong>, and <strong>Certificate thumbprint</strong> fields instead.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Certificate root store</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the name of the root store where the SSL certificate that is used to help secure the website is installed. By default, the root store is set to <strong>LocalMachine</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Certificate store</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the name of the certificate store where the SSL certificate that is used to help secure the website is installed. By default, the certificate store is set to <strong>My</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Certificate thumbprint</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Enter the thumbprint for the SSL certificate that is used to help secure the website.</p>
    
    > [!NOTE]
    > <P>The certificate must be installed on the target computer before you attempt to deploy this component.</P>

    </td>
    </tr>
    <tr class="even">
    <td><p><strong>Database server</strong></p>
    <p>This control is available only in versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</p></td>
    <td><p>Optionally, enter the name of the database server that is used to connect to the channel database. By default, the computer name that was used to deploy the database is used.</p></td>
    </tr>
    </tbody>
    </table>

## Create a deployment profile for .NET Business Connector

Define a deployment profile for each instance of .NET Business Connector in the environment.

1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Business Connector deployment profile**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>AOS Server</strong></p></td>
    <td><p>Enter the name of the server where the instance of Microsoft Dynamics AX Application Object Server (AOS) is installed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AOS instance</strong></p></td>
    <td><p>Enter the name of the AOS instance.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>TCP port</strong></p></td>
    <td><p>Enter the TCP port for the AOS instance.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>WSDL port</strong></p></td>
    <td><p>Enter the WSDL port for the AOS instance.</p></td>
    </tr>
    </tbody>
    </table>


## Create a deployment profile for Retail Hardware Station

Define a deployment profile for each computer where you plan to deploy Retail Hardware Station.


> [!NOTE]
> <P>This deployment profile type is available only with Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



1.  Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Deployable components** \> **Retail Hardware Station deployment**.

2.  Enter a name and description for the profile.

3.  Enter or select the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Web application name</strong></p></td>
    <td><p>Enter the name of the web application that hosts Retail Hardware Station.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Website name</strong></p></td>
    <td><p>Enter the name of the website that hosts Retail Hardware Station.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Computer name</strong></p></td>
    <td><p>Select the computer where Hardware Station will be installed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Application pool name</strong></p></td>
    <td><p>Enter the name of the application pool for the web application where Hardware Station runs.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>HTTP port</strong></p></td>
    <td><p>Enter the port that the website uses for HTTP communication.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>HTTPS port</strong></p></td>
    <td><p>Enter the port that the website uses for SSL communication.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retail Server deployment</strong></p></td>
    <td><p>Select a Retail Server deployment profile to use with this deployment profile. Retail Hardware Station will connect to the Retail Server that is specified in the profile.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Website install folder</strong></p></td>
    <td><p>Enter the path of the physical folder where website files are stored.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Service Credential ID</strong></p>
    <p>This control is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the credential ID and security file location to use when Hardware Station is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Certificate ID</strong></p>
    <p>This control is available only if AX 2012 R3 CU8 is installed.</p></td>
    <td><p>Select the certificate ID and security file location to use when Hardware Station is deployed.</p>
    <p>For more information about security files, see <a href="create-a-security-file-for-retail-deployment.md">Create a security file for Retail deployment</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retail Channel</strong></p></td>
    <td><p>Select the retail channel that will use this instance of Hardware Station.</p></td>
    </tr>
    </tbody>
    </table>


## Step 3: Export the retail deployment plan from Microsoft Dynamics AX

After computers and deployment information have been defined in Microsoft Dynamics AX, you can export the deployment plan by using the Retail mass deployment toolkit.


> [!NOTE]
> <P>To run the ExportRetailTopology command, the toolkit must be able to connect to Microsoft Dynamics AX via .NET Business Connector, regardless of whether the Application Object Server (AOS) is locally or remotely installed.</P>



1.  Open a Command Prompt window, and change the directory to the folder where RetailConfigMgrToolkit.exe is located. By default, the file is located at \<Drive\>:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\ConfigManagerToolKit.

2.  Run the following command to export the topology that you defined to an XML file:
    
    **RetailConfigMgrToolkit.exe -o ExportRetailTopology -f \<file name.xml\>**

3.  Import the topology XML file into the deployment tool that you’re using. For more information, see [Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md) or [Set up a self-service Retail deployment](set-up-a-self-service-retail-deployment.md).

## Use the Retail deployment visualizer to work with a graphical view of the topology

Click **Retail** \> **Setup** \> **Retail mass-deployment** \> **Retail deployment visualizer**.

The retail deployment visualizer shows the deployment profiles that have been set up for each retail component.

The retail topology is arranged in a hierarchy, with the organization at the top, and a branch for each type of retail component. To list the deployment profiles that have been set up for each component, click a component node and then click the **Search** button in the right pane. To add a new deployment profile, select the related component node and then click **Insert** \> **(Component)**. The deployment profile form for that component opens.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


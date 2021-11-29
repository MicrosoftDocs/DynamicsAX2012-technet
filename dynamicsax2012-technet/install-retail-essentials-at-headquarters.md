---
title: Install Retail essentials at headquarters
TOCTitle: Install Retail essentials at headquarters
ms:assetid: c2aa753b-f03b-4cee-b588-3c24eee3824c
ms:mtpsurl: https://technet.microsoft.com/library/Dn741221(v=AX.60)
ms:contentKeyID: 62219111
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
---

# Install Retail essentials at headquarters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to install Retail essentials at headquarters.

Retail essentials is a retail-centric configuration option for Microsoft Dynamics AX. Retail essentials provides a simplified, streamlined user experience that is optimized for organizations that use only the retail management functions of Microsoft Dynamics AX.


> [!IMPORTANT]
> <P>To install Retail essentials, you must slipstream Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



Install and configure Retail essentials at headquarters before you install and configure Retail essentials at the store. For more information about how to install Retail essentials at the store, see [Install Retail essentials at the store or at the point of sale](install-retail-essentials-at-the-store-or-at-the-point-of-sale.md).

You will typically have the following computers at headquarters.

![Computers at headquarters](images/Dn741221.RetailEssentialsHQ(AX.60).gif "Computers at headquarters")

The following sections are included in this document:

  - Recommended topology

  - Install Retail Essentials on the database server

  - Install Retail Essentials on the Microsoft Dynamics AX server

  - Install Retail Essentials on the online store web server

## Recommended topology

Install the following components on the Microsoft Dynamics AX server.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AOS</p></td>
<td><p>AOS is a Windows service that controls communications among Microsoft Dynamics AX clients, databases, and applications.</p></td>
</tr>
<tr class="even">
<td><p>Client</p></td>
<td><p>The Microsoft Dynamics AX client is the interface that is used to connect to an AOS instance.</p></td>
</tr>
<tr class="odd">
<td><p>.NET Business Connector</p></td>
<td><p>.NET Business Connector for Microsoft Dynamics AX enables applications to interact with AOS instances. .NET Business Connector is required for Commerce Data Exchange: Real-time Service.</p></td>
</tr>
<tr class="even">
<td><p>Retail essentials</p></td>
<td><p>Retail essentials includes components that are required to use Retail functionality in Microsoft Dynamics AX.</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Async Server</p></td>
<td><p>Async Server is part of the asynchronous system that shares data between the Microsoft Dynamics AX database and channel databases. Async Server is installed at headquarters and communicates with Microsoft Dynamics AX.</p></td>
</tr>
<tr class="even">
<td><p>Real-time Service</p></td>
<td><p>Real-time Service is an integrated service that provides real-time communication between Microsoft Dynamics AX and retail channels. Real-time Service enables individual point of sale (POS) computers to retrieve certain data from Microsoft Dynamics AX in real time.</p></td>
</tr>
<tr class="odd">
<td><p>Data Import/Export Framework server and client components</p></td>
<td><p>The Data Import/Export Framework for Microsoft Dynamics AX 2012 is an extension that helps you import and export data in Microsoft Dynamics AX.</p>
<p>This component is required if you plan to migrate data from another system. To install and use Data Import/Export Framework, you must install SQL Server Integration Services (SSIS) on the database server.</p></td>
</tr>
</tbody>
</table>


Install the following components on the database server.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Databases</p></td>
<td><p>Microsoft Dynamics AX Application Object Server (AOS) connects to the Microsoft Dynamics AX database to process transactions. AOS connects to the model store to display forms and reports.</p></td>
</tr>
<tr class="even">
<td><p>Data Import/Export Framework service component</p></td>
<td><p>The Data Import/Export Framework for Microsoft Dynamics AX 2012 is an extension that helps you import and export data in Microsoft Dynamics AX.</p>
<p>This component is required if you plan to migrate data from another system. To install and use Data Import/Export Framework, you must install SQL Server Integration Services (SSIS) on the database server.</p></td>
</tr>
</tbody>
</table>


To view reports in Retail essentials, you must also install Microsoft SQL Server Reporting Services and the Reporting Services extensions for Microsoft Dynamics AX. For more information, see [Checklist: Install the Reporting Services extensions and deploy reports](checklist-install-the-reporting-services-extensions-and-deploy-reports.md).

Install the following components on the online store server.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Retail online channel</p></td>
<td><p>The Retail online store is an online sales channel that is fully integrated with Microsoft Dynamics AX. Starter stores accelerate the development of a highly customized online channel.</p>
<p>To install and use the Retail online store, you must install Microsoft SharePoint Server 2013.</p></td>
</tr>
</tbody>
</table>


## Install Retail essentials on the database server

## Before you install Retail essentials on the database server

  - Select a service account for the Data Import/Export Framework service. For information about the requirements for this account, see [Create service accounts](create-service-accounts.md).

  - On the computer where you plan to install these components, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install components of Retail essentials on the database server

Use this procedure to install Retail essentials on the database server. If you select to install additional components, or if you clear the default selections, the installation steps will vary.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**.

4.  On the **Ready to install** page, click **Install**.

5.  On the **Select an installation option** page, click **Microsoft Dynamics Retail essentials**. Select the **Headquarters** option, and then click **Next**.

6.  On the **Add or modify components** page, the components that are required to install Retail essentials at headquarters are automatically selected. Review and change the selections as you require, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location in which to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Select databases** page, select whether you want to create new databases by using Setup, or whether you want to configure existing databases.

10. If you want Setup to create the databases, on the **Create new databases** page, in the **Server name** list, select the name of the computer that runs Microsoft SQL Server. Provide database names, or accept the default database names. By default, the transaction database is named **MicrosoftDynamicsAX**. The baseline database is optional. By default, the baseline database is named **MicrosoftDynamicsAXBaseline**.
    
    If you want to connect to an existing database, on the **Connect to the databases** page, select the name of the computer that runs SQL Server, and then select the names of the existing databases to configure.
    

    > [!IMPORTANT]
    > <P>The database name must not include any spaces or any of the following characters: backslashes (\), slashes (/), periods (.), commas (,), colons (:), brackets ([ ]), parentheses (( )), or hyphens (-). For more information about characters that are allowed by SQL Server, see the <A href="https://go.microsoft.com/fwlink/?linkid=214698">Identifiers</A> topic on MSDN.</P>

    
    Click **Next**.

11. On the **Select additional models** page, select models in the **Available Models** list. Setup lists all the models that are contained in the Models folder and its subfolders. Required models are selected by default, and you cannot clear the selection.
    
    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><img src="images/Ee355075.alert_security(AX.60).gif" title="Security note" alt="Security note" /><strong>Security Note</strong></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>You might have models, or .axmodel files, that are not electronically signed. The Setup program cannot verify the publisher of an unsigned model file. If you import an unsigned model file into the model store, you create a security risk. Setup displays an error message if a selected model file does not have a digital signature. Before you decide whether to continue or cancel the installation, carefully review the models that you have selected.</p></td>
    </tr>
    </tbody>
    </table>
    
    If you install models other than the Foundation models, you must complete the **Compile application** task when you run the initialization checklist. If you do not complete the **Compile application** task, you encounter errors when you run the **Synchronize database** task in the initialization checklist. For more information about the initialization checklist, see [Initialize Microsoft Dynamics AX](initialize-microsoft-dynamics-ax.md).
    
    Click **Next** to continue.

12. On the **Configure the Data Import/Export Framework service** page, specify the service account that will run the Data Import/Export Framework service. Click **Next**.

13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is completed, click **Finish** to close the wizard.

## Install Retail essentials on the Microsoft Dynamics AX server

## Before you install Retail essentials on the Microsoft Dynamics AX server

  - Select service accounts for AOS, the .NET Business Connector proxy, Real-time Service, and Async Server. For information about the requirements for these accounts, see [Create service accounts](create-service-accounts.md).

  - Obtain SSL certificates for Async Server and Real-time Service.

  - On the computer where you plan to install these components, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install components of Retail essentials on the Microsoft Dynamics AX server

Use this procedure to install Retail essentials on the Microsoft Dynamics AX server. If you select to install additional components, or if you clear the default selections, the installation steps will vary.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**.

4.  On the **Ready to install** page, click **Install**.

5.  On the **Select an installation option** page, click **Microsoft Dynamics Retail essentials**. Select the **Headquarters** option, and then click **Next**.

6.  On the **Add or modify components** page, the components that are required to install Retail essentials at headquarters are automatically selected. Review and change the selections as you require, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location in which to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Configure an Application Object Server (AOS) instance** page, assign a name to the AOS instance. Optionally, you can specify the ports that are listed in the following table.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Port</p></th>
    <th><p>Purpose</p></th>
    <th><p>Default value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>TCP/IP port</p></td>
    <td><p>Other Microsoft Dynamics AX components use this port to communicate with AOS.</p></td>
    <td><p>2712</p></td>
    </tr>
    <tr class="even">
    <td><p>Services WSDL port</p></td>
    <td><p>External applications use this port to access the WSDL for AOS-based Microsoft Dynamics AX web services.</p></td>
    <td><p>8101</p></td>
    </tr>
    <tr class="odd">
    <td><p>Services endpoint port</p></td>
    <td><p>External applications use this port to access AOS-based Microsoft Dynamics AX web services.</p></td>
    <td><p>8201</p></td>
    </tr>
    </tbody>
    </table>


10. On the **Specify an AOS account** page, select the Network Service account of the local computer (recommended only for development environments), a managed service account, or a domain account for the AOS service. If you select to use a managed service account, make sure that you specify the account in the format *Domain*\\*AccountName*$.
    

    > [!WARNING]
    > <P>The process of manually changing the service account for an AOS instance is complex and prone to error. Therefore, if you must change the service account for an AOS instance, we recommend that you uninstall and reinstall the AOS instance by using Setup.exe. For more information, see <A href="change-the-account-used-by-aos.md">Change the account used by AOS</A>.</P>



11. On the **Select client preferences** page, select the display language that is used in the client, and specify whether you want Setup to create a desktop shortcut for the client. Additionally, select one of the following installation types:
    
      - **Business user** – The basic client is installed. This type of client installation is appropriate for most users.
    
      - **Developer** – The client, the developer workspace, and additional files that are required for development tasks are installed.
    
      - **Administrator** – The client and additional files that are required for administrative tasks are installed. Administrative tasks include the deployment of artifacts and creating users.
    
    Click **Next**.

12. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by .NET Business Connector. Click **Next**.

13. On the **Configure Async Server** page, select the check box to configure Async Server by using Setup.
    
    Enter the following information:
    
      - **Application name** – The name of the web application that hosts Async Server.
    
      - **App pool name** – The name of the application pool that the web application runs under.
        
        We recommend that you specify separate application pools if multiple Retail components are installed on the same computer. Multiple web applications can share an application pool if resources on the computer are limited. However, if the shared application pool fails, all of the applications that use it will stop responding. In addition, if one application is heavily used, it can negatively affect the performance of the other applications in the pool.
    
      - **Website name** – The name of the website that Async Server runs on.
    
      - **User name** and **Password** – The credentials for the application pool identity.
    
      - **HTTPS port** – The port on which Async Server receives HTTPS requests. You can specify any available port. Verify that the port is open in Windows Firewall, and also record the port number. The port is used to create the URL for Async Server in the following format: https://\<server name\>:port/\<web application name\>. This URL is required when you configure instances of Commerce Data Exchange: Async Client that connect to this instance of Async Server.
        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **TCP port (optional)** – The port on which Async Server receives TCP requests. Specify a TCP port if your environment uses high-performance data synchronization. You can specify any available port. Verify that the port is open in Windows Firewall.
    
      - **AOS service user** – The user account that the AOS instance runs as.
    
      - **SSL certificate thumbprint** – The thumbprint for the Secure Sockets Layer (SSL) encryption certificate. You must obtain a valid, registered certificate from a provider.
    
    Click **Next** to continue.

14. On the **Select a database to use with Async Server** page, create a new message database for Async Server. If you install a subsequent instance of Async Server for load balancing, you must select the same message database.
    

    > [!NOTE]
    > <P>You must set up a separate message database for each partition in Microsoft Dynamics AX.</P>

    
    Click **Next**.

15. On the **Configure Real-time Service** page, select the check box to configure Real-time Service by using Setup.
    
    Enter the following information:
    
      - **Application name** – The name of the web application that hosts Real-time Service.
    
      - **Website name** – The name of the website that hosts Real-time Service.
    
      - **App pool name** – The name of the application pool that Real-time Service runs in.
        
        We recommend that you specify separate application pools if multiple Retail components are installed on the same computer. Multiple web applications can share an application pool if resources on the computer are limited. However, if the shared application pool fails, all of the applications that use it will stop responding. In addition, if one application is heavily used, it can negatively affect the performance of the other applications in the pool.
    
      - **User name** and **Password** – The credentials for the application pool identity.
    
      - **HTTPS port** – The port on which Real-time Service receives secure HTTP requests. You can specify any available port. Verify that the port is open in Windows Firewall.
        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **TCP port** – The port on which Real-time Service receives TCP requests. You can specify any available port. Verify that the port is open in Windows Firewall.
    
      - **SSL certificate thumbprint** – The thumbprint for your SSL encryption certificate. You must obtain a valid, registered certificate from a provider.
    
    Click **Next** to continue.

16. On the **Configure the Data Import/Export Framework extensions** page, specify the name of the computer where the Data Import/Export Framework service is installed. By default, the local computer is used. Click **Next**.

17. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

18. On the **Ready to install** page, click **Install**.

19. After the installation is completed, click **Finish** to close the wizard.
    
    The AOS service can take several minutes to start the first time after it is installed. To determine whether the AOS service has started, click **Administrative tools** \> **Services**, and review the status of the **Microsoft Dynamics AX Object Server** service.

## After you install Retail essentials on the Microsoft Dynamics AX server

Open the Microsoft Dynamics AX client. The initialization checklist opens automatically. You must complete the checklist before you can complete any tasks in Retail essentials. For more information, see [Initialization checklists](initialization-checklists.md).

Install Retail essentials at the store and at the point of sale. For more information, see [Install Retail essentials at the store or at the point of sale](install-retail-essentials-at-the-store-or-at-the-point-of-sale.md).

Customize the online store for your company. For more information, see [Getting started with customizing the Retail online sample store](getting-started-with-customizing-the-retail-online-sample-store.md).

## Install Retail essentials on the online store web server

## Before you install Retail essentials on the online store web server

  - Select service accounts for the SharePoint services for the online store. For information about the requirements for these accounts, see [Create service accounts](create-service-accounts.md).

  - Prepare for the installation. For more information, see “Before you begin” in the topic [Install a Microsoft Dynamics AX Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md).

  - Obtain SSL certificates for online store.

  - On the computer where you plan to install these components, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install components of Retail essentials on the online store web server

Use this procedure to install Retail essentials on the online store server. If you select to install additional components, or if you clear the default selections, the installation steps will vary.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**.

4.  On the **Ready to install** page, click **Install**.

5.  On the **Select an installation option** page, click **Microsoft Dynamics Retail essentials**. Select the **Headquarters** option, and then click **Next**.

6.  On the **Add or modify components** page, the components that are required to install Retail essentials at headquarters are automatically selected. Review and change the selections as you require, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location in which to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Configure a Microsoft Dynamics AX Retail online store** page, select the check box to configure the online store by using Setup.
    
    Enter the following information:
    
      - **Storefront to deploy**: Select a Retail starter store to deploy. The Contoso starter store is modeled after an online electronics retailer. The Fabrikam starter store is modeled after an online clothing retailer.
    
      - **Database server**: The name of the server that will host the Retail online store databases.
    
      - **Channel database name**: The name of the Retail channel database. If this database does not exist, you must cancel Setup and install a Retail channel database.
    
      - **User name and Password**: The credentials for a domain account that has permission to create web applications and execute PowerShell scripts in SharePoint.
    
      - **Pfx file path**: The path to the Pfx file for the SSL certificate.
        

        > [!IMPORTANT]
        > <P>This path cannot contain any special characters. If the path contains a special character deployment fails.</P>

    
      - **Password**: The password for the Pfx file.
    
      - **Channel operating unit number**: A channel operating unit number is specified when you create an online channel in the Microsoft Dynamics AX client. You must create the channel before you deploy the Retail online store. To locate this operating unit number, click **Navigation Path Not Found**

10. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

11. On the **Ready to install** page, click **Install**.

12. After the installation is completed, click **Finish** to close the wizard.

## After you install Retail essentials on the online store web server

Install Retail essentials at the store and at the point of sale. For more information, see [Install Retail essentials at the store or at the point of sale](install-retail-essentials-at-the-store-or-at-the-point-of-sale.md).

Customize the online store for your company. For more information, see [Getting started with customizing the Retail online sample store](getting-started-with-customizing-the-retail-online-sample-store.md).

  



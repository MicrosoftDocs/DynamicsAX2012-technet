---
title: Install Retail essentials at the store or at the point of sale
TOCTitle: Install Retail essentials at the store or at the point of sale
ms:assetid: 1ad177a8-6fa2-4b42-87b0-ea60c84683d5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741217(v=AX.60)
ms:contentKeyID: 62219112
ms.date: 01/28/2015
mtps_version: v=AX.60
---

# Install Retail essentials at the store or at the point of sale 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to install Retail essentials on the store server and on point of sale registers.

Retail essentials is a retail-centric configuration option for Microsoft Dynamics AX. Retail essentials provides a simplified, streamlined user experience that is optimized for organizations that will use only the retail management functions of Microsoft Dynamics AX.


> [!IMPORTANT]
> <P>To install Retail essentials, you must slipstream Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



Install and configure Retail essentials at headquarters before you install and configure Retail essentials at the store. For more information, see [Install Retail essentials at headquarters](install-retail-essentials-at-headquarters.md).

You will typically have the following computers at the store.

![Computers at the store](images/Dn741217.RetailEssentialsStore(AX.60).gif "Computers at the store")

The following sections are included in this document:

  - Recommended topology

  - Install Retail Essentials on the store server

  - Install Retail Essentials on point of sale devices

## Recommended topology

Install the following components on the store server.

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
<td><p>Commerce Data Exchange: Async Client</p></td>
<td><p>Async Client is part of the asynchronous system that shares data between the Microsoft Dynamics AX database and channel databases. Async Client is installed at the channel and communicates with the channel database.</p>
<p>Install Async Client on the store server. Clear this check box if you are installing on register computers.</p>
<p>The Async Client Configuration Tool is installed with Async Client. This tool enables you to test connections and specify whether to use streaming. The streaming option is ideal for initial high speed data synchronization, however for ongoing synchronization the non-streaming option is more reliable. For more information, see <a href="configure-settings-for-async-client.md">Configure settings for Async Client</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail Channel Configuration Utility</p></td>
<td><p>The Retail Channel Configuration Utility can be used to configure Retail POS and Offline Sync Service, create a channel database, and create or re-provision an offline database.</p>
<p>Install the Retail Channel Configuration Utility on computers that host a retail database or an instance of Retail POS.</p>
<p>A channel database may be created either on a stand-alone database server or on a POS computer.</p></td>
</tr>
<tr class="odd">
<td><p>Retail Server</p></td>
<td><p>Retail Server provides services and business logic for Retail Modern POS (point of sale) clients.</p>
<p>Clear this check box if you are using the Retail POS client.</p>
<p>Install Retail Server on the store server. Clear this check box if you are installing on point of sale devices.</p></td>
</tr>
<tr class="even">
<td><p>Retail channel database</p></td>
<td><p>Channel databases hold retail data for one or more retail channels, such as online stores or brick-and-mortar stores.</p>
<p>Install one channel database per store, on the store server. Clear this check box if you are installing on register computers.</p></td>
</tr>
<tr class="odd">
<td><p>Retail Hardware Station</p></td>
<td><p>Retail Hardware Station provides services that enable Retail Modern POS clients and peripherals such as printers, cash drawers, or payment devices, to communicate.</p>
<p>Install Hardware Station on the store server. Clear this check box if you are installing on point of sale devices.</p>
<p>This component is not required if you are using the Retail POS client.</p></td>
</tr>
</tbody>
</table>


Install one of the following components on point of sale devices.

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
<td><p>Retail POS</p></td>
<td><p>Retail POS is a type of POS client that is used in the day-to-day operations at a store.</p>
<p>If you are using this type of POS client, install this component on each register computer at the store.</p></td>
</tr>
<tr class="even">
<td><p>Retail Modern POS</p></td>
<td><p>Retail Modern POS is a type of POS client for personal computers and tablets that are running Windows 8.1 Update 1 or later. Sales staff can process sales transactions and customer orders and perform daily operations and inventory management with mobile devices anywhere in the store, as well as at PC-based registers. Install this component on each point of sale device at the store.</p>
<p>Clear this check box if you are using the Retail POS client.</p></td>
</tr>
</tbody>
</table>


## Install Retail essentials on the store server

## Before you install Retail essentials on the store server

  - Decide which POS client you are going to use: Retail POS or Modern POS. Depending on the type of client you choose, you will need to install different components.

  - Select service accounts for Async Client. You’ll need an account to run the Async Client Windows service and an account to connect to Async Server. You’ll also need accounts for .NET Business Connector, Retail Server, and Retail Hardware Station. For information about the requirements for service accounts, see [Create service accounts](create-service-accounts.md).

  - Create the channel database that will be used with this instance of Async Client. When you install a channel database, the groups that have permissions on the database are created. During the Async Client installation, the service user is added to this group. For more information, see [Install a Retail channel database](install-a-retail-channel-database.md).

  - If you’re using Modern POS, obtain SSL certificates for Hardware Station and Retail Server.

  - On the computer where you plan to install these components, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

## Install Retail essentials on the store server for Retail POS clients

Use this procedure to install Retail essentials on the store server. If you select to install additional components, or if you clear the default selections, the installation steps will vary.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the initial wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select an installation option** page, click **Microsoft Dynamics Retail essentials**. Select the **Point of sale** option, and then click **Next**.

5.  On the **Add or modify components** page, the components that are required to install Retail essentials at the point of sale are automatically selected. Review and change the selections as needed, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Configure Async Client** page, select the check box to configure Async Client by using Setup.
    
    Enter the following information:
    
      - **Async Server URL** – The URL for the instance of Async Server. Typically, the URL is in the format https://\<server name\>:port/\<web application name\>.
        
        If Async Server is installed in a cluster with a load balancer, enter the URL to the service on the load balancer.
    
      - **Channel database ID** – The identifier in Microsoft Dynamics AX for the channel database that is used by the selected instance of Async Client.
    
      - **User name** and **Password** (Async Server connection) – The credentials for the user that connects to Async Server. These credentials must match the credentials that are specified in the channel database profile. Credentials are case sensitive. The credentials are used to identify and authenticate Async Client.
    
      - **User name** and **Password** (Async Client) – The credentials for the user that runs the Windows service for Async Client. The user does not have to be a domain account. It can be a member of a workgroup on the local computer. Credentials are case sensitive.
    
    Optionally, click **Test connection** to verify that Async Client is configured correctly.
    
    Click **Next**.

8.  On the **Select or specify a database to use with Async Client** page, enter server and database information for the message database and the channel database that will be used by Async Client.
    
    You can connect to only an existing channel database. Setup does not create a new channel database if you enter a channel database name that doesn’t exist. If you specify a message database name that doesn’t exist, Setup creates a new message database.
    
    Click **Next**.

9.  On the **Create a channel database** page, select the check box to configure a channel database by using Setup.
    
    Enter the name of the server on which to create the database and the name of the database.
    

    > [!NOTE]
    > <P>If you’re using a named instance of SQL Server, enter the server name in the format <EM>ServerName</EM>\<EM>InstanceName</EM>.</P>



10. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

11. On the **Ready to install** page, click **Install**.

12. After the installation is complete, click **Finish** to close the wizard.

## Install Retail essentials on the store server for Retail Modern POS clients

Use this procedure to install Retail essentials on the store server. If you select to install additional components, or if you clear the default selections, the installation steps will vary.

1.  Install [Microsoft Sync Framework hotfix 2703853](https://support.microsoft.com/kb/2703853) on all computers on which you plan to install Retail Modern POS.
    

    > [!IMPORTANT]
    > <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



2.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

3.  Advance through the initial wizard pages.

4.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

5.  On the **Select an installation option** page, click **Microsoft Dynamics Retail essentials**. Select the **Point of sale** option, and then click **Next**.

6.  On the **Add or modify components** page, the components that are required to install Retail essentials at the point of sale are automatically selected. Review and change the selections as needed, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Configure Async Client** page, select the check box to configure Async Client by using Setup.
    
    Enter the following information:
    
      - **Async Server URL** – The URL for the instance of Async Server. Typically, the URL is in the format https://\<server name\>:port/\<web application name\>.
        
        If Async Server is installed in a cluster with a load balancer, enter the URL to the service on the load balancer.
    
      - **Channel database ID** – The identifier in Microsoft Dynamics AX for the channel database that is used by the selected instance of Async Client.
    
      - **User name** and **Password** (Async Server connection) – The credentials for the user that connects to Async Server. These credentials must match the credentials that are specified in the channel database profile. Credentials are case sensitive. The credentials are used to identify and authenticate Async Client.
    
      - **User name** and **Password** (Async Client) – The credentials for the user that runs the Windows service for Async Client. The user does not have to be a domain account. It can be a member of a workgroup on the local computer. Credentials are case sensitive.
    
    Optionally, click **Test connection** to verify that Async Client is configured correctly.
    
    Click **Next**.

9.  On the **Select or specify a database to use with Async Client** page, enter server and database information for the message database and the channel database that will be used by Async Client.
    
    You can connect to only an existing channel database. Setup does not create a new channel database if you enter a channel database name that doesn’t exist. If you specify a message database name that doesn’t exist, Setup creates a new message database.
    
    Click **Next**.

10. On the **Configure Retail Server** page, select the check box to configure Retail Server by using Setup.
    
    Enter the following information:
    
      - **Application name** – The name of an existing web application in your server environment or the name of an application that you want Setup to create.
    
      - **Website name** – The name of an existing web site in your server environment or the name of a site that you want Setup to create.
    
      - **App pool name** – The name of an existing web application pool in your server environment or the name of an application pool that you want Setup to create.
    
      - **User name and Password** – The credentials for the application pool identity. The user does not have to be a domain account. It can be a member of a work group on the local computer.
    
      - **HTTP port and HTTPS port** – You can specify any available ports. Verify that these ports are open in Windows firewall. Also, make a note of these port numbers. The port is used to create the URL for Retail Server in the format: https://\< *ServerName*\>:*Port*/\<*WebApplicationName*\>. This URL is required to activate Modern POS devices that connect to Retail Server.
        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **SSL certificate thumbprint** – The thumbprint for your Secure Sockets Layer (SSL) encryption certificate.

11. On the **Create a channel database** page, select the check box to configure a channel database by using Setup.
    
    Enter the name of the server on which to create the database and the name of the database.
    

    > [!NOTE]
    > <P>If you’re using a named instance of SQL Server, enter the server name in the format <EM>ServerName</EM>\<EM>InstanceName</EM>.</P>



12. On the **Configure Retail Hardware Station** page, select the check box to configure Hardware Station by using Setup.
    
    Enter the following information:
    
      - **Application name** – The name of an existing web application or the name of an application that you want Setup to create.
    
      - **Website name** – The name of an existing web site or the name of a site that you want Setup to create.
    
      - **App pool name** – The name of an existing web application pool in your server environment or the name of an application pool that you want Setup to create.
    
      - **User name and Password** – The credentials for the application pool identity. The user does not have to be a domain account. It can be a member of a work group on the local computer.
    
      - **HTTP port and HTTPS port** – You can specify any available ports. Verify that these ports are open in Windows firewall.
        

        > [!WARNING]
        > <P>To avoid conflicts with the Default Web Site on the computer, we recommend that you do not use the default HTTPS port (443).&nbsp;A nonstandard port number also helps make the website more secure.</P>

    
      - **SSL certificate thumbprint** – The thumbprint for your Secure Sockets Layer (SSL) encryption certificate.
    
      - **Retail Server URL** – The URL specified when Retail Server was installed. By default, the URL is created by using the following parameters:
        
        https://\<*ServerName*\>:*Port*/\<*WebApplicationName*\>

13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is complete, click **Finish** to close the wizard.

## After you install Retail essentials on the store server

  - Create a channel database profile in the Microsoft Dynamics AX client. For more information, see [Set up a channel database profile (Retail essentials)](set-up-a-channel-database-profile-retail-essentials.md).

  - Configure data distribution settings. For more information, see [Configure and schedule retail data distribution](configure-and-schedule-retail-data-distribution.md).

  - Use the Async Client Configuration Tool to test the connections to Async Server, the channel database, and the channel message database. You can also use the utility to set advanced options. For more information, see [Configure settings for Async Client](configure-settings-for-async-client.md).

  - After you have determined that all connections are working, run the distribution schedule that sends data to each channel database. Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**. Then click **Full data sync** and select the **Full sync** distribution schedule.

  - If you’re using the Modern POS client, create a channel profile for Retail Server in the Microsoft Dynamics AX client. For more information, see [Set up a channel profile](set-up-a-channel-profile.md).

## Install Retail essentials on point of sale devices

## Before you install Retail essentials on point of sale devices

  - Decide which POS client you are going to use: Retail POS or Modern POS. Depending on the type of client you choose, you will need to install different components.

  - Install [Microsoft Sync Framework hotfix 2703853](https://support.microsoft.com/kb/2703853) on all computers on which you plan to install either Retail POS or Retail Modern POS.
    

    > [!IMPORTANT]
    > <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



  - On the computer where you plan to install these components, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

## Install Retail essentials on point of sale devices

Use this procedure to install Retail essentials on point of sale devices. If you select to install additional components, or if you clear the default selections, the installation steps will vary.

1.  Install [Microsoft Sync Framework hotfix 2703853](https://support.microsoft.com/kb/2703853) on all computers on which you are going to install Retail POS or Retail Modern POS.
    

    > [!IMPORTANT]
    > <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



2.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

3.  Advance through the initial wizard pages.

4.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

5.  On the **Select an installation option** page, click **Microsoft Dynamics Retail essentials**. Select the **Point of sale** option, and then click **Next**.

6.  On the **Add or modify components** page, the components that are required to install Retail essentials at the point of sale are automatically selected. Review and change the selections as needed, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is complete, click **Finish** to close the wizard.

## After you install Retail essentials on point of sale devices

  - If you’re using the Modern POS client, start the Retail Modern POS app. In the **Device Activation** page, enter the URL for Retail Server. After you enter the URL, the device is queued in the Microsoft Dynamics AX client, where it must be approved. After the device has been approved, the client is ready to use.

  



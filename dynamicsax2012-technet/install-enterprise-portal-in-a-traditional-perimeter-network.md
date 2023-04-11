---
title: Install Enterprise Portal in a traditional perimeter network
TOCTitle: Install Enterprise Portal in a traditional perimeter network
ms:assetid: 935a3dc1-157c-4020-a75a-c5ad593484d5
ms:mtpsurl: https://technet.microsoft.com/library/Dd361998(v=AX.60)
ms:contentKeyID: 36607353
author: tonyafehr
ms.date: 02/04/2015
mtps_version: v=AX.60
f1_keywords:
- EP with DMZ
- EP with TPN
- TPN
---

# Install Enterprise Portal in a traditional perimeter network 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to set up a traditional perimeter network to support Enterprise Portal for Microsoft Dynamics AX. A traditional perimeter network uses two firewalls and two domain controllers to restrict access to Microsoft Dynamics AX data, forms, and business processes. More specifically, a traditional perimeter network enables internal users of your corporate network (CORP users) to access Enterprise Portal in the perimeter network from either the intranet or the Internet. External users can access Enterprise Portal in the perimeter network from the Internet, but are not permitted to access files or information in the intranet. This restricted access is accomplished by using firewalls and a separate Active Directory forest with 1-way, outgoing, transitive, forest-level trust with the Active Directory forest in the intranet.


> [!WARNING]
> <P>If you do not have experience setting up and configuring network security, contact a Microsoft Certified Partner for help. If you do not set up the perimeter network correctly, the system might be vulnerable to security threats.</P>



This topic includes information about the following.

  - About traditional perimeter networks

  - Before you begin

  - Configure the traditional perimeter network

  - Name resolution

  - Enterprise Portal pre-installation tasks

  - Install Enterprise Portal

  - Enable users to access the Enterprise Portal site


> [!NOTE]
> <P>If you are upgrading Enterprise Portal between Microsoft Dynamics AX 2012, Microsoft Dynamics AX 2012 Feature Pack, and Microsoft Dynamics AX 2012 R2, you should review <A href="scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md">Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3</A>.</P>



## About traditional perimeter networks

A traditional perimeter network contains two Microsoft Active Directory domain controllers separated by firewall devices in two distinct networks, as shown in Figure 1.

Figure 1: A traditional perimeter network

![Enterprise Portal traditional perimeter network](images/Dd361998.TPN(AX.60).gif "Enterprise Portal traditional perimeter network")

The perimeter network contains the Enterprise Portal Web server that is running IIS, SharePoint, and an Active Directory domain controller. The perimeter domain controller hosts accounts for those users who are external to the organization and who require Enterprise Portal access. These user accounts are set up on the perimeter domain controller as follows:

1.  External users have no rights on the internal domain.

2.  External users cannot access the internal network

3.  The internal network contains a complete installation of Microsoft Dynamics AX. This includes the following components:
    
    1.  An Active Directory domain controller that contains the accounts for all internal Microsoft Dynamics AX users
    
    2.  A database that stores Microsoft Dynamics AX data
    
    3.  A Microsoft Dynamics AX AOS

The internal forest has a one-way, incoming, transitive, forest-level trust with the perimeter forest. In the following description, the intranet/internal network is referred to as CORP. This configuration enables the following access scenarios.

  - CORP users can access the AOS by using the Microsoft Dynamics AX Win32 client or the browser-based Enterprise Portal on an internal computer

  - CORP users can access the AOS by using the Microsoft Dynamics AX Win32 client or browser-based Enterprise Portal from an external computer

  - External users can access the AOS by using the browser-based Enterprise Portal from an external computer

The configurations in this document are only one example of how to configure internal and external users to access the AOS by using Enterprise Portal.

## Before you begin

Complete the following tasks before you install Enterprise Portal in a traditional perimeter network.

  - Verify that you have the appropriate permissions to install Enterprise Portal. For more information about permissions, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

  - Install and configure Microsoft Dynamics AX required components in your internal network. If you already installed Microsoft Dynamics AX required components, you must verify that the AOS service runs as a domain user account that is a member of your internal network. The AOS service cannot run as NT Authority\\Network Service for a traditional perimeter network deployment that hosts Enterprise Portal. Verify that the unqualified AOS DNS hostname is not greater than 15 characters. At a minimum, you must install the Microsoft Dynamics AX client, the Application Object Server (AOS), and the database. You must be a local administrator on the server(s) were you want to deploy these components. For more information, see [Install Microsoft Dynamics AX 2012](install-microsoft-dynamics-ax-2012.md).

  - If you installed a non-SYS layer model file in the Microsoft Dynamics AX environment, compile Microsoft Dynamics AX before you install Enterprise Portal. If you do not compile Microsoft Dynamics AX, the Enterprise Portal installation might fail.

  - While logged in as a CORP user who is a local administrator on the server, install SharePoint on the perimeter-network server that will host Enterprise Portal. Verify that you are an administrator on the server and in the Microsoft SQL Server instance that will host SharePoint. When SharePoint prompts you to specify credentials for a service, specify a domain user account that is a member of the internal network. You will specify this same account as the .NET Business Connector proxy account when you install Enterprise Portal. The account does not have to be a member of the administrators group on the server.

  - If you want to deploy Enterprise Portal in multiple languages, you must download and deploy SharePoint language packs onto the web server before you install Enterprise Portal. You can download SharePoint language packs from Microsoft.com. Enterprise Portal is currently supported in the following languages:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p>Arabic</p>
    <p>Chinese (Simplified)</p>
    <p>Czech</p>
    <p>Danish - 1030</p>
    <p>Dutch (Netherlands)</p>
    <p>Dutch (Belgium)</p>
    <p>English</p>
    <p>English (Australia)</p>
    <p>English (Canada)</p>
    <p>English (India)</p>
    <p>English (Ireland)</p>
    <p>English (Malaysia)</p>
    <p>English (New Zealand)</p>
    <p>English (Singapore)</p>
    <p>English (South Africa)</p>
    <p>English (UK)</p>
    <p>English (US)</p>
    <p>Estonian</p>
    <p>Finnish</p>
    <p>French (France)</p>
    <p>French (Canada)</p></td>
    <td><p>French (Belgium)</p>
    <p>French (Switzerland)</p>
    <p>German (Germany)</p>
    <p>German (Austria)</p>
    <p>German (Switzerland)</p>
    <p>Hungarian</p>
    <p>Icelandic</p>
    <p>Italian</p>
    <p>Italian (Switzerland)</p>
    <p>Japanese</p>
    <p>Latvian</p>
    <p>Lithuanian</p>
    <p>Norwegian</p>
    <p>Polish</p>
    <p>Portuguese (Brazilian)</p>
    <p>Russian</p>
    <p>Spanish (international)</p>
    <p>Spanish (Mexico)</p>
    <p>Swedish</p>
    <p>Thai</p></td>
    </tr>
    <tr class="even">
    <td><p></p></td>
    <td><p></p></td>
    </tr>
    </tbody>
    </table>
    
    To deploy Enterprise Portal in one of the languages list here, you must create a Web application in SharePoint and specify the new language. For more information, see [Create an Enterprise Portal site](create-an-enterprise-portal-site.md).

  - Verify that the name of the server that will host Enterprise Portal does not include an underscore, for example EPserver\_1. If an Enterprise Portal server includes an underscore in the server name, lookups and web pages might display errors.

  - On the computer where you will install Enterprise Portal, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - If you are installing Enterprise Portal on a server that already hosts an Enterprise Portal deployment and you want to overwrite that deployment, you must have Full Control permission in SharePoint for the existing Enterprise Portal site collection. If you do not have Full Control permission, you will not be able to delete the existing site collection by using Setup.


> [!IMPORTANT]
> <P>If you attempt to install Enterprise Portal on an existing Internet Information Services (IIS) site that is already configured to use a host header, the installation fails, unless you create a <A href="https://go.microsoft.com/fwlink/?linkid=194948">BackConnectionHostNames</A> registry entry.</P>



## Configure the traditional perimeter network

This section describes how to configure ports and a one-way trust for a traditional perimeter network that supports Enterprise Portal.

## Configure ports

This section describes how to configure ports in the perimeter network and the internal network so that users can access the appropriate Microsoft Dynamics AX information by using Enterprise Portal. Table 1 at the end of this section provides a complete list of ports and the associated direction, connection, and connection type information.

Figure 2: A request for an Enterprise Portal page

![A request for an Enterprise Portal page](images/Dd361998.EPRequest(AX.60).gif "A request for an Enterprise Portal page")

A request is processed as follows:

1.  By default, the Enterprise Portal Web server receives the request from the firewall on TCP port 80 (or 443, if the Web server is configured for Secure Sockets Layer \[SSL\] encryption). The firewall therefore must have port 80 or 443 open for incoming Internet requests.

2.  After the Web server receives the request, it sends the request to the perimeter domain controller on UDP port 53 to verify whether the user is an external or internal user.

3.  The perimeter domain controller and the internal domain controller communicate by using various ports, as shown in Table 1 at the end of this section.

4.  The perimeter domain controller identifies the user and then returns the request to the Web server on UDP port 53.

5.  The Web server authenticates the user and then sends the request to the AOS using TCP. The default port is 2712. The Web server and the AOS communicate by using the Business Connector proxy account.

6.  The AOS communicates with the Microsoft Dynamics AX SQL Server database on port 1433, by default.

7.  After the AOS retrieves the necessary data from the database, it returns the response to the Web server.

8.  The Web server responds back to the client (browser).

Table 1: Ports for a traditional perimeter network to support Enterprise Portal

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Port</p></th>
<th><p>Direction</p></th>
<th><p>Connection</p></th>
<th><p>Type</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>80 or 443 (by default)</p></td>
<td><p>Inbound/ Outbound</p></td>
<td><p>Perimeter firewall to the Enterprise Portal Web server</p></td>
<td><p>TCP</p></td>
<td><p>Verify which ports are used in your environment</p></td>
</tr>
<tr class="even">
<td><p>2712 (by default)</p></td>
<td><p>Inbound/ Outbound</p></td>
<td><p>Enterprise Portal server to Microsoft Dynamics AX AOS</p></td>
<td><p>TCP</p></td>
<td><p>Verify which port is used in your environment</p></td>
</tr>
<tr class="odd">
<td><p>8201</p></td>
<td><p>Inbound/ Outbound</p></td>
<td><p>Enterprise Portal server to Microsoft Dynamics AX AOS</p></td>
<td><p>TCP</p></td>
<td><p>For WCF service interface</p></td>
</tr>
<tr class="even">
<td><p>53</p></td>
<td><p>Inbound/ Outbound</p></td>
<td><p>DNS</p></td>
<td><p>UDP</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>135</p></td>
<td><p>Outbound</p></td>
<td><p>Internal domain controller to perimeter domain controller</p></td>
<td><p>TCP</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>135</p></td>
<td><p>Inbound</p></td>
<td><p>Perimeter domain controller to internal domain controller</p></td>
<td><p>TCP</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>445</p></td>
<td><p>Outbound</p></td>
<td><p>Internal domain controller to perimeter domain controller</p></td>
<td><p>TCP</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>445</p></td>
<td><p>Inbound</p></td>
<td><p>Perimeter domain controller to internal domain controller</p></td>
<td><p>TCP</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>1638</p></td>
<td><p>Outbound</p></td>
<td><p>Internal domain controller to perimeter domain controller</p></td>
<td><p>TCP</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>1638</p></td>
<td><p>Inbound</p></td>
<td><p>Perimeter domain controller to internal domain controller</p></td>
<td><p>TCP</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>389</p></td>
<td><p>Outbound</p></td>
<td><p>Internal domain controller to perimeter domain controller</p></td>
<td><p>UDP</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>389</p></td>
<td><p>Inbound</p></td>
<td><p>Perimeter domain controller to internal domain controller</p></td>
<td><p>UDP</p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


If necessary, use Telnet or Netmon to verify these ports. For more information about how to configure firewall ports, see [How to configure a firewall for domains and trusts](https://support.microsoft.com/kb/179442).

## Configure DNS

The following procedures describe how to configure your Domain Name System (DNS) to create a one-way trust between the domain controllers in your network. For Enterprise Portal, the perimeter network domain controller should trust the internal domain controller, but the internal domain controller should not trust the perimeter domain controller.

To create the one-way trust, complete the following procedures:

  - Configure zone transfers on both domain controllers

  - Create a secondary zone on both domain controllers

  - Create trust from the internal domain controller to the perimeter domain controller

## Configure zone transfers on both domain controllers

Complete this procedure to make sure that the domain controllers can communicate with each other.

1.  Log on to the internal domain controller by using an account that is a member of the domain administrators group.

2.  Open DNS (**Start** \> **Programs** \> **Administrative Tools**).

3.  In the **DNS console**, expand the local name server.

4.  Expand **Forward Lookup Zones**, right-click the domain name, and then click **Properties**.

5.  Click the **Zone Transfers** tab.

6.  Select **Allow Zone Transfers**, and then select **Only to the Following Servers**.

7.  Enter the IP address for the perimeter network domain controller, and then click **Add**.

8.  Click **OK**, and then restart the DNS server.

9.  Repeat this procedure for the perimeter domain controller.

## Create a secondary zone on both domain controllers

Complete this procedure to make sure that the domain controllers know each other's fully qualified domain names.

1.  Log on to the internal domain controller by using an account that is a member of the Domain Administrators group.

2.  Open DNS(**Start** \> **Programs** \> **Administrative Tools**).

3.  In the **DNS console**, expand the local name server.

4.  Right-click **Forward Lookup Zones**, click **New Zone**, and then click **Next**.

5.  On the **Zone type** page, select **Secondary zone**, and then click **Next**.

6.  On the **Zone Name** page, enter the fully qualified domain name of the perimeter network, and then click **Next**.

7.  Enter the IP address for the perimeter domain controller, and then click **Next**.

8.  Click **Finish** to complete the wizard, and then restart the DNS server.

9.  Repeat this procedure for the perimeter domain controller.

## Create a one-way trust between the domain controllers

Complete this procedure to set up the one-way trust between the internal domain controller and the perimeter domain controller.

1.  Log on to the perimeter domain controller by using an account that is a member of the Domain Administrators group.

2.  Open Active Directory Domains and Trusts (**Start** \> **Programs** \> **Administrative Tools**).

3.  In the console tree, right-click the domain name for the domain that you want to administer, and then click **Properties**.

4.  Click the **Trust** tab.

5.  Click **New Trust**, and then click **Next**.

6.  On the **Trust Name** page, enter the fully qualified domain name for the internal domain, and then click **Next**.

7.  Select **One Way: Outgoing**, and then click **Next**.

8.  Select **Both this domain and the specified domain**, and then click **Next**.

9.  Enter the domain administrator credentials for the internal domain, select **Domain Wide Authentication**, and then click **Next**.

10. Click **Next** two times, and then click **Yes** to confirm outgoing trust.

11. Click **Finish**.

## Enable claims authentication in a perimeter network

To configure SharePoint and to authenticate CORP users in a perimeter network with claims authentication, complete the following steps.


> [!NOTE]
> <P>These steps will allow CORP users to access the SharePoint site in the perimeter network using Windows authentication. External users and traditional perimeter domain users cannot access the SharePoint site in the perimeter network using Windows authentication. However, keep in mind, anonymous and claims authenticated access are supported since they are not domain-specific authentication mechanisms.</P>



1.  Create a CORP account to run the Claims to Windows Token Service. The account must have the following characteristics:
    
      - It must be a dedicated account. (A dedicated account is used only for a specific service.)
    
      - It must have a password that does not expire.
    
      - It must have minimal access to network resources.
    
      - It must be an account that exists in the CORP (parent, or trusted) domain.

2.  Add the CORP account that you created in step 1 to SharePoint. You can do this using the [New-SPManagedAccount](https://technet.microsoft.com/library/ff607831.aspx) command in PowerShell.

3.  In the SharePoint Central Administration console, configure the Claims to Windows Token Service to run as the CORP account, as shown in the following image.
    

    > [!NOTE]
    > <P>This image was taken using SharePoint 2013. Keep in mind that SharePoint 2010 is supported, as well.</P>

    
    ![Service Accounts page in SharePoint](images/Dd361998.EP_ClaimsAuthentication(AX.60).png "Service Accounts page in SharePoint")

4.  Give the CORP account permission to enumerate user groups in the CORP Active Directory. For instructions about how to do this, click [here](https://serverfault.com/questions/167371/what-permissions-are-required-for-enumerating-users-groups-in-active-directory).

5.  Give the CORP account the following permissions on all servers running the Claims to Windows Token Service.
    
      - Add the CORP account to the local Administrators group.
    
      - Open the Local Security Policy console (secpol.msc) and go to the Local Policies\\User Rights Assignment folder. Then add the CORP account to these policies:
        
          - Act as part of the operating system
        
          - Impersonate a client after authentication
        
          - Logon as a service
    
      - Log off and log on again for the changes to take effect.
    
      - Restart the Claims to Window Token Service.

6.  Verify that the Claims to Windows Token Service can resolve tokens for the Business Connector proxy account. To do so, complete the following steps as a user who is a local administrator and is part of the WSS\_WPG local group. Remember to logoff/logon after adding the user to the WSS\_WPG group.
    
    1.  Open the SharePoint Central Administration console.
    
    2.  Run \[Microsoft.IdentityModel.WindowsTokenService.S4UClient\]::UpnLogon("bcnet@corp.com")
        

        > [!NOTE]
        > <P>The command shown above assumes that the Business Connector proxy account runs as bcnet@corp.com.</P>

    
    **Expected result:** ImpersonationLevel should be Impersonate, NOT Identity

## Name resolution

The Enterprise Portal server, which is located in the perimeter network, must resolve the host name of the AOS, which is located on the internal or corporate network (CORP). If the AOS does not use a fully qualified domain name (FQDN) such as EP1.corp.contoso.com, then you must manually resolve hostnames. You can resolve hostnames by using one of the following options.

1.  For environments that use a dynamic host configuration protocol (DHCP) server, add the CORP DNS suffix (for example, EP1.corp.contoso.com) to the DNS suffix search list on the DHCP server. Then verify that the perimeter network server resolves hostnames by using the DNS suffix list on the DHCP server.

2.  Edit the hosts file on the Enterprise Portal server (%windir%\\system32\\drivers\\etc\\hosts). Add the non-FQDN AOS computer name to IP mapping. Be aware that making this change in the host file might change the IP address of the AOS server and result in name resolution failures.

3.  For environments that do not use a DHCP server, add the CORP DNS suffix (for example, EP1.corp.contoso.com) to the DNS suffix search list on the Enterprise Portal server, as described in the following procedure.

**Configure the DNS suffix**

1.  On the server that will host Enterprise Portal, click **Start** \> **Control Panel**, and then click **Network and Sharing Center**.

2.  Click **Change adapter settings**.

3.  Right-click **Local Area Connection** and then click **Properties**.

4.  Click **Internet Protocol Version 6 (TCP/IPv6)** and then click **Properties**.

5.  Click **Advanced**.

6.  In the **Advanced TCP/IP settings** dialog box, click the **DNS** tab.

7.  Click **Append these DNS suffixes (in order)** and then click the **Add** button.

8.  Enter the domain to append, for example, corp.contoso.com.

9.  Click **OK** until you are returned to the **Local Area Connection Properties** page.

10. Click **Internet Protocol Version 4 (TCP/IPv4)** and then click **Properties**.

11. Repeat steps 5 – 8 of this procedure to append a DNS suffix for IPv4.

12. When you are finished, click **OK**.

## Enterprise Portal pre-installation tasks

Perform the following tasks to verify that you can deploy Enterprise Portal on the Web server.

1.  A member of the CORP network that has local administrator rights on the server must install SharePoint. If you did not install SharePoint on the server, then you must also verify the following points.

2.  Verify that you are member of the CORP network.

3.  Verify that you can open SharePoint Central Administration on the Enterprise Portal server.

4.  Verify that you have the appropriate permissions to create sites by using SharePoint Central Administration to create a SharePoint team site.

5.  Verify that you can browse the team site without prompts and resolve the URL without proxy errors or other problems.

6.  If you intend to deploy or configure Enterprise Portal at a command prompt, verify that you can start the SharePoint Management Shell.

## Install Enterprise Portal

This section describes how to install Enterprise Portal by using Setup. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages vary, based on the components that you are installing.


> [!TIP]
> <P>By default, when you install SharePoint, the system creates a Web application on port 80. Microsoft Dynamics AX Setup deploys an Enterprise Portal site on the port 80 Web application unless you specify a different Web application. If you do not intend to deploy Enterprise Portal on the default port-80 Web application, you must use SharePoint Central Administration to create a new Web application before you install Enterprise Portal. Also note, if you intend to deploy Enterprise Portal on a Web application that is already configured to use a host header, you must use SharePoint Central Administration to create a new Web application using the host header before you install Enterprise Portal. For any new Web application, you must specify the Business Connector proxy account as the application pool account in the <STRONG>Configurable</STRONG> list.</P>



1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Enterprise Portal (EP)**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want Enterprise Portal to access configuration information from the registry on the local computer or from a shared configuration file. If you select to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the fully qualified domain name (FQDN) of the computer that is running the Application Object Server (AOS) instance that you want to connect to. You can optionally specify the TCP/IP port number and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this screen is not displayed. Subsequent installations on this computer reuse the existing AOS connection. For all Microsoft Dynamics AX installations that use a traditional perimeter network, you must specify the FQDN for the AOS when you are prompted.</P>



11. On the **Specify Business Connector proxy account information** page, if the .NET Business Connector (BC) proxy account has not been configured in Microsoft Dynamics AX, then you must specify a username and password. The proxy must be a domain account from the CORP domain. If the BC proxy was previously configured, then you must enter the password. Click **Next**.

12. On the **Configure a Web site for Enterprise Portal** page, select a web site. If no web sites are available in the list, you must cancel Setup, create a web site by using SharePoint Central Administration, and then try the installation again.
    
    We recommend that you select the **Configure for Windows SharePoint Services** option. If you select this option, Setup verifies that the site is a SharePoint site. If the site is not a SharePoint site, Setup extends the site in SharePoint. Setup also sets the application pool to run under the service account and sets the authentication method to Windows NTLM.
    

    > [!IMPORTANT]
    > <P>Note the following important information about the <STRONG>Create Web site</STRONG> option:</P>
    > <UL>
    > <LI>
    > <P>Clear this option if you are installing Enterprise Portal for a public site, such as an unsolicited vendor portal. For public sites, you must create the Enterprise Portal site by using the public site template. For more information, see <A href="create-a-public-enterprise-portal-site.md">Create a public Enterprise Portal site</A>.</P>
    > <LI>
    > <P>If you are installing Enterprise Portal for a stand-alone installation select the <STRONG>Create Web site</STRONG> option to create a site at the following URL: http://<EM>ServerName</EM>/sites/DynamicsAX. Setup creates a new site in the SharPoint web application that uses port 80.</P></LI></UL>

    
    Click **Next**.

13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is complete, click **Finish** to close the wizard.

## Enable users to access the Enterprise Portal site

Users must be listed in the Microsoft Dynamics AX **Users** form and be assigned to, at the very least, the System user role before they can access Enterprise Portal. You cannot provision users in Microsoft Dynamics AX by using Enterprise Portal. You must provision user by using the Microsoft Dynamics AX 32-bit client. For more information, see [Manage users](manage-users.md). After you have verified that all users are listed in Microsoft Dynamics AX, you must enable users or groups to access the Enterprise Portal site in SharePoint as described in the following procedure.

1.  Open the Enterprise Portal site in a Web browser. By default, the URL is http://*server\_name*/sites/DynamicsAX.

2.  On the menu bar, click **Site Actions** \> **Site Permissions**.

3.  Click **Grant Permissions**.

4.  In the **Users/Groups** text box, enter the name of each user or group, and then click **Check Names**.

5.  Under **Grant permissions**, click the permission level that you want to set. At a minimum, users and groups must have Read permissions.
    
      - If you do not want users to be able to personalize their Role Center pages or modify the shared view of a Web part, assign Read permissions.
    
      - If you want users to be able to personalize their Role Center pages and modify the shared view of a Web part, assign Contribute permissions.
    
      - If you want users to be able to personalize their Role Center pages, but you do not want them to be able to modify the shared view of a Web part, assign Read permissions, and then configure the set of Read permissions in SharePoint. From the Enterprise Portal site, click **Site Actions** \> **Site Permissions** \> **Permission Levels**. Click the **Read** permission link. Under **Personal Permissions**, select the options that you want.
    
      - If you want users to be able to filter reports using a custom parameter value, assign Design permissions.
    
      - If you want users to be able to add and modify financial indicators and key performance indicators (KPIs), assign Design permissions.

6.  Click **OK**.

Internal users can now view Enterprise Portal in a Web browser. If you granted users access to an Enterprise Portal with Role Centers, then those users can now view content in their Role Centers. Page access and the content that is displayed in Enterprise Portal and Role Centers are automatically trimmed according to both the user's security role in Microsoft Dynamics AX and the permissions that you specified in SharePoint.


> [!NOTE]
> <P>If users are prompted to enter their credentials when they view the Enterprise Portal site, they can automate authentication by adding the site to the list of local intranet sites. In Internet Explorer, click <STRONG>Tools</STRONG> &gt; <STRONG>Internet Options</STRONG> &gt; <STRONG>Security</STRONG> &gt; <STRONG>Local intranet</STRONG> &gt; <STRONG>Sites</STRONG>.</P>



## See also

[Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md)

  



---
title: Client security and protection
TOCTitle: Client security and protection
ms:assetid: 60c8d10d-9c97-43c0-b99c-9bda66c8376f
ms:mtpsurl: https://technet.microsoft.com/library/Hh202063(v=AX.60)
ms:contentKeyID: 35949304
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Client security and protection 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes important considerations and best practices for the security of Microsoft Dynamics AX 2012 client computers. One of the most important security considerations is how you deploy the client. Attention must be given to security when the Microsoft Dynamics AX client is deployed. Otherwise, malicious users may gain access to Microsoft Dynamics AX data, or users in your business or organization may unintentionally gain access to sensitive data. Regardless of whether your business or organization runs only a few Microsoft Dynamics AX clients or dozens of clients, we recommend that you deploy the client in the way that is described in this topic. By following these recommendations, you can help protect your data and reduce the overall attack surface of your computing environment. This topic includes the following information:

  - Terminal Services deployment (more secure)

  - Individual deployments (less secure)

  - Encrypt communications between the client and Application Object Server (AOS)

  - Best practices for secure client deployments

## Terminal Services deployment (more secure)

Terminal Services, which is a feature of the Windows Server 2008 operating system, uses the Remote Desktop Protocol (RDP) to communicate between clients and servers. After you deploy an application on a Terminal Services server, clients can connect over a remote access connection, a local area network (LAN), a wide area network (WAN), or the Internet.

When a user accesses an application such as Microsoft Dynamics AX on a Terminal Services server, the application runs on the server. Only information from the keyboard, mouse, and display is transmitted over the network. Users can view only their own sessions. Each session is managed transparently by the server's operating system, and each session is independent of every other client session.

From a security perspective, there are several benefits to running the Microsoft Dynamics AX client on a Terminal Services cluster:

  - Only keyboard strokes, mouse actions, and images of the information that is displayed on the Terminal Services server are transmitted over the network. Because Microsoft Dynamics AX data is not transmitted over the network to client computers, the threat that a malicious user may acquire data that is stored on a user's local client computer is reduced.

  - No data is processed, cached, or stored on a user's local computer. All data processing, caching, and storage occur on the Windows Server computer that is running the Microsoft Dynamics AX client. Therefore, if a user's local client computer is stolen or lost, a malicious user cannot access Microsoft Dynamics AX data on that computer.

  - If a security update is issued for Microsoft Dynamics AX, that update must be applied only to the computers in the Terminal Services cluster. Therefore, the overall attack surface of Microsoft Dynamics AX is minimized.

Figure 1 shows an example of an architecture in which Microsoft Dynamics AX runs on a Terminal Services cluster.

**Figure 1: Microsoft Dynamics AX deployed on a Terminal Services cluster**

![Microsoft Dynamics AX on Terminal Services cluster](images/Hh202063.AXClientWithTerminalServices(AX.60).gif "Microsoft Dynamics AX on Terminal Services cluster")

1.  Users log on to their client computers. The users then open either a remote desktop connection or, if they connect by using the HTTP service, a remote desktop Web connection. Alternatively, users can double-click the Microsoft Dynamics AX client icon on their computers and run the application as a Terminal Services session. This capability is a feature of Windows Server 2008 that is named RemoteApp.

2.  The load balancing solution routes traffic to the Terminal Services cluster based on server availability and load.

3.  Terminal Services receives the session request. Terminal Services then communicates with the Terminal Services Directory and Licensing Services to manage sessions, and to verify that a license is available. If a license is available, Terminal Services starts a unique session for each user. Depending on the configuration of Terminal Services, users may see a Windows desktop. These users can then access the Microsoft Dynamics AX client from the **All Programs** menu. Alternatively, if users are using Terminal Services RemoteApp, the Microsoft Dynamics AX client opens and appears to the users as an application that runs on their client computer.

4.  The Microsoft Dynamics AX clients that run on the Terminal Services cluster communicate with the Microsoft Dynamics AX AOS and database server through ordinary channels.

5.  The Terminal Services cluster transmits images of the information that is displayed on the Terminal Services server over the network to client computers. No data is transmitted over the network. Therefore, no Microsoft Dynamics AX data resides on any user's client computer.

## Deployment considerations

  - By default, Terminal Services enables only two client sessions at the same time. Before you can deploy a Terminal Services cluster, business decision makers in your business or organization must assess the cost of purchasing additional Terminal Services licenses. We highly recommend the investment, because a Terminal Services cluster reduces administrative overhead. Additionally, a Terminal Services cluster reduces the attack surface for security threats against Microsoft Dynamics AX and any other line-of-business applications that run on the cluster.

  - Every user who connects to the Microsoft Dynamics AX client on the Terminal Services cluster must be a member of the Remote Desktop Users group in **Microsoft Windows Users and Groups**.

  - To enhance the security of your computing environment, deploy Group Policy and Encrypting File System on all computers. If your business or organization uses Windows Server 2008, Windows 7, or Windows Vista, deploy Windows BitLocker Drive Encryption. Group Policy and Encrypting File System are described in more detail in the next section.

For more information about Terminal Services, see the [Windows Server 2008 Terminal Services Technical Library](http://go.microsoft.com/fwlink/?linkid=118304).

## Individual deployments (less secure)

The Microsoft Dynamics AX client can be deployed on users' local computers. However, for the following reasons, this kind of deployment is less secure than a deployment of the Microsoft Dynamics AX client on a Terminal Services server.

  - Because more data is transmitted over the network, there is more risk that a malicious user may intercept Microsoft Dynamics AX data that is sent between the client and AOS.

  - If users do not diligently help secure their computers, or if a computer is lost or stolen, there is more risk that a malicious user may access data that is stored on individual computers.

  - If users have access to the Internet, there is more risk of virus attacks or problems with malicious software.

  - If your business or organization does not enforce a policy that requires that users download and install security updates as soon as they are available, your computing environment is at more risk.

You can reduce some of these security risks by deploying the Windows security features that are described in the following sections.

## Deployment considerations

If you deploy the Microsoft Dynamics AX client on individual computers, we recommend that you use the deployment practices that are described in this section. By following these recommendations, you can improve security and reduce some of the risks that were described earlier in this topic.

## Deploy Group Policy

If you intend to deploy the Microsoft Dynamics AX client on individual computers in your business or organization, we recommend that you first implement Group Policy, and then deploy Microsoft Dynamics AX. Group Policy is a feature of Windows Server 2008. Group Policy provides an infrastructure for delivering and applying configurations or policy settings to users and computers in an Active Directory environment. By using Group Policy you can perform the following tasks:

  - Manage user settings and computers from a central location.

  - Implement security settings across an enterprise.

  - Implement standard computing environments for groups of users.

  - Centrally manage software installations, updates, repairs, and upgrades, and software removal.

  - Centrally deploy, recover, restore, and replace users' data, software, and personal settings.

  - Centrally configure and customize users' computers to provide a consistent computing environment and consistent system settings.

  - Centrally manage and control power settings for computers.

  - Control device installation and access to devices such as USB drives, CD-RW drives, DVD-RW drives, and other removable media.

  - Manage Group policy settings for your firewall and Internet Protocol security (IPsec) at the same time. This feature provides more security when you must help secure server-to-server communications over the Internet, limit access to domain resources based on trust relationships or the health of a computer, and protect data communication to a specific server to meet regulatory requirements for data privacy and security.

  - Open and edit Group Policy settings for Internet Explorer. This feature reduces the risk that you may unintentionally change the state of the policy settings based on the configuration of the administrative computer.

  - Assign printers based on either a location in the business or organization or a geographic location. You can also enable Group Policy settings that allow users to install printer drivers.

For more information, see [Group Policy in Windows Server 2008](http://go.microsoft.com/fwlink/?linkid=118676).

## Use the client configuration utility securely

This section describes recommended practices for using the Microsoft Dynamics AX 2012 Configuration utility in a secure manner.

  - Do not install the Microsoft Dynamics AX 2012 Configuration utility on the client computers in a production environment. Instead, create a client configuration file, and store the file in a network shared folder. To install Microsoft Dynamics AX clients that do not include the Microsoft Dynamics AX 2012 Configuration utility, you must perform a silent installation. For more information, see [Mass deployment of the Microsoft Dynamics AX Windows client](mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md).

  - Configure the network shared folder that contains the client configuration file so that all Microsoft Dynamics AX users who are not system administrators have read-only permission. By storing the configuration file in a network shared folder that is configured for read-only permission, you can help prevent accidental changes to the configuration file.

## Deploy Encrypting File System

Encrypting File System (EFS) is a component of the NTFS file system on Windows operating systems. EFS is used to encrypt files and folders on client computers and remote servers. When EFS is used, users can help protect their data from unauthorized access by other users or malicious users. Any individual or application that does not have the appropriate cryptographic key cannot read the encrypted data.

By deploying EFS on the computers where you install the Microsoft Dynamics AX client, you add another level of security for any data or files that users may store locally.

For more information, see [EFS in Windows Server 2008](http://go.microsoft.com/fwlink/?linkid=118685).

## Deploy Windows BitLocker Drive Encryption

Windows BitLocker Drive Encryption, or BitLocker, is a feature that is available in the Windows Server 2008, Windows 7, and Windows Vista operating systems. This feature can help protect data that is stored on client computers, especially mobile client computers.

BitLocker performs two functions:

  - BitLocker encrypts all data that is stored on the Windows operating system volume and any data volumes that are configured. This data includes the Windows operating system, hibernation and paging files, applications, and data that is used by applications.

  - BitLocker is configured to use a Trusted Platform Module (TPM) to help guarantee the integrity of components that are used in the early stages of the startup process. Any volumes that are protected by BitLocker are "locked." Therefore, these volumes remain protected, even if the computer is tampered with when the operating system is not running.

If a volume is protected by BitLocker, all data that is written to the volume is encrypted. This includes the operating system itself, and all applications and data. In this way, BitLocker helps protect data from unauthorized access. Although the physical security of servers remains important, BitLocker can help also protect data if a computer is stolen or shipped from one location to another, or if the computer is otherwise out of a user's physical control.

By encrypting the disk, BitLocker helps prevent offline attacks. For example, a malicious user may try to bypass Windows security provisions, such as permissions that are enforced by access control lists (ACLs) in NTFS, by removing a disk drive from one computer and installing it in another computer.

For more information, see [Windows BitLocker Drive Encryption](http://go.microsoft.com/fwlink/?linkid=118687).

## Special considerations for client computers that are used in development environments

Client computers that are used for Microsoft Dynamics AX development must be isolated from the clients, AOS instances, and database computers that are used in the production environment. Otherwise, if the environments are not correctly isolated, the process of testing or developing customizations may unintentionally affect the production environment.

To help maintain the security of the production environment, we recommend that you not grant developers access to the Microsoft Dynamics AX production database. Instead, make sure that client computers that are used for development have their own AOS instance and database, and that the development environment has its own data set. To help maintain security and privacy, do not use production data in a development environment.

## Encrypt communications between the client and AOS

Microsoft Dynamics AX AOS performs business logic and data processing for all incoming and outgoing requests from client computers. If a malicious user intercepts requests between a client computer and AOS, that user may gain access to data or information. By using encryption, you can reduce the risk that a malicious user may intercept requests between client computers and AOS.

## Remote procedure call encryption

By default, Microsoft Dynamics AX is configured to encrypt all credentials and data that are transmitted over the network between clients and AOS, and between AOS and the database. Microsoft Dynamics AX uses the remote procedure call (RPC) to perform the encryption.

We recommend that you not disable the RPC security feature. You can verify that RPC encryption is enabled by using the Microsoft Dynamics AX 2012 Configuration utility. The configuration utility is automatically installed when you install the Microsoft Dynamics AX client. If you suspect that users or administrators have disabled RPC encryption, verify the encryption setting on each Microsoft Dynamics AX client computer in your business or organization.

1.  Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  Click the **Connection** tab.

3.  Verify that **Encrypt client to server communications** is selected. If this option is not selected, select it, and then click **OK**.

## Role Center encryption

Role Centers provide overview information for Microsoft Dynamics AX users. This information includes work lists, activities, common links, and key information about business intelligence. Role Centers use the framework for Enterprise Portal for Microsoft Dynamics AX to display information either on an Enterprise Portal Web site or on a Role Center home page in the Microsoft Dynamics AX client.

If your business or organization uses Role Centers, and if the administrator installed Enterprise Portal without Secure Sockets Layer (SSL) encryption, all communications between Role Centers in the Microsoft Dynamics AX client and AOS are sent in clear text. As a result, if a malicious user intercepts communications between a client computer that is using Role Centers and AOS, that user can see data from those communications.

If your business or organization uses Role Centers, you must make sure that Enterprise Portal is configured to use SSL encryption. SSL encryption is a feature of Internet Information Services (IIS), which is the Web server software that hosts the Enterprise Portal framework. For more information about how to configure SSL encryption, see [Secure Sockets Layer encryption in IIS 7.0](http://go.microsoft.com/fwlink/?linkid=118362).

## Best practices for secure client deployments

The following table describes the best practices that apply to all deployments of the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Recommendation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Always assign the least permissions when you set up and configure the user security features in Microsoft Dynamics AX.</p></td>
<td><p>Before you set up and configure the least permissions in Microsoft Dynamics AX, consider the following recommendations:</p>
<ul>
<li><p>By default, and by design, only Microsoft Dynamics AX system administrators have access to the Application Object Tree (AOT). Do not grant users access to the AOT, unless the users are members of a development role who must access the AOT as part of their job requirements. If you grant regular users access to the AOT, the users may intentionally or unintentionally compile the application, synchronize the application, change license files, or change module configurations. All of these actions can cause problems in your business or organization.</p></li>
<li><p>Do not make users members of the <strong>System administrators</strong> role, or grant these users access to <strong>System administration</strong> in Microsoft Dynamics AX, unless the users are responsible for setting up and configuring Microsoft Dynamics AX in your business or organization. If you grant regular users access to this group and module, the users may intentionally or unintentionally cause problems in the Microsoft Dynamics AX application.</p></li>
<li><p>Do not assign users to the Windows <strong>Administrators</strong> group or <strong>Power Users</strong> group on their local computers, unless the users are explicitly required to perform the job functions of an administrator or power user. Members of these groups can add applications to their local computers and remove applications from their local computers, and these actions can introduce security risks. Instead, assign users to the Windows <strong>User</strong> group. Click <strong>Start</strong> &gt; <strong>Administrative Tools</strong> &gt; <strong>Server Manager</strong> &gt; <strong>Local Users and Groups</strong>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Educate users about how to use strong passwords, and define password policies.</p></td>
<td><p>Strong passwords and password policies in your domain help maintain a secure computing environment. We highly recommend that you implement password best practices in your business or organization. For more information, see <a href="http://go.microsoft.com/fwlink/?linkid=118273">Password Best Practices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enable Windows Firewall or another firewall device on each computer.</p></td>
<td><p>A firewall drops incoming traffic that has not been sent in response to a request of the computer. Traffic that is sent in response to a request is named solicited traffic. The firewall also drops unsolicited traffic that has not been specified as allowed. Traffic that is unsolicited but allowed is named excepted traffic. A firewall adds a level of protection against malicious users and applications that rely on unsolicited incoming traffic to attack computers.</p>
<p>We recommend that you enable Windows Firewall or another firewall device on every computer in your business or organization. Windows Firewall is a Control Panel feature that is used to set restrictions on the traffic that can enter your network from the Internet.</p>
<p>For more information, see <a href="http://go.microsoft.com/fwlink/?linkid=118283">Windows Firewall</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enable a virus scanner on each computer.</p></td>
<td><p>The threat of virus attacks is ongoing and always changes. We recommend that you deploy a virus scanner on every computer in your business or organization, and that you configure the scanners to scan computers and update virus signatures regularly.</p></td>
</tr>
<tr class="odd">
<td><p>Deploy smart cards in your business or organization.</p></td>
<td><p>We recommend that you deploy smart cards in your business or organization. A smart card contains a small computer chip that is used to store security keys or other types of personal information. Smart cards use cryptographic technology to store the information. Some businesses or organizations deploy smart card readers on every laptop and desktop computer, and require that employees insert their smart card into the reader to connect to the corporate network. By deploying smart cards in this manner, the business or organization adds another physical layer of security to its computing environment, because every user who connects to the corporate network must have a valid password and a smart card.</p>
<p>For more information, see the <a href="http://go.microsoft.com/fwlink/?linkid=118292">Smart Card Reference</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[Set up user security in Microsoft Dynamics AX](set-up-user-security-in-microsoft-dynamics-ax.md)

[TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=118293)

  



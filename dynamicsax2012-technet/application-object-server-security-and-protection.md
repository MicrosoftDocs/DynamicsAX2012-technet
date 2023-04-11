---
title: Application Object Server security and protection
TOCTitle: Application Object Server security and protection
ms:assetid: ec82b5b9-8fa0-4d9e-9ac2-6ffa985be9c5
ms:mtpsurl: https://technet.microsoft.com/library/Hh202118(v=AX.60)
ms:contentKeyID: 35949377
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Application Object Server security and protection 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Application Object Server (AOS) processes client requests for data and performs Microsoft Dynamics AX business logic. If a malicious user gains access to AOS, that user may gain access to sensitive data, such as financial information and trade secrets. Therefore, we recommend that you follow the guidelines in this topic when you deploy AOS. By following these guidelines, you can help protect the data in your business or organization, and reduce the overall attack surface of this core component of Microsoft Dynamics AX.

## Configure AOS to use a domain account

When you install AOS by using Setup, you can configure the service to use either a domain account, a managed service account, or the Network Service account. By default, a domain account is used. The Network Service account is less secure than a domain account, provided that you set up and configure the domain account correctly. The Network Service account is less secure, because it is available to other applications that are installed on the same server. Additionally, the Network Service account is translated into a computer account if the service must communicate with a different server. For example, you deploy four AOS instances that use the Network Service account, and these servers communicate with a separate instance of Microsoft SQL Server. As a result, four different computer accounts are created in SQL Server. Therefore, in this scenario, you have four accounts that a malicious user may be able to use to gain access to AOS or the database. By using a domain account, there is only one account that you must help secure. Therefore, the attack surface of your computing environment is reduced.

Work with your domain administrator to create a new managed service account or domain account in Active Directory. Managed service accounts are managed domain accounts that provide automatic password management and simplified service principal name (SPN) management. SPN management includes delegation of management to other administrators. For information about managed service accounts, see [Service Accounts Step-by-Step Guide](https://go.microsoft.com/fwlink/?linkid=218113).

If you use a standard domain account, the account must not be used for any other services or back office operations. The account must be a dedicated account. You must make sure that the permissions for the new account are as low, or restrictive, as possible, to help reduce the risk of processes that can harm the server. Verify with the domain administrator that the account has the following configuration:

  - The password for the domain user account is a strong password.

  - The domain user account does not have interactive logon rights.

  - The domain user account can log on as a service.

  - The domain user account is not listed as a member of any Active Directory groups that are added to Microsoft Dynamics AX. Otherwise, the account automatically becomes a Microsoft Dynamics AX user.

  - The domain user account is not listed as a user or member of any groups in **Windows Users and Groups** on AOS.

For more information about Microsoft Dynamics AX service accounts, see [Create service accounts](create-service-accounts.md).

## Change the default port that is used by AOS

By default, when you install Microsoft Dynamics AX, AOS is configured to listen on port 2712 for TCP/IP communications, port 8101 for WSDL communications, and port 8201 for NET-TCP communications. If you install other AOS services on the same computer, the port numbers are incremented by 1 for each service.

If a malicious user who knows the default port numbers learns about a vulnerability in Microsoft Dynamics AX, that user may attempt to gain access to data by using a port number. You can reduce the attack surface by changing the default port numbers. For more information, see [Change AOS ports](change-aos-ports.md).

You must also specify the new port number on each client that connects to the AOS. You can change the port number by using the **Microsoft Dynamics 2012 Configuration** utility.

1.  On a client computer, click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  In the **Configuration target** drop-down list, select **Local client**.

3.  Click **Manage** \> **Create configuration**.

4.  Enter a name, and then select **Copy from Active configuration**.

5.  On the **Connection tab**, select the appropriate instance in the text box, and then click **Edit**.

6.  Enter the new port number, and then click **OK**.

To expedite the process of configuring multiple client computers, you can export this configuration to a file and then import the configuration to all other client computers. For more information, see [Manage a client configuration](manage-a-client-configuration.md).

## Use Windows features to reduce the attack surface

Microsoft Windows operating systems include security features that can help you reduce the attack surface of your computing environment. We recommend that you implement and use the following features on AOS.

## Internet Protocol Security (IPsec)

IPsec is a feature of Microsoft Windows Server 2008 that helps protect networks from active and passive attacks by using packet filtering, cryptographic security services, and trusted communications.

IPsec helps provide in-depth defense against the following kinds of attacks:

  - Network-based attacks from unknown computers

  - Denial-of-service attacks

  - Data corruption

  - Data theft

  - User credential theft

For more information, see [IPsec](https://go.microsoft.com/fwlink/?linkid=119801).

## Windows Firewall

Windows Firewall is a Control Panel feature that is used to set restrictions on the traffic that can enter the network from the Internet. Windows Firewall is included in Windows Server 2008.

For more information, see [Windows Firewall](https://go.microsoft.com/fwlink/?linkid=118283).

## The Microsoft Security Configuration Wizard

The Microsoft Security Configuration Wizard reduces the attack surface of the Microsoft Windows Server 2008 operating system. The wizard determines the minimum set of features that is required for a server's role or roles, and then disables all features that are not required.

The Security Configuration Wizard performs the following tasks:

  - Disable nonessential services

  - Block unused ports

  - Enable additional address or security restrictions for ports that are left open

  - Prohibit unnecessary Web extensions for Internet Information Services (IIS)

  - Reduce protocol exposure to server message block (SMB), LanMan, and Lightweight Directory Access Protocol (LDAP)

  - Define a high signal-to-noise audit policy

To open the Security Configuration Wizard, click **Start** \> **Administrative Tools** \> **Security Configuration Wizard**. We recommend that you read the Help for the wizard before you change the system. For more information about services, ports, and protocols on the Windows Server 2008 operating system, see [Service overview and network port requirements for the Windows Server system](https://go.microsoft.com/fwlink/?linkid=119804).

## Microsoft Security Baseline Analyzer

The Microsoft Baseline Security Analyzer scans your computer to detect non-secure configurations and identify any security updates that are missing. The analyzer then recommends changes and updates that can help improve the security of the computer.

For more information, see [Microsoft Security Baseline Analyzer](https://go.microsoft.com/fwlink/?linkid=119802).

## See also

[Client security and protection](client-security-and-protection.md)

[Set up user security in Microsoft Dynamics AX](set-up-user-security-in-microsoft-dynamics-ax.md)

  



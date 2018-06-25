---
title: Change the account used by AOS
TOCTitle: Change the account used by AOS
ms:assetid: 87aaf2fa-1190-4036-9d39-c1252c48da88
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ585430(v=AX.60)
ms:contentKeyID: 48808018
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Change the account used by AOS [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The account that is used by Application Object Server (AOS) is assigned security permissions in multiple locations in Microsoft Dynamics AX. This topic describes the tasks that you must complete to change the AOS account. If you try to change the account that is used by AOS without completing the tasks in this topic, Microsoft Dynamics AX might stop working. In this case, you might receive the following message: *Exception: A call to SSPI failed, see inner exception. InnerException:System.Security.Authentication.AuthenticationException: A call to SSPI failed, see inner exception. System.ComponentModel.Win32Exception: The target principal name is incorrect.*

## Change the AOS account

We recommend that you uninstall and then reinstall AOS to change the AOS account. Attempts to manually change the account or to change the account by using the Grant-DBPermissionsToAosAccount script might affect permissions and cause Microsoft Dynamics AX to stop working.


> [!NOTE]
> <P>If you change the account that is used by AOS, you must also update the service configuration that is used by clients, as described here. If you do not update the service configuration, clients such as Enterprise Portal for Microsoft Dynamics AX stop working.</P>



1.  Use Microsoft Dynamics AX Setup to uninstall and then reinstall AOS. For more information, see [Install an AOS instance](install-an-aos-instance.md).

2.  Create a new configuration by using the Microsoft Dynamics AX Configuration utility. To open the configuration utility, click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

3.  In the **Configuration target** list, select **Local client**.

4.  Click **Manage**, and then click **Create configuration**.

5.  In the **Create configuration** dialog box, in the **Name** box, type a name.

6.  You can copy settings from either the active configuration or the original configuration, which is the default configuration. Select the configuration to copy settings from, and then click **OK**.

7.  Click the **Connection** tab.

8.  Click the **Refresh** button to update the service configuration for client SDK applications.


> [!NOTE]
> <P>If you use the Kerberos protocol for authentication in your environment, you must update the user principal name (UPN) of the server for each AOS client after you change the AOS account. By updating the service configuration as described in the previous procedure, you update the UPN for Microsoft Dynamics AX clients. If you have developed a Microsoft Dynamics AX client that invokes any Microsoft Dynamics AX services and is configured by using a Windows Communication Foundation (WCF) configuration file, you must update the UPN in the .config file, as described here.</P>



To enable the client to use the Kerberos protocol after you change the account that is used by AOS, you must regenerate the WCF .config file that is used by the client, so that the .config file includes the UPN of the AOS instance. You can use Microsoft Visual Studio to generate the .config file automatically for the client, or you can create your own .config file.

The following example shows the format of the entry in the WCF .config file that specifies a UPN.

    <endpoint address="net.tcp://<hostname>:<port>/DynbamicA/Services/SysSecurityServices" binding="netTCPBinding"
                    bindingConfiguration="netTcpBinding_SysUserManagement" contract="SysUserManagement"
                    name="netTcpBinding">
                    <identity>
                        <userPrincipalName value="username@contoso.com"/>
                    </identity>
                </endpoint>

For more information, see the following topics:

  - [Service Identity and Authentication](http://msdn.microsoft.com/en-us/library/ms733130.aspx)

  - [Overriding the Identity of a Service for Authentication](http://msdn.microsoft.com/en-us/library/ms733130.aspx)

  - [Kerberos](http://technet.microsoft.com/en-us/library/cc753173\(ws.10\).aspx)

## See also

[Troubleshoot services and AIF](troubleshoot-services-and-aif.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


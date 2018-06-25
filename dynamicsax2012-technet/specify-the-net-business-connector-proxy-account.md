---
title: Specify the .NET Business Connector proxy account
TOCTitle: Specify the .NET Business Connector proxy account
ms:assetid: 3e46dc0a-2ff4-4a06-ae61-041e52dcc774
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496652(v=AX.60)
ms:contentKeyID: 35132612
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Specify the .NET Business Connector proxy account [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The .NET Business Connector for Microsoft Dynamics AX provides a set of managed classes that provide access to X++ functionality. As a result, applications can interact with Application Object Servers (AOS).

For some components, the .NET Business Connector must be configured to connect to Microsoft Dynamics AX by using a proxy account. By using a proxy, the .NET Business Connector can connect on behalf of Microsoft Dynamics AX users when it authenticates with an AOS instance.

## Specify the proxy account for the .NET Business Connector

When you install the .NET Business Connector, Setup prompts you to enter a domain user account and password. Setup then specifies the domain account as the proxy account for the .NET Business Connector in the **System service accounts** form in Microsoft Dynamics AX. Depending on the features that you installed when you installed the .NET Business Connector, Setup also adds the proxy account to the IIS\_IUSRS and WSS\_WPG Windows groups. If your Microsoft Dynamics AX environment is running Enterprise Portal for Microsoft Dynamics AX, Setup also configures the Internet Information Services (IIS) application pool to use the proxy account for the .NET Business Connector.

Use the following procedure to change the name of the proxy account for the .NET Business Connector in Microsoft Dynamics AX.

1.  In the Microsoft Dynamics AX client, open the **System service accounts** form. Click **System administration** \> **Setup** \> **System** \> **System service accounts**.

2.  In the **Business connector proxy** section, enter the alias and the domain. The alias must be a domain account. For more information about the domain account for the .NET Business Connector, see [Create service accounts](create-service-accounts.md).

3.  Click **OK**.

## See also

[Install the .NET Business Connector](install-the-net-business-connector.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


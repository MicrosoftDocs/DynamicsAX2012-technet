---
title: Create a configuration for .NET Business Connector
TOCTitle: Create a configuration for .NET Business Connector
ms:assetid: 91fd7a36-5a5f-4a2d-b85c-c7ecaec9c405
ms:mtpsurl: https://technet.microsoft.com/library/Aa569654(v=AX.60)
ms:contentKeyID: 37822170
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a configuration for .NET Business Connector 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

.NET Business Connector is a component of the development environment for Microsoft Dynamics AX. You use .NET Business Connector to build software applications that can be integrated with Microsoft Dynamics AX. You can think of .NET Business Connector as a Microsoft Dynamics AX client that does not have a user interface. In other words, .NET Business Connector is non-interactive. You can use .NET Business Connector to access the same X++ code, business logic, and security model that are available to the Microsoft Dynamics AX client. .NET Business Connector contains a kernel that is used to interpret and run code, and it provides a run-time environment for interaction with elements in the Application Object Tree (AOT). For more information about .NET Business Connector, see the [.NET Business Connector](https://go.microsoft.com/fwlink/?linkid=231141) developer documentation on MSDN.

## Create a configuration for an instance of .NET Business Connector

To modify the configuration options for an instance of .NET Business Connector, you must be a member of the Administrators group on the local computer. You cannot modify the original configuration of a system. To change a configuration, you must create and modify a new configuration. By default, changes that are made to configurations are stored in the registry for each user.


> [!NOTE]
> <P>You can install an instance of .NET Business Connector and the Microsoft Dynamics AX client on the same computer. However, in this case, the configuration settings for the client are used for both components if .NET Business Connector runs under the account that is currently logged in. If you want to run an instance of .NET Business Connector and the Microsoft Dynamics AX client on the same computer, we recommend that you specify a unique domain account for .NET Business Connector. For more information, see <A href="configure-system-accounts.md">Configure system accounts</A>.</P>



1.  Open the Microsoft Dynamics AX 2012 Configuration utility. Click **Start**, click **Administrative Tools**, and then click **Microsoft Dynamics AX 2012 Configuration**.

2.  In the **Configuration Target** list, click **Business Connector (non-interactive use only)**.

3.  Click **Manage**, and then click **Create configuration**.

4.  In the **Create configuration** dialog box, in the **Name** box, type a name.

5.  You can copy settings from either the active configuration or the original configuration. The original configuration is the default configuration. Select the configuration that you want to copy settings from, and then click **OK**.
    

    > [!NOTE]
    > <P>You cannot delete or rename the original configuration. You can only rename or delete configurations that you create.</P>



For more information about the fields and options in the Microsoft Dynamics AX 2012 Configuration utility, press F1 to view Help content for this tool on Microsoft TechNet.

## See also

[Manage a client configuration](manage-a-client-configuration.md)

  



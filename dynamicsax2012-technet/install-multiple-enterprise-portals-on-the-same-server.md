---
title: Install multiple Enterprise Portals on the same server
TOCTitle: Install multiple Enterprise Portals on the same server
ms:assetid: 56af673f-1fcb-4396-90d2-7480f0ba8b0a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh328926(v=AX.60)
ms:contentKeyID: 36689191
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Install multiple Enterprise Portals on the same server 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install and configure multiple Enterprise Portals on the same server. Portals can be configured to access the same or different Microsoft Dynamics AX Application Object Server (AOS) instances, as described in this topic.


> [!WARNING]
> <P>Before you continue, consider the following.</P>
> <UL>
> <LI>
> <P>If you install multiple portals on the same server, you create a single point of failure for all portals if SharePoint or IIS are not available on the server.</P>
> <LI>
> <P>Scheduled downtime for maintenance affects all portals on the server which might limit how often you can perform maintenance.</P>
> <LI>
> <P>If you plan to install portals for development, testing, and production on the same server (not recommended) you could unintentionally deploy development changes to production which could cause data-integrity problems.</P>
> <LI>
> <P>Multiple portals consume more resources on the server than a single portal. Plan your topology accordingly.</P>
> <LI>
> <P>You can deploy multiple portals on the same server as long as the user controls are the same. This means the controls must use the same AX model. Multiple portals on the same server are not supported if the codebase is different.</P></LI></UL>



## Enterprise Portal and the AOS

Enterprise Portal determines which AOS instance to connect to by reading a Microsoft Dynamics AX client configuration. If you install Enterprise Portal on a server that hosts an AOS instance, the client configuration is stored, by default, in the registry on the AOS. If you install Enterprise Portal on a server that does not host an AOS or if Setup cannot locate a client configuration on the Web server, you are prompted to specify the location of the client configuration. If you create additional Enterprise Portals on the server, those portals use the AOS that is specified in the client configuration unless you specify a different client configuration, as described in this topic.

## Multiple portals on the same server that use the same AOS

By default, when you install Enterprise Portal, Setup creates an Enterprise Portal site on the SharePoint-80 Web application. You can create additional sites on the port 80 Web application by using SharePoint Central Administration. All sites created in this manner use the same AOS. For more information about how to create an Enterprise Portal site, see [Create an Enterprise Portal site](create-an-enterprise-portal-site.md).

If you create additional web applications by using SharePoint Central Administration, you must deploy Enterprise Portal on the new web applications by using Microsoft Dynamics AX Setup. You can then create additional sites on the new web application by using SharePoint Central Administration. All sites created in this manner use the same AOS.

## Multiple portals on the same server that use different AOSs

To install multiple portals on the same server and have those portals connect to different AOS instances, you must follow these steps.

## Before you begin

Enterprise Portal determines which AOS to connect to by reading a Microsoft Dynamics AX client configuration. To install multiple portals on the same server and have those portals connect to different AOS instances, the portals must read separate Microsoft Dynamics AX client configurations. Create one or more Microsoft Dynamics AX client configuration files by using the Microsoft Dynamics AX 2012 Configuration utility and store the configuration files on a network share. For more information about how to create a configuration file, see [Manage a client configuration](manage-a-client-configuration.md).

1.  Use Microsoft Dynamics AX Setup to install Enterprise Portal on the server. By default, Setup creates an Enterprise Portal intranet site on the SharePoint-80 Web application. For the purpose of this procedure, this portal is called Portal1 and it is connected to AOS1. For more information about how to install Enterprise Portal, see [Install Enterprise Portal on a single server](install-enterprise-portal-on-a-single-server.md).

2.  Create a new web application on the Enterprise Portal server by using SharePoint Central Administration. For more information about how to create a new web application, see the SharePoint online Help.

3.  Install Enterprise Portal on the new web application by using Microsoft Dynamics AX Setup. By default, a second portal is created on the port that is specified in SharePoint Central Administration. For the purpose of this procedure, this portal is called Portal2. Copy the URL of Portal2. You will need the URL later in this procedure when you register the portal. Portal2 is currently connected to AOS1.

4.  Specify the new Microsoft Dynamics AX client configuration file for Portal2 by editing the web.config file. By default the web.config file is located in the following directory: C:\\inetpub\\wwwroot\\wss\\VirtualDirectories\\\<port number\>

5.  Add the following Microsoft.Dynamics element under \</system.web\>. Replace \<server\_name\>, \<path\>, and \<configuration\_file\>.axc with the information specific to your computing environment. For example: \<Session Configuration="C:\\inetpub\\wwwroot\\dynamicsax.axc" /\>
    
    \<Microsoft.Dynamics\>
    
    \<Session Configuration="\\\\\<server\_name\>\\\<path\>\\\<configuration\_file\>.axc" /\>
    
    \</Microsoft.Dynamics\>

6.  Save your changes in the web.config file.

7.  Verify that the Business Connector Proxy account for AOS2 is the same as AOS1. Click **System administration** \> **Setup** \> **System** \> **System service accounts**.

8.  Use the Microsoft Dynamics AX client to register Portal2 on AOS2. Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Web sites**. Enter the URL in the **Internal URL** and **External URL** fields.

9.  In the **Type** field, click **Full (Web parts and site templates)**. Portal2 is now connected to AOS2.

10. Delete Portal2 from the **Web sites** form on AOS1.

11. On the Enterprise Portal server, open a command prompt and run the following command. This command closes stale Business Connector connections: iisreset /noforce

## Next steps

After you create the portals you must configure security, user access, and portal-wide settings. For more information, see [Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md).

## See also

[Checklist: Configure Role Centers](checklist-configure-role-centers.md)

  



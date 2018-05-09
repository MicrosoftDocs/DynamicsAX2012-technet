---
title: Troubleshoot installation issues with Enterprise Portal and Role Centers
TOCTitle: Troubleshoot installation issues with Enterprise Portal and Role Centers
ms:assetid: e0cee771-4fcb-42e3-9213-5b297c8f6fe5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee355087(v=AX.60)
ms:contentKeyID: 39555419
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Troubleshoot installation issues with Enterprise Portal and Role Centers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following sections provide information to help you troubleshoot issues you may encounter when you install Enterprise Portal for Microsoft Dynamics AX and Role Centers.

## Known Issues: SharePoint 2010 mode on SharePoint 2013

The following changes in Enterprise Portal functionality or behavior result when you run on SharePoint 2013.

**Unable to install or configure Enterprise Portal**: Installation can fail if the Claims to Windows Token Service is not running in SharePoint Central Administration. The Setup log file includes the following error: Server was unable to process request. ---\> Could not retrieve a valid Windows identity. ---\> The message could not be dispatched because the service at the endpoint address 'net.pipe://localhost/s4u/022694f3-9fbd-422b-b4b2-312e25dae2a2' is unavailable for the protocol of the address.

To resolve this issue, in **SharePoint Central Administration**, click **System Settings** \> **Manage services on server**. Start the Claims to Windows Token Service and then install Enterprise Portal.

**Experience all that SharePoint 2013 has to offer \> Missing Site Templates**: After you install Enterprise Portal on SharePoint 2013 you see a message bar that says, “Experience all that SharePoint 2013 has to offer.” If you click the link provided, you see an error that states, “Missing Site Templates”. You can ignore this message. To retain important functionality, features, and design, Enterprise Portal uses the SharePoint 2010 mode provided by SharePoint 2013.

**Sign-in as a different user:** The option to sign-in as a different user was removed from SharePoint 2013. Because of this change, you cannot switch users when you are logged into Enterprise Portal. If you want to log in to Enterprise Portal as a different user, you must start the browser when logged in as that user or by using the *runas* command. For more information, see ["Sign in as Different User" menu option is missing in SharePoint Server 2013](http://support.microsoft.com/kb/2752600).

**Search Enterprise Portal Help**: SharePoint 2013 does not support search in Help content that is disk-based. The application only supports searching through Help content that is hosted online or on a web site. Users can still access Enterprise Portal Help by pressing F1 or by using the table of contents, but they cannot search the .cab-based system.

## Permissions issues

Most installation issues for Enterprise Portal result from insufficient permissions by the person performing the installation. Verify that you have the appropriate permissions to perform the installation. If this list does not help you identify and resolve the problem, view the Windows Event Logs for more information about the error you are receiving.

  - Membership in the **System administrator** role in Microsoft Dynamics AX

  - Membership in the **Administrators** group in Windows on the Web server

  - Membership in the **Farm Administrators** group in SharePoint

  - Membership in the **dbcreator** role on the instance of SQL Server that is used for SharePoint

  - Membership in the **WSS\_Content\_Application\_Pools** database role in the SharePoint\_Config database

We also recommend that you follow these steps before you deploy Enterprise Portal to verify that you have the correct permissions for the installation.

1.  Verify that you can open SharePoint Central Administration on the Enterprise Portal server.

2.  Verify that you have the appropriate permissions to create sites by using SharePoint Central Administration to create a SharePoint team site.

3.  Verify that you can browse the team site without prompts and resolve the URL without proxy errors or other problems.

4.  If you intend to deploy or configure Enterprise Portal at a command prompt, verify that you can start the SharePoint Management Shell.


> [!TIP]
> <P>By default, when you install SharePoint, the system creates a Web application on port 80. Microsoft Dynamics AX Setup deploys an Enterprise Portal site on the port 80 Web application unless you specify a different Web application. If you do not intend to deploy Enterprise Portal on the default port-80 Web application, you must use SharePoint Central Administration to create a new Web application before you install Enterprise Portal by using Setup. Also note, if you create a new Web application, you must specify the Business Connector proxy account as the application pool account in the <STRONG>Configurable</STRONG> list. If necessary, register a new managed account with SharePoint.</P>



## Error installing Enterprise Portal: Access denied

If Enterprise Portal could not be installed and the setup summary and the Microsoft Dynamics AX setup log displayed an access denied message, it might mean that you do not have permission to overwrite an existing site collection on the port 80 web application. If you are a member of the farm administrator group in SharePoint, you can use SharePoint Central administration to delete the existing site collection on the port 80 web application. After you delete the site collection, restart IIS (Start \> Run, type iisreset, and press Enter). After IIS restarts, try installing Enterprise Portal again.

## Installing to a site that uses a host header fails

If you attempt to install Enterprise Portal on an existing IIS site that is already configured to use a host header, the installation fails, unless you create a BackConnectionHostNames registry entry.

## Setup fails and the IIS application pool crashes when you attempt to install Enterprise Portal

When installing Enterprise Portal and Role Centers, you may encounter the following error: “An error occurred when Setup was creating a new site. The underlying connection was closed: An unexpected error occurred on a receive. An existing connection was forcibly closed by the remote host.” This error occurs if SQL Server Analysis Management Objects (AMO) has not been installed on the Enterprise Portal server. To download AMO, download the **Microsoft SQL Server 2008 R2 Analysis Management Objects** package, which is included in the [Microsoft SQL Server 2008 R2 Feature Pack – June 2010](http://www.microsoft.com/downloads/en/details.aspx). After you install AMO, restart IIS and attempt to install Enterprise Portal again.

## SharePoint Search stops working after you install Enterprise Portal

If you install Enterprise Portal on a server that hosts a SharePoint Team site, the default Search settings for the team site can change. SharePoint Search returns errors. To restore Search for the SharePoint team site, reset the SharePoint Search settings to their default values.

1.  Open the **Search Settings** page. By default, the URL is: http://\< *server\_name*\>/\_layouts/enhancedSearch.aspx

2.  Under **Site Collection Search Center**, click **Do not use custom scopes**.

3.  Under **Site Collection Search Dropdown Mode**, click **Do not show scopes dropdown, and use contextual scope**.

4.  Under **Site Collection Search Results Page**, click **/\_layouts/OSSSearchResults.aspx**, and then click **OK**.

## Multiple portals on a server

If you intend to deploy multiple Enterprise Portals on the same server and those portals will connect to different Application Object Servers, then you must update the web.config file. For more information, see [Install multiple Enterprise Portals on the same server](install-multiple-enterprise-portals-on-the-same-server.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


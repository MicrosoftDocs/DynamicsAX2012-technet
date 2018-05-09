---
title: Move an Enterprise Portal deployment to a different server
TOCTitle: Move an Enterprise Portal deployment to a different server
ms:assetid: c58183aa-8bf0-4abf-acca-bf2cd89b263c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352315(v=AX.60)
ms:contentKeyID: 36687944
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Move an Enterprise Portal deployment to a different server 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to move an Enterprise Portal for Microsoft Dynamics AX deployment from one server to another. Moving an Enterprise Portal deployment across servers is common for businesses or organizations that perform development and testing in one environment, and then move the deployment into a production environment. To move specific Enterprise Portal objects to a different server, see [Checklist: Deploy Enterprise Portal changes to a different server](checklist-deploy-enterprise-portal-changes-to-a-different-server.md).

## Before you begin

For the purpose of this discussion, *Server1* is the name of the current Enterprise Portal server and *Server2* is the name of the new or target server. Before you begin, you must complete the following tasks.

1.  Use Setup to deploy the Microsoft Dynamics AX client on *Server2*. For more information, see [Install the Microsoft Dynamics AX client](install-the-microsoft-dynamics-ax-client.md).

2.  Use Setup to install Enterprise Portal on *Server2*. In Setup, on the **Configure a Web site for Enterprise Portal** page, clear the **Create Web site** option. You will create the site by using the procedure in this topic. For more information, see [Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md).

## Move an Enterprise Portal deployment to a different server

Use the following procedure to move an Enterprise Portal deployment to a different server.

1.  Open a Command Prompt window on *Server1* and locate the following directory. If you are using SharePoint 2013, change ‘14’ in the following path to ‘15’:
    
    C:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\BIN

2.  At the command prompt, type: Backup-SPSite http://Server1/sites/DynamicsAX -Path c:\\axep.bak
    
    For this command, replace Server1 with the computer name of *Server1*.

3.  Copy the axep.bak file from C:\\ on *Server1* to C:\\ on *Server2*.

4.  Use the Microsoft Dynamics AX 2012 Server Configuration utility to verify that *Server2* is configured to communicate with the same Microsoft Dynamics AX database as *Server1*.

5.  Use the Microsoft Dynamics AX client to verify that the URL is available. Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Web sites**.

6.  Verify that no sites in the **Web sites** form use the http://*Server2*/sites/DynamicsAx URL.
    

    > [!IMPORTANT]
    > <P>If a site on Server2 does use the http://<EM>Server2</EM>/sites/DynamicsAx URL you must configure the site to use a different URL or delete the site because the Enterprise Portal deployment you are currently moving from <EM>Server1</EM> to <EM>Server2</EM> will use this URL.</P>



7.  Open a Command Prompt window on *Server2* and locate the following directory. If you are using SharePoint 2013, change ‘14’ in the following path to ‘15’:
    
    C:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\BIN

8.  At the command prompt, type: Restore-SPSite http://Server2/sites/DynamicsAX -Path c:\\axep.bak
    
    For this command, replace Server2 with the computer name of *Server2*.

9.  On *Server2*, click the **Register site** button on the **Web sites** form.

10. In the **Internal URL** and **External URL** fields, enter http://*Server2*/sites/DynamicsAx

11. In the **Type** field, select **Full (Web parts and site templates)**.

12. Verify that the **Default Enterprise Portal site** and the **Website used to display Role Centers in the client** fields show the correct URL.

13. On the **General** tab, select **Company independent** if this site should host data for multiple legal entities in Microsoft Dynamics AX. Or, clear the option if this site should host data for a specific legal entity in Microsoft Dynamics AX.

14. Open a web browser and enter http://*Server2*/sites/DynamicsAx in the **Address** bar to verify that the Enterprise Portal deployment is available.

15. Configure user access to the site. For more information, see [Enable users to access Enterprise Portal](enable-users-to-access-enterprise-portal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


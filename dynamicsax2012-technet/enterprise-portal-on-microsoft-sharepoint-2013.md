---
title: Enterprise Portal on Microsoft SharePoint 2013
TOCTitle: Enterprise Portal on Microsoft SharePoint 2013
ms:assetid: 5906047d-4a98-4e86-9f2d-f405e3d69b22
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn169057(v=AX.60)
ms:contentKeyID: 53378097
ms.date: 08/26/2014
mtps_version: v=AX.60
---

# Enterprise Portal on Microsoft SharePoint 2013 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Enterprise Portal is supported on SharePoint 2013. This topic describes prerequisites for running Enterprise Portal on either Microsoft SharePoint Foundation 2013 or Microsoft SharePoint Server 2013. You must complete the steps in this topic before you install Enterprise Portal. Known issues about Enterprise Portal on SharePoint 2013 are described later in this topic.


> [!IMPORTANT]
> <P>Currently SharePoint 2013 is supported only with Microsoft Dynamics AX 2012 R2.</P>



## Install required hotfixes on R2 servers

1.  You must install one of the following updates if you plan to run Enterprise Portal on either Microsoft SharePoint Foundation 2013 or Microsoft SharePoint Server 2013 (required for Microsoft Dynamics AX 2012 R2 or earlier; not required for Microsoft Dynamics AX 2012 R3). Choose an update that matches the SharePoint version on which you plan to deploy Enterprise Portal.
    
    [Update for Microsoft SharePoint Enterprise Server 2013 (KB2767999)](http://go.microsoft.com/fwlink/?linkid=290893)
    
    [Update for Microsoft SharePoint Foundation 2013 (KB2768000)](http://go.microsoft.com/fwlink/?linkid=286742)

2.  After you install an update, you must run the SharePoint 2013 Products Configuration wizard.

3.  Download and install the Microsoft Dynamics AX 2012 R2 [setup hotfix (KB2830441)](http://go.microsoft.com/fwlink/?linkid=294676) (required for Microsoft Dynamics AX 2012 R2 or earlier; not required for Microsoft Dynamics AX 2012 R3).

4.  Download and install the Microsoft Dynamics AX 2012 R2 [claims-mode authentication hotfix (KB2824690)](http://go.microsoft.com/fwlink/?linkid=294677) (required for Microsoft Dynamics AX 2012 R2 or earlier; not required for Microsoft Dynamics AX 2012 R3).

5.  Reboot the server and then install Enterprise Portal. For more information about how to install Enterprise Portal or Enterprise Search, see [Install Enterprise Portal](install-enterprise-portal.md) and [Install Microsoft Dynamics AX Enterprise Search](install-microsoft-dynamics-ax-enterprise-search.md).

## Known issues and updates

The following changes in Enterprise Portal functionality or behavior result when you run on SharePoint 2013.

**Deprecated SharePoint features**: See [Changes from SharePoint 2010 to SharePoint 2013](http://go.microsoft.com/fwlink/?linkid=306200) for a list of features that were deprecated in SharePoint 2013.

**Unable to install or configure Enterprise Portal**: Installation can fail if the Claims to Windows Token Service is not running in SharePoint Central Administration. The Setup log file includes the following error: Server was unable to process request. ---\> Could not retrieve a valid Windows identity. ---\> The message could not be dispatched because the service at the endpoint address 'net.pipe://localhost/s4u/022694f3-9fbd-422b-b4b2-312e25dae2a2' is unavailable for the protocol of the address.

To resolve this issue, in **SharePoint Central Administration**, click **System Settings** \> **Manage services on server**. Start the Claims to Windows Token Service and then install Enterprise Portal.

**Experience all that SharePoint 2013 has to offer \> Missing Site Templates**: After you install Enterprise Portal on SharePoint 2013 you see a message bar that says, “Experience all that SharePoint 2013 has to offer.” If you click the link provided, you see an error that states, “Missing Site Templates”. You can ignore this message. To retain important functionality, features, and design, Enterprise Portal uses the SharePoint 2010 mode provided by SharePoint 2013.

**Search Scope**: The SharePoint 2013 feature called result sources replaces SharePoint 2010 search scopes. For more information, see [Understanding result sources for search in SharePoint Server 2013](http://go.microsoft.com/fwlink/?linkid=306201) and [Configure result sources for search in SharePoint Server 2013](http://go.microsoft.com/fwlink/?linkid=306202).

**Search Enterprise Portal Help**: SharePoint 2013 does not support search in Help content that is disk-based. The application only supports searching through Help content that is hosted online or on a web site. Users can still access Enterprise Portal Help by pressing F1 or by using the table of contents, but they cannot search the .cab-based system.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Map a network drive to the SharePoint 2013 files for online stores
TOCTitle: Map a network drive to the SharePoint 2013 files for online stores
ms:assetid: 9c9a0a16-3545-4cdb-912b-ab8818d8a231
ms:mtpsurl: https://technet.microsoft.com/library/Dn151472(v=AX.60)
ms:contentKeyID: 53098976
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Map a network drive to the SharePoint 2013 files for online stores 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can map a network drive to access files that Microsoft SharePoint Server 2013 uses to support an Microsoft Dynamics AX 2012 R2 Retail online store. First, you must make sure that you have [Web Distributed Authoring and Versioning (WebDAV)](http://go.microsoft.com/fwlink/?linkid=324007&clcid=0x409) installed and running on your computer.

These procedures work for Windows Server operating systems. For information about mapping a drive on other operating systems, see [How to: Map a network drive to the SharePoint 2013 Master Page Gallery](http://msdn.microsoft.com/en-us/library/jj733519.aspx).


> [!NOTE]
> <P>These procedures must be performed by a user who has full permissions to the SharePoint online store. This user must be logged into the site before mapping the drive. To log into the site, open the Site Settings page in a browser window. The URL for the Site Settings page for your installation typically resembles the following:</P>
> <P>http://&lt;your-server-name&gt;:40003/sites/RetailPublishingPortal/_layouts/15/Settings.axpx</P>



### To verify that WebDAV is installed and running

1.  Click **Start**, **Administrative Tools**, and then click **Services**.

2.  Scroll through the list of services and verify that the **WebClient** service is started.

3.  If the **WebClient** service name is not present you must install the **Desktop Experience** Windows feature.
    
    ### To install Windows Desktop Experience
    
    1.  Click **Start**, **Administrative Tools**, and then click **Server Manager**.
    
    2.  Right-click on the **Features** node and then click **Add Features**.
    
    3.  In the **Add Feature Wizard**, check **Desktop Experience**.
    
    4.  Click **Next** and install the feature. The installation may take some time.

4.  Right-click the **Web Client** service and then click **Properties**.

5.  On the **General** tab, set the **Startup Type** to **Automatic**.

### To map a network drive

1.  Open Windows Explorer.

2.  Right-click **My Computer** and then click **Map Network Drive…**.

3.  Enter the path of the online store publishing portal in the **Folder** box. The path typically resembles the following:
    
    http://\<your-server-name\>:40003/sites/RetailPublishingPortal

4.  Click **Finish**.
    
    The drive appears in the list under **Computer**. The folders containing the files that SharePoint uses are listed when you expand the node for the drive. Master pages are listed in the **\_Catalogs** folder, which is a hidden folder.
    
    ### To view hidden folders
    
    1.  Click **Start**, **Control Panel**, and then click **Folder Options**.
    
    2.  On the **View** tab, select **Show hidden files, folders, and drives**.
    
    3.  Clear **Hide protected operating system files**.
    
    4.  Click **OK** to close the **Folder Options** window.


> [!TIP]
> <P>If the hidden folders are not visible, you can type the drive letter and specify the _Catalogs folder directly in an Explorer or a Run window. For example, if your network drive is mapped to <STRONG>Z:</STRONG>, you can click <STRONG>Start</STRONG>, <STRONG>Run</STRONG>, and then type Z:\_Catalogs.</P>



## See also

[SharePoint 2013 development overview](http://msdn.microsoft.com/en-us/library/jj164084.aspx)

[How-tos for SharePoint 2013](http://msdn.microsoft.com/en-us/library/jj901636.aspx)

  



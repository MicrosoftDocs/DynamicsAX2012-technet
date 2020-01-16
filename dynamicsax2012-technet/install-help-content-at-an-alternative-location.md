---
title: Install Help content at an alternative location
TOCTitle: Install Help content at an alternative location
ms:assetid: 51d9dc28-1b6d-4949-adbc-055d0d6db756
ms:mtpsurl: https://technet.microsoft.com/library/JJ735269(v=AX.60)
ms:contentKeyID: 49693270
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install Help content at an alternative location 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Help server folder on the file system contains both system files and content files. The location of this folder is a fixed parameter in Microsoft Dynamics AX. However, you can store the content at a different location by using the virtual directory feature in Internet Information Services (IIS).

The Microsoft Dynamics AX setup utility installs Help server files at C:\\inetpub\\wwwroot\\DynamicsAX6HelpServer. Help content files are located in the Content folder under this directory. The following procedure shows how to move the Content folder to another location on the file system, so that Microsoft Dynamics AX can continue to access the folder.

1.  On the Help server computer, create a content folder that is not located under the default directory for the Help server, C:\\inetpub\\wwwroot\\DynamicsAX6HelpServer. In this example, the new folder is D:\\content.

2.  Move the Help files that are currently under C:\\inetpub\\wwwroot\\DynamicsAX6HelpServer\\Content so that they are under D:\\content. Delete the original Content folder after it is empty.
    

    > [!IMPORTANT]
    > <P>Do not put any configuration files in the new folder. This folder should contain only subfolders and content-related files, such as HTML, JavaScript, or image files.</P>



3.  Give the domain account for the Microsoft Dynamics AX administrative user **Read & execute**, **List folder contents**, **Read**, and **Write** permissions to the new folder. Additionally, give the local IIS user group, IIS\_IUSRS, **Read & execute**, **List folder contents**, and **Read** permissions to the folder.

4.  Click **Start** \> **Control Panel** \> **Indexing Options** \> **Modify**, and add the new folder as an indexed location.

5.  Click **Start** \> **Administrative Tools** \> **Internet Information Services (IIS) Manager** to open IIS Manager.

6.  In the navigation pane, expand the nodes to display C:\\inetpub\\wwwroot\\DynamicsAX6HelpServer.

7.  Right-click **DynamicsAX6HelpServer**, and then select **Add Virtual Directory**.

8.  In the **Add Virtual Directory** window, in the **Alias** field, type **Content**. The directory tree that the Help server accesses when it retrieves content is restored, in virtual form.

9.  In the **Physical path** field, type the path of the new folder, D:\\content. Alternatively, you can navigate to the folder. Then click **OK**, and close IIS Manager.

10. Under C:\\inetpub\\wwwroot\\DynamicsAX6HelpServer, locate the web.config file, and configure this file for the new content location. Open web.config in a text editor, and locate the **basePath** attribute. After the **basePath** attribute, add a new **contentPath** attribute that has the same format, and that contains the new content folder. In this example, the XML element begins as follows.
    
    \<dynamicsHelpConfig basePath="C:\\inetpub\\wwwroot\\DynamicsAX6HelpServer" contentPath="D:\\content"....

11. To trigger indexing of the new folder, click **Start** \> **Administrative Tools** \> **Services**, and then restart the Windows Search Service. The Help system should work correctly after indexing is completed.

  



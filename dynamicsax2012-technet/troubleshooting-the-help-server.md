---
title: Troubleshooting the Help server
TOCTitle: Troubleshooting the Help server
ms:assetid: 101d572f-df9f-4bce-b3d0-aecc5d222fb3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751351(v=AX.60)
ms:contentKeyID: 35132547
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Troubleshooting the Help server [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following sections provide information to help you troubleshoot issues that you may encounter when you install or use the Help server.

## Help topics are not displayed in the Help viewer

If Help topics are not displayed in the Help viewer, the Windows Search Service may not be indexing the folder that contains the Help content. Follow these steps to configure the Windows Search Service to index the Help content.


> [!NOTE]
> <P>The Windows Search Service may require several hours to index the Help content.</P>



1.  Open the Windows **Indexing Options** feature. Click **Start** \> **Control Panel**. In the search box, enter **indexing options**. Then click the **Indexing Options** link.

2.  In the **Indexing Options** window, verify that the Help content folder, \\\<*WebSitePhysicalDirectory*\>\\DynamicsAX6HelpServer\\content, appears in the list of locations that are indexed.

3.  If the folder is not listed, follow these steps:
    
    1.  Click **Modify**.
    
    2.  In the **Indexed Locations** window, expand the tree view, and then locate the content folder that is mentioned in step 2 of this procedure. Select the check box for that folder.
    
    3.  Click **OK** to close the **Indexed Locations** window.

## Links to the World Wide Web are blocked

To display Help topics, the Microsoft Dynamics AX client relies on the instance of Internet Explorer that is installed locally. If you are in a computing environment that uses a proxy server to access the World Wide Web, you must configure proxy settings for Internet Explorer on each client computer. Otherwise, you cannot view Help content that is hosted on the web. Incorrect proxy settings cause a browser error when you try to follow links that point outside your local area network (LAN).

To access the web from a Microsoft Dynamics AX client that is hosted on a LAN, follow these steps to change the Internet Explorer settings for each user.

1.  On the computer where the Microsoft Dynamics AX client is installed, start Internet Explorer.

2.  Click **Tools** \> **Internet options**.

3.  Click the **Connections** tab.

4.  Click **LAN settings**.

5.  Select **Use a proxy server for your LAN**.

6.  In the **Address** field, enter the address of the web proxy server. Then click **OK**.
    
    For a deployment that has many clients and users, it may be more practical to push these proxy settings to the browsers by using Group Policy settings in Active Directory Domain Services.

## Search results pages do not load over RDP

To display Help topics, the Microsoft Dynamics AX client relies on the instance of Internet Explorer that is installed locally. If you access a client system by using a Remote Desktop Protocol (RDP) file, the trust relationship between the client and the Help server must be correctly configured in Internet Explorer on the client system. Incorrect configuration causes error messages in the browser and prevents access to search results in the Help viewer.

To add the Help server as a trusted site, follow these steps to change the Internet Explorer settings for each user.

1.  On the computer where the Microsoft Dynamics AX client is installed, start Internet Explorer.

2.  Click **Tools** \> **Internet options**.

3.  Click the **Security** tab.

4.  Click **Trusted sites**.

5.  Click **Sites**.

6.  Clear the **Require server verification** check box.

7.  In the **Add this website to the zone** field, enter the URL of the Help server. Click **Add**.

8.  Click **Close** and then **OK**.

## Accessing Help causes redundant web security checks

If a user encounters repeated and redundant website security checks when he or she opens the Help viewer, you can resolve the problem by deleting the user’s Windows profile.


> [!NOTE]
> <P>A user profile can be deleted only if the user who owns it is logged off from Windows.</P>



Follow these steps to remove a user profile.

1.  Click **Start** \> **Computer** \> **System properties** \> **Advanced system settings**.

2.  In the **System Properties** window, in the **User Profiles** section, click **Settings**.

3.  Select the user profile, and then click **Delete**.

The next time that the user logs on to Windows, the security prompt should occur one time and then never again.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Install the help server
TOCTitle: Install the help server
ms:assetid: 03749eca-de34-4fa7-8077-9cd2365da6ab
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751342(v=AX.60)
ms:contentKeyID: 35132527
ms.date: 04/13/2015
mtps_version: v=AX.60
---

# Install the help server 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to install the Help server and Help files. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages will vary based on the components that you are installing.


> [!NOTE]
> <P>To install the most recent help updates, see the blog post <A href="http://blogs.msdn.com/b/axsupport/archive/2015/02/02/ax-content-help-server-update-for-ax2012-r3-is-available-easier-to-find-and-install.aspx">AX Content: Help Server update for AX2012 R3 is available, easier to find and install</A>.</P>
> <P>If you are upgrading Help server between Microsoft Dynamics AX 2012, Microsoft Dynamics AX 2012 Feature Pack, and Microsoft Dynamics AX 2012 R2, you should review <A href="scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md">Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3</A>.</P>



1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the initial wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Help Server**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md).
    

    > [!NOTE]
    > <P>Validation errors can be resolved through the <STRONG>Prerequisite validation results</STRONG> page only if you are installing the Help server on a supported server operating system. If you are installing on an unsupported client operating system for demonstration or development purposes, you must supply missing prerequisites manually.</P>

    
    When no errors remain, click **Next**.

8.  On the **Specify a location for configuration settings** page, specify whether you want the help server to access configuration information from the registry on the local computer or from a shared configuration file. If you select to use a shared configuration file, you must enter the network location of the file. Click **Next**.

9.  On the **Connect to an AOS instance** page, enter the name of the computer that is running the Application Object Server (AOS) instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this screen is not displayed. Subsequent installations on this computer reuse the existing AOS connection.</P>



10. The Help Server must be installed on a 64-bit operating system. When you install Microsoft Dynamics AX components on a 64-bit system, the **Select a file location** page is displayed. Use this page to select the location where 32-bit versions of Microsoft Dynamics AX files should be installed, and then click **Next**.

11. On the **Select a display language** page, select a language and click **Next**.

12. On the **Specify a location for configuration settings** page, indicate whether client and server configuration settings should be stored locally or in a shared configuration file on the network. If you select the shared configuration, enter the network location of the file. Click **Next**.

13. On the **Connect to AOS instance** page, provide the name of the AOS server that the Help server will be using. You can optionally specify the AOS instance name, the AOS TCP/IP port number, and the services WSDL port. Click **Next**.

14. On the **Configure a Web site for Help Server** page, select the web site that you have chosen to host the Help server. Verify that the location of the physical directory for the web site is displayed. Click **Next**.

15. On the **Specify the Help Server account** page, enter a domain user account and password. This account must be the same as the .NET Business Connector proxy account for the AOS, and it must be a user in Microsoft Dynamics AX. This should be a service account that does not expire. Click **Next**.

16. On the **Language and content selection** page, select the Help languages and content types to install. EN-US must be installed, and is checked by default. Click **Next**.
    

    > [!TIP]
    > <P>To add additional languages or content later, obtain the necessary MSI files and run Setup again.</P>



17. On the **Prerequisite Validation** page, resolve any errors. When no errors remain, click **Next**.

18. On the **Ready to install** page, click **Install**.

19. After the installation is complete, click **Finish** to close the wizard.

After the Microsoft Dynamics AX Help files are installed, they must be indexed by Windows Search Service before you can view them. Depending on system load and the number of files, it may take up to an hour for indexing to finish.

## See also

[Set Help system parameters](set-help-system-parameters.md)

  



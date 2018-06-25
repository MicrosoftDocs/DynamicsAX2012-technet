---
title: Install web services on IIS
TOCTitle: Install web services on IIS
ms:assetid: 83827f45-6e85-4ec4-b673-133d284b2763
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731848(v=AX.60)
ms:contentKeyID: 35132705
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Install web services on IIS [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes installation of the Microsoft Dynamics AX web services on Internet Information Services (IIS).


> [!NOTE]
> <P>Web services on IIS is an optional component. The Application Object Server (AOS) is the Windows Communication Foundation (WCF) service host for Microsoft Dynamics AX services. The AOS-hosted services are available to users and applications across an intranet. To consume services over the Internet, you must host services on Internet Information Services (IIS). Skip this procedure if you do not need to expose the Microsoft Dynamics AX services over the Internet.</P>



## Before you install the Web services on IIS

Verify that the following steps are completed before you install the Microsoft Dynamics AX web services on IIS:

  - On the computer where you will install the web services, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).
    

    > [!WARNING]
    > <P>Do not install web services on IIS on a server that is a network domain controller.</P>



  - Create a domain account that will be used as the Business Connector proxy account. For more information, see [Create service accounts](create-service-accounts.md).

  - Make sure that you have the required permissions to install the web services. For more information, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

## Install and configure the Web Server (IIS) Role

Use the following steps to verify that the Web Server role is configured properly:

1.  When you ran the prerequisite validation utility in the preceding section, it configured the Web Server role. However, the prerequisite validation utility does not install the ASP.NET role service. Use the following steps to install the ASP.NET role service. For more information about role services, see [Available Role Services by Category](http://technet.microsoft.com/en-us/library/cc753473.aspx).
    
      - Start Server Manager. Expand the **Server Manager (computer\_name)** node. Right-click **Web Server (IIS)**, and then click **Add Role Services**.
    
      - On the **Select Role Services** dialog, expand the **Web Server (Installed)** \> **Application Development (Installed)** node, and then select **ASP.NET**. Click **Next** and step through the wizard pages. Restart the server.

2.  Create a website that Setup will use to install the Microsoft Dynamics AX web services. You can create a new website or use an existing one, such as Default Web Site on IIS. See the IIS documentation for instructions about how to create a new website.
    

    > [!TIP]
    > <P>For ease of administration, we recommend that you create a new website before installing Microsoft Dynamics AX web services.</P>



## Install the web services on IIS

Use this procedure to install the Microsoft Dynamics AX web services on IIS. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages vary based on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the initial wizard pages.

3.  If the setup support files have not yet been installed, the **Select a file location** page is displayed. The setup support files are required for installation. Provide a file location or accept the default location and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Web services on IIS**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where 32-bit versions of Microsoft Dynamics AX files should be installed and then click **Next**.

9.  On the **Connect to an AOS instance** page, enter the name of the computer that is running the AOS instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the Web Services Description Language (WSDL) port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on this computer reuse the existing AOS connection.</P>



10. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account used by the .NET Business Connector. Click **Next**.

11. On the **Configure IIS for Web services** page, accept default values or provide information for the website, application pool, and virtual directory. Setup will create a virtual directory and an application pool for the Microsoft Dynamics AX web services under the selected website. The application pool will run as the .NET Business Connector proxy user that you entered in the previous step.
    

    > [!IMPORTANT]
    > <P>You must restart IIS after Setup installs the web services. Select <STRONG>Restart IIS after installation is complete</STRONG> to automatically restart IIS.</P>

    
    Click **Next** to continue.

12. On the **Specify an AOS account** page, provide the service accounts for the AOS instances that you will use with web services on IIS. For more information about AOS accounts, see, [Create service accounts](create-service-accounts.md).
    
    Click **Next** to continue.

13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is complete, click **Finish** to close the wizard.

## After you install the Web services on IIS

This section provides instructions for how to configure and test web services on IIS.

## Configure IIS

For IIS 7.0, use the following steps to configure the application pool that is associated with Microsoft Dynamics AX web services. This step is required to set the correct version of the .NET Framework.

1.  In Server Manager, Expand the **Server Manager \> Roles \> Web Server (IIS)** node and then click **Internet Information Services (IIS) Manager**.

2.  In the **Connections** pane, expand the node for your server name and then click **Application Pools**.

3.  In the **Application Pools** pane, right-click the application pool that is associated with the Microsoft Dynamics AX web services and click **Basic Settings…**.

4.  In the **Edit Application Pool** dialog box, select .NET Framework 4.0 or a later version, such as V4.0.30319. Select **Integrated** from the **Managed pipeline mode** list. Notice that the **Start application pool immediately** option is selected. Click **OK** to return to Server Manager.

5.  Restart the server.

## Verify the website registration in Microsoft Dynamics AX

Use the following steps to register the website in Microsoft Dynamics AX.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Web sites**.

2.  On the **Web sites** form, verify that the website was created and has appropriate values for the **Name**, **Virtual directory share path**, **Description**, and **URL** fields. The default name is computername-Default Web Site-MicrosoftDynamicsAXAif60. The default URL is http://computername:8101/MicrosoftDynamicsAXAif60. The default share path for the virtual directory is \\\\computername\\MicrosoftDynamicsAXAif60.

3.  Click **Validate**. Verify that the Infolog dialog confirms:
    
      - The website is configured properly.
    
      - You can access the computer and the website.

For information about how to add or configure websites, see [Add or configure websites](add-or-configure-websites.md).


> [!NOTE]
> <P>When you install web services on IIS, a record for the new website is added to AifWebsites table. If you uninstall web services on IIS, this record is not deleted from the table. This record may cause a warning to be displayed if you reinstall web services on IIS. You can manually delete the record from the AifWebsites table or simply ignore the warning.</P>



## Create an enhanced integration port

For information about managing integration ports, see [Services and AIF operations](services-and-aif-operations.md).

## See also

[Walkthrough: Exchanging documents by using the HTTP adapter](walkthrough-exchanging-documents-by-using-the-http-adapter.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


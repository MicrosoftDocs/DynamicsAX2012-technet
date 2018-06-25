---
title: Install the synchronization service for Microsoft Project Server
TOCTitle: Install the synchronization service for Microsoft Project Server
ms:assetid: b665dd6c-1d1f-4002-b69d-03e2006ea52d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362048(v=AX.60)
ms:contentKeyID: 35132825
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install the synchronization service for Microsoft Project Server [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Project synchronization service synchronizes project data in Microsoft Dynamics AX with data in Microsoft Project Server.

To use this functionality, you must install both the synchronization proxy and the synchronization service. You can install the synchronization service and the synchronization proxy at the same time. This topic explains only how to install the synchronization service.

If Project Server uses a Microsoft Database Engine (MSDE) database or a Microsoft SQL Server Express Edition database, install the synchronization service on the computer that runs Project Server.

When you install the synchronization service, Setup configures a message queue for the service. Setup also installs and starts the synchronization service.

## Before you install the synchronization service

Complete the following tasks before you install the synchronization service:

  - On the computer where you are installing this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - Install the Microsoft Dynamics AX databases and Application Object Server (AOS) in the environment.

  - Configure a domain account that the synchronization service can run as. For more information, see [Create service accounts](create-service-accounts.md).

## Install the synchronization service

Use the following procedure to install the synchronization service. If you install other Microsoft Dynamics AX components at the same time, the installation screens vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Synchronization service for Microsoft Project Server**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing the synchronization service on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want 32-bit versions of Microsoft Dynamics AX files to be installed, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want the synchronization service to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that runs the AOS instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



11. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by .NET Business Connector. Click **Next**.

12. On the **Enter the password for the service account** page, enter the account information for the synchronization service. Click **Next**.

13. On the **Connect to a message queue** page, specify whether you want to create a new message queue or connect to an existing message queue.
    
      - If you want to create a new queue, Setup creates a private queue by default. Private queues can be accessed only from the local computer. Select **Make this a public queue** to allow other computers to access the queue.
    
      - If you want to connect to an existing queue, enter the queue address.
    
    Click **Next**.

14. On the **Specify service accounts for synchronization message queues** page, enter the service accounts that communicate through message queues. You must provide a domain account that is used by the Project Server eventing service, and the service account of at least one AOS instance. Otherwise, Setup cannot configure the correct permissions. Click **Next**.

15. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

16. On the **Ready to install** page, click **Install**.

17. After the installation is completed, click **Finish** to close the wizard.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


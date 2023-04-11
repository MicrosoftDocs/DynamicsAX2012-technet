---
title: Install the synchronization proxy for Microsoft Project Server
TOCTitle: Install the synchronization proxy for Microsoft Project Server
ms:assetid: 1b3a19a1-cfbf-4bfe-85cb-b66ae4c615e7
ms:mtpsurl: https://technet.microsoft.com/library/Dd309614(v=AX.60)
ms:contentKeyID: 35132566
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install the synchronization proxy for Microsoft Project Server 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The synchronization proxy for Microsoft Project helps support the synchronization of project data in Microsoft Dynamics AX with data in Microsoft Project Server.

To use this functionality, you must install both the synchronization proxy and the synchronization service. You can install the synchronization service and the synchronization proxy at the same time. This topic explains only how to install the synchronization proxy.

The synchronization proxy uses Message Queuing to connect to Project Server and Microsoft Dynamics AX. You must install the synchronization proxy on the same computer as Project Server.

## Before you install the synchronization proxy

Complete the following tasks before you install the synchronization proxy:

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - Verify that you have the permissions that are required to install the synchronization proxy. For more information, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

## Install the synchronization proxy

Use this procedure to install the synchronization proxy. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Synchronization proxy for Microsoft Project Server**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want the synchronization proxy to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that runs the instance of Application Object Server (AOS) that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



11. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by .NET Business Connector. Click **Next**.

12. On the **Synchronization proxy/Message Queuing: Enter the service account information** page, enter the domain user account for the synchronization service, and then click **Next**.

13. On the **Connect to Microsoft Project Server** page, enter the name of the Project Server and the name of the database that is used for Project Server reporting. In the **Project web access URL** box, enter the URL of the website that is used to access Project Server.
    

    > [!NOTE]
    > <P>If the synchronization proxy must connect to multiple URLs for Project Server, use the first URL when you install the synchronization proxy. However, you must then uninstall and reinstall the synchronization proxy. When you reinstall the synchronization proxy, use a different URL. Uninstalling the proxy does not affect the proxy’s ability to synchronize with URLs that were specified during previous installations.</P>

    
    Click **Next**.

14. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

15. On the **Ready to install** page, click **Install**.

16. After the installation is completed, click **Finish** to close the wizard.

  



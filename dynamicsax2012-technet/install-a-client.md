---
title: Install a client
TOCTitle: Install a client
ms:assetid: 8211f4bd-180f-4a0b-b3d0-88f6dbfceda4
ms:mtpsurl: https://technet.microsoft.com/library/Aa834494(v=AX.60)
ms:contentKeyID: 35132703
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Install a client 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you install a Microsoft Dynamics AX client, the following components are included:

  - The Microsoft Dynamics AX interface that connects to an instance of Application Object Server (AOS)

  - The Microsoft Dynamics AX Configuration utility

You can access the Microsoft Dynamics AX Configuration utility from the **Administrative Tools** menu. On computers that run Windows 7, **Administrative Tools** is an item in Control Panel.

If you are installing many clients, we recommend that you install them from a file server and create a shared configuration file. For more information, see [Mass deployment of the Microsoft Dynamics AX Windows client](mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md).


> [!NOTE]
> <P>If you are upgrading clients between AX 2012, AX 2012 Feature Pack, AX 2012 R2, and AX 2012 R3, you should review <A href="scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md">Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3</A>.</P>



## Before you install a client

Complete the following tasks before you install a Microsoft Dynamics AX client.

  - Read [Client security and protection](client-security-and-protection.md) to learn about deployment best practices that can help secure the Microsoft Dynamics AX client.

  - On the computer where you plan to install the client, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - Install the Microsoft Dynamics AX databases and AOS in the environment.

## Install a client

Use this procedure to install a Microsoft Dynamics AX client by using the Setup wizard. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Client**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Select client preferences** page, select the display language that is used in the client, and specify whether you want Setup to create a desktop shortcut for the client. Additionally, select one of the following installation types:
    
      - **Business user** – The basic client is installed. This type of client installation is appropriate for most users.
    
      - **Developer** – The client, the developer workspace, and additional files that are required for development tasks are installed.
    
      - **Administrator** – The client and additional files that are required for administrative tasks are installed. Administrative tasks include the deployment of artifacts and the creation of users.
    
    Click **Next**.

10. On the **Specify a location for configuration settings** page, specify whether you want the client to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file.
    
    If you use a shared configuration file, client configuration settings are not stored locally, and the Microsoft Dynamics AX Configuration utility is not installed on the client computer.
    

    > [!NOTE]
    > <P>If you install the client at the same time as an AOS instance, this screen is not displayed, and configuration settings are saved in the registry automatically.</P>

    
    For more information about how to use a shared configuration file, see [Configure clients to use a shared configuration](configure-clients-to-use-a-shared-configuration.md).
    
    Click **Next**.

11. On the **Connect to an AOS instance** page, enter the name of the computer that runs the AOS instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services.
    
    If you do not know the name of the AOS instance or the port information, contact the Microsoft Dynamics AX administrator.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>

    
    Click **Next**.

12. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

13. On the **Ready to install** page, click **Install**.

14. After the installation is completed, click **Finish** to close the wizard.

  



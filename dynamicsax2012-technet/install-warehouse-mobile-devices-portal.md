---
title: Install Warehouse Mobile Devices Portal
TOCTitle: Install Warehouse Mobile Devices Portal
ms:assetid: 217803ec-a153-4ec4-ac90-0f1c5c3ccb4e
ms:mtpsurl: https://technet.microsoft.com/library/Dn741429(v=AX.60)
ms:contentKeyID: 62219713
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Install Warehouse Mobile Devices Portal 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Warehouse Mobile Devices Portal lets users complete tasks in a warehouse facility by using mobile devices. Warehouse Mobile Devices Portal includes a website that can be accessed by mobile devices, and therefore must be installed on a server that runs Internet Information Services (IIS).

Warehouse Mobile Devices Portal communicates with Microsoft Dynamics AX Application Object Server (AOS) by using Windows Communication Foundation (WCF) services.

If you’re using Warehouse Mobile Devices Portal with multiple companies in Microsoft Dynamics AX, you must install an instance of Warehouse Mobile Devices Portal for each company. Each instance must use a different service account. If the instances are installed on the same computer, they must use different port numbers.

## Before you install Warehouse Mobile Devices Portal

  - Create service accounts. You must create a separate service account for each instance of Warehouse Mobile Devices Portal that you plan to install. Each service account is used as the application pool identity for a Warehouse Mobile Devices Portal website. For more information, see [Create service accounts](create-service-accounts.md).

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install Warehouse Mobile Devices Portal

Use this procedure to install Warehouse Mobile Devices Portal. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Warehouse Mobile Devices Portal**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Configure the Warehouse Mobile Devices Portal** page, enter information in the following fields:
    
      - **Domain**, **User name**, and **Password** – Enter information about the service account that will run the application pool for the website. If you are installing multiple instances of Warehouse Mobile Devices Portal to support multiple companies in Microsoft Dynamics AX, each instance must use a different service account.
    
      - **Website port** – Enter the port number that the website will run on. If multiple instances of Warehouse Mobile Devices Portal are installed on the same computer, use a different port number for each instance.

9.  On the **Best practices checklist** page, read about each recommended best practice. Select the corresponding check box to indicate that an item is completed.
    

    > [!IMPORTANT]
    > <P>We strongly recommend that you follow the security best practices on this page. However, the list of best practices is included in Setup as a reminder only. You can continue the installation regardless of your selections on this page.</P>



10. On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

11. On the **Ready to install** page, click **Install**.

12. After the installation is completed, click **Finish** to close the wizard.

## After you install Warehouse Mobile Devices Portal

Complete the following tasks to complete the setup of Warehouse Mobile Devices Portal.

## Connect Warehouse Mobile Devices Portal to an AOS instance

You can install Warehouse Mobile Devices Portal on either the same server as the AOS instance that it connects to or a separate server.

By default, Warehouse Mobile Devices Portal is configured to connect to an AOS instance that is installed on the same computer. If the AOS instance is installed on a separate computer, you must modify the web.config file for the instance of Warehouse Mobile Devices Portal. Use this procedure to modify the web.config file.

1.  On the web server, open Internet Information Services (IIS) Manager.

2.  Right-click the website for an instance of Warehouse Mobile Devices Portal. Click **Explore** to open the physical folder for the site.

3.  Before you make any changes, we recommend that you make a copy of the web.config file. You can then easily revert to the previous version if you have to undo your changes.

4.  Open the web.config file in a text editor.

5.  Locate the net.tcp binding that is named NetTcpBinding\_WHSMobileDevicesService.

6.  Update the endpoint address that is associated with the net.tcp binding.

7.  Save and close the web.config file.

## Configure mobile devices

After you install Warehouse Mobile Devices Portal, complete the configuration procedures for mobile devices. For more information, see [Setting up mobile devices](setting-up-mobile-devices.md).

  



---
title: Install management utilities
TOCTitle: Install management utilities
ms:assetid: 09d85a6e-911b-4067-a512-9176b3aee44d
ms:mtpsurl: https://technet.microsoft.com/library/Gg751346(v=AX.60)
ms:contentKeyID: 35132534
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install management utilities 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Management utilities let you configure and manage Microsoft Dynamics AX components and artifacts. Use these utilities to deploy artifacts, such as reports and Web controls, from the metadata store.

## Before you install management utilities

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - Make sure that the Windows Update service is running on the computer where you will install this component.

## Install management utilities

Use this procedure to install the Microsoft Dynamics AX management utilities. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Management utilities**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify client configuration options** page, specify whether you want management utilities to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that runs the instance of Application Object Server (AOS) that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



11. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

12. On the **Ready to install** page, click **Install**.

13. After the installation is complete, click **Finish** to close the wizard.

  



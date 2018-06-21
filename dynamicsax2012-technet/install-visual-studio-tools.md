---
title: Install Visual Studio Tools
TOCTitle: Install Visual Studio Tools
ms:assetid: 03fbd4fd-0e0e-48d6-bf02-a0e600883a37
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309576(v=AX.60)
ms:contentKeyID: 35132529
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install Visual Studio Tools [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Visual Studio Tools integrate the development of Microsoft Dynamics AX with Microsoft Visual Studio. Developers can use these tools to create managed code that accesses X++ objects. Developers can also use the tools to create or modify controls for Enterprise Portal for Microsoft Dynamics AX and reports for Microsoft SQL Server Reporting Services. For more information about Visual Studio Tools, see [Visual Studio Development for Microsoft Dynamics AX](https://technet.microsoft.com/en-us/library/gg889157\(v=ax.60\)).


> [!NOTE]
> <P>If you want to have access to all the development capabilities, we recommend that you install the Microsoft Dynamics AX client on the same computer as Visual Studio Tools.</P>



## Before you install Visual Studio Tools

Complete the following tasks before you install Visual Studio Tools:

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - If Visual Studio is running, we recommend that you close it before you install Visual Studio Tools.

## Install Visual Studio Tools

Use this procedure to install Visual Studio Tools. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Visual Studio Tools**. When you select **Visual Studio Tools**, the **Management utilities** component is selected automatically. Click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want Visual Studio Tools to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that runs the instance of Application Object Server (AOS) that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



11. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

12. On the **Ready to install** page, click **Install**.

13. After the installation is completed, click **Finish** to close the wizard.

## See also

[Visual Studio Integration](https://technet.microsoft.com/en-us/library/gg889299\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Perform a single-computer installation
TOCTitle: Perform a single-computer installation
ms:assetid: f8fe95af-2975-403e-b918-5685faf4a9c4
ms:mtpsurl: https://technet.microsoft.com/library/Aa497063(v=AX.60)
ms:contentKeyID: 35133297
author: tonyafehr
ms.date: 05/09/2014
mtps_version: v=AX.60
---

# Perform a single-computer installation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the information in this topic to perform a single-computer installation of Microsoft Dynamics AX. Use this type of installation to install a complete Microsoft Dynamics AX system on a single computer for development, demonstration, or testing.

If you install by using the **Single-computer installation** option in Setup, default settings are used to configure all components. User names and passwords are the only input that is required. For more information about the components that are included in the single-computer installation option, see [Installation types](installation-types.md). For more information about individual components, see the corresponding topics in this guide.


> [!IMPORTANT]
> <P>We do not recommend that you perform a single-computer installation in a production environment. Use this type of installation only for development and testing.</P>



## Before you perform a single-computer installation

Prerequisites for all components that are included in the single-server installation must be installed before you can use this type of installation. On the computer where you plan to perform the installation, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md). For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

If you add Retail components to a single-computer installation, and the computer is a primary domain controller, the operating system must be Windows Server 2008 R2 or a later release.


> [!NOTE]
> <P>Reports and online analytical processing (OLAP) cubes may display errors if the computer is not connected to a domain.</P>



## Perform a single-computer installation

This procedure describes how to install Microsoft Dynamics AX for demonstration or development by using the **Single-computer installation** option in Setup.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Single-computer installation**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Specify an AOS account** page, select whether you want to use the Network Service account of the local computer or a domain account to run the Application Object Server (AOS) service. Click **Next**.

8.  On the **Specify Business Connector proxy account information** page, enter the name and password for the proxy account that is used for .NET Business Connector. Click **Next**.

9.  On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

10. On the **Ready to install** page, click **Install**.

11. After the installation is completed, click **Finish** to close the wizard.


> [!NOTE]
> <P>If you install Help Server at the same time as other Microsoft Dynamics AX components, the Help Server installation may fail. In the Setup log, you see the following error: “Component installation task stopped due to an error.” To resolve this issue, uninstall and then reinstall the Help Server component.</P>


  



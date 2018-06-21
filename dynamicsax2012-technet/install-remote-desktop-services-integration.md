---
title: Install Remote Desktop Services integration
TOCTitle: Install Remote Desktop Services integration
ms:assetid: 59891698-40b9-4d94-b75a-14e0c1e2231b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731800(v=AX.60)
ms:contentKeyID: 35132645
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install Remote Desktop Services integration [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Remote Desktop Services integration components for Microsoft Dynamics AX support integration with local applications, such as Microsoft Word and Microsoft Excel, when Microsoft Dynamics AX is hosted on a Remote Desktop server. Install the Remote Desktop Services integration components on local client computers. The Remote Desktop Services integration components are selected automatically when you install the Office Add-ins for Microsoft Dynamics AX.

## Before you install the Remote Desktop Services integration components

On the computer where you plan to install the components, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

## Install the Remote Desktop Services integration components

Use this procedure to install the Remote Desktop Services integration components on a client computer. If you install other Microsoft Dynamics AX components at the same time, the installation screens vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Specify a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Remote Desktop Services integration**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Ready to install** page, click **Install**.

9.  After the installation is completed, click **Finish** to close the wizard.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


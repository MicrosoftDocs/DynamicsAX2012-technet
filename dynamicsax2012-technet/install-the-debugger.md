---
title: Install the debugger
TOCTitle: Install the debugger
ms:assetid: 8a34aa8c-9d94-4d5a-89c5-988c573e50dd
ms:mtpsurl: https://technet.microsoft.com/library/Dd309746(v=AX.60)
ms:contentKeyID: 35132713
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install the debugger 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The debugger tool provides debugging capabilities for X++ developers. The debugger tool communicates with the Microsoft Dynamics AX client, .NET Business Connector, or batch jobs that run on the Microsoft Dynamics AX server.


> [!NOTE]
> <P>To use the Help documentation for the debugger, the Microsoft Dynamics AX client must also be installed.</P>



## Before you install the debugger

On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install the debugger

Use this procedure to install the debugger. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Debugger**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

10. On the **Ready to install** page, click **Install**.

11. After the installation is completed, click **Finish** to close the wizard.

## After you install the debugger

To use the debugger, users must belong to the **Microsoft Dynamics AX Debugging Users** local group on the computer. The person who installed the debugger is automatically added to this group.

  



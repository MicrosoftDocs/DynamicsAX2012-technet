---
title: Install Report Designer for Management Reporter
TOCTitle: Install Report Designer for Management Reporter
ms:assetid: 654ea989-41a0-4e71-8dbb-f03865c2621b
ms:mtpsurl: https://technet.microsoft.com/library/Dn507081(v=AX.60)
ms:contentKeyID: 59623133
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install Report Designer for Management Reporter 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to install Report Designer by using the Microsoft Dynamics AX Setup wizard. Report Designer is a component of Management Reporter for Microsoft Dynamics ERP that is used to create the building blocks that define a report. For more information about Management Reporter, see [the Management Reporter page](https://go.microsoft.com/fwlink/?linkid=324871) on CustomerSource (logon is required).


> [!NOTE]
> <P>Report Designer is available through the Microsoft Dynamics AX Setup wizard in AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2 (CU 7). For information about how to install Report Designer with CU 7, see the <A href="https://go.microsoft.com/fwlink/?linkid=329982">Installation Guide for cumulative update 7</A>.</P>
> <P>If you’re not using Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can use the stand-alone installation for Management Reporter. For more information, see the <A href="https://go.microsoft.com/fwlink/?linkid=325393">Management Reporter Installation Guide</A>.</P>



## Before you install Report Designer

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install Report Designer

Use this procedure to install Report Designer. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Management Reporter Report Designer**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Ready to install** page, click **Install**.

9.  After the installation is completed, click **Finish** to close the wizard.

## After you install Report Designer

For information about how to use Report Designer, see the [Management Reporter technical library](https://go.microsoft.com/fwlink/?linkid=325396) on TechNet.

## See also

[Install Management Reporter server components](install-management-reporter-server-components.md)

  



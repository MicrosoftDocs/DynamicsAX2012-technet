---
title: Install Retail Headquarters
TOCTitle: Install Retail Headquarters
ms:assetid: 1c05c344-96a3-4619-801f-a3f4038ad442
ms:mtpsurl: https://technet.microsoft.com/library/Hh575193(v=AX.60)
ms:contentKeyID: 39555323
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install Retail Headquarters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

The Retail Headquarters component installs runtime components that are required to enable key aspects of Retail functionality, such as the screen layout designer. This component must be installed on the Application Object Server (AOS) computer and on Microsoft Dynamics AX client computers.


> [!NOTE]
> <P>Retail components are available with Microsoft Dynamics AX 2012 R3, AX 2012 R2, and AX 2012 Feature Pack.</P>



## Before you install Retail Headquarters

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - Before you install Retail Headquarters, we recommend that you install the AOS, Microsoft Dynamics AX clients, and the Microsoft Dynamics AX databases with all required models.

## Install Retail Headquarters

Use this procedure to install Retail Headquarters. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  On the **Modify Microsoft Dynamics AX installation** page, click **Add or modify components**, and then click **Next**.

4.  On the **Add or modify components** page, select **Retail headquarters**, and then click **Next**.

5.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

6.  On the **Ready to install** page, click **Install**.

7.  After the installation is completed, click **Finish** to close the wizard.

## After you install Retail Headquarters

After you install the **Retail Headquarters** component on AOS computers and Microsoft Dynamics AX client computers, you must initialize the retail configuration.


> [!IMPORTANT]
> <P>Before you initialize the retail configuration, make sure that you have specified a language and a postal address for each legal entity where you will set up retail stores.</P>



1.  Open the Microsoft Dynamics AX client.

2.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

3.  Click **Initialize**.

4.  Close the Microsoft Dynamics AX client.

5.  In Windows, open the **Services** control panel.

6.  Restart the **Microsoft Dynamics AX Object Server** service.

  



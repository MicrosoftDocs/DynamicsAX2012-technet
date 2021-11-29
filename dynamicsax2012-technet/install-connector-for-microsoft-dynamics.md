---
title: Install Connector for Microsoft Dynamics
TOCTitle: Install Connector for Microsoft Dynamics
ms:assetid: ac5e9a21-f216-4c75-953d-db6a8bddab63
ms:mtpsurl: https://technet.microsoft.com/library/Dn507083(v=AX.60)
ms:contentKeyID: 59623131
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install Connector for Microsoft Dynamics 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to install Connector for Microsoft Dynamics by using the Microsoft Dynamics AX Setup wizard. Use Connector to integrate data between Microsoft Dynamics CRM and Microsoft Dynamics AX. For example, you can integrate Microsoft Dynamics AX customers with Microsoft Dynamics CRM accounts. This integration gives you access to up-to-date customer and account information in both systems. For more information about Connector, see [the Connector page](https://go.microsoft.com/fwlink/?linkid=324872) on CustomerSource (logon is required).


> [!NOTE]
> <P>Connector is available through the Microsoft Dynamics AX Setup wizard in cumulative update 7 for Microsoft Dynamics AX 2012 R2 (CU 7) and AX 2012 R3. For information about how to install Connector with CU 7, see the <A href="https://go.microsoft.com/fwlink/?linkid=329982">Installation Guide for cumulative update 7</A>.</P>
> <P>If you’re not using Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can use the stand-alone installation for Connector. Download and run the .msi file that is available on CustomerSource. For information about how to run the stand-alone installation, see <A href="https://go.microsoft.com/fwlink/?linkid=325397">Installation Guide</A> (PDF) for Connector.</P>



You must install Connector on a computer where Microsoft Dynamics AX Application Object Server (AOS), the Microsoft Dynamics AX client, and .NET Business Connector are installed. If these components have not been installed, they will be selected automatically in Setup when you install Connector.

## Before you install Connector for Microsoft Dynamics

  - Create or select the user accounts that will be used to run the Connector service and to integrate data between Microsoft Dynamics AX and Microsoft Dynamics CRM. For more information about the requirements for these accounts, see [Create service accounts](create-service-accounts.md).

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install Connector for Microsoft Dynamics

Use this procedure to install Connector. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Connector for Microsoft Dynamics**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing Connector on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want 32-bit versions of Microsoft Dynamics AX files to be installed, and then click **Next**.

9.  On the **Configure the CRM connector installation** page, enter the name of the Microsoft SQL Server instance that will host the Microsoft Dynamics Integration (MSDI) database.
    

    > [!NOTE]
    > <P>The MSDI database doesn’t have to be on the same physical server as Connector for Microsoft Dynamics.</P>



10. On the **Enter server and port information to connect CRM Connector to an AOS instance** page, enter the name of the server where the AOS instance is installed, and enter the port number that the AOS instance uses for TCP/IP communication.

11. On the **Configure an integration user** page, enter information about the user account that is used to integrate data between Microsoft Dynamics CRM and Microsoft Dynamics AX. If the user does not already exist in Microsoft Dynamics AX, select **Create new account**. The user will be added, and the Microsoft Dynamics AX user ID will be *AxIntUsr*. If the user already exists in Microsoft Dynamics AX, select **Use existing account**, and enter a user ID.

12. On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

13. On the **Ready to install** page, click **Install**.

14. After the installation is completed, click **Finish** to close the wizard.

## After you install Connector for Microsoft Dynamics

After you have installed Connector, you must configure the adapter settings for Microsoft Dynamics CRM and Microsoft Dynamics AX. For more information about how to configure adapter settings for Microsoft Dynamics CRM, see the [Installation Guide](https://go.microsoft.com/fwlink/?linkid=325397) (PDF) for Connector. For more information about how to configure adapter settings for Microsoft Dynamics AX, see the [Configuration Guide](https://go.microsoft.com/fwlink/?linkid=325398) (PDF) for the Microsoft Dynamics AX adapter.

  



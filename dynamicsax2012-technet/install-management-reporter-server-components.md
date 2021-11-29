---
title: Install Management Reporter server components
TOCTitle: Install Management Reporter server components
ms:assetid: a5908e80-5fbe-49f8-9f2c-448b7f4cf67f
ms:mtpsurl: https://technet.microsoft.com/library/Dn507082(v=AX.60)
ms:contentKeyID: 59623130
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install Management Reporter server components 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to install Management Reporter for Microsoft Dynamics ERP by using the Microsoft Dynamics AX Setup wizard. Management Reporter is a financial reporting tool that is used to create, distribute, and analyze financial statements. For more information about Management Reporter, see [the Management Reporter page](https://go.microsoft.com/fwlink/?linkid=324871) on CustomerSource (logon is required).


> [!NOTE]
> <P>Management Reporter is available through the Microsoft Dynamics AX Setup wizard in AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2 (CU 7). For information about how to install Management Reporter with CU 7, see the <A href="https://go.microsoft.com/fwlink/?linkid=329982">Installation Guide for cumulative update 7</A>.</P>
> <P>If you’re not using Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can use the stand-alone installation for Management Reporter. Download and run the installation package that is available on CustomerSource. For information about how to run the stand-alone installation, see the <A href="https://go.microsoft.com/fwlink/?linkid=325393">Management Reporter Installation Guide</A> (PDF).</P>



When you install Management Reporter, Microsoft SQL Server change tracking is enabled on the Microsoft Dynamics AX business database.

## Before you install Management Reporter

  - Create the service account that will be used to run the Windows service for Management Reporter. Additionally, create or select the account that will be used to integrate data between Microsoft Dynamics AX and Management Reporter. For more information about the requirements for these accounts, see [Create service accounts](create-service-accounts.md).

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Install Management Reporter

Use this procedure to install Management Reporter. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Management Reporter**, and then click **Next**.

7.  On the **Connect Management Reporter to an AOS instance** page, enter the name, TCP/IP port, and services endpoint port of the instance of Microsoft Dynamics AX Application Object Server (AOS) to use together with Management Reporter. By default, AOS uses port 2712 for TCP/IP communication and port 8201 for the services endpoint.
    
    Click **Next**.

8.  On the **Connect Management Reporter to a database** page, select the server name and database where Microsoft Dynamics AX transaction data is located. Reporting will be enabled for the database that you select. The Management Reporter database will also be created on the selected server.
    
    Click **Next**.

9.  On the **Select a service account** page, enter the account to run the Management Reporter Windows service, and then click **Next**.

10. On the **Configure Management Reporter** page, enter the following information:
    
      - The port number that the Management Reporter application server uses for communication. By default, the application server uses port 4712.
    
      - The name of the Management Reporter database.
    
      - The name of the data mart database.
    
    Click **Next**.

11. On the **Configure an integration user** page, enter information about the user account that is used to integrate data between Management Reporter and Microsoft Dynamics AX. If the user does not already exist in Microsoft Dynamics AX, select **Create new account**. The user will be added, and the Microsoft Dynamics AX user ID will be *AxIntUsr*. If the user already exists in Microsoft Dynamics AX, select **Use existing account**, and enter a user ID. Click **Next**.

12. On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

13. On the **Ready to install** page, click **Install**.

14. After the installation is completed, click **Finish** to close the wizard.
    

    > [!NOTE]
    > <P>The Setup wizard installs Management Reporter in two phases. First, the Management Reporter software is installed. Then, Management Reporter is configured to connect to Microsoft Dynamics AX. If the Setup wizard reports a failure, we recommend that you run the Management Reporter Configuration Console to complete the configuration.</P>



## After you install Management Reporter

After installation, you must open the Report Designer client and enter registration keys. After you have entered registration keys, additional configuration might be required before you can add report viewers or users. For information about how to configure Management Reporter, see the [Management Reporter Installation Guide](https://www.microsoft.com/en-us/download/details.aspx?id=5916).

Management Reporter is available to Microsoft Dynamics AX users based on role membership in Microsoft Dynamics AX. For information about how Management Reporter integrates with Microsoft Dynamics AX, see the [Management Reporter Integration Guide for Microsoft Dynamics AX](https://go.microsoft.com/fwlink/?linkid=325395) (PDF).

For information about how to use Management Reporter, see the [Management Reporter technical library](https://go.microsoft.com/fwlink/?linkid=325396) on TechNet.

## See also

[Install Report Designer for Management Reporter](install-report-designer-for-management-reporter.md)

  



---
title: Install the Trace Parser
TOCTitle: Install the Trace Parser
ms:assetid: c80a7da2-2914-485b-a797-4c8e5b9b1179
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731935(v=AX.60)
ms:contentKeyID: 35132867
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install the Trace Parser [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Trace Parser consolidates information from multiple sources, such as RPC and SQL, to provide an integrated view of the application’s performance at run time.

## Before you install the Trace Parser

On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

## Install the Trace Parser

Use this procedure to install the Trace Parser. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Trace Parser**. When you select **Trace Parser**, **.NET Business Connector** is automatically selected. Click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Select a display language** page, select the language in which you want to run Microsoft Dynamics AX for the first time.
    

    > [!NOTE]
    > <P>.NET Business Connector is a kind of Microsoft Dynamics AX client. Therefore, if .NET Business Connector is the first client that you install on a computer, Setup requires that you set the display language.</P>



10. On the **Specify a location for configuration settings** page, specify whether you want .NET Business Connector to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file. Click **Next**.

11. On the **Connect to an AOS instance** page, enter the name of the computer that runs the instance of Application Object Server (AOS) that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



12. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by .NET Business Connector. Click **Next**.

13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is completed, click **Finish** to close the wizard.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


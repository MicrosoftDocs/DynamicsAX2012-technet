---
title: Install the .NET Business Connector
TOCTitle: Install the .NET Business Connector
ms:assetid: c67944e8-73c5-4434-94d6-84484c810333
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548683(v=AX.60)
ms:contentKeyID: 35132857
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install the .NET Business Connector [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The .NET Business Connector for Microsoft Dynamics AX enables applications to interact with instances of Application Object Server (AOS). .NET Business Connector provides a set of managed classes that make it easier for applications to access X++ functionality.

The .NET Business Connector is installed automatically for Microsoft Dynamics AX components that require it. The .NET Business Connector can also be installed as a stand-alone component and used to develop third-party applications that can be integrated with Microsoft Dynamics AX. You must install .NET Business Connector on each computer where the integrated application is installed. The application then communicates with AOS through the instance of .NET Business Connector on the local computer.

Some components require that .NET Business Connector be configured to connect to Microsoft Dynamics AX by using a proxy account. When a proxy account is used, .NET Business Connector can connect to an AOS instance on behalf of Microsoft Dynamics AX users. For more information, see [Specify the .NET Business Connector proxy account](specify-the-net-business-connector-proxy-account.md).

When you install .NET Business Connector, the Microsoft Dynamics AX Configuration utility is also installed.


> [!NOTE]
> <P>Windows Communication Foundation (WCF) services are the preferred method for integration with Microsoft Dynamics AX. The .NET Business Connector installation is provided for backward compatibility.</P>



## Before you install .NET Business Connector

Complete the following tasks before you install .NET Business Connector.

  - On the computer where you plan to install .NET Business Connector, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - Install the Microsoft Dynamics AX databases and AOS in the environment. Alternatively, you can install these components when you install .NET Business Connector.

## Install .NET Business Connector

Use this procedure to install .NET Business Connector. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **.NET Business Connector**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Select a display language** page, select the language in which you want to run Microsoft Dynamics AX for the first time.
    

    > [!NOTE]
    > <P>.NET Business Connector is a kind of Microsoft Dynamics AX client. Therefore, if .NET Business Connector is the first client that you install on a computer, Setup requires that you set the display language.</P>



10. On the **Specify a location for configuration settings** page, specify whether you want .NET Business Connector to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file. Click **Next**.

11. On the **Connect to an AOS instance** page, enter the name of the computer that runs the instance of Application Object Server (AOS) that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered information about the AOS connection for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>



12. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

13. On the **Ready to install** page, click **Install**.

14. After the installation is completed, click **Finish** to close the wizard.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Install Office Add-ins
TOCTitle: Install Office Add-ins
ms:assetid: 7e6aaf42-8ba7-4a4d-af53-06395c0d8730
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731844(v=AX.60)
ms:contentKeyID: 35132697
ms.date: 04/21/2014
mtps_version: v=AX.60
---

# Install Office Add-ins 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install Microsoft Office Add-ins by using the Microsoft Dynamics AX Setup wizard. In Microsoft Dynamics AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2, the Microsoft Project client add-in is included with the Office Add-ins.

Use the Office Add-ins for Microsoft Dynamics AX to integrate the Microsoft Dynamics AX client with Microsoft Excel or Microsoft Word. When you install the Office Add-ins, a new contextual tab for Microsoft Dynamics AX is created on the ribbon in Excel and Word. Users can use the controls on this tab to create and update data in an Excel spreadsheet or a Word document.

With the Microsoft Project client add-in, users can take advantage of features in both Microsoft Dynamics AX and Microsoft Project to manage a project. These features include assigning workers to projects and managing work breakdown structures.

## Before you install the Office Add-ins

On the computer where you are installing this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

## Install the Office Add-ins

Use this procedure to install the files for the Office Add-ins on a client computer. If you install other Microsoft Dynamics AX components at the same time, the installation screens vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Office Add-ins**. When you select **Office Add-ins**, **Remote Desktop Services integration** is selected automatically. Click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  If you are installing the Office Add-ins on a 64-bit operating system, the **Select a file location** page is displayed. Select the location where you want 32-bit versions of Microsoft Dynamics AX files to be installed, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want the Office Add-ins to access configuration information from the registry on the local computer or from a shared configuration file. If you want to use a shared configuration file, you must enter the network location of the file.
    
    If you use a shared configuration file, client configuration settings are not stored locally, and the Microsoft Dynamics AX Configuration utility is not installed on the client computer.
    
    For more information about how to use a shared configuration file, see [Configure clients to use a shared configuration](configure-clients-to-use-a-shared-configuration.md).
    
    Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that runs the Application Object Server (AOS) instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services.
    
    If you do not know the name of the AOS instance or the port information, contact the Microsoft Dynamics AX administrator.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this page is not displayed. Subsequent installations on the same computer reuse the existing AOS connection.</P>

    
    Click **Next**.

11. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

12. On the **Ready to install** page, click **Install**.

13. After the installation is completed, click **Finish** to close the wizard.

14. The first time that you open Excel or Word on a computer where the Office Add-ins component was installed, you are prompted to install the add-in. Click **Install** to continue with the installation.

## After you install the Office Add-ins

For information about how to configure Office Add-ins in Microsoft Dynamics AX, see [Set up integration with Microsoft Office Add-ins](set-up-integration-with-microsoft-office-add-ins.md). For information about how to configure the Microsoft Project client add-in, see [Specify options for Microsoft Project integration](specify-options-for-microsoft-project-integration.md).

## See also

[Integrating Microsoft Dynamics AX with Microsoft Office](integrating-microsoft-dynamics-ax-with-microsoft-office.md)

  



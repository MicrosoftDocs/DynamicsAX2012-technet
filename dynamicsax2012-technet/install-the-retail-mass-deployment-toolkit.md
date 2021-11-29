---
title: Install the Retail mass deployment toolkit
TOCTitle: Install the Retail mass deployment toolkit
ms:assetid: ece974c0-634d-4b2e-8744-e2f96ff35fa2
ms:mtpsurl: https://technet.microsoft.com/library/Dn741223(v=AX.60)
ms:contentKeyID: 62219110
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install the Retail mass deployment toolkit 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Retail mass deployment toolkit is a command-line tool that helps you deploy the components of a retail environment. You specify configuration settings for components and design the topology of the environment in Microsoft Dynamics AX. Then you use the toolkit to export this preconfigured information and use it during deployment.

For information about the deployment scenarios where you can use the toolkit, see [Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md).


> [!NOTE]
> <P>The Retail mass deployment toolkit is available only with Microsoft Dynamics AX 2012 R3.</P>



## Before you install the Retail mass deployment toolkit

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - To export retail topologies from Microsoft Dynamics AX, the toolkit must be able to connect to Microsoft Dynamics AX via .NET Business Connector.

  - If you’re using the toolkit with System Center Configuration Manager, you must install the toolkit on the computer where the Configuration Manager console is installed. To run toolkit operations that require Configuration Manager, you must install the toolkit on the same computer as the central administration site for Configuration Manager, if Configuration Manager has multiple primary sites. If Configuration Manager has only one primary site, install the toolkit on the same computer as the primary site. You can’t use the toolkit on the computer for a secondary site.

## Install the Retail mass deployment toolkit

Use this procedure to install the Retail mass deployment toolkit. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Retail mass deployment toolkit**, and then click **Next**.

7.  On the **Connect to an AOS instance** page, enter information about the instance of Microsoft Dynamics AX Application Object Server (AOS) to connect to. Click **Next**.

8.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is completed, click **Finish** to close the wizard.

## After you install the Retail mass deployment toolkit

Follow these steps to initialize the toolkit.

1.  Share the content root folder. By default, the folder is located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail Scaleout Deployment\\ConfigManagerContent. Note the folder location. You must enter the Universal Naming Convention (UNC) path of this location when you run the initialization command.

2.  Run the following command in the toolkit:
    
        RetailConfigMgrToolkit.exe -o CreateApplications -contentRootFolder <UNC Path to the content root folder>

3.  You are prompted to confirm that the application will open specific ports on your behalf on target computers. Press **Y** to confirm.


> [!TIP]
> <P>To see the full list of commands that are available for the toolkit, open a Command Prompt window in the folder where RetailConfigMgrToolkit.exe is installed, and type <STRONG>RetailConfigMgrToolkit.exe</STRONG>. To see the parameters that are available for a command, run the command <STRONG>RetailConfigMgrToolkit.exe -o &lt;command&gt; -?</STRONG>.</P>


  



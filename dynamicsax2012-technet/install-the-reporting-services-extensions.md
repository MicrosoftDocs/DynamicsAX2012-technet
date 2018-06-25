---
title: Install the Reporting Services extensions
TOCTitle: Install the Reporting Services extensions
ms:assetid: d876745a-a2e7-4ce8-b608-beca6f8548dd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362088(v=AX.60)
ms:contentKeyID: 28119595
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Install the Reporting Services extensions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to install the Microsoft SQL Server Reporting Services extensions. You must complete this procedure on the computer that is running Reporting Services.

This procedure assumes that you are installing the Reporting Services extensions on a dedicated server where no other Microsoft Dynamics AX components are installed. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the initial wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, select **Custom installation**. Click **Next**.

6.  On the **Select components** page, follow these steps:
    
    1.  Select the **Reporting Services extensions** check box.
        
        When you select the option to install the Reporting Services extensions, the management utilities are automatically selected for installation, also.
    
    2.  A message is displayed that states that you must complete the code upgrade checklist if you are upgrading. Click **OK**.
    
    3.  Click **Next**.

7.  On the **Prerequisite Validation** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location in which to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want the Reporting Services extensions to access configuration information from the registry on the local computer or from a shared configuration file. If you select to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that is running the Application Object Server (AOS) instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>You can connect to an AOS instance that is part of an AOS cluster. However, do not connect to an AOS instance that serves as the dedicated load balancer for a cluster. For more information about how to integrate Reporting Services with an AOS scale-out deployment, see <A href="planning-for-reporting-in-microsoft-dynamics-ax.md">Planning for reporting in Microsoft Dynamics AX</A>.</P>



11. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by Business Connector. Click **Next**.

12. On the **Specify a Reporting Services instance** page, complete the action listed in the following table.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Action you should take</p></th>
    <th><p>Notes</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Instance name</strong></p></td>
    <td><p>Select the name of the Reporting Services instance.</p>
    <p>If you are using Reporting Services 2012 or 2014 in SharePoint integrated mode, select <strong>@Sharepoint</strong>.</p></td>
    <td><p>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Site URL</strong></p></td>
    <td><p>Select the URL of the SharePoint site that has been integrated with Reporting Services.</p></td>
    <td><p>This field is displayed only when Reporting Services 2012 or 2014 is running in SharePoint integrated mode.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Deploy reports</strong></p></td>
    <td><p>Select the check box to deploy the default reports that are included with Microsoft Dynamics AX.</p>
    <p>If you do not deploy the reports now, you can deploy them later by using Windows PowerShell commands. For more information, see <a href="deploy-the-default-reports.md">Deploy the default reports</a>.</p></td>
    <td><p>This check box is displayed only when Reporting Services is running in native mode.</p>
    <p>If Reporting Services is running in SharePoint integrated mode, you must deploy the reports after you complete this wizard. Deploy the reports by using Windows PowerShell commands. For more information, see <a href="deploy-the-default-reports.md">Deploy the default reports</a>.</p></td>
    </tr>
    </tbody>
    </table>
    
    Click **Next**.

13. On the **Prerequisite Validation** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.
    
    If you selected to deploy the reports in step 11, a Windows PowerShell window is displayed. This window shows the progress of the deployment, which may take several minutes. Do not close this window. When the reports are deployed, the window closes automatically.

15. Click **Finish** to close the Setup wizard.
    
    If you selected to deploy the reports in step 11, you can close the Setup wizard before the reports have finished being deployed. The deployment of the reports is not affected.

16. The **Microsoft Dynamics AX 2012 Setup Summary Report** is displayed. This report lists additional procedures that you must complete to integrate Microsoft Dynamics AX and Reporting Services. For more information about the procedures, see [Complete the Reporting Services integration](complete-the-reporting-services-integration.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


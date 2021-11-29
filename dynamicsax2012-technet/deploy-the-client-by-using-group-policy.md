---
title: Deploy the client by using Group Policy
TOCTitle: Deploy the client by using Group Policy
ms:assetid: ea4a6465-9c70-49a6-866e-1ab3d1e46ac2
ms:mtpsurl: https://technet.microsoft.com/library/Hh378078(v=AX.60)
ms:contentKeyID: 36870661
author: Khairunj
ms.date: 05/23/2014
mtps_version: v=AX.60
---

# Deploy the client by using Group Policy 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Group Policy provides an infrastructure that lets you centrally manage the configuration of operating systems and applications. This topic describes the processes and procedures that you must use to deploy Microsoft Dynamics AX clients by using Group Policy.

When you publish the Microsoft Dynamics AX client by using Group Policy, the program becomes available from the **Install a program from the network** option in the **Programs and Features** Control Panel. Users can install the Microsoft Dynamics AX client by using the settings that you specify.

For more information about Group Policy, see the [Group Policy Planning and Deployment Guide](https://technet.microsoft.com/library/cc754948\(v=ws.10\).aspx) on TechNet.

## Overview of the deployment process

You must perform the following procedures to deploy Microsoft Dynamics AX clients by using Group Policy.

1.  **Create a distribution point** – Create the location from which the software is installed.

2.  **Create a transform for the ClientOba.msi file** – Modify the Microsoft Windows Installer package, or .msi file, for the Microsoft Dynamics AX client to enable the client to be deployed by using Group Policy. There are two versions of the .msi file: ClientOba.msi, which is for 32-bit systems, and ClientOba64.msi, which is for 64-bit systems.

3.  **Create a Group Policy object** – Create a Group Policy object and publish it to the domain.

4.  (Optional) **Update Group Policy settings on client computers** – Run the Gpupdate utility if you want the changes to be applied to a client computer immediately. If you do not use Gpupdate, you must wait the default update interval or restart the computer.

## Create a distribution point

To publish the Microsoft Dynamics AX installation by using Group Policy, you must first create a distribution point on the publishing server.

1.  Log on to the server computer as an administrator.

2.  Create a shared network folder where you can put the .msi file for the Microsoft Dynamics AX client components.

3.  Set permissions on the shared network folder to allow access to the distribution package. Make sure that all users who must install Microsoft Dynamics AX have Read access to this directory.

4.  Install the package to the distribution point. From the folder where you saved the Microsoft Dynamics AX DVD image, run the msiexec tool. In the command, include the */a* parameter, and specify the location of the distribution point. For example, you might use the following command to install the 64-bit Microsoft Dynamics AX client components to the distribution point:
    
    msiexec /a ClientOba64.msi TARGETDIR=\\\\\<Server\>\\\<Directory\>\\\<SharedFolder\>)
    

    > [!NOTE]
    > <P>The msiexec tool lets you install, modify, and perform operations on Windows Installer files from the command line. For more information about how to use msiexec, see <A href="https://technet.microsoft.com/library/cc759262(ws.10).aspx">Msiexec (command-line options)</A> on TechNet.</P>



## Create a transform for the ClientOba.msi file

The .msi file for the Microsoft Dynamics AX client components must be modified before it can be published by using Group Policy. You can use the Orca database editor to modify .msi files. For more information about how to install and use Orca, see the Microsoft Knowledge Base article [How to use the Orca database editor to edit Windows Installer files](https://support.microsoft.com/kb/255905).

1.  Open ClientOba.msi or ClientOba64.msi by using the Orca editor.

2.  Click **Transform** \> **New Transform**.

3.  Select the features that you want to install. In the left pane, select the **Feature** table. In the right pane, use the **Level** column to specify whether features are installed on client computers. The following table shows the possible values.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Level</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>0</p></td>
    <td><p>The feature is not available for installation.</p></td>
    </tr>
    <tr class="even">
    <td><p>&lt;150</p></td>
    <td><p>The feature is installed on the local hard disk.</p></td>
    </tr>
    <tr class="odd">
    <td><p>&gt;150</p></td>
    <td><p>The feature is available for installation, but it is not installed by default.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If you do not want a feature to be installed automatically on client computers, set the level to 0. If a parent feature has a level of 0, all child features are also unavailable.</P>



4.  Set information about the connection to Application Object Server (AOS). In the left pane, select the **Property** table. In the right pane, double-click to add a line for each property and value. The following table describes the properties that you can set.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>AOS2</strong></p></td>
    <td><p>(Required) Enter the name of the AOS instance that clients connect to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ClientAOSServer</strong></p></td>
    <td><p>(Required) Enter the name of the AOS instance that clients connect to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AOSPort</strong></p></td>
    <td><p>Enter the TCP/IP port for the AOS. By default, the AOS uses port 2712.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AOSWSDLPort</strong></p></td>
    <td><p>Enter the WSDL port for the AOS. By default, the AOS uses port 8101.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>InstallDir</strong></p></td>
    <td><p>(Required) Specify the location where program files for Microsoft Dynamics AX are installed. By default, the path is <em>&lt;Drive&gt;</em>:\Program Files\Microsoft Dynamics AX\60.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>InstallDir32</strong></p></td>
    <td><p>(Required for 64-bit operating systems) Specify the location where 32-bit versions of program files for Microsoft Dynamics AX are installed. You cannot specify the same path for both 64-bit files and 32-bit files.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>DIRECTEXECUTE</strong></p></td>
    <td><p>(Required) Enter <strong>1</strong> to enable the .msi file to be run directly.</p></td>
    </tr>
    </tbody>
    </table>


5.  Click **Transform** \> **Generate Transform**. Enter a name and location for the .mst file.

## Create a Group Policy object

An Active Directory–based Group Policy object (GPO) is a virtual collection of policy settings. Active Directory–based GPOs can be linked to a domain, site, or organizational unit. The settings in GPOs can be applied to users or computers. GPOs are stored in a domain and replicated to all the domain controllers for the domain.

Use the following procedure to create a GPO that installs the Microsoft Dynamics AX client components.

1.  On the domain controller, click **Administrative Tools** \> **Group Policy Management** to open the Group Policy Management console.

2.  Under the domain for which you want to create a GPO, right-click **Group Policy Objects** and then click **New**.

3.  Specify a name for the GPO and then click **OK**.

4.  Select the new GPO and then click the **Settings** tab.

5.  Under **User Configuration**, right-click, and then select **Edit** to open the Group Policy Management Editor.

6.  Expand **User Configuration** \> **Policies** \> **Software Settings**.

7.  Right-click **Software Installation**, and then select **New Package**.

8.  Browse to the distribution point that you set up.

9.  Click **Advanced**.
    
      - On the **Deployment** tab, select a deployment type of **Published**.
    
      - On the **Modification** tab, select the .mst file that you created.

10. Click **OK** to finish configuring the GPO.

## (Optional) Update Group Policy settings on client computers

Typically, after you modify group policy settings, you must wait a default update interval or restart the computer. The default update interval is 90 minutes on domain members and 5 minutes on domain controllers. However, if you want the changes to be applied immediately, you can run the Gpupdate utility at a command prompt.

For more information about how to use the Gpupdate utility, see [Gpupdate](https://technet.microsoft.com/library/bb490983.aspx) on TechNet.

  



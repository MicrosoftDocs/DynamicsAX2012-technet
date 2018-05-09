---
title: Install the VSS writer for Microsoft Dynamics AX
TOCTitle: Install the VSS writer for Microsoft Dynamics AX
ms:assetid: cac0e744-8a85-48a9-9499-4e0fa66b0e27
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507084(v=AX.60)
ms:contentKeyID: 59623132
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install the VSS writer for Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Volume Shadow Copy Service writer for Microsoft Dynamics AX (AX VSS writer) can be used together with Microsoft System Center 2012 Data Protection Manager (DPM) to help protect Microsoft Dynamics AX data and servers.

The AX VSS writer coordinates backup and restore operations. For more information, see [Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)](protecting-microsoft-dynamics-ax-environments-with-system-center-2012-data-protection-manager-dpm.md).


> [!NOTE]
> <P>The AX VSS writer is available through the Microsoft Dynamics AX Setup wizard in AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2 (CU 7). For information about how to install the AX VSS writer with CU 7, see the <A href="http://go.microsoft.com/fwlink/?linkid=329982">Installation Guide for cumulative update 7</A>.</P>



## Before you install the AX VSS writer

  - Ensure that a System Center 2012 Data Protection Manager server is installed and configured.
    

    > [!IMPORTANT]
    > <P>Agents cannot be installed on the Data Protection Manager server. Do not install AX 2012 components on the same server.</P>



  - Create a folder that the AX VSS writer will use to store temporary backup files. This folder should not be used for any other purpose, and access should be limited to the service account for the AX VSS writer.

  - Create a service account for the AX VSS writer. This account must be a local administrator on all the computers that you plan to protect by using this component. Additionally, the account must have read/write permission to the location where temporary backup files are stored.

  - Install a DPM agent on all the computers that you plan to protect by using this component. For more information about Data Protection Manager, see [Installing and Configuring Protection Agents](http://technet.microsoft.com/en-us/library/hh758039.aspx).

  - On the computers where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

## Install the AX VSS writer

Use this procedure to install the AX VSS writer. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  On every computer that you plan to protect, start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Modify Microsoft Dynamics AX installation** page, click **Add or modify components**, and then click **Next**.

5.  On the **Add or modify components** page, select **VSS writer**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  Enter the requested information for the component that you are installing.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Component</p></th>
    <th><p>Required information</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Microsoft Dynamics AX Application Object Server (AOS)</p></td>
    <td><p>The AOS instance</p></td>
    </tr>
    <tr class="even">
    <td><p>Database</p></td>
    <td><p>The Microsoft SQL Server instance</p>
    <p>The database name for the business database</p></td>
    </tr>
    <tr class="odd">
    <td><p>Microsoft SQL Server Analysis Services</p></td>
    <td><p>The name of the Analysis Services instance</p></td>
    </tr>
    <tr class="even">
    <td><p>Microsoft SQL Server Reporting Services</p></td>
    <td><p>The name of the Reporting Services instance</p>
    <p>The name of the reporting database server</p>
    <p>The name of the Report Server database</p></td>
    </tr>
    <tr class="odd">
    <td><p>All</p></td>
    <td><p>The name of the DPM server</p>
    <p>The name of the AX VSS writer service account</p>
    <p>The password for the AX VSS writer service account</p>
    <p>The temporary file location that is used to temporarily hold copies of protected media.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This location can contain important data. We strongly recommend that you limit access to this location to the AX VSS writer service account, and that you use the location only to store temporary VSS files.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


8.  On the **Ready to install** page, click **Install**.

9.  After the installation is completed, click **Finish** to close the wizard.

10. Repeat these steps for all other components that you plan to protect.

## Next steps

The following topics describe the next steps:

  - [Protect a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager](protect-a-microsoft-dynamics-ax-2012-r2-environment-with-system-center-2012-data-protection-manager.md)

  - [Recover a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager](recover-a-microsoft-dynamics-ax-2012-r2-environment-with-system-center-2012-data-protection-manager.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


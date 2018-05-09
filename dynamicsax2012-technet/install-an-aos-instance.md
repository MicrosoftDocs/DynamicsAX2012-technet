---
title: Install an AOS instance
TOCTitle: Install an AOS instance
ms:assetid: ed12bb98-25eb-42ce-b5f7-651a06abe688
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee355089(v=AX.60)
ms:contentKeyID: 35133211
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Install an AOS instance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install an Application Object Server (AOS) instance for Microsoft Dynamics AX 2012.


> [!NOTE]
> <P>If you are upgrading AOS instances between AX 2012, AX 2012 Feature Pack, AX 2012 R2, and AX 2012 R3you should review <A href="scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md">Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3</A>.</P>



## Before you install the AOS instance

  - On the computer where you will install the AOS instance, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).
    

    > [!NOTE]
    > <P>A 64-bit computer is not required to install an AOS instance. However, if you need to complete a full Common Intermediate Language (CIL) generation, such as in a development environment, a 64-bit computer is required.</P>



  - Verify that you have the appropriate permissions to install the AOS instance. For more information, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

  - If you plan to enable database mirroring in SQL Server, you must do so after installing the Microsoft Dynamics AX database and Application Object Server (AOS). If you enable database mirroring before installing Microsoft Dynamics AX components, the AOS instance will install with warnings.

  - Select a service account for the AOS service. Before you install an AOS instance, you must determine which account you want the AOS service to run as. The AOS service can run as a domain account, as a managed service account, or as the Network Service account of the computer that you install the AOS service on. For more information about how to set up an account for the AOS service, see [Create service accounts](create-service-accounts.md).

  - Choose a name for the AOS instance. We recommend that you use a uniform naming convention for all aspects of the installation, such as the database name and the name of the AOS instance. Because Microsoft Dynamics AX installations typically include one database and multiple AOS instances, make sure that the name of each AOS instance is unique but consistent with the naming convention. For example, you can use a name such as Fabrikam\_DYNAX6\_Live\_AOS1, which includes a shortened form of your business name, the Microsoft Dynamics AX version, a code that describes the purpose of the installation, and an identifier for the AOS instance.
    
    The instance name must not include any blank characters or any of the following characters: ampersand (&), backslash (\\), slash (/), colon (:), brackets (\[\]), parentheses (()), angle brackets (\<\>), quotation marks (“”), question mark (?), exclamation point (\!), asterisk (\*), percent (%), caret (^), or pipe (|).

  - You must install an initial AOS instance and complete the **Initialization checklist** on that instance before you install additional AOS instances. If you install additional AOS instances before you have completed the **Initialization checklist** those AOS instances will not start. For more information about how to install additional AOS instances, see [Install multiple AOS instances](install-multiple-aos-instances.md).

## Install the first or only AOS instance

Use this procedure to install a single or first instance of AOS on a server. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages vary, based on the components that you are installing.

## Install an AOS instance

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the initial wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Application Object Server (AOS)**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location where you want 32-bit versions of Microsoft Dynamics AX files to be installed, and then click **Next**.

9.  On the **Connect to the databases** page, in the **Server name** box, type or select the name of the Microsoft SQL Server computer. In the **Database name** box, select the name of the Microsoft Dynamics AX transaction database. Optionally, select the name of the baseline database.
    
    If you are upgrading code or data from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009, you must select **Register database for upgrade** and select a baseline database. The **Register database for upgrade** option is available when you install the first AOS in the computing environment. If you install more AOSs, this option is not available. You can determine whether the database was registered for upgrade by opening the Microsoft Dynamics AX client. If the database was registered for upgrade, the **Data upgrade checklist** is displayed when you open the client. Click **Next**.

10. On the **Configure an Application Object Server (AOS) instance** page, assign a name to the AOS instance. Optionally, you can specify the ports that are listed in the following table.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Port</p></th>
    <th><p>Purpose</p></th>
    <th><p>Default</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>TCP/IP port</p></td>
    <td><p>Used by other Microsoft Dynamics AX components to communicate with AOS.</p></td>
    <td><p>2712</p></td>
    </tr>
    <tr class="even">
    <td><p>Services WSDL port</p></td>
    <td><p>Used by external applications to access the WSDL for AOS-based Microsoft Dynamics AX Web services.</p></td>
    <td><p>8101</p></td>
    </tr>
    <tr class="odd">
    <td><p>Services endpoint port</p></td>
    <td><p>Used by external applications to access AOS-based Microsoft Dynamics AX Web services.</p></td>
    <td><p>8201</p></td>
    </tr>
    </tbody>
    </table>


11. On the **Specify an AOS account** page, select the Network Service account of the local computer (recommended only for development environments), a managed service account, or a domain account for the AOS service. If you select to use a managed service account, make sure to specify the account in the format *Domain*\\*AccountName*$.
    

    > [!WARNING]
    > <P>The process of manually changing the service account for an AOS is complicated and prone to error. For this reason, if you must change the service account for an AOS, we recommend that you uninstall and reinstall the AOS by using Setup.exe. For more information, see <A href="change-the-account-used-by-aos.md">Change the account used by AOS</A>.</P>



12. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

13. On the **Ready to install** page, click **Install**.

14. After the installation is complete, click **Finish** to close the wizard.
    
    The AOS service can take several minutes to start the first time after it is installed. To determine whether the AOS service has started, click **Administrative tools** \> **Services**, and review the status of the **Microsoft Dynamics AX Object Server** service.

## Start the AOS Windows service

After you install an AOS instance, you must wait for the **Microsoft Dynamics AX Object Server** Windows service to start.

By default, if a Windows service takes longer than 30 seconds to start, the system displays a message informing you that the service did not respond to a start command. The AOS Windows service can take longer than 30 seconds to start, and the lack of a response in 30 seconds can cause the service to stop. Therefore, if an AOS instance repeatedly does not start, you may want to configure the registry to give Windows services more time, such as 120 seconds, to start before the error message is displayed.


> [!WARNING]
> <P>This section describes how to modify the registry so that the AOS Windows service has enough time to start before Windows displays an error message. Be aware that serious problems can occur if you modify the registry incorrectly. We recommend that you back up the registry before you modify it. If a problem occurs, you can restore it. For more information about how to back up and restore the registry, see <A href="http://go.microsoft.com/fwlink/?linkid=214428">Backup and recovery</A>.</P>



1.  Click **Start**, click **Run**, type **regedit**, and then click **OK**.

2.  Locate and then click the following registry subkey: \\HKEY\_LOCAL\_MACHINE\\System\\CurrentControlSet\\Control

3.  Right-click **Control**, and then click **New** \> **DWORD (32-Bit) Value**.

4.  Right-click the new key, and then click **Rename**. Enter the name **ServicePipeTimeout**.

5.  Right-click the key again, and then click **Modify**.

6.  In the **Value data** text box, enter **120000**, and then click **OK**. The AOS Windows service now has 120 seconds to start before the system displays an error message.

If the AOS instance does not start after you implement this registry key, use the Microsoft Dynamics AX Server Configuration utility to verify that the AOS instance is using a unique port. Port conflicts prevent AOS instances from starting. For more information, see [Change AOS ports](change-aos-ports.md).

## Run the initialization checklist

After you install and start an AOS instance, and before you complete any other tasks in Microsoft Dynamics AX, you must run the initialization checklist. For more information, see [Initialize Microsoft Dynamics AX](initialize-microsoft-dynamics-ax.md).

## See also

[Install multiple AOS instances](install-multiple-aos-instances.md)

[Troubleshoot installation issues with AOS](troubleshoot-installation-issues-with-aos.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


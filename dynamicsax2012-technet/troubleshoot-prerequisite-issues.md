---
title: Troubleshoot prerequisite issues
TOCTitle: Troubleshoot prerequisite issues
ms:assetid: e3771aed-bde7-4610-bff2-aa64212a8352
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh285826(v=AX.60)
ms:contentKeyID: 36607354
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Troubleshoot prerequisite issues 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information that can help you troubleshoot issues that you may encounter when you run the prerequisite validation utility.


> [!IMPORTANT]
> <P>This topic does not contain an exhaustive list of prerequisite errors. Before you use the information in this topic, try to resolve prerequisite issues by using the instructions that are provided in the prerequisite validation utility.</P>



For more information about how to use the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

## Prerequisite errors related to Enterprise Portal

For information about how to troubleshoot prerequisite issues for Enterprise Portal, see [Troubleshoot installation issues with Enterprise Portal and Role Centers](troubleshoot-installation-issues-with-enterprise-portal-and-role-centers.md).

## Prerequisite errors related to Enterprise Search

For information about how to correctly configure software prerequisites for Enterprise Search, see [Install and configure Search prerequisites](install-and-configure-search-prerequisites.md).

## Prerequisite check for Windows Search Service fails after you configure the service by using the prerequisite validation utility

If you use the prerequisite validation utility to configure Windows Search Service on Windows Server 2012, and the prerequisite check continues to fail, you must restart your computer before you continue with Setup. On Windows Server 2012, the prerequisite validation utility does not detect that a restart is required after it configures Windows Search Service.

## Cumulative Update 3 for Microsoft SQL Server 2008 R2 cannot be installed

If the “Required updates for Microsoft SQL Server” prerequisite fails, the prerequisite validation utility instructs you to install Cumulative Update 3 for SQL Server 2008 R2. When you attempt to install Cumulative Update 3, and other Cumulative Updates have already been installed, you may receive a message that states that a higher version number of SQL Server 2008 R2 is already installed. If you receive this message and the prerequisite check still fails, we recommend that you download and install [Cumulative update package 8](http://support.microsoft.com/kb/2534352/en-us) or higher for SQL Server 2008 R2.

## Required restart after you install the Microsoft .NET Framework version 4.0

Most of the time, a pending restart of the computer is not considered a mandatory prerequisite. However, if you just installed the Microsoft .NET Framework version 4.0, the installation of some components may fail if you do not restart the computer. To avoid issues, we recommend that you restart the computer after you install the .NET Framework version 4.0.

## Prerequisite check failure for the Microsoft SQL Server Reporting Services service

If you are running the stand-alone prerequisite validation utility, you cannot select the instance of Microsoft SQL Server Reporting Services that is validated for the Reporting Services extensions. By default, the utility validates the first instance that matches the supported version. If multiple instances of Reporting Services are installed, and the instance that the utility validates is not running, the prerequisite check fails. When you run the Setup wizard, you can select a specific instance. In this case, the prerequisite check passes.

## Prerequisite check failure for Microsoft Visual Studio 2010 Tools for the Microsoft Office system

The following prerequisites may conflict with each other:

  - Required updates for Microsoft Visual Studio 2010

  - Visual Studio 2010 Tools for the Microsoft Office system

If you must install both prerequisites on the same computer, we recommend that you install the required updates for Visual Studio first. If you install the Visual Studio updates later, an older version of Visual Studio 2010 Tools for Microsoft Office is installed, and the Office Add-ins for Microsoft Dynamics AX may not work correctly.

## Prerequisite check warning for the startup type of the SQL Server Full-text Filter Daemon Launcher service

If multiple instances of SQL Server are installed, the prerequisite check for the startup type of the SQL Server Full-text Daemon Launcher service may generate a warning, even if the startup type is set correctly. This warning is generated because Setup verifies the prerequisite for the default instance of SQL Server instead of the instance that you selected.

There is a workaround for this issue. For the instance of SQL Server where you are installing Microsoft Dynamics AX components, make sure that the startup type for the SQL Server Full-text Daemon Launcher service is set to **Automatic**. If the startup type is set correctly, you can ignore the prerequisite warning and continue with the installation.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


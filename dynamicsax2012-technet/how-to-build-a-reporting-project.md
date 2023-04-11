---
title: 'How to: Build a Reporting Project'
TOCTitle: 'How to: Build a Reporting Project'
ms:assetid: f27ff4c5-0f40-473d-a8f4-81d47ee7f464
ms:mtpsurl: https://technet.microsoft.com/library/Cc642185(v=AX.60)
ms:contentKeyID: 28119616
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Build a Reporting Project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you build a reporting project, the report is updated in the model store. Managed projects with report business logic will build the assembly and add it to the output path for the project. You can build at the solution level or at the project level. When you build at the solution level, all projects that are contained in the solution are built. When you build at the project level, the project and any nested projects that are contained in the project are built. You can build from the Microsoft Visual Studio development environment, or you can build from the command line using MSBuild.exe. The following procedures explain how to build a solution or a project.

### To build a solution by using Microsoft Visual Studio

  - In Solution Explorer, right-click the solution, and then click **Build Solution**.
    
    \- or -

  - On the **Build** menu, click **Build Solution**.

### To build a project contained in a solution by using Microsoft Visual Studio

  - In Solution Explorer, right-click the project, and then click **Build**.
    
    \- or -

  - On the **Build** menu, click **Build \[project name\]**.

### To build a project or a solution from the command line

1.  Open a **Visual Studio 2010 Command Prompt** window. From the **Start** menu, point to **All Programs**, click **Microsoft Visual Studio 2010** \> **Visual Studio Tools** \> **Visual Studio Command Prompt (2010)**.

2.  Change the directory to the location of your solution or project file.

3.  At the command prompt, execute the following command:
    
    MSBuild.exe \[solution or project name\]
    
    For example, to build a solution called InventoryReports.sln, type:
    
    MSBuild.exe InventoryReports.sln
    
    There are several options that you can use when you build with MSBuild.exe from the command line. For more information, see [MSBuild Command Line Reference](https://go.microsoft.com/fwlink/?linkid=107298).

## Security

When building from the command line, Microsoft Dynamics AX reporting tools does not perform any checks for unsafe entries in the project file. The project file entries are not analyzed by Microsoft Dynamics AX reporting tools from a security perspective. Therefore, we strongly recommend that you do not build third-party reporting projects from the command line. Build from the command line only in trusted scenarios.

## See also

[Creating Reports Overview](creating-reports-overview.md)

[Reporting Project Overview](reporting-project-overview.md)

[How to: Create a Reporting Project](how-to-create-a-reporting-project.md)

[How to: Add a Reporting Project to a Solution](how-to-add-a-reporting-project-to-a-solution.md)


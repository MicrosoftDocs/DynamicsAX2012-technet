---
title: Troubleshoot issues when running the Setup wizard to configure Analysis Services
TOCTitle: Troubleshoot issues when running the Setup wizard to configure Analysis Services
ms:assetid: d3e32164-d488-4729-b9d5-67778e6f824b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724129(v=AX.60)
ms:contentKeyID: 35133489
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Troubleshoot issues when running the Setup wizard to configure Analysis Services [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information that can help you troubleshoot issues that you may encounter when you configure Microsoft SQL Server Analysis Services by using the Microsoft Dynamics AX Setup wizard.

## Setup encountered an error when it tried to retrieve a list of Analysis Services instances

If the Microsoft Dynamics AX Setup wizard cannot retrieve a list of Analysis Services instances, follow these steps to troubleshoot the issue.

  - Verify that the server name was entered correctly.

  - Verify that you have the permissions that are required to access the Analysis Services instances on the specified computer.

  - If you encounter a Windows Management Instrumentation (WMI) exception, the problem may be related to an issue in SQL Server. To resolve the WMI error that prevents Setup from accessing SQL Server, open a Command Prompt window, running as the Administrator. Then type the appropriate command, based on the SQL Server version that you are using.
    
      - If you are using SQL Server 2008, type the following command:
        
            mofcomp.exe "C:\Program Files (x86)\Microsoft SQL Server\100\Shared\sqlmgmproviderxpsp2up.mof"
    
      - If you are using SQL Server 2012, type the following command:
        
            mofcomp.exe "C:\Program Files (x86)\Microsoft SQL Server\110\Shared\sqlmgmproviderxpsp2up.mof"
    
    After the command has finished running, try to run Setup again.

## Setup displays a warning that states that you must install cumulative update package 1 for SQL Server 2012

If the Microsoft Dynamics AX Setup wizard displays a warning that states that you must install cumulative update package 1 for SQL Server 2012, follow these steps.

1.  Download and install [cumulative update package 1 for SQL Server 2012](http://support.microsoft.com/kb/2679368).

2.  Open SQL Server Management Studio and connect to your instance of Analysis Services.

3.  In the Object Explorer pane, verify that the version number of Analysis Services is 11.0.2316.0.

After you install cumulative update package 1, if the Setup wizard continues to display the warning message, you can ignore the warning message and click **Next** to continue with the wizard.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


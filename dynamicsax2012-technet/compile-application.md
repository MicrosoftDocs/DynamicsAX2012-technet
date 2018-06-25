---
title: Compile application
TOCTitle: Compile application
ms:assetid: 0e8bcd9c-b497-4fce-8ec5-1ea3253aca9b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309589(v=AX.60)
ms:contentKeyID: 35132542
ms.date: 06/11/2014
mtps_version: v=AX.60
f1_keywords:
- compile
- upgrade
---

# Compile application [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When the Microsoft Dynamics AX application is compiled, its X++ source code is translated into a machine-executable format that can be interpreted by the Microsoft Dynamics AX server and clients. This topic addresses the **Compile application** task common to several checklists as well as other situations where you may need to compile.

## Situations requiring you to compile

The application code must usually be compiled when you are installing or upgrading, or customizing. Compile in any of the following circumstances:

  - Though the **Compile application** task is optional in the upgrade checklists, we recommend that you compile all your code after code upgrade to prevent unexpected program behavior.

  - During installation or upgrade, you must compile the application if there is more than one layer in your system.

  - You must compile the application during a new installation that includes a service pack. This compilation is required because the references from the standard application must be updated.

  - If you installed a model other than the Foundation models, you must complete the **Compile application** task in the **Initialization checklist**. Otherwise, you will encounter errors when you run the **Synchronize database** task.

  - Compile the application if you have imported one or more models.

  - Compile the application if you have imported metadata elements through the client using XPO files, creating changes that could affect inheritance in classes or method signatures.

  - Compile if you have manually customized the application.

  - Compile the application periodically if multiple developers are sharing metadata in order to validate consistency during the development cycle.

## Compilation methods

Because there are several ways to compile, you should choose the most efficient method for the task that you are trying to complete.

1.  If you are installing or upgrading, the easiest way to compile is simply to click the **Compile application** task that is included in the **Initialization checklist** and the various upgrade checklists. This method compiles the code in full on the client computer. Consequently, depending on your hardware, the client system may be rendered unusable for several hours until compilation completes. An alternative, server-based compilation method is described below.
    

    > [!NOTE]
    > <P>.NET Business Connector must be installed on the computer where you run the <STRONG>Compile application</STRONG> task.</P>



2.  If you have access to the Developer Workspace, you can compile the application from the Microsoft Dynamics AX Application Object Tree (AOT). As in method 1, this is a client-based compilation. For more information, see [Code Compiler](https://technet.microsoft.com/en-us/library/aa865330\(v=ax.60\)).

3.  In Microsoft Dynamics AX 2012 R3, and starting in cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can use AxBuild.exe to perform a complete X++ compilation. AxBuild.exe is a server-based command-line tool that supports multithreading and can deliver significant performance gains compared to doing a full compilation from the client. To use AxBuild.exe, you must stop the AOS and run the command manually on the AOD server computer. Afterward, you can restart the AOS, open a client, and continue with other tasks.
    
    For more information, see [AxBuild.exe for Parallel Compile on AOS of X++ to p-code](https://technet.microsoft.com/en-us/library/dn528954\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


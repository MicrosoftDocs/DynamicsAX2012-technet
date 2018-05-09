---
title: Compile into .NET Framework CIL
TOCTitle: Compile into .NET Framework CIL
ms:assetid: f680b5f3-5b33-408f-8faf-36bb1f766988
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg723921(v=AX.60)
ms:contentKeyID: 35133270
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- .NET
- CIL
---

# Compile into .NET Framework CIL 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Compile into .NET Framework CIL** task converts your compiled application code into Common Intermediate Language (CIL) code that can be consumed by the Microsoft .NET Framework.

## The purpose of CIL

CIL is the bytecode language that the just-in-time (JIT) compiler of the .NET Framework interprets. Microsoft Dynamics AX converts compiled X++ code, or p-code, to CIL. This conversion provides interoperability with .NET classes, and it also improves performance. The following Microsoft Dynamics AX components rely on the speed of CIL:

  - Batch jobs

  - Application Integration Framework (AIF) and services

  - Run-as scenarios, in which .NET functions are substituted for X++ functions at run time

## Scenarios that require the CIL task

You may have to run the **Compile into .NET Framework CIL** task in the following two scenarios:

  - You are installing Microsoft Dynamics AX, and you encounter the task in the **Initialization checklist**.

  - You are performing an upgrade on a Microsoft Dynamics AX system that includes customized application code, and you encounter the task in either the **AOD code upgrade checklist** or the **Model code upgrade checklist**.


> [!IMPORTANT]
> <P>In all checklists that include the <STRONG>Compile into .NET Framework CIL</STRONG> task, the previous task is <STRONG>Compile application</STRONG>. You must complete the <STRONG>Compile application</STRONG> task before you can perform the <STRONG>Compile into .NET Framework CIL</STRONG> task.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


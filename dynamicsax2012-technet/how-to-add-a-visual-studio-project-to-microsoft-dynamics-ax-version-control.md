---
title: 'How to: Add a Visual Studio Project to Microsoft Dynamics AX Version Control'
TOCTitle: 'How to: Add a Visual Studio Project to Microsoft Dynamics AX Version Control'
ms:assetid: 387359f5-30f7-4433-94c4-0a804eb02050
ms:mtpsurl: https://technet.microsoft.com/library/Gg886625(v=AX.60)
ms:contentKeyID: 35267992
author: tonyafehr
ms.date: 08/27/2014
mtps_version: v=AX.60
---

# How to: Add a Visual Studio Project to Microsoft Dynamics AX Version Control 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to add a Visual Studio project in the AOT to version control. If a project is under version control, basic version control scenarios can be performed in Visual Studio. Advanced scenarios must be performed in the MorphX Integrated Development Environment (IDE).

The actions you can perform from Visual Studio under version control are as follows:

  - Check in

  - Check out

  - Undo checkout

  - Get latest

  - Rename

## To Add a Visual Studio Project to Version Control

1.  Configure version control in Microsoft Dynamics AX. For more information, see [Configuring Version Control in Microsoft Dynamics AX](https://technet.microsoft.com/library/aa496630\(v=ax.60\)).

2.  Configure version control in Visual Studio. Click **Tools** \> **Options**. Click Source Control and then select **Dynamics AX Version Control**.

3.  Create or open a project in Visual Studio.

4.  Right-click the project you want to add to version control, and then click **Add to Source Code Control**.

5.  Right-click the project and then click **Check In**.

You can check projects in and out in both Visual Studio Solution Explorer and MorphX IDE. You can view the history in MorphX IDE.

Analysis Services projects are not supported for Microsoft Dynamics AX TFS source control. To put an Analysis Services project under TFS source control, set the source control provider in TFS to Visual Studio instead of Microsoft Dynamics AX. Add files to source control directly from the TFS source control explorer.


> [!NOTE]
> <P>Only one developer should work on a Visual Studio project at a given time. When you save an element, it replaces the AOT version of the element.</P>



## See also

[Version Control System](https://technet.microsoft.com/library/aa639568\(v=ax.60\))

[Working with Reporting Projects](working-with-reporting-projects.md)

[Visual Studio Development for Microsoft Dynamics AX](https://technet.microsoft.com/library/gg889157\(v=ax.60\))

  



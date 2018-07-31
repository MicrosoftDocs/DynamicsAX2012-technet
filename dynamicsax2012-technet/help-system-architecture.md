---
title: Help system architecture
TOCTitle: Help system architecture
ms:assetid: 929971c1-2b66-42df-a047-3baa684c8bdc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731869(v=AX.60)
ms:contentKeyID: 35132763
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Help system architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following diagram illustrates the architecture of the Microsoft Dynamics AX Help system.

![Help system topology (excluding Internet)](images/Gg731869.InternalHelp(AX.60).png "Help system topology (excluding Internet)")

To better understand how the components in this diagram work together, consider the following example.

1.  An employee clicks the **Help** menu or presses **F1** when viewing a form in Microsoft Dynamics AX.

2.  The Microsoft Dynamics AX client determines which Help topic should be displayed. It requests that specific topic from the Help server.

3.  The Help server locates the topic and determines if there are any labels to define for that topic. If so, the Help server requests the definitions of the labels from the Microsoft Dynamics AX Application Object Server (AOS).
    
    For example, suppose a help topic contains the label *@SYS11904*. The help sever will request the definition of this label from the AOS. After the AOS returns the definition, *Customer group*, the Help server replaces all instances of *@SYS11904* with *Customer group*.

4.  The Help server sends the topic to the client, where it is displayed in the Help viewer.

  



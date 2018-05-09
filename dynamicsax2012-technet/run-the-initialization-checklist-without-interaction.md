---
title: Run the initialization checklist without interaction
TOCTitle: Run the initialization checklist without interaction
ms:assetid: 29b0bd8e-a046-4fe5-b1f3-87c16d988d2f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee355044(v=AX.60)
ms:contentKeyID: 35132587
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Run the initialization checklist without interaction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedure to run the initialization checklist without user interaction.

1.  On the Microsoft Dynamics AX client, create an XML file.

2.  Add tags to the XML file specifying the following parameters:
    
      - Microsoft Dynamics AX version.
    
      - Name and location of the log file.
    
      - Each checklist item to be run along with the appropriate attributes.
        
        The XML file syntax is described in the documentation for the **SysAutoRun** class. For more information, see [SysAutoRun](https://technet.microsoft.com/en-us/library/gg922801\(v=ax.60\)).

3.  Open a command prompt and type the following:
    
        ax32.exe –StartupCmd=AutoRun_c:\PathToFile\FileName.XML
    

    > [!NOTE]
    > <P>The XML code allows you to skip steps that are marked as mandatory.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


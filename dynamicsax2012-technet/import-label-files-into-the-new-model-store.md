---
title: Import label files into the new model store
TOCTitle: Import label files into the new model store
ms:assetid: a6e7c246-0478-4b8c-83d0-cc9dc32a5a3d
ms:mtpsurl: https://technet.microsoft.com/library/Gg731886(v=AX.60)
ms:contentKeyID: 35132797
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- label
- model
- model store
- new model store
---

# Import label files into the new model store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Import custom label files, or .ald files, into the new model store.

For developer documentation about code upgrade in Microsoft Dynamics AX 2012, see the downloadable [code upgrade white papers](https://go.microsoft.com/fwlink/?linkid=215083). See also *Inside Microsoft Dynamics AX 2009*, Chapter 18: “Code upgrade,” pp. 623–644.

## Importing label files into the new model store

### To import label files into the new model store

1.  On the Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 source system, create a label file for the layer that you are importing by using the **Label File Wizard**. Then copy the label file to the Microsoft Dynamics AX 2012 system.

2.  In the **Select file** dialog box, select the name of the label file that you want to import. You must select the label file that corresponds to the .aod file that you imported in the previous step of the **AOD code upgrade checklist**.

3.  Click **OK** to import the label file.

4.  In the **AOD code upgrade checklist**, continue with the next steps for the label file that you imported. Then return to this procedure when you are ready to import the next label file. You can then import the remaining layers one at a time, starting with the lowest layer.

## See also

[Restart Application Object Server](restart-application-object-server.md)

  



---
title: Import initial setup data
TOCTitle: Import initial setup data
ms:assetid: 943f1a1b-c8f6-4034-a3f6-c9b1988bd6c4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548605(v=AX.60)
ms:contentKeyID: 35132769
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Import initial setup data 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you plan to import data, you must complete this task before you start using Microsoft Dynamics AX in a production environment. Parameters, setup data, default data, and master data are typically imported for initial setup.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 and AX 2012 R2, data is imported only for the current partition.</P>



1.  Click **System administration** \> **Common** \> **Data export/import** \> **Import**. (The form can also be opened from the initialization checklist.)

2.  In the **Definition group** field, select a definition group.
    
    A definition group defines the tables and fields into which you will import data. (Click **System administration** \> **Common** \> **Data export/import** \> **Definition groups**.) Using a definition group is optional.

3.  In the **File name** field, enter the path of the file, and then click **Open**.
    
    The file type must be .dat, which is the file type that is used for a Standard export (instead of Excel or Custom) from Microsoft Dynamics AX.

4.  To run the import on the server, select the **Execute on AOS** check box.
    
    If this option is selected, the file that you selected in step 3 must be on the server, and you must have appropriate permissions to the server folder and the file.

5.  Click the **Advanced** tab to select additional options for the data import. Click the **Batch** tab to define batch processing parameters for the import.

6.  Click **OK** to start the data import.

## See also

[Data import, export and migration](data-import-export-and-migration.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


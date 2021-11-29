---
title: 'How to: Remove (Uninstall) a Model'
TOCTitle: 'How to: Remove (Uninstall) a Model'
ms:assetid: 6552673a-a386-4349-9438-64c0de94ca7d
ms:mtpsurl: https://technet.microsoft.com/library/Hh433514(v=AX.60)
ms:contentKeyID: 36941295
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: Remove (Uninstall) a Model 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can remove a model from a model store. However, we recommend that you remove a model only if you want to permanently delete it.

You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to perform this task.


> [!WARNING]
> <P>Deletion of a model or layer may cause significant loss of business data, and also loss of metadata. When you run a command to delete a model, we recommend that you use the –Details or /verbose parameter to list the elements that may be deleted. In this way, you can determine the effect of the deletion on your environment.</P>
> <UL>
> <LI>
> <P>Business data may be lost if the database schema is changed. The database schema is changed when tables or fields are removed.</P>
> <LI>
> <P>Element IDs may be lost. If element IDs are lost, existing business data may become invalid.</P>
> <LI>
> <P>Orphaned metadata elements in other models or layers are deleted.</P></LI></UL>



If you want to upgrade a model or replace a model with a newer version, we recommend that you import the model over the existing model. For more information about how to import models, see [How to: Export and Import a Model](how-to-export-and-import-a-model.md). We recommend this approach, because element IDs and element handles are assigned at installation. Therefore, if you delete a model, and then reimport that model or a newer version of it, element IDs and element handles are randomized, and data integrity can be affected. For more information about element IDs and element handles, see [Maintaining Installation-Specific Element IDs and Element Handles](maintaining-installation-specific-element-ids-and-element-handles.md).

### Validate permissions

  - Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

### Uninstall a model (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Uninstall-AXModel -Model <Modelname>
    ```
    
    This command uninstalls the specified model. By default, a confirmation request is displayed.
    
    For more information, see [Uninstall-AXModel](uninstall-axmodel.md).

### Uninstall a model (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil delete /model:<name>
    
    This command uninstalls the specified model. By default, a confirmation request is displayed.

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).


---
title: 'How to: Export and Import a Model Store'
TOCTitle: 'How to: Export and Import a Model Store'
ms:assetid: 754c52af-4025-4495-979c-f99d8c5b7d89
ms:mtpsurl: https://technet.microsoft.com/library/Hh433530(v=AX.60)
ms:contentKeyID: 36941318
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: Export and Import a Model Store 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can export and import a model store as a unit. If you must create similar environments, the preferred method is to export and import a model store. Additionally, we recommend that you use this method when you deploy major changes to a production environment. For more information about how to choose the method that you use to deploy a solution, see [Models, Layers, and the Model Store](models-layers-and-the-model-store.md).

When you export or import a model store, you affect all model elements, layers, and models.

You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to manage the model store.

## Preparing the system

### Validate permissions

  - Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

## Exporting a model store

The model store that you export remains in the original environment. The model store is not deleted.

### Export a model store (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Export-AXModelStore -File <Filename> -Details
    ```
    
    This command exports the model store to an .axmodelstore file.
    
    For more information, see [Export-AXModelStore](export-axmodelstore.md).

### Export a model store (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil exportstore /file:filename [/verbose]
    
    This command exports the model store to an .axmodelstore file.

## Importing a model store

When you import a model store, you can import the new model store directly to the default schema, dbo. Alternatively, you can import the model store to a different schema, and then apply the model store to the default schema.

  - If you import the new model store directly to the dbo schema, downtime is likely to be greater, because you must stop all Application Object Server (AOS) instances while the model store is imported.

  - If you import the model store file to a non-default schema, downtime may be less, because AOS instances can remain active throughout the import process.

AOS instances must be stopped when the new model store is applied to the default schema. However, less time is required to stop an AOS instance than to import a model store.

When you import a model store, you can back up the existing model store to another schema. The schema that you back up the model store to cannot exist before you import the model store.

By default, if a conflict of element IDs occurs while an .axmodelstore file is imported, the import is stopped.

By default, optimization steps are performed if the number of elements in a model increases by more than 50 percent when a model or model store is reimported. For more information, see [How to: Optimize a Model Store for Runtime](how-to-optimize-a-model-store-for-runtime.md).

### Import a model store to the dbo schema (Windows PowerShell)

1.  Drain all client connections from the AOS instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
        Import-AXModelStore -File <Filename> 
    
    This command imports a model store to the Microsoft Dynamics AX database and associates the model store with the default schema, dbo. You can also use the -BackupSchema parameter to copy the model store that is overwritten to a new schema. The schema that is specified by the -BackupSchema parameter cannot exist at the time that you run the cmdlet.
    
    For more information, see [Import-AXModelStore](import-axmodelstore.md).

### Install a model store to the dbo schema (AXUtil)

1.  Drain all client connections from the AOS instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  On the **Start** menu, click **Command prompt**.

3.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

4.  At the command prompt, type the following command, and then press ENTER.
    
        axutil importstore /file:filename
    
    This command imports a model store to the Microsoft Dynamics AX database and associates the model store with the default schema, dbo. You can also use the /BackupSchema parameter to copy the model store that is overwritten to a new schema. The schema that is specified by the /BackupSchema parameter cannot exist at the time that you run AXUtil.

### Import a model store to a temporary schema, and then apply the model store (Windows PowerShell)

1.  For this example, the non-default schema is named TemporarySchema.
    
    At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
        Import-AXModelStore -File Staging.axmodelstore -SchemaName TemporarySchema
    
    This command installs the model store file in the schema that you specify.
    

    > [!NOTE]
    > <P>The model store that you import to the non-default schema is not visible to Microsoft Dynamics AX.</P>



2.  After the model store has been imported, drain all client connections from the AOS instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

3.  After all AOS connections have been closed, type the following command, and then press ENTER.
    
        Import-AXModelStore -Apply:TemporarySchema
    
    This command applies a model store that was associated with the non-default schema, TemporarySchema, to the dbo schema. The model store then becomes visible to Microsoft Dynamics AX.
    
    For more information, see [Import-AXModelStore](import-axmodelstore.md).

### Install a model store to a temporary schema, and then apply the model store (AXUtil)

1.  For this example, the non-default schema is named TemporarySchema.
    
    On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil importstore /file:filename /schemaname:name /verbose
    
    This command installs the model store file in the schema that you specify.
    

    > [!NOTE]
    > <P>The model store that you import to the non-default schema is not visible to Microsoft Dynamics AX.</P>



4.  Drain the client connections that are connected to the AOS instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

5.  At the command prompt, type the following command, and then press ENTER.
    
        axutil importstore /apply /schemaname:TemporarySchema /verbose 
    
    This command applies a model store that was associated with the non-default schema, TemporarySchema, to the dbo schema. The model store then becomes visible to Microsoft Dynamics AX.

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).


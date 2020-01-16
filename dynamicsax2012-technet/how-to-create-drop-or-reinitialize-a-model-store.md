---
title: 'How to: Create, Drop, or Reinitialize a Model Store'
TOCTitle: 'How to: Create, Drop, or Reinitialize a Model Store'
ms:assetid: d978b12c-4e2c-4d36-93b1-b8b70f554ee5
ms:mtpsurl: https://technet.microsoft.com/library/Hh433540(v=AX.60)
ms:contentKeyID: 36941333
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: Create, Drop, or Reinitialize a Model Store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The model store is a database where all application elements for Microsoft Dynamics AX are stored. This topic describes how to create, remove, and reinitialize a model store.


> [!IMPORTANT]
> <P>In Microsoft Dynamics AX 2012 R2, the model store was moved into a database that is separate from the business database.</P>



The following table describes the scenarios in which you may want to create, remove, or reinitialize a model store.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Scenario</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create an empty model store.</p></td>
<td><p>You want to archive a version of a model store.</p></td>
</tr>
<tr class="even">
<td><p>Remove a temporary model store. A temporary model store is not associated with the dbo schema.</p></td>
<td><p>You created a temporary model store during import.</p></td>
</tr>
<tr class="odd">
<td><p>Initialize a model store. Initializing a model store recreates stored procedures, and creates tables if they do not exist.</p></td>
<td><p>The schema of the model store does not match the default model store.</p></td>
</tr>
</tbody>
</table>


You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to perform these tasks.

### Validate permissions

1.  If you are initializing a model store, you must drain the client connections that are connected to the Application Object Server (AOS) instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

### Create an empty model store (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Initialize-AXModelStore -AOSAccount "Domain\AccountName" -SchemaName <NewSchema> -Server <ServerName -Database <DatabaseName>
    ```
    
    This command creates an empty model store on the specified server, in the specified database, and in the specified schema. The command also grants access rights to the specified domain account.
    
    For more information, see [Initialize-AXModelStore](initialize-axmodelstore.md).

### Create an empty model store (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil schema /db:databasename /s:servername /config[[:aosinstance]:name] /schemaname:name 
    
    This command creates an empty model store on the specified server, in the specified database, and in the specified schema. The command also grants access rights to the specified domain account. If no parameters are provided, /config is the default.
    
    The /db parameter specifies the database name for the model store on the server. The database must exist before the connection. It cannot be used with the /config parameter. The default value is tempdb.
    
    The  /s parameter specifies the server name for the model store database. This parameter cannot be used with /config parameter. Default: "(local)".
    
    The /config parameter specifies an Application Object Server (AOS) configuration to use to determine the model store database and server name. The default for AOS instance is the name of the "01" AOS instance on the local computer. The default for name is the name of the current configuration on the specified instance. This parameter cannot be used with the /db or /s parameters.

### Remove a temporary, or non-dbo-schema, model store (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Initialize-AXModelStore –Drop <SchemaName> 
    ```
    
    This command removes the model store from the specified schema.
    

    > [!NOTE]
    > <P>Only model stores that are associated with non-default schemas can be removed. The model store that is associated with dbo cannot be removed.</P>

    
    For more information, see [Initialize-AXModelStore](initialize-axmodelstore.md).

### Remove a temporary, or non-dbo-schema, model store (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil schema /drop:name
    
    This command removes the model store from the specified schema.
    

    > [!NOTE]
    > <P>Only model stores that are associated with non-default schemas can be removed. The model store that is associated with dbo cannot be removed.</P>



### Reinitialize a model store (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Initialize-AXModelStore 
    ```
    
    This command reinitializes the default model store.
    
    For more information, see [Initialize-AXModelStore](initialize-axmodelstore.md).

### Reinitialize a model store (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil schema
    
    This command reinitializes the default model store.

## See also

[Troubleshooting working with model files](troubleshooting-working-with-model-files.md)

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).


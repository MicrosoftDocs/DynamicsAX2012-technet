---
title: Import-AXModelStore
TOCTitle: Import-AXModelStore
ms:assetid: 58EF9DEB-34C7-481D-931A-1E417AB9F94D
ms:mtpsurl: https://technet.microsoft.com/library/JJ720259(v=AX.60)
ms:contentKeyID: 49720043
author: tonyafehr
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Import-AXModelStore


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Import-AXModelStore

Imports a model store from a file to a database. Syntax

## Syntax

    Parameter Set: Default
    Import-AXModelStore [-Apply <String> ] [-BackupSchema <String> ] [-Config <String> ] [-Database <String> ] [-Details] [-File <FileInfo> ] [-IdConflict <String> ] [-NoPrompt] [-SchemaName <String> ] [-Server <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Import-AXModelStore cmdlet enables you to move metadata between environments by importing a model store from a file. You can either choose to import the new model store directly to the default schema (dbo), or you can import the model store to a different schema, and then apply it to the default schema.

If you import the new model store directly to the dbo schema, you are likely to incur greater downtime, because you must stop all Application Object Server (AOS) instances while the model store is being imported. If you import the model store file to a non-default schema, you may incur less downtime, because AOS instances can remain active throughout the import process. AOS instances must be stopped when the new model store is applied to the default schema, but this is a shorter process than import.

When you import a model store, you can back up the existing model store to another schema. If an element ID conflict occurs during import of an .axmodelstore file, the import will be stopped by default.

## Parameters

### \-Apply\<String\>

Moves a model store that has been imported into a non-default schema to the default schema (dbo) in a model store. This parameter is required if the **File** parameter has not been specified.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-BackupSchema\<String\>

Specifies a schema to move the model store to. The specified schema cannot exist at the time that you run the cmdlet, and must be a valid schema name.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-Config\<String\>

Specifies an Application Object Server (AOS) configuration to use to determine the model store database and server name. The default value is the currently active configuration. This parameter cannot be used with the -Database or -Server parameters. If no -Database, -Server, or -Config parameters are supplied, the default configuration is used.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-Database\<String\>

Specifies the database that contains the Microsoft Dynamics AX model store. This parameter cannot be used with the -Config parameter. If the -Database parameter is specified without a -Server parameter, the default server value of "(local)" is used.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-Details

Specifies that the cmdlet return additional details about the import process.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-File\<FileInfo\>

Identifies an .axmodelstore file to import to a Microsoft Dynamics AX database. This parameter is required if the **Apply** parameter has not been specified.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-IdConflict\<String\>

Allows element ID conflicts during the import of an .axmodelstore file. We recommend that you use this parameter cautiously because data may become corrupted.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-NoPrompt

Specifies that no prompts be shown during the import of an .axmodelstore file.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-SchemaName\<String\>

overwrite the default model store in the Microsoft Dynamics AX database. When this parameter is specified, the following message is generated, unless the -NoPrompt parameter is also specified:

This will import the models and metadata in the target database. This can be done with the AOS running and will temporarily impact server performance in the target system. It has no functional impact on the installation.

Use the /apply parameter later to enable the imported metadata.Continue (Y/N)?

Continue with this operation?

\[Y\] Yes \[N\] No \[S\] Suspend \[?\] Help (default is "Y"):

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \-Server\<String\>

Specifies the server that hosts the Microsoft Dynamics AX model store database. This parameter can only be used with the -Database parameter--it cannot be used by itself.

  

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Aliases</p></td>
<td><p>none</p></td>
</tr>
<tr class="even">
<td><p>Required?</p></td>
<td><p>false</p></td>
</tr>
<tr class="odd">
<td><p>Position?</p></td>
<td><p>named</p></td>
</tr>
<tr class="even">
<td><p>Default Value</p></td>
<td><p>none</p></td>
</tr>
<tr class="odd">
<td><p>Accept Pipeline Input?</p></td>
<td><p>false</p></td>
</tr>
<tr class="even">
<td><p>Accept Wildcard Characters?</p></td>
<td><p>false</p></td>
</tr>
</tbody>
</table>


### \<CommonParameters\>

This cmdlet supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, OutBuffer, OutVariable, WarningAction, and WarningVariable. For more information, see about\_CommonParameters https://go.microsoft.com/fwlink/?LinkID=113216

## Inputs

The input type is the type of the objects that you can pipe to the cmdlet.

  - **None**
    
    You cannot pipe input to this cmdlet.
    
      

## Outputs

The output type is the type of the objects that the cmdlet emits.

  - **None**
    
    The cmdlet does not generate any output.
    
      

## Examples

### Example 1: associate a model store with the default (dbo) schema

This example imports a model store to the Microsoft Dynamics AX database, and associates it with the default schema (dbo). In order to use this cmdlet without the -SchemaName parameter, all AOS instances must be stopped.

  

    PS C:\>Import-AXModelStore -File Staging.axmodelstore

### Example 2: associate a model store with a non-default schema

This example imports a model store to the Microsoft Dynamics AX database, and associates it with a non-default schema (TemporarySchema). The new model store is not be visible to Microsoft Dynamics AX until the imported model store has been applied to the default schema (dbo) by running Import-AXModelStore with the -Apply parameter.

  

    PS C:\>Import-AXModelStore -File Staging.axmodelstore -SchemaName TemporarySchema

### Example 3: move a model store from the non-default schema to the default schema

This example applies a model store that has been associated with the non-default schema TemporarySchema to the dbo schema, to make it visible to Microsoft Dynamics AX.

  

    PS C:\>Import-AXModelStore -Apply:TemporarySchema



``` 
PS C:\>
                        
```

## Related topics

  
[How to: Export and Import a Model Store](how-to-export-and-import-a-model-store.md)  
  
[Export-AXModelStore](export-axmodelstore.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


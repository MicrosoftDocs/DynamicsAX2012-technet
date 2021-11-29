---
title: Edit-AXModelManifest
TOCTitle: Edit-AXModelManifest
ms:assetid: DBDDFF16-8B0A-4166-B2C3-26AA4D2F500E
ms:mtpsurl: https://technet.microsoft.com/library/JJ720289(v=AX.60)
ms:contentKeyID: 49720080
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Edit-AXModelManifest


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Edit-AXModelManifest

Modifies the descriptive properties of a model in the Microsoft Dynamics AX model store database.

## Syntax

    Parameter Set: Default
    Edit-AXModelManifest -Model <String> [-Config <String> ] [-Database <String> ] [-ManifestFile <String> ] [-ManifestProperty <String> ] [-Server <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Edit-AXModelManifest cmdlet enables you to modify the descriptive properties of a model in the Microsoft Dynamics AX model store database. You can pass in an XML manifest file that contains a list of properties to change for a model, or you can change individual properties from the cmdlet. A manifest file can pass values for the following properties, in the data type indicated in parentheses: Name (String), DisplayName (String), Description (String), Publisher (String), Signed (Logical), Category (Int), InstallMode (Int), and Version. Version is a four-part indicator, in the format Number.Number.Number.Number, for example, 6.0.0.0. To change a manifest, you must identify the model, and pass in either a manifest file location, or the ManifestProperty that you want to change.

## Parameters

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

Specifies the the Microsoft Dynamics AX model store database. This parameter cannot be used with the -Config parameter. If the -Database parameter is specified without a -Server parameter, the default server value of "(local)" is used.

  

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


### \-ManifestFile\<String\>

Specifies an XML file that contains descriptive properties of a model (a model manifest file). Use the Get-AXModelManifest cmdlet with the -Xml parameter to output a sample manifest.

  

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


### \-ManifestProperty\<String\>

Specifies the properties to change. The properties that can be changed include the following, with data type indicated in parentheses: Name (String), DisplayName (String), Description (String), Publisher (String), Version, and InstallMode (String).

Property names are case-sensitive when they are passed in.

Version is a four-part indicator, in the format Number.Number.Number.Number, for example, 6.0.0.0.

Possible values for InstallMode are Standard, Overwrite, and Conflict. Standard stops the import process if a conflicting model element is encountered in the same layer. Overwrite replaces the existing model element with the imported model element. Conflict creates a conflict model that contains the conflicting model element in the related update layer. For example, for the ISV layer, the update layer is ISP. The default value is Standard.

**Note**: Manifests also include the following properties that cannot be modified through this cmdlet: Signed, Layer, Category.

  

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


### \-Model\<String\>

Specifies the model in the Microsoft Dynamics AX model store database to update.

  

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
<td><p>true</p></td>
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

  - **Manifest (XML)**
    
    Example of a manifest XML file:
    
    \<?xml version="1.0" encoding="utf-8"?\>
    
    \<ModelManifest SchemaVersion="1.5" ModelFileVersion="7"\>
    
    \<Name\>Public Sector\</Name\>
    
    \<DisplayName\>PS\</DisplayName\>
    
    \<Description\>Public Sector for Microsoft Dynamics AX\</Description\>
    
    \<Publisher\>Microsoft Corporation\</Publisher\>
    
    \<InstallMode\>Standard\</InstallMode\>
    
    \<Version\>6.0.0.0\</Version\>
    
    \</ModelManifest\>
    
      

## Outputs

The output type is the type of the objects that the cmdlet emits.

  - **ModelManifest**
    
    Returns the model manifest.
    
      

## Examples


This example sets the version of the model LitwareMigration to the value 2.2.0.0.

  

    PS C:\>Edit-AXModelManifest -Model LitwareMigration -Property "Version=2.2.0.0"



``` 
PS C:\>
                        
```

## Related topics

  
[How to: View or Change the Manifest Properties of a Model](how-to-view-or-change-the-manifest-properties-of-a-model.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


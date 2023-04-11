---
title: Export-AXModel
TOCTitle: Export-AXModel
ms:assetid: 6A37B6EB-1001-48F4-9C33-38A3E97BFF18
ms:mtpsurl: https://technet.microsoft.com/library/JJ720261(v=AX.60)
ms:contentKeyID: 49720050
author: tonyafehr
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Export-AXModel


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Export-AXModel

Exports a Microsoft Dynamics AX model to an .axmodel file.

## Syntax

    Parameter Set: Default
    Export-AXModel -File <String> -Model <String> [-Config <String> ] [-Database <String> ] [-Key <String> ] [-ManifestFile <String> ] [-Server <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Export-AXModel cmdlet exports a Microsoft Dynamics AX model to an .axmodel file. Use this cmdlet to move models between environments and to strong-name sign a model file.

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

Specifies the Microsoft Dynamics AX model store database. This parameter cannot be used with the -Config parameter. If the -Database parameter is specified without a -Server parameter, the default server value of "(local)" is used.

  

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


### \-File\<String\>

Specifies the name and location of the .axmodel file to create.

  

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


### \-Key\<String\>

Specifies the strong-name key pair file to use to sign a model. To strong-name sign a model, you must use the Strong Name Tool (SN.exe) to generate a key pair file.

  

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

Specifies an XML file that identifies a model. Use the Get-AXModelManifest cmdlet with the -Xml parameter to output a sample manifest file.

  

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

Specifies the name of the model to export.

  

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

  - **None**
    
    You cannot pipe input to this cmdlet.
    
      

## Outputs

The output type is the type of the objects that the cmdlet emits.

  - **ModelManifest**
    
    Returns the model manifest class.
    
      

## Examples

### Example 1: Export a model

This example exports the Packaging model to the file Packaging.axmodel.

  

    PS C:\>Export-AXModel -model Packaging -file c:\models\Packaging.axmodel

### Example 2: Export a signed model

This example exports the Packaging model to the file PackagingSigned.axmodel, and signs it with the previously generated key file mykey.snk.

  

    PS C:\>Export-AXModel -model Packaging -file c:\models\PackagingSigned.axmodel -key c:\keys\mykey.snk

## Related topics

  
[How to: Export and Import a Model](how-to-export-and-import-a-model.md)  
  
[Install-AXModel](install-axmodel.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


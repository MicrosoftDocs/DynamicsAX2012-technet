---
title: Get-AXModelManifest
TOCTitle: Get-AXModelManifest
ms:assetid: E0AB4577-5FB8-4A33-941B-A480583A402D
ms:mtpsurl: https://technet.microsoft.com/library/JJ720291(v=AX.60)
ms:contentKeyID: 49720076
author: Khairunj
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# Get-AXModelManifest

## Get-AXModelManifest

Retrieves the properties of a model file.

## Syntax

    Parameter Set: Default
    Get-AXModelManifest [-Config <String> ] [-Database <String> ] [-File <String> ] [-Model <String> ] [-Server <String> ] [-Xml] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXModelManifest cmdlet retrieves the properties of a model. It can be used to retrieve properties from a model in a model store or an .axmodel file. The cmdlet can also be used to output an XML version of a model manifest. This cmdlet returns all properties of a model, including properties that you cannot set values for, such as Category, Signed, and Layer.

Possible values for Category are Standard, Hotfix, and Virtual. Most models are in the Standard category. Hotfix describes the models that are created by the Microsoft sustained engineering team. Virtual describes models that are created by using the Install-AXModel cmdlet with the -CreateParents parameter.

Signed indicates whether a model has been signed.

Layer indicates the name of the layer that the model is in.

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

Specifies an .axmodel file to retrieve the manifest properties from.

  

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

Specifies a model to get the manifest for.

  

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


### \-Xml

Specifies that the model manifest should be returned in XML format, which can be piped to a file.

  

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

This cmdlet supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, OutBuffer, OutVariable, WarningAction, and WarningVariable. For more information, see about\_CommonParameters http://go.microsoft.com/fwlink/?LinkID=113216

## Inputs

The input type is the type of the objects that you can pipe to the cmdlet.

  - **None**
    
    You cannot pipe input to this cmdlet.
    
      

## Outputs

The output type is the type of the objects that the cmdlet emits.

  - **ModelManifest**
    
    Returns the model manifest class.
    
      

## Examples

### Example 1: Return an XML file

This example outputs an XML manifest from the model MyModel.

  

    PS C:\>Get-AXModelManifest -File MyModel -Xml

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">&lt;?xml version="1.0" encoding="utf-8"?&gt;
<br />&lt;ModelManifest SchemaVersion="1.9" ModelFileVersion="17" ElementCount="0"&gt;
<br />&lt;Name&gt;MyModel&lt;/Name&gt;
<br />&lt;DisplayName&gt;MyModel&lt;/DisplayName&gt;
<br />&lt;Description /&gt;
<br />&lt;Publisher /&gt;
<br />&lt;Signed&gt;false&lt;/Signed&gt;
<br />&lt;Category&gt;Standard&lt;/Category&gt;
<br />&lt;InstallMode&gt;Standard&lt;/InstallMode&gt;
<br />&lt;Version&gt;1.0.0.0&lt;/Version&gt;
<br />&lt;Layer&gt;ISV&lt;/Layer&gt;
<br />&lt;DependencyState /&gt;
<br />&lt;/ModelManifest&gt;PS C:\Windows\system32&gt;</pre>


### Example 2: output a manifest

This example outputs a manifest from the model MyModel.

  

    PS C:\>Get-AXModelManifest -File MyModel

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">Category : Standard
<br />DependencyState :
<br />Description :
<br />DisplayName : MyModel
<br />InstallMode : Standard
<br />Layer : Usr
<br />Name : MyModel
<br />Publisher :
<br />Signed : False
<br />Version : 1.0.0.0
<br />Details :</pre>




``` 
PS C:\>
                        
```

## Related topics

  
[How to: View or Change the Manifest Properties of a Model](how-to-view-or-change-the-manifest-properties-of-a-model.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


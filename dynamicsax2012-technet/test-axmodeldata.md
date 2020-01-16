---
title: Test-AXModelData
TOCTitle: Test-AXModelData
ms:assetid: 3C0ECDB1-9201-4C47-8E95-3034243D9BD1
ms:mtpsurl: https://technet.microsoft.com/library/JJ720251(v=AX.60)
ms:contentKeyID: 49720041
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Test-AXModelData

## Test-AXModelData

Verifies whether a specified model or layer contains data.

## Syntax

    Parameter Set: Default
    Test-AXModelData [-Config <String> ] [-Database <String> ] [-Layer <String> ] [-ManifestFile <String> ] [-Model <String> ] [-Server <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Test-AXModelData cmdlet verifies whether a specified model or layer contains data.

## Parameters

### \-Config\<String\>

Specifies an Application Object Server (AOS) configuration to use to determine the model store database and server name. The default value is the configuration that is currently active. This parameter cannot be used with the -Database or -Server parameters. If no -Database, -Server, or -Config parameters are supplied, the default configuration is used.

  

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


### \-Layer\<String\>

Specifies a layer to be tested. This parameter is required if the **Model** parameter has not been specified.

  

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

Specifies an XML file that identifies a model.

  

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

Specifies a model to be tested. This parameter is required if the **Layer** parameter has not been specified.

  

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

  - **ModelManifest**
    
    Returns the model manifest class.
    
      

## Examples


This example tests whether the USR layer contains data, and displays the outcome to the screen.

  

    PS C:\>Test-AXModelData -Layer USR -Verbose

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">VERBOSE: AXUtil 6.0 - Microsoft Dynamics AX Admin Utility (6.0.906.0)
(c) Copyright, Microsoft Corporation, 2011. All rights reserved.
<br />VERBOSE:
<br />VERBOSE: The AXUtil command was started in the mode: EXISTS.
<br />VERBOSE:
<br />VERBOSE: Working against model store RDVM806000-GU/MicrosoftDynamicsAX.
<br />VERBOSE:
<br />VERBOSE: Model data exists in Usr layer.
<br />VERBOSE:</pre>




``` 
PS C:\>
                        
```

## Related topics

  
[How to: View and verify contents of a model](how-to-view-and-verify-contents-of-a-model.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


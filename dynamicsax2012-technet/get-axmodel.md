---
title: Get-AXModel
TOCTitle: Get-AXModel
ms:assetid: 470C2556-10CF-493F-883F-0FEAD27DA49A
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ720257(v=AX.60)
ms:contentKeyID: 49720046
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# Get-AXModel

## Get-AXModel

Returns a list of the models in the model store, or a list of elements from a particular model or model file.

## Syntax

    Parameter Set: Default
    Get-AXModel [-All] [-Config <String> ] [-Database <String> ] [-Details] [-File <String> ] [-Layer <String> ] [-ManifestFile <String> ] [-Model <String> ] [-Server <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXModel cmdlet returns a list of the models in the model store, or a list of elements from a particular model or model file. By default, system-generated models are only returned if they contain data.

## Parameters

### \-All

Specifies that a list of all models be returned, whether or not they contain data. If you do not use this parameter, system-generated models that do not contain data are not returned.

  

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

Specifies an Application Object Server (AOS) configuration to use to determine the model store database and server name. The default value is the currently active configuration. This parameter cannot be used with the Database or Server parameters. If no Database or Server parameters are supplied, the default configuration is used.

  

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


### \-Details

Specifies that additional details about the contents of a model or model file should be returned. Details returned include the Path, Name, ElementHandle, ParentHAndle, ElementType, and InModel.

  

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

Specifies the name and location of an .axmodel file.

  

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

Specifies the three-letter name of the Microsoft Dynamics AX layer to return, for example, VAR.

  

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

Specifies the name of the model to retrieve.

  

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

This cmdlet supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, OutBuffer, OutVariable, WarningAction, and WarningVariable. For more information, see about\_CommonParameters http://go.microsoft.com/fwlink/?LinkID=113216

## Inputs

The input type is the type of the objects that you can pipe to the cmdlet.

  - **None**
    
    You cannot pipe input to this cmdlet.
    
      

## Outputs

The output type is the type of the objects that the cmdlet emits.

  - **ModelManifest**
    
    Returns the model manifest class
    
      

## Examples

### Example 1: SYS layer models

This example returns a list of the models, their IDs, names, versions, and publishers in the SYS layer.

  

    PS C:\>Get-AXModel -Layer SYS

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />ID Layer                        Model    Version                   Publisher
----- ----- ---------------------------- ---------- ---------------------------
<br />1   Sys                    SYS Model    1.0.0.0
<br />17   Sys              SYS Application    6.0.0.0              Microsoft Corp
<br />21   Sys                   SYS Labels    6.0.0.0              Microsoft Corp</pre>


### Example 2: USR layer models

This example returns a list of the model "USR Model".

  

    PS C:\>(Get-AXModel -Model "USR Model" -Details).Elements | Out-String

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">Path          : \Forms\TaxYearlyComReport_IT\Designs\DesignList\TaxData
<br />Name          : TaxData
<br />ElementHandle : 467440
<br />ParentHandle  : 467429
<br />ElementType   : FormControl
<br />InModel       : True
<br />ModelId       : 0
<br />Layer         : Sys

<br />Path          : \Forms\TaxYearlyComReport_IT\Designs\DesignList\TaxPayer
<br />Name          : TaxPayer
<br />ElementHandle : 467436
<br />ParentHandle  : 467429
<br />ElementType   : FormControl
<br />InModel       : True
<br />ModelId       : 0
<br />Layer         : Sys

<br />Path          : \Forms\TaxYearlyComReport_IT\Designs\DesignList\Writer
<br />Name          : Writer
<br />ElementHandle : 467437
<br />ParentHandle  : 467429
<br />ElementType   : FormControl
<br />InModel       : True
<br />ModelId       : 0
<br />Layer         : Sys
<br /><br />Path          : \Jobs\Job1
<br />Name          : Job1
<br />ElementHandle : 554360
<br />ParentHandle  : 0
<br />ElementType   : Job
<br />InModel       : True
<br />ModelId       : 0
<br />Layer         : Sys
<br /><br />Path          : \SSRS Reports\Report Datasources\DynamicsAXOLAP
<br />Name          : DynamicsAXOLAP
<br />ElementHandle : 505471
<br />ParentHandle  : 0
<br />ElementType   : SSRSReportDatasource
<br />InModel       : True
<br />ModelId       : 0
<br />Layer         : Sys</pre>




``` 
PS C:\>
                        
```

## Related topics

  
[How to: View and verify contents of a model](how-to-view-and-verify-contents-of-a-model.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


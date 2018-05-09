---
title: Optimize-AXModelStore
TOCTitle: Optimize-AXModelStore
ms:assetid: B1A6F7BA-79ED-43B0-A3F3-DAF4E1246662
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ720277(v=AX.60)
ms:contentKeyID: 49720066
ms.date: 04/28/2013
mtps_version: v=AX.60
---

# Optimize-AXModelStore

## Optimize-AXModelStore

Runs a series of steps to optimize the model store for runtime performance.

## Syntax

    Parameter Set: Default
    Optimize-AXModelStore [-Config <String> ] [-Database <String> ] [-Server <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Optimize-AXModelStore cmdlet runs a series of steps to optimize the model store for runtime performance. These steps include re-indexing the database that contains the model store, and performing a DBCC SHRINKDATABASE command. Optimization is performed, by default, when models are installed. This cmdlet is only required when optimization has been switched off during model installation.

In versions of Microsoft Dynamics AX 2012 prior to Microsoft Dynamics AX 2012 R2, the model store tables are stored in the same database as the business data. If your environment contains a large combined business and model store database, we recommend that you avoid running the Microsoft Dynamics AX optimization command. Instead, we suggest that you create a Microsoft SQL Server maintenance plan that reindexes the database.

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

  - **None**
    
    You cannot pipe input to this cmdlet.
    
      

## Examples


This example optimizes the model store in the Production database.

  

    PS C:\>Optimize-AXModelStore -Database Production



``` 
PS C:\>
                        
```

## Related topics

  
[How to: Optimize a Model Store for Runtime](how-to-optimize-a-model-store-for-runtime.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


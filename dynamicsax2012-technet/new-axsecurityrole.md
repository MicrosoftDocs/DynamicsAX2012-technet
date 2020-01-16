---
title: New-AXSecurityRole
TOCTitle: New-AXSecurityRole
ms:assetid: B63231AF-FE63-4D13-9787-D7563C920D7A
ms:mtpsurl: https://technet.microsoft.com/library/JJ720280(v=AX.60)
ms:contentKeyID: 49720070
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# New-AXSecurityRole

## New-AXSecurityRole

Creates a new Microsoft Dynamics AX security role.

## Syntax

    Parameter Set: Default
    New-AXSecurityRole -AOTName <String> -Description <String> -Name <String> [ <CommonParameters>]

  
  

## Detailed description

The New-AXSecurityRole cmdlet creates a new Microsoft Dynamics AX security role.

## Parameters

### \-AOTName\<String\>

Specifies the name in the AOT of the Microsoft Dynamics AX security role.

  

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


### \-Description\<String\>

Specifies a description for the Microsoft Dynamics AX security role.

  

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


### \-Name\<String\>

Specifies a name for the new Microsoft Dynamics AX security role.

  

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


This example creates the Tester security role in Microsoft Dynamics AX.

  

    C:\PS>New-AXSecurityRole -Name Tester -AOTName Tester -Description "Tests customizations"

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />RecId Name                Description         AOTName<br />----- ----                -----------         -------<br />1599507 Tester              Tests customizations Tester<br /></pre>


  
  
Copyright Microsoft Corporation. All rights reserved.


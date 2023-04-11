---
title: Get-AXSecurityRoleMember
TOCTitle: Get-AXSecurityRoleMember
ms:assetid: C3B88DD0-D326-4F12-9CCF-BC123BE49BDD
ms:mtpsurl: https://technet.microsoft.com/library/JJ720284(v=AX.60)
ms:contentKeyID: 49720073
author: tonyafehr
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Get-AXSecurityRoleMember


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Get-AXSecurityRoleMember

Returns a list of Microsoft Dynamics AX user IDs associated with the specified security role.

## Syntax

    Parameter Set: Default
    Get-AXSecurityRoleMember -AOTName <String> [-PartitionKey <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXSecurityRoleMember cmdlet returns a list of Microsoft Dynamics AX user IDs that are members of the specified security role.

## Parameters

### \-AOTName\<String\>

Specifies the AOTName of the Microsoft Dynamics AX security role to return information about.

  

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


### \-PartitionKey\<String\>

Specifies the partition to return information about. By default, the cmdlet returns information about the initial partition.

  

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


This example retrieves all members of the system administrators security role in Microsoft Dynamics AX.

  

    C:\PS>Get-AXSecurityRoleMember -AOTName InventCostClerk

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />InventCostClerk<br /><br />brian<br /></pre>


## Related topics

  
[Add-AXSecurityRoleMember](add-axsecurityrolemember.md)  
  
[Get-AXPartitionInfo](get-axpartitioninfo.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


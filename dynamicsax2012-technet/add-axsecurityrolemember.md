---
title: Add-AXSecurityRoleMember
TOCTitle: Add-AXSecurityRoleMember
ms:assetid: 7D6028DE-08F5-45A5-AC36-9B5548368F8A
ms:mtpsurl: https://technet.microsoft.com/library/JJ720265(v=AX.60)
ms:contentKeyID: 49720053
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Add-AXSecurityRoleMember

## Add-AXSecurityRoleMember

Adds a Microsoft Dynamics AX user to a Microsoft Dynamics AX security role.

## Syntax

    Parameter Set: Default
    Add-AXSecurityRoleMember -AOTName <String> -AxUserID <String> [-PartitionKey <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Add-AXSecurityRoleMember cmdlet adds a Microsoft Dynamics AX user to a Microsoft Dynamics AX security role.

## Parameters

### \-AOTName\<String\>

Specifies the name that is used in the AOT for the Microsoft Dynamics AX security role to add the user to.

  

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


### \-AxUserID\<String\>

Specifies the Microsoft Dynamics AX User ID to add to the Microsoft Dynamics AX security role.

  

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

Specifies the partition to add the security role to. By default, the security role is added to the initial partition.

  

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


This example adds the user Vamsi Kuppa (vamsik) to the Microsoft Dynamics AX LedgerAccountant security role.

  

    C:\PS>Add-AXSecurityRoleMember -AxUserID vamsik -AOTName LedgerAccountant

## Related topics

  
Remove-AXSecurityRoleMember  
  
[Get-AXPartitionInfo](get-axpartitioninfo.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


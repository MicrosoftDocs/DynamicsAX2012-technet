---
title: Remove-AXSecurityRole
TOCTitle: Remove-AXSecurityRole
ms:assetid: BAD5A9D8-8A91-48F5-ACFB-A5DF5253B680
ms:mtpsurl: https://technet.microsoft.com/library/JJ720281(v=AX.60)
ms:contentKeyID: 49720069
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Remove-AXSecurityRole


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Remove-AXSecurityRole

Removes a security role from Microsoft Dynamics AX.

## Syntax

    Parameter Set: Default
    Remove-AXSecurityRole -AOTName <String> [ <CommonParameters>]

  
  

## Detailed description

The Remove-AXSecurityRole cmdlet removes a security role from Microsoft Dynamics AX.

## Parameters

### \-AOTName\<String\>

Specifies the AOTName of the security role to be removed.

  

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


This example removes the Tester security role from Microsoft Dynamics AX.

  

    C:\PS>Remove-AXSecurityRole -AOTName Tester

  
  
Copyright Microsoft Corporation. All rights reserved.


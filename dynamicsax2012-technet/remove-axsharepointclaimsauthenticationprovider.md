---
title: Remove-AXSharepointClaimsAuthenticationProvider
TOCTitle: Remove-AXSharepointClaimsAuthenticationProvider
ms:assetid: C23DBDF4-2AAD-4DFD-B6B5-9E27EAD9F9BE
ms:mtpsurl: https://technet.microsoft.com/library/JJ720283(v=AX.60)
ms:contentKeyID: 49720072
author: tonyafehr
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Remove-AXSharepointClaimsAuthenticationProvider


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Remove-AXSharepointClaimsAuthenticationProvider

Unregisters a claims authentication provider from the local Microsoft SharePoint Server and deletes the web application associated with it.

## Syntax

    Parameter Set: Default
    Remove-AXSharepointClaimsAuthenticationProvider -Name <String> [ <CommonParameters>]

  
  

## Detailed description

The Remove-AXSharePointClaimsAuthenticationProvider cmdlet unregisters a claims authentication provider from SharePoint Server and deletes the web application associated with it.

## Parameters

### \-Name\<String\>

Specifies the name of the claims authentication provider to be unregistered.

  

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


This example removes the LIVE-CONTOSO provider.

  

    C:\PS>Remove-AXSharepointClaimsAuthenticationProvider -Name LIVE-CONTOSO

## Related topics

  
[Add-AXSharepointClaimsAuthenticationProvider](add-axsharepointclaimsauthenticationprovider.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


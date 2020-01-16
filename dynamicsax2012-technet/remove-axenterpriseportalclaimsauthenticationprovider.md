---
title: Remove-AXEnterprisePortalClaimsAuthenticationProvider
TOCTitle: Remove-AXEnterprisePortalClaimsAuthenticationProvider
ms:assetid: 627DA167-BA8A-49F0-BDBB-6972FCABFA47
ms:mtpsurl: https://technet.microsoft.com/library/JJ720260(v=AX.60)
ms:contentKeyID: 49720049
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Remove-AXEnterprisePortalClaimsAuthenticationProvider

## Remove-AXEnterprisePortalClaimsAuthenticationProvider

Removes a registered claims-based authentication provider from the Enterprise Portal server.

## Syntax

    Parameter Set: Default
    Remove-AXEnterprisePortalClaimsAuthenticationProvider -Name <String> -URL <String> [ <CommonParameters>]

  
  

## Detailed description

The Remove-AXEnterprisePortalClaimsAuthenticationProvider cmdlet removes a registered claims-based authentication provider from Enterprise Portal. The associated users no longer have access to the web application.

## Parameters

### \-Name\<String\>

The name of the trusted identify provider to be removed.

  

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


### \-URL\<String\>

The Enterprise Portal Server website URL to remove the claims authentication provider from.

  

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

This cmdlet supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, OutBuffer, OutVariable, WarningAction, and WarningVariable. For more information, see about\_CommonParameters http://go.microsoft.com/fwlink/?LinkID=113216

## Inputs

The input type is the type of the objects that you can pipe to the cmdlet.

  - **None**
    
      
    You cannot pipe input to this cmdlet.  
    
      

## Outputs

The output type is the type of the objects that the cmdlet emits.

  - **None**
    
      
    The cmdlet does not generate any output.  
    
      

## Examples


This example removes the LIVE-CONTOSO authentication provider from the DynamicsAXEP Enterprise Portal site.

  

    C:\PS>Remove-AXEnterprisePortalClaimsAuthenticationProvider -Name LIVE-CONTOSO -URL https://DynamicsAXEP:5000

## Related topics

  
[Add-AXEnterprisePortalClaimsAuthenticationProvider](add-axenterpriseportalclaimsauthenticationprovider.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


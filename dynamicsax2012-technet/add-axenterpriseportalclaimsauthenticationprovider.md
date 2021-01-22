---
title: Add-AXEnterprisePortalClaimsAuthenticationProvider
TOCTitle: Add-AXEnterprisePortalClaimsAuthenticationProvider
ms:assetid: 93AEDF6E-7DA8-4FB5-89C3-8BCBA3B92916
ms:mtpsurl: https://technet.microsoft.com/library/JJ720269(v=AX.60)
ms:contentKeyID: 49720058
author: Khairunj
ms.author: daxcpft
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Add-AXEnterprisePortalClaimsAuthenticationProvider

## Add-AXEnterprisePortalClaimsAuthenticationProvider

Adds a registered claims-based authentication provider to the Enterprise Portal server.

## Syntax

    Parameter Set: Default
    Add-AXEnterprisePortalClaimsAuthenticationProvider -Name <String> -URL <String> [ <CommonParameters>]

  
  

## Detailed description

The Add-AXEnterprisePortalClaimsAuthenticationProvider cmdlet associates an existing Microsoft SharePoint Server claims authentication provider with an Enterprise Portal site. All users of the authentication provider are added as users to the Enterprise Portal web application and are granted full control of the web application.

## Parameters

### \-Name\<String\>

Specifies the name of the trusted identity provider that will be used to register the provider with SharePoint Server. The provider name will be used as the domain for the claims-based users that are registered with the provider. The provider name must be registered with the Enterprise Portal website.

  

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

Specifies the URL for the Enterprise Portal site with which to register the claims authentication provider.

  

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


This example adds the LIVE-CONTOSO authentication provider to the Enterprise Portal site https://CONTOSO:5005.

  

    C:\PS>Add-AXEnterprisePortalClaimsAuthenticationProvider -Name LIVE-CONTOSO -URL "https://contoso:5005"

  
  
Copyright Microsoft Corporation. All rights reserved.


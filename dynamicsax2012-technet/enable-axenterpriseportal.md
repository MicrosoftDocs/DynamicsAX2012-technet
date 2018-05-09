---
title: Enable-AXEnterprisePortal
TOCTitle: Enable-AXEnterprisePortal
ms:assetid: A794347A-EA1B-47FF-A466-0B887A00D194
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ720276(v=AX.60)
ms:contentKeyID: 49720065
ms.date: 02/19/2013
mtps_version: v=AX.60
---

# Enable-AXEnterprisePortal

## Enable-AXEnterprisePortal

Deploys a new virtual server site to an IIS web server that already has Enterprise Portal installed.

## Syntax

    Parameter Set: Default
    Enable-AXEnterprisePortal -Credential <PSCredential> -WebApplication <String> [ <CommonParameters>]

  
  

## Detailed description

The Enable-AXEnterprisePortal cmdlet deploys a new virtual server site to an IIS web server that already has Enterprise Portal installed.

This cmdlet cannot be run remotely.

## Parameters

### \-Credential\<PSCredential\>

The credentials to use when running the command. The account provided must be the .NET Business Connector proxy account.

  

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


### \-WebApplication\<String\>

The name of the web application on which the new Enterprise Portal site will be deployed.

  

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


The following example creates the default DynamicsAx virtual server site to be used for Enterprise Portal development in the "SharePoint – 80" web application. Because the required credentials parameter is not supplied with the cmdlet, the user will be prompted to enter administrator credentials.

  

    PS C:\>Enable-AxEnterprisePortal –webapplication "SharePoint – 80" 
    ---



``` 
PS C:\>
                        
```

  
  
Copyright Microsoft Corporation. All rights reserved.


---
title: New-AXClaimsAwareEnterprisePortalServer
TOCTitle: New-AXClaimsAwareEnterprisePortalServer
ms:assetid: 26DC4045-7F50-412A-93A9-396C8AAE8DB1
ms:mtpsurl: https://technet.microsoft.com/library/JJ720244(v=AX.60)
ms:contentKeyID: 49720033
author: Khairunj
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# New-AXClaimsAwareEnterprisePortalServer

## New-AXClaimsAwareEnterprisePortalServer

Creates a claims-aware instance of Enterprise Portal.

## Syntax

    Parameter Set: Default
    New-AXClaimsAwareEnterprisePortalServer [-ClearTextPassword <String> ] [-Credential <PSCredential> ] [-Port <Int32> ] [-SSLCertificate <X509Certificate2> ] [-UseNTLMExclusively] [-UserName <String> ] [ <CommonParameters>]

  
  

## Detailed description

The New-AXClaimsAwareEnterprisePortalServer cmdlet creates a claims-aware SharePoint web application and installs an instance of Enterprise Portal.

## Parameters

### \-ClearTextPassword\<String\>

Sends the password of the business connector proxy in clear text, rather than encrypted. UserName and ClearTextPassword are a way to specify the business connector proxy account. They cannot be used with the Credential parameter. UserName and ClearTextPassword are often used in scripts in which no user interaction is expected.

When the cmdlet is executed, this account is added to the list of SharePoint farm administrators. Also, the claims-based Enterprise Portal SharePoint web application uses this account as its IIS application pool identity.

Important: Using an account other than the business connector proxy account can result in errors when accessing Microsoft Dynamics AX through Enterprise Portal.

  

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


### \-Credential\<PSCredential\>

Specifies an account with administrator privileges on the SharePoint site. You must use the Business Connector proxy account. The Credential parameter cannot be used with the UserName and ClearTextPassword parameters.

When the cmdlet is executed, this account is added to the list of SharePoint farm administrators. Also, the claims-based Enterprise Portal SharePoint web application uses this account as its IIS application pool identity.

Important: Using an account other than the business connector proxy account can result in errors when accessing Microsoft Dynamics AX through Enterprise Portal.

  

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


### \-Port\<Int32\>

Specifies which port to install Enterprise Portal on. This must be a port that is not already in use. If you attempt to create a web application on a port that is already in use, an error is returned.

  

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


### \-SSLCertificate\<X509Certificate2\>

Specifies the secure socket layer (SSL) certificate to use for Enterprise Portal. The common name (CN) of the SSL certificate must be the name of the computer that you are installing Enterprise Portal on and are running the cmdlet on.

  

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


### \-UseNTLMExclusively

Configures the web application for Enterprise Portal to use the NTLM method of Windows authentication.

  

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


### \-UserName\<String\>

Specifies the username of the administrator for the SharePoint Server web application that will be created. You must use the Business Connector proxy account.

UserName and ClearTextPassword are a way to specify the business connector proxy account. They cannot be used with the Credential parameter. UserName and ClearTextPassword are often used in scripts in which no user interaction is expected.

When the cmdlet is executed, this account is added to the list of SharePoint farm administrators. Also, the claims-based Enterprise Portal SharePoint web application uses this account as its IIS application pool identity.

Important: Using an account other than the business connector proxy account can result in errors when accessing Microsoft Dynamics AX through Enterprise Portal.

  

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
    
      
    The cmdlet does not generate any output.  
    
      

## Examples


This example creates a claims aware SharePoint web application that uses Secure Socket Layers and installs an instance of Enterprise Portal on port 5000. The variables in the example were given values in previous statements.  
$Cred = Get-Credential  
$SSLCert = Get-PfxCertificate c:\\certs\\SSLCertForEP.pfx

  

    C:\PS>New-AXClaimsAwareEnterprisePortalServer -Credential $Cred -Port 5000 -SSLCertificate $SSLCert

  
  
Copyright Microsoft Corporation. All rights reserved.


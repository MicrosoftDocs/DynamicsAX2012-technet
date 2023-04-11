---
title: Add-AXSharepointClaimsAuthenticationProvider
TOCTitle: Add-AXSharepointClaimsAuthenticationProvider
ms:assetid: 3C9C6812-F9C1-426D-A06E-1A35C3CAA03A
ms:mtpsurl: https://technet.microsoft.com/library/JJ720252(v=AX.60)
ms:contentKeyID: 49720039
author: tfehr
ms.author: daxcpft
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Add-AXSharepointClaimsAuthenticationProvider


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Add-AXSharepointClaimsAuthenticationProvider

Adds a claims-based authentication provider to a Microsoft SharePoint Server installation. It also creates a web application associated with the provider where applicable.

## Syntax

    Parameter Set: Default
    Add-AXSharepointClaimsAuthenticationProvider -Name <String> -SigningCertificate <X509Certificate2> -Type <String> [-ClearTextPassword <String> ] [-ConnectionString <String> ] [-Credential <PSCredential> ] [-Port <Int32> ] [-ServerUrl <String> ] [-SSLCertificate <X509Certificate2> ] [-UserName <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Add-AXSharepointClaimsAuthenticationProvider adds a claims-based authentication provider to a SharePoint Server installation and creates a web application associated with it when the type of authentication provider is Forms.

## Parameters

### \-ClearTextPassword\<String\>

Sends the password of the business connector proxy account in clear text, rather than encrypted. UserName and ClearTextPassword are a way to specify the business connector proxy account. They cannot be used with the Credential parameter. UserName and ClearTextPassword are often used in scripts in which no user interaction is expected.

The SharePoint security token server (STS) web application created by this cmdlet uses this account as its IIS application pool identity.

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


### \-ConnectionString\<String\>

Specifies the string to use to connect to the ASP.NET SQLMembership database that is used for forms-based authentication.

  

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

The SharePoint security token server (STS) web application created by this cmdlet uses this account as its IIS application pool identity.

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


### \-Name\<String\>

Specifies the name to be associated with the authentication provider. When creating users in a forms-based authentication provider using New-AXUser, the value of this parameter is specified for the –UserDomain parameter.

  

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


### \-Port\<Int32\>

Specifies the port on which the authentication provider SharePoint web application is created. The Port parameter is only valid for use with forms-based authentication—it cannot be specified if the provider is ADFS. If the specified port is already in use, the cmdlet returns an error.

  

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

Specifies the Secure Socket Layer (SSL) certificate to be associated with the SharePoint web application created for the authentication provider. SSL is required with forms-based authentication to help ensure the security of the credentials presented by the user to the forms-based authentication provider SharePoint web application. This parameter is not required for Type ADFS.

  

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


### \-ServerUrl\<String\>

Specifies the Federation Service URL for the Active Directory Federation Service (ADFS) provider. This parameter is required when the Type is ADFS, and cannot be specified for other types of providers.

  

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


### \-SigningCertificate\<X509Certificate2\>

Specifies the self-signed certificate for use by the trusted identity provider. The provider uses the certificate to sign security tokens that it issues. The Enterprise Portal SharePoint web application uses this certificate to verify the authenticity of security tokens it receives.

  

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


### \-Type\<String\>

Specifies the type of authentication provider to add. Provider types can be Forms or ADFS.

  

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


### \-UserName\<String\>

Specifies the username of the business connector proxy account. UserName and ClearTextPassword are a way to specify the business connector proxy account. They cannot be used with the Credential parameter. UserName and ClearTextPassword are often used in scripts in which no user interaction is expected.

The SharePoint security token server (STS) web application created by this cmdlet uses this account as its IIS application pool identity.

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

### Example 1: Add a forms-based authentication provider

This example adds a secure socket layers claims based authentication provider to a Microsoft SharePoint Server installation. The variables in the example were given values in previous statements.  
$Cred = Get-Credential  
$SigningCert = Get-PfxCertificate c:\\certs\\FORMS-CERT.cer  
$SSLSTSCert = Get-PfxCertificate c:\\certs\\SSLCertForFBA.pfx

  

    C:\PS>Add-AXSharepointClaimsAuthenticationProvider -Type Forms -Name FBAProvider -SigningCertificate $SigningCert -Credential $Cred -Port 7000 -SSLCertificate $SSLSTSCert

### Example 2: Add an ADFS claims based authentication provider

This example adds an ADFS claims based authentication provider to a Microsoft SharePoint Server installation. The variables in the example were given values in previous statements.  
$SigningCert = Get-PfxCertificate c:\\certs\\ADFS-CERT.cer

  

    C:\PS>Add-AXSharepointClaimsAuthenticationProvider -Type ADFS -Name ADFSPROVIDER -SigningCertificate $SigningCert -ServerUrl "https://machinename.corp.contoso.com/adfs/ls/"

  
  
Copyright Microsoft Corporation. All rights reserved.


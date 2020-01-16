---
title: New-AXUser
TOCTitle: New-AXUser
ms:assetid: 744188E5-3DF1-41E6-85AA-44D0B04A3E88
ms:mtpsurl: https://technet.microsoft.com/library/JJ720263(v=AX.60)
ms:contentKeyID: 49720052
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# New-AXUser

## New-AXUser

Creates a new user in Microsoft Dynamics AX.

## Syntax

    Parameter Set: Default
    New-AXUser -AccountType <String> -AXUserId <String> -UserDomain <String> -UserName <String> [-ClearTextPassword <String> ] [-Company <String> ] [-CreateInProvider] [-Disabled] [-PartitionKey <String> ] [ <CommonParameters>]

  
  

## Detailed description

The New-AXUser cmdlet creates a new user in Microsoft Dynamics AX. You can specify the type of user to add. If you are creating a claims user, specify the name of the claims provider in the UserDomain parameter. If you are using forms-based claims authentication, you can also create a new user in the provider. You can also specify the partition to create the user in.

## Parameters

### \-AXUserId\<String\>

Specifies the UserID of the user to be added to Microsoft Dynamics AX. The UserID must be unique within Microsoft Dynamics AX, or an error is returned.

  

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


### \-AccountType\<String\>

Specifies the type of user to add to Microsoft Dynamics AX. Valid values include: ClaimsUser, WindowsUser, and WindowsGroup.

  

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


### \-ClearTextPassword\<String\>

Sets a password for the user in clear text, rather than encrypted. This parameter is only valid when creating a user in a forms-based-authentication provider. The user should be encouraged to change the password as soon as possible.

  

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


### \-Company\<String\>

Specifies the company to create the user in. By default, users are created in the default company.

  

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


### \-CreateInProvider

Specifies that a user be created in a forms-based authentication provider, in addition to Microsoft Dynamics AX. All users created with a forms-based authentication provider will have full read access to the Enterprise Portal site. If you use this parameter, you must also use the -UserDomain parameter to specify the provider to create the user in. You must also use the -ClearTextPassword parameter to provide a password for the user. The user should be encouraged to change the password as soon as possible.

  

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


### \-Disabled

Disables the user. By default, users are enabled when they are created.

  

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


### \-PartitionKey\<String\>

Specifies the partition to create the user in. By default, users are created in the initial partition.

  

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


### \-UserDomain\<String\>

Specifies the domain for the user. When you specify a ClaimsUser, specify the name of the claims provider in the UserDomain parameter. The Name parameter is specified in the Add-AXSharepointClaimsAuthenticationProvider cmdlet.

  

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

Specifies the UserName of the user to be added to Microsoft Dynamics AX.

  

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
    
      

## Notes

  - You cannot specify the company of the user that is created--all users are created in the default company. All users are enabled when they are created.  

## Examples

### Example 1: Create a user authenticated with forms-based authentication

This example creates the Microsoft Dynamics AX user Samantha Smith. In this example, an authentication provider named FMFMBAProvider has already been created by using other Windows PowerShell cmdlets. The user is authenticated with the FMFBAProvider forms-based authentication provider.

  

    C:\PS>New-AXUser -AccountType ClaimsUser -AXUserId ssmith -UserName SamanthaSmith -UserDomain FMFBAProvider -CreateInProvider -ClearTextPassword "Yukon!!90"

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />AccountType : ClaimsUser<br />AXUserId    : ssmith<br />Name        : FMFBAProvider\SamanthaSmith<br />SID         : S-1-5-21-2127521184-1604012920-1887927527-1530910<br />Enabled     : Enabled<br />UserName    : SamanthaSmith<br />UserDomain  : FMFBAProvider<br />Company     : DAT<br /></pre>


### Example 3: Create a user authenticated with Windows Active Directory

This example creates the Microsoft Dynamics AX user Ray Chow. The user is authenticated by Windows Active Directory.

  

    C:\PS>New-AXUser -AccountType WindowsUser -AXUserId rchow -UserName RayChow -UserDomain CONTOSO

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />AccountType : WindowsUser<br />AXUserId    : rchow<br />Name        : CONTOSO\RayChow<br />SID         : S-1-5-21-2127521184-1604012920-1887927527-1530910<br />Enabled     : Enabled<br />UserName    : RayChow<br />UserDomain  : CONTOSO<br />Company     : DAT<br /></pre>


### Example 4: Create a user from an Active Directory group

This example creates a Windows group user (also called an Active Directory user) in Microsoft Dynamics AX from the Active Directory group daxtwo.

  

    C:\PS>New-AXUser -AccountType WindowsGroup -AXUserId daxtwo -UserName daxtwo -UserDomain CONTOSO

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />AccountType : WindowsGroup<br />AXUserId    : daxtwo<br />Name        : Redmond\daxtwo<br />SID         : S-1-5-21-2127521184-1604012920-1887927527-5384279<br />Enabled     : Enabled<br />UserName    : daxtwo<br />UserDomain  : CONTOSO<br />Company     : DAT<br /></pre>


## Related topics

  
[Get-AXUser](get-axuser.md)  
  
[Get-AXPartitionInfo](get-axpartitioninfo.md)  
  
[Configure Enterprise Portal flexible authentication](deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


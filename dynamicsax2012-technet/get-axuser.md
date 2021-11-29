---
title: Get-AXUser
TOCTitle: Get-AXUser
ms:assetid: A66FE6FF-8F75-438E-88D1-999127A8D314
ms:mtpsurl: https://technet.microsoft.com/library/JJ720275(v=AX.60)
ms:contentKeyID: 49720063
author: Khairunj
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# Get-AXUser


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Get-AXUser

Returns a list of all users and their properties from Microsoft Dynamics AX.

## Syntax

    Parameter Set: Default
    Get-AXUser [-AXUserId <String> ] [-PartitionKey <String> ] [ <CommonParameters>]

  
  

## Detailed description

Returns a list of users and their properties from Microsoft Dynamics AX. The properties returned are AccountType, UserID, Name, SID, Enabled, UserName, UserDomain, and Company. The cmdlet can optionally take a user ID, a partition key, or both as a parameter.

## Parameters

### \-AXUserId\<String\>

Specifies a Microsoft Dynamics AX user ID to return properties for. If both a user ID and a partition key are specified, and the user does not exist in the specified partition, an error is returned.

  

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

Specifies the partition to return a list of users from. By default, the cmdlet returns the users in the initial partition.

  

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

### Example 1: Return properties of all users

This example returns the properties of all Microsoft Dynamics AX users.

  

    C:\PS>Get-AXUser

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />AccountType : WindowsUser<br />AXUserId    : Admin<br />Name        :<br />SID         : S-1-5-21-2127521184-1604012920-1887927527-2163647<br />Enabled     : Enabled<br />UserName    : VamsiK<br />UserDomain  : CONTOSO<br />Company     : DAT<br /><br />AccountType : WindowsUser<br />AXUserId    : Guest<br />Name        :<br />SID         :<br />Enabled     : Disabled<br />UserName    :<br />UserDomain  :<br />Company     : DAT<br /><br />.<br />.<br />.<br /></pre>


### Example 2: Return properties of one user

This example returns the properties of a single Microsoft Dynamics AX user.

  

    C:\PS>Get-AXUser -AXUserId admin

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />AccountType : WindowsUser<br />AXUserId    : Admin<br />Name        :<br />SID         : S-1-5-21-2127521184-1604012920-1887927527-2163647<br />Enabled     : Enabled<br />UserName    : VamsiK<br />UserDomain  : CONTOSO<br />Company     : DAT<br /></pre>


## Related topics

  
[Get-AXPartitionInfo](get-axpartitioninfo.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


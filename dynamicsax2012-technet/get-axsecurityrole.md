---
title: Get-AXSecurityRole
TOCTitle: Get-AXSecurityRole
ms:assetid: 891D722A-A8B9-4A6F-908B-9B8F6AC43206
ms:mtpsurl: https://technet.microsoft.com/library/JJ720266(v=AX.60)
ms:contentKeyID: 49720055
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Get-AXSecurityRole

## Get-AXSecurityRole

Retrieves a list of the security roles within Microsoft Dynamics AX that the specified UserID is associated with.

## Syntax

    Parameter Set: Default
    Get-AXSecurityRole -AxUserID <String> [-PartitionKey <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXSecurityRole cmdlet retrieves a list of the security roles within Microsoft Dynamics AX that the specified user ID is associated with.

## Parameters

### \-AxUserID\<String\>

Specifies a Microsoft Dynamics AX UserID to retrieve security role membership information for.

  

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

Specifies the partition from which to return the security roles that are associated with a user. By default, the cmdlet returns the security roles in the initial partition. If both a user ID and a partition key are specified, and the user does not exist in the specified partition, an error is returned.

  

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


This example returns the Microsoft Dynamics AX security roles that the user Vamsi Kuppa is a member of. The output is piped to the FL (format list) cmdlet to make it easier to read.

  

    C:\PS>Get-AXSecurityRole -AxUserID VamsiK | FL

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />RecId       : 492999<br />Name        : Accountant<br />Description : Documents accounting events and responds to accounting inquiries<br />AOTName     : LedgerAccountant<br /><br />RecId       : 493021<br />Name        : System administrator<br />Description : Maintains the Microsoft Dynamics AX system, has access to all art<br />ifacts in the system, and  cannot be modified<br />AOTName     : -SYSADMIN-<br /><br />RecId       : 493026<br />Name        : System user<br />Description : System role for all users<br />AOTName     : SystemUser<br /></pre>


## Related topics

  
[New-AXSecurityRole](new-axsecurityrole.md)  
  
[Get-AXPartitionInfo](get-axpartitioninfo.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


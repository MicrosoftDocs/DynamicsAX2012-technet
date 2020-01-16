---
title: Get-AXPartitionInfo
TOCTitle: Get-AXPartitionInfo
ms:assetid: 8E97AB68-00DA-46EA-85DD-C62F91AC1E6D
ms:mtpsurl: https://technet.microsoft.com/library/JJ720268(v=AX.60)
ms:contentKeyID: 49720057
author: Khairunj
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# Get-AXPartitionInfo

## Get-AXPartitionInfo

Returns a list of all partitions.

## Syntax

    Parameter Set: Default
    Get-AXPartitionInfo [-PartitionKey <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXPartitionInfo cmdlet returns a list of all partitions. If the optional parameter PartitionKey is specified, the results are limited to the specified partition.

## Parameters

### \-PartitionKey\<String\>

Specifies a partition to return information about. By default, information is returned about all partitions.

  

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


This example returns a list of all partitions in Microsoft Dynamics AX.

  

    PS C:\>Get-AXPartitionInfo

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />Name                       PartitionKey                       PartitionId<br /><br />----                       ------------                       -----------<br /><br />Initial Partition                       initial                       5637144576<br /><br />Partition1                       Partition1                       5637144827<br /><br />Partition2                       Partition2                       5637144828<br /></pre>


## Related topics

  
[Disable-AXUser](disable-axuser.md)  
  
[Get-AXSecurityRole](get-axsecurityrole.md)  
  
[Get-AXSecurityRoleMember](get-axsecurityrolemember.md)  
  
[Get-AXUser](get-axuser.md)  
  
[New-AXUser](new-axuser.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


---
title: Get-AXSecurityRoleInfo
TOCTitle: Get-AXSecurityRoleInfo
ms:assetid: 9F8327B0-C2A9-49AC-B98F-530EF1BF3216
ms:mtpsurl: https://technet.microsoft.com/library/JJ720272(v=AX.60)
ms:contentKeyID: 49720061
author: Khairunj
ms.date: 10/24/2012
mtps_version: v=AX.60
---

# Get-AXSecurityRoleInfo

## Get-AXSecurityRoleInfo

Returns a list of Microsoft Dynamics AX security roles, and information about them.

## Syntax

    Parameter Set: Default
    Get-AXSecurityRoleInfo [-AOTName <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXSecurityRoleInfo cmdlet returns information about Microsoft Dynamics AX security roles. It returns the RecordID, Name, Description, and AOTName of all or one of the security roles. To make the output of the cmdlet easier to read, we recommend that you pipe it to the FL (format list) cmdlet.

## Parameters

### \-AOTName\<String\>

Specifies the AOTName of the security role to return information about.

  

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

### Example 1: Get information about a single role

This example returns information about the Microsoft Dynamics AX LedgerFinancialController security role. The output is piped to the FL (format list) cmdlet to make it easier to read.

  

    PS C:\>Get-AXSecurityRoleInfo -AOTName LedgerFinancialController | FL

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />Name        : Financial controller<br /><br />Description : Reviews all accounting process performance and enables those    processes<br /><br />AOTName     : LedgerFinancialController<br /></pre>


### Example 2: Get information about all roles

This example returns information about all Microsoft Dynamics AX security r oles. The output is piped to the FL (format list) cmdlet to make it easier to read.

  

    PS C:\>Get-AXSecurityRoleInfo | FL

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />Name        : Receiving clerk<br /><br />Description : Documents receiving operation events and responds to warehouse receiving operation inquiries    <br />AOTName     : InventReceivingClerk    <br />RecId       : 492994    <br />Name        : Shipping clerk    <br />Description : Documents shipping operation events and responds to warehouse     shipping operation inquiries    <br />AOTName     : InventShippingClerk</pre>




``` 
PS C:\>
                        
```

  
  
Copyright Microsoft Corporation. All rights reserved.


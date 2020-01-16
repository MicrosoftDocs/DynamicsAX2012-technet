---
title: Get-AXWebComponent
TOCTitle: Get-AXWebComponent
ms:assetid: 0841FDDA-AE4A-480B-A0C6-BCA780BEFDCC
ms:mtpsurl: https://technet.microsoft.com/library/JJ720243(v=AX.60)
ms:contentKeyID: 49720030
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Get-AXWebComponent

## Get-AXWebComponent

Returns a list of web components for a specified Enterprise Portal site.

## Syntax

    Parameter Set: Default
    Get-AXWebComponent -WebSiteUrl <Uri> [-AOTNode <String> ] [-IISReset] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXWebComponent cmdlet returns the web components associated with an Enterprise Portal site in a node of the AOT.

## Parameters

### \-AOTNode\<String\>

Specifies an AOT node to return a list of web components from.

To return all web files and images, specify \\Web or \*.

  

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


### \-IISReset

Specifies that IIS will be restarted after the operation has been completed.

  

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


### \-WebSiteUrl\<Uri\>

The URL of the site to deploy content to. The required format is

http:// *serverName*\[:port\]/ *Sites/SiteName*

is the name of the server on which Enterprise Portal is running.

*SiteName* is the name of the virtual server site to be updated.

  

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


The following example returns a list of the web components in the AOT Node Web Controls associated with the DynamicsAX site on the DEVEP server.

  

    PS C:\>Get–AXWebComponent –AOTNode "Web\Web Files\Web Controls\WorkOrderDetails" – WebSiteUrl 
    http://DEVEP/Sites/DynamicsAX 

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />Name : WebProductCatalog <br />CreatedBy : Admin <br />CreatedDate : 6/28/2011 3:14:14 AM <br />ChangedBy : Admin ChangedDate : 6/28/2011 3:14:14 AM <br />Layer : sys <br />ModelName : Foundation <br />Type : WebControl <br />Name : WebProductCatalogItem <br />CreatedBy : Admin <br />CreatedDate : 6/28/2011 3:14:14 AM <br />ChangedBy : Admin <br />ChangedDate : 6/28/2011 3:14:14 AM <br />Layer : sys <br />ModelName : Foundation <br />Type : WebControl ---</pre>




``` 
PS C:\>
                        
```

  
  
Copyright Microsoft Corporation. All rights reserved.


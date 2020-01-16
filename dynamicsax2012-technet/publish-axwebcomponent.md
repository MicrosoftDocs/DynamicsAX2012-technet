---
title: Publish-AXWebComponent
TOCTitle: Publish-AXWebComponent
ms:assetid: A5B30D76-12A4-4843-A1BA-0AAB831931D4
ms:mtpsurl: https://technet.microsoft.com/library/JJ720274(v=AX.60)
ms:contentKeyID: 49720064
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Publish-AXWebComponent

## Publish-AXWebComponent

Publishes web components to an Enterprise Portal site.

## Syntax

    Parameter Set: Default
    Publish-AXWebComponent -WebSiteUrl <Uri> [-AOTNodePathList <String> ] [-IISReset] [-Image] [-ModifiedAfter <DateTime> ] [-Proxy] [ <CommonParameters>]

  
  

## Detailed description

The Publish-AXWebComponent cmdlet enables you to deploy proxies, images, and web components to an Enterprise Portal site.

## Parameters

### \-AOTNodePathList\<String\>

The relative path of the AOT Node from which to deploy an updated web component such as a control, page definition, module, or resource. The path begins with the Web node. For example, the path Web\\Web Files\\Page Definitions\\FCMWorkOrdersListPage indicates the page named FCMWorkOrdersListPage.

  

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

Specifies that IIS will be restarted after the publish operation has been completed.

  

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


### \-Image

Redeploys all images in the Resources node of the AOT to an Enterprise Portal site.

  

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


### \-ModifiedAfter\<DateTime\>

Specifies that only files updated after a specific date be deployed. Can only be used with the Image and AOTNodePathList parameters.

  

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


### \-Proxy

Deploys all of the proxies from Microsoft Visual Studio projects in the Microsoft Dynamics AX AOT that have the **Deploy To EP** property set to **Proxies**.

  

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

### Example: Update proxies

The following example updates all of the proxies for the DynamicsAX site on the DEVEP server.

  

    PS C:\>Publish-AXWebComponent -Proxy – WebSiteUrl http://DEVEP/Sites/DynamicsAX 

### Example: Update images

The following example updates all of the images on the DynamicsAX site on the DEVEP server.

  

    PS C:\>Publish-AXWebComponent -Image – WebSiteUrl http://DEVEP/Sites/DynamicsAX 

### Example: Update a web component

The following example updates the WorkOrderDetails web control for the DynamicsAX site on the DEVEP server.

  

    PS C:\>Publish–AXWebComponent –AOTNodePathList "Web\Web Files\Web Controls\WorkOrderDetails" – 
    WebSiteUrl http://DEVEP/Sites/DynamicsAX

### Example: Update web components by using a ModifiedAfter

The following example deploys all web controls that have been modified since yesterday by using the **modifiedAfter** parameter.

  

    PS C:\>$webSite = "http://serverName[:port]/sites/SiteName" 
    ---
    
    Publish-AXWebComponent -AOTNodePathList "\Web\Web Files\Web Controls" -WebSiteUrl $webSite -
    ModifiedAfter $date –IISReset 
    ---

  
  
Copyright Microsoft Corporation. All rights reserved.


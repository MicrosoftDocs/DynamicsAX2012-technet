---
title: Get-AXAnalysisProjectDetail
TOCTitle: Get-AXAnalysisProjectDetail
ms:assetid: 35531528-60C0-45FD-A4C3-A6F9C0D69BE6
ms:mtpsurl: https://technet.microsoft.com/library/JJ720249(v=AX.60)
ms:contentKeyID: 49720037
author: Khairunj
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# Get-AXAnalysisProjectDetail


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Get-AXAnalysisProjectDetail

Returns a list of all Microsoft SQL Server Analysis Services projects in the Microsoft Dynamics AX Application Object Tree (AOT).

## Syntax

    Parameter Set: Default
    Get-AXAnalysisProjectDetail [-ServicesAOSName <String> ] [-ServicesAOSWSDLPort <Int32> ] [-ServicesFilePath <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXAnalysisProjectDetail cmdlet returns a list of all Microsoft SQL Server Analysis Services projects in the Microsoft Dynamics AX Application Object Tree (AOT). It is often used in scripts that compare lists of published and unpublished projects.

## Parameters

### \-ServicesAOSName\<String\>

Specifies the name of an AOS instance to connect to instead of the default value.

  

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


### \-ServicesAOSWSDLPort\<Int32\>

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


### \-ServicesFilePath\<String\>

Specifies a client configuration parameter file (.axc) to use instead of the configuration that is stored in the registry.

  

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


This example returns a list of the Analysis Services projects in the AOT, piped to the Format-List cmdlet (FL).

  

    PS C:\>Get-AXAnalysisProjectDetail | FL 

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />Name : Dynamics AX <br />Layer : gls <br />ProjectFilename : Dynamics AX.dwproj <br />ModifiedDateTime : 4/19/2012 8:26:02 AM </pre>




``` 
PS C:\>
                        
```

## Related topics

  
[Get-AXAnalysisDatabaseDetail](get-axanalysisdatabasedetail.md)  
  
[Get-AXAnalysisServerConfiguration](get-axanalysisserverconfiguration.md)  
  
[Publish-AXAnalysisProject](publish-axanalysisproject.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


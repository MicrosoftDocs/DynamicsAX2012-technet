---
title: Get-AXAnalysisDatabaseDetail
TOCTitle: Get-AXAnalysisDatabaseDetail
ms:assetid: 025F2E16-8208-4C67-B173-F4B26C0D08A8
ms:mtpsurl: https://technet.microsoft.com/library/JJ720242(v=AX.60)
ms:contentKeyID: 49720031
author: Khairunj
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# Get-AXAnalysisDatabaseDetail

## Get-AXAnalysisDatabaseDetail

Returns a list of Microsoft SQL Server Analysis Services databases (projects) that were published by Microsoft Dynamics AX.

## Syntax

    Parameter Set: Default
    Get-AXAnalysisDatabaseDetail [-ServicesAOSName <String> ] [-ServicesAOSWSDLPort <Int32> ] [-ServicesFilePath <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXAnalysisDatabaseDetail cmdlet returns a list of Microsoft SQL Server Analysis Services databases (projects) that were published by Microsoft Dynamics AX. It is often used in scripts that compare lists of published and unpublished projects.

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

Specifies the web service (WSDL) port of an AOS instance to connect to instead of the default value.

  

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


This example returns a list of the databases published by Microsoft Dynamics AX, piped to the Format-List cmdlet (FL).

  

    PS C:\>Get-AXAnalysisDatabaseDetail | FL 

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">						<br />
						<br />PartitionKey : initial <br />ServerName : dax62bi <br />IsDefault : True <br />Description : Dynamics AX analysis server <br /><br />ServerName : dax62bi <br />DatabaseName : Dynamics AX initial <br />PartitionKey : initial <br />IsDefault : True <br />LastDeployedDateTime : 10/11/2012 12:00:00 AM <br />StatusMessage : </pre>




``` 
PS C:\>
                        
```

## Related topics

  
[Get-AXAnalysisProjectDetail](get-axanalysisprojectdetail.md)  
  
[Get-AXAnalysisServerConfiguration](get-axanalysisserverconfiguration.md)  
  
[Publish-AXAnalysisProject](publish-axanalysisproject.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


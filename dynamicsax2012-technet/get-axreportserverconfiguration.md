---
title: Get-AXReportServerConfiguration
TOCTitle: Get-AXReportServerConfiguration
ms:assetid: 9B10AFF9-C425-4133-8BC8-9A864755FFDD
ms:mtpsurl: https://technet.microsoft.com/library/JJ720271(v=AX.60)
ms:contentKeyID: 49720060
author: Khairunj
ms.date: 12/18/2012
mtps_version: v=AX.60
---

# Get-AXReportServerConfiguration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Get-AXReportServerConfiguration

Retrieves the configuration that specifies the connection settings between a Microsoft Dynamics AX Application Object Server (AOS) instance and a Microsoft SQL Server Reporting Services instance.

## Syntax

    Parameter Set: Default
    Get-AXReportServerConfiguration -Id <String> [-ServicesAOSName <String> ] [-ServicesAOSWSDLPort <Int32> ] [-ServicesFilePath <String> ] [-UseDefault] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXReportServerConfiguration cmdlet retrieves the configuration that specifies the connection settings between an AOS instance and a Reporting Services instance.

## Parameters

### \-Id\<String\>

Specifies the identifier of the configuration to retrieve.

  

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


### \-UseDefault

Specifies that the default configuration should be returned.

  

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

  - **See example**

## Examples


This example returns a list of the settings in the configuration ReportServer01.

  

    PS C:\>C:\PS>Get-AXReportServerConfiguration -Id ReportServer01 

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">AOSName : 01@RDVM806000-GU <br />ConfigurationId : ReportServer01 <br />Description : <br />Default : True <br />ReportServerFolder : DynamicsAX <br />ReportServerName : ReportServer1 <br />ReportServerInstanceName : DynamicsReports <br />ReportServerManagerUrl : http://ReportServer1/Reports <br />ReportServerWebServiceUrl : http://ReportServer1/ReportServer <br />SharePointIntegregrated : False </pre>




``` 
PS C:\>
                        
```

## Related topics

  
[Set-AXReportServerConfiguration](set-axreportserverconfiguration.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


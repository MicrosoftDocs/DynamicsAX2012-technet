---
title: Get-AXReport
TOCTitle: Get-AXReport
ms:assetid: CBCD1B4C-72F5-4B55-858A-2E6FD7247E95
ms:mtpsurl: https://technet.microsoft.com/library/JJ720285(v=AX.60)
ms:contentKeyID: 49720074
author: tonyafehr
ms.date: 10/17/2012
mtps_version: v=AX.60
---

# Get-AXReport


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Get-AXReport

Retrieves a list of Microsoft SQL Server Reporting Services reports available from Microsoft Dynamics AX.

## Syntax

    Parameter Set: Default
    Get-AXReport [-OnlyName] [-ReportName <String> ] [-ServicesAOSName <String> ] [-ServicesAOSWSDLPort <Int32> ] [-ServicesFilePath <String> ] [ <CommonParameters>]

  
  

## Detailed description

The Get-AXReport cmdlet retrieves a list of Reporting Services reports available from Microsoft Dynamics AX. The cmdlet returns values for ChangedBy, ChangedDate, CreatedBy, CreatedDate, DataSources, Designs, Name, and VsProjectNames.

## Parameters

### \-OnlyName

Specifies that only report names will be returned by the cmdlet.

  

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


### \-ReportName\<String\>

Specifies names of reports to query for in Microsoft Dynamics AX.

  

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


### \-ServicesAOSName\<String\>

Specifies the name of a Microsoft Dynamics AX Application Object Server (AOS) instance to connect to instead of the default value.

  

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

### Example 1

This example returns detailed information for the AssetAddition report.

  

    C:\PS>Get-AXReport -ReportName AssetAddition

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">ChangedBy      : Admin<br />ChangedDate    : 5/10/2011 12:00:00 PM<br />CreatedBy      : Admin<br />CreatedDate    : 5/10/2011 12:00:00 PM<br />DataSources    : {}<br />Designs        : {Report}<br />Name           : AssetAddition<br />VSProjectNames : {}<br /></pre>


### Example 2

This example returns a list of all of the reports whose names begin with cust.

  

    C:\PS>Get-AXReport -OnlyName -ReportName Cust*

<pre IsFakePre="true" xmlns="http://www.w3.org/1999/xhtml">CustAccountStatement_FR<br />CustAccountStatementExt<br />CustAccountStatementInt<br />CustAgingReport<br />CustAuditor<br />CustBalanceList<br />CustBalanceList_MY<br />.<br />.<br />.<br /></pre>


## Related topics

  
[Deploy the default reports](deploy-the-default-reports.md)  
  

  
  
Copyright Microsoft Corporation. All rights reserved.


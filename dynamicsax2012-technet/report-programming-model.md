---
title: Report Programming Model
TOCTitle: Report Programming Model
ms:assetid: 3c7af73f-0fcf-4fc2-a5f7-62601638f935
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn249829(v=AX.60)
ms:contentKeyID: 54768104
ms.date: 06/09/2013
mtps_version: v=AX.60
---

# Report Programming Model 


Microsoft Dynamics AX reports are built on the concepts of the Model View Controller (MVC) pattern. The report programming model provides APIs to define concepts like the [SrsReportRunController](https://technet.microsoft.com/en-us/library/gg940296\(v=ax.60\)) class, [SrsReportDataContract](https://technet.microsoft.com/en-us/library/gg185207\(v=ax.60\)) class, and [SrsReportDataContractUIBuilder](https://technet.microsoft.com/en-us/library/gg185240\(v=ax.60\)) class.

## Overview of concepts

The following table describes the concepts for the report programming model.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Concept</p></th>
<th><p>Class</p></th>
<th><p>Description</p></th>
<th><p>When to override</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Report data provider (RDP) contract</p></td>
<td><p>Object</p></td>
<td><p>A contract used to specify parameters in an RDP class.</p></td>
<td><p>Every RDP class that requires input parameters is associated with a contract. Nested contracts are supported by RDP contracts.</p></td>
</tr>
<tr class="even">
<td><p>Report definition language (RDL) contract</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg939600(v=ax.60)">SrsReportRdlDataContract</a></p></td>
<td><p>A framework contract used for query-based, data method–based, and OLAP-based reports, and for reports that contain static parameters created in a report. This contract provides a weakly typed representation of parameters. It contains methods that can be used to get or set values. It also contains a map of parameter names and the <a href="https://technet.microsoft.com/en-us/library/gg909329(v=ax.60)">SRSReportParameter</a> class.</p></td>
<td><p>Override when you must do the following:</p>
<ul>
<li><p>Add custom validation to parameters. Call super before you validate.</p></li>
<li><p>Add custom initialization to your parameters.</p></li>
<li><p>Add your own UI builder for the parameters.</p></li>
</ul>
<p>Use the <a href="https://technet.microsoft.com/en-us/library/gg909302(v=ax.60)">SrsReportNameAttribute</a> attribute on the overridden class to specify which report uses this contract, and to bind the contract to the report. Use this attribute for reports that bind to a query or data method to tie the contract to the report.</p></td>
</tr>
<tr class="odd">
<td><p>Print contract</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg938492(v=ax.60)">SRSPrintDestinationSettings</a></p></td>
<td><p>A contract that contains all the relevant contracts after a report RDL is parsed. This contract contains an instance of the RDP contract, RDL contract, print contract, and query contract.</p></td>
<td><p>Do not override.</p></td>
</tr>
<tr class="even">
<td><p>Query contract</p></td>
<td><p>No direct class.</p>
<p>A map that contains the parameter name and query object</p></td>
<td><p>A contract that provides the query contracts that are used in the report.</p></td>
<td><p>Do not override.</p></td>
</tr>
<tr class="odd">
<td><p>Report contract</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg185207(v=ax.60)">SrsReportDataContract</a></p></td>
<td><p>A contract that contains all the relevant contracts after a report RDL is parsed. This contract contains an instance of the RDP contract, RDL contract, print contract, and query contract.</p></td>
<td><p>Do not override.</p></td>
</tr>
<tr class="even">
<td><p>Controller</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg940296(v=ax.60)">SrsReportRunController</a></p></td>
<td><p>The controller of the Model View Controller (MVC) pattern. Given the report name, the controller does the following:</p>
<ul>
<li><p>Call <a href="https://technet.microsoft.com/en-us/library/gg940386(v=ax.60)">SrsReportRunInterface</a> to parse RDL.</p></li>
<li><p>Get the report contracts.</p></li>
<li><p>Create the necessary UI builders and invoke them.</p></li>
<li><p>Call validate on contracts. Validation occurs on the server through a service call.</p></li>
<li><p>Save to the SysLastValue table.</p></li>
<li><p>After the form is displayed, and the user clicks OK, run the report.</p></li>
</ul></td>
<td><p>Override when you must do the following:</p>
<ul>
<li><p>Change the contract before you run it. For example, to change the query based on parameters in the form, override the modifyReportContract method.</p></li>
<li><p>React to form control events. In this case, override the method, and provide the override events.</p></li>
<li><p>Add basic validation that is not part of the contract, or not at the table level. In this case, override the validate method, and call the super method.</p></li>
<li><p>Change the name of the report that is being run based on a parameter. In this case, override the modifyReportContract method, and set <a href="https://technet.microsoft.com/en-us/library/gg185217(v=ax.60)">parmReportName</a>.</p></li>
<li><p>Modify the company or culture. In this case, override the modifyReportContract method, and set the company and culture on <a href="https://technet.microsoft.com/en-us/library/gg939600(v=ax.60)">SrsReportRdlDataContract</a>.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Group and order</p></td>
<td><p></p></td>
<td><p>You specify the group and order as follows:</p>
<ul>
<li><p>If you are using an RDP class, specify them on the contract or in Visual Studio.</p></li>
<li><p>If you are using a query or data method, specify them by using report designer.</p></li>
<li><p>If you are using a mix of an RDP class, query, and data method, specify them by using Visual Studio.</p></li>
</ul></td>
<td><p>In Visual Studio, you can create groups and orders, and preview them in Visual Studio and the Microsoft Dynamics AX client.</p></td>
</tr>
<tr class="even">
<td><p>UI Builders</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg185240(v=ax.60)">SrsReportDataContractUIBuilder</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/gg962720(v=ax.60)">SysOperationAutomaticUIBuilder</a></p></td>
<td><p>UI builders do the following</p>
<ul>
<li><p>Lay out the fields on the contract.</p></li>
<li><p>Transfer data from a field to the contract, and bind fields to contract members.</p></li>
</ul>
<p>The group and order are specified in the contract in the Visual Studio designer.</p>
<p>The <a href="https://technet.microsoft.com/en-us/library/gg185240(v=ax.60)">SrsReportDataContractUIBuilder</a> class provides the capability to show the date effective tab and valid values that are specified in the report.</p>
<p>The <a href="https://technet.microsoft.com/en-us/library/gg962720(v=ax.60)">SysOperationAutomaticUIBuilder</a> class provided by the SysOperation framework renders the UI for a given data contract.</p></td>
<td><p>Override when you must do the following:</p>
<ul>
<li><p>Provide additional grouping or ordering. For example, you can provide radio buttons for groups.</p></li>
<li><p>Change the layout from one column to multiple columns. For example, you can display three columns of parameters on the form.</p></li>
</ul>
<p><strong>Note:</strong> To react to control events, you do not need to override the UI builder, because the control override methods need to be specified in the controller.</p>
<p>Evaluate how much you need to override. For example, you can change the layout from one to three columns without an override. In the UI builder, override the build method, update the current form group property columns to 3, and then call super(). The base class lays out the fields.</p></td>
</tr>
</tbody>
</table>


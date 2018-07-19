---
title: Guidance for Choosing the Data Source Type
TOCTitle: Guidance for Choosing the Data Source Type
ms:assetid: 93a04e51-820b-414b-9f8a-cbeff12c1f6c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee909902(v=AX.60)
ms:contentKeyID: 28119399
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Guidance for Choosing the Data Source Type 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you define a report in Microsoft Dynamics AX you must specify how to access the data for your report. The options for data source type are query, business logic, report data provider, and AX enum provider.

## Data Source Types

The following table provides detail on when to use each data source type to access data for your report.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Data source type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="using-queries-to-access-report-data.md">Query</a></p></td>
<td><p>Use when data can be accessed using an AX Query. An AX Query is a query that is defined in the AOT.</p>
<p>When you select <strong>Query</strong> as the data source type for the report you will select a query defined in the AOT.</p>
<p>The only X++ code involved is the code for the display methods in the tables used for the query.</p>
<p>Any code that would be necessary must be accomplished using the Reporting Services functions.</p>
<p>A query to access data has the following advantages:</p>
<ul>
<li><p>Filtering occurs in SQL which is faster.</p></li>
<li><p>There are no X++ classes to develop.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><a href="using-business-logic-in-report-data-methods-to-access-report-data.md">Business Logic</a></p></td>
<td><p>Use to access a data source other than Microsoft Dynamics AX. To use a data method as a data source the following must be true:</p>
<ul>
<li><p>The return value must be an IEnumerable&lt;DataRow&gt; instance.</p></li>
<li><p>The class and report must have the same name. This means that you can only use a data method for one report.</p></li>
<li><p>You must build the project.</p></li>
<li><p>You must add the project to the AOT.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><a href="using-report-data-provider-classes-to-access-report-data.md">Report Data Provider</a></p></td>
<td><p>Use when the data to be rendered in the report is not available through a query, you need to further process the data at the time the report is run, and the business logic is based on X++. The following is a list of specific cases when you would use a report data provider:</p>
<ul>
<li><p>You are using a parameter that is entered in the UI in X++ code, and the business logic processing is based on that parameter.</p></li>
<li><p>Data to be rendered can be accessed by calling X++ business classes.</p></li>
<li><p>You are using the dynamic filter and want to add more filters at runtime based on UI parameters.</p></li>
</ul>
<div class="alert">
<div class="mtps-table">
<div class="mtps-row">
<img src="images/Dn527205.alert_note(AX.60).gif" title="Note" alt="Note" class="note" /><strong>Note</strong>
</div>
<div class="mtps-row">
A query should be considered before you use a Report Data Provider class.
</div>
</div>
</div></td>
</tr>
<tr class="even">
<td><p><a href="how-to-use-an-enum-as-a-report-parameter.md">AX Enum Provider</a></p></td>
<td><p>Use when the report parameter is an Enum type. These parameters expose Enum types on a report in a friendly drop-down list. You can create a range on a query to expose an enum parameter in the Microsoft Dynamics AX client. However, if you want the report to be run from Enterprise Portal, you must use an AX Enum Provider to define the parameter. For more information, see <a href="how-to-use-an-enum-as-a-report-parameter.md">How to: Use an Enum as a Report Parameter</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[Considerations for Creating a Report](considerations-for-creating-a-report.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).


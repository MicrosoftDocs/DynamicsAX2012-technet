---
title: Best Practices for Designing Reports
TOCTitle: Best Practices for Designing Reports
ms:assetid: 49ef5396-4500-4004-9a35-5cf925966a95
ms:mtpsurl: https://technet.microsoft.com/library/Dn280817(v=AX.60)
ms:contentKeyID: 54837977
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Best Practices for Designing Reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This section provides best practices and guidance for creating Microsoft Dynamics AX reports, including how to make a sequence of decisions on the data access, controls, and design for the report.

## Elements of Report Design

Data access determines the source of the report’s data set. The data access options for a report include:

  - AX Query – A modeled solution for data access.

  - X++ Business logic – Use Report Data Provider (RDP) classes to produce a data set.

Controls determine how inputs (parameters) are passed to the report. Controls include:

  - Query Ranges – data set filters defined on the AX Query.

  - Data Contract – filters for data sets generated from X++ Business logic.

  - UI Builder – fully customizable dialogs

Design determines the document layout template of the report. Options for the design include:

  - Auto Design – modeled solution for basic layouts

  - Precision Design – flexible solution for advanced layout

![Elements of a report](images/Dn280817.ReportDesignElements(en-us,AX.60).png "Elements of a report")

## Sequence of Report Design

A report’s data access type determines which controls can be used, and the controls chosen affect the layout of a report, so the elements of a report should be chosen in this sequence.

1.  Data Access

2.  Controls

3.  Design

![Report Development Sequence](images/Dn280817.ReportDevelopmentSequence(en-us,AX.60).png "Report Development Sequence")

## General Best Practices

The following table provides additional general best practices for developing Microsoft Dynamics AX reports.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Best practice</p></th>
<th><p>Additional information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use query based reports when possible, for best performance.</p></td>
<td><p>A query to access data has the following advantages:</p>
<ul>
<li><p>A query with a display method has no code that needs to run. You can query for data directly from a table. The filter of data occurs in SQL which is faster.</p></li>
<li><p>There are no X++ classes to develop. You define a query in the AOT.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Return a TempDB based temporary table when appropriate.</p></td>
<td><p>In-Memory tables are not a SQL based concept so the performance is slower than when you return a TmpDB temporary table. This is especially true for large datasets.</p></td>
</tr>
<tr class="odd">
<td><p>For calculated fields, use a view wrapped in a query.</p></td>
<td><p>Views provide the ability to add calculations. For more information, see <a href="https://technet.microsoft.com/library/cc634339(v=ax.60)">View Overview</a>.</p></td>
</tr>
<tr class="even">
<td><p>Keep business logic as close to the data as possible.</p></td>
<td><p>This promotes reuse of business logic. When the business logic filters data, less data is moved through the system and demands fewer resources.</p>
<p></p></td>
</tr>
<tr class="odd">
<td><p>Use a precision design for all reports. An auto design is a good start point to create a precision design for a report. An auto design will not create medium or complex reports.</p></td>
<td><p>For more information, see <a href="how-to-create-a-precision-design-for-a-report.md">How to: Create a Precision Design for a Report</a> and <a href="how-to-create-an-auto-design-for-a-report.md">How to: Create an Auto Design for a Report</a></p></td>
</tr>
<tr class="even">
<td><p>Do not define a sort or a group in a Microsoft Dynamics AX query.</p></td>
<td><p>The dataset returned to SQL Server Reporting Services will be flattened. Use sort and group in the Reporting Services report definition. For more information, see <a href="working-with-data-regions.md">Working with Data Regions</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Use RDP class based reports when calculated fields in a view perform poorly.</p></td>
<td><p>In reports where there is reuse of one or more expensive calculated fields, performance might improve when you use temporary tables to cache data.</p>
<p>For more information, see <a href="how-to-use-a-report-data-provider-class-in-a-report.md">How to: Use a Report Data Provider Class in a Report</a>.</p></td>
</tr>
<tr class="even">
<td><p>Avoid using RDP classes when the data for the report is in a table and the report dataset can use the table.</p></td>
<td><p>RDP classes provide extra flexibility but also introduce complexity and potential performance degradation.</p>
<p>Use an RDP class when the report data needs to be calculated and complex business logic is required to define the data for a report.</p>
<p>When the report data is accessibly in Microsoft Dynamics AX tables, then use a query and display methods or use a view.</p></td>
</tr>
</tbody>
</table>


## Additional details

The following topics, which provide further details on choosing the data access, controls, and design for reports, are found in this section:

[Considerations for Creating a Report](considerations-for-creating-a-report.md)

[Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md)

[Best Practices for Report Performance](best-practices-for-report-performance.md)

[Coding Guidelines for Reporting](coding-guidelines-for-reporting.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).


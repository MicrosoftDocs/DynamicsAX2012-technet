---
title: "What's New: AOS and Database for Developers in Microsoft Dynamics AX 2012"
TOCTitle: AOS and Database for Developers
ms:assetid: 90301cc1-e1f6-492c-8d66-f51e4044e2ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg841655(v=AX.60)
ms:contentKeyID: 35247423
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# What's New: AOS and Database for Developers in Microsoft Dynamics AX 2012 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the new and enhanced features that are available for Microsoft Dynamics AX Application Object Server (AOS) in Microsoft Dynamics AX 2012.

## What is new or changed?

The following improvements were made in AOS:

  - Valid Time State Tables

  - UnitOfWork Class

  - Inheritance Among Tables

  - Full Text Index

  - TempDB Temporary Tables

  - Computed Columns in Views

  - Filters for Outer Join

  - Add a Having Clause to a Query in the AOT

  - Effect of Disabling a Table

### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")Valid Time State Tables

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Let the system automatically manage data relationships that are valid only during a specified date range.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>You can set the <strong>ValidTimeStateFieldType</strong> property on a table to make it a valid time state table. The system then automatically adds the <strong>ValidFrom</strong> and <strong>ValidTo</strong> columns that track a date range in each row.</p>
<p>The system ensures that the values in these date fields remain valid by automatically preventing overlap among date ranges, based on the primary key value. The X++ select statement has the validTimeState keyword, so that rows can be filtered by date or date range. The Query class has properties, such as ValidTimeStateDateTimeRange, that provide a filter by date range.</p></td>
<td><p>The code that manages data relationships over date ranges is complex. Now, Microsoft Dynamics AX can manage these relationships for you.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg861781(v=ax.60)">Valid Time State Tables and Date Effective Data</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")UnitOfWork Class

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Manage the operation sequence and transaction integrity for row-based database operations.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>You can use the UnitOfWork class to safely manage the operation sequence and transaction integrity for row-by-row database deletes, inserts, and updates. First, register each SQL data modification call with the UnitOfWork object. Then, by using one method call, you instruct the object to run the data modification calls. The object calculates the correct sequence used to run the data modification calls.</p></td>
<td><p>Application programmers who perform a set of data modification calls no longer have to track every detail of foreign key relationships. The UnitOfWork class helps enforce transaction integrity.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg846338(v=ax.60)">How to: Use the UnitOfWork Class to Manage Database Transactions</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")Inheritance Among Tables

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Let a table inherit fields, methods, and relationships from another table.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>Just as an X++ class could inherit from another X++ class in AX 2009, a table can inherit from another table in AX 2012. As in earlier releases, the Common table is still the base table of every table.</p>
<p>A table that inherits from a base table is called a derived table. The terms parent table and child table describe foreign key relationships, not inheritance.</p></td>
<td><p>Table inheritance can improve the design of data models and reuse of schema components.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg844024(v=ax.60)">Walkthrough: Creating Base and Derived Tables</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")Full Text Index

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a full text index on a table.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>A full text index has a separate entry for each significant word in a string field. The QueryRange class can enable an instance of the Query class to benefit from a full text index.</p></td>
<td><p>This feature supports full text queries. Full text queries improve the performance of SQL statements that have a where clause condition that is directed at a word that is embedded in the middle of a string field.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg845129(v=ax.60)">How to: Create a Full Text Index</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")TempDB Temporary Tables

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Have a temporary table of the <strong>TempDB</strong> type.</p></td>
<td><p>Only temporary tables of the <strong>InMemory</strong> type were supported.</p></td>
<td><p>In the properties for a table in the Microsoft Dynamics AX Application Object Tree (AOT), the <strong>TableType</strong> property is now an enum property. The enum value <strong>InMemory</strong> is the legacy type of a temporary table that is hosted in the client. The enum value <strong>TempDb</strong> is the new type of temporary table that is hosted in the TempDb database of the underlying Microsoft SQL Server. <strong>TempDB</strong> temporary tables can be joined with regular tables on the database tier. By joining <strong>TempDB</strong> temporary tables with regular tables, you can often improve performance and simplify the programming model.</p></td>
<td><p><strong>TempDB</strong> temporary tables can be joined with regular tables on the database tier. By joining <strong>TempDB</strong> temporary tables with regular tables, you can often improve performance and simplify the programming model.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg845661(v=ax.60)">Temporary TempDB Tables</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")Computed Columns in Views

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Have a computed column in a view.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>A computed column is the output of a computation that uses a regular column as input.</p></td>
<td><p>By using a computed column, you can simplify application development. Various parts of the client code can all rely on the computed column that is processed by the server in one location.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg845841(v=ax.60)">Walkthrough: Add a Computed Column to a View</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")Filters in Outer Joins

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Implement filtering of the result set from an outer join.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>You can use the new QueryFilter class to filter the result set from an outer join. The QueryFilter class can produce different results to those of the QueryBuildRange class in outer joins. The QueryFilter class filters later in the process for internal queries and can prevent rows that have null values from appearing in the result set.</p></td>
<td><p>By filtering the result set from an outer join, you can reduce the number of rows that the database server must scan.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg881181(v=ax.60)">How to: Use the QueryFilter Class with Outer Joins</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")Add a Having Clause to a Query in the AOT

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use the AOT to add a having clause on the data source for a query.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>The AOT now has a <strong>Having</strong> node under <strong>Queries</strong> &gt; MyQuery &gt; <strong>Data Sources</strong>. This node corresponds to the having clause in standard SQL.</p></td>
<td><p>In a query, you can now specify a filter condition for an aggregate value.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/hh745337(v=ax.60)">Walkthrough: Creating an AOT Query that has Group By and Having Nodes</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg841655.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg841655.collapse_all(en-us,AX.60).gif")Effect of Disabling a Table

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Retain the table in the underlying SQL Server database when the table is disabled in Microsoft Dynamics AX.</p></td>
<td><p>The underlying table was dropped as soon as it was disabled.</p></td>
<td><p>When you disable the configuration key for a table that is listed in the AOT, the corresponding table in the underlying database management system is not dropped. When you modify a configuration key to disable a table, you must decide whether you want to manually delete the data that is in the table.</p></td>
<td><p>External programs and SQL Server cubes no longer fail when you disable a table. The programs and cubes can continue to read the data from the table, because they bypass AOS.</p>
<p>You must decide whether you want external processes to continue to read from the disabled table.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/en-us/library/gg845255(v=ax.60)">Effect of Disabling a Table or Column</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[What's New in Microsoft Dynamics AX 2012 for Developers](https://technet.microsoft.com/en-us/library/gg845327\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).


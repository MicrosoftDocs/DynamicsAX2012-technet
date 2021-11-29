---
title: Report Data Overview
TOCTitle: Report Data Overview
ms:assetid: 366f8274-bb03-4d38-8ea7-0c5b593e8824
ms:mtpsurl: https://technet.microsoft.com/library/Cc596629(v=AX.60)
ms:contentKeyID: 28119341
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Report Data Overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Visual Studio tools for Microsoft Dynamics AX allow you to create reports using data from several different sources. This topic provides a description of the key concepts involved when specifying data for your reports. 

## Report Data Sources

A data source represents a source of data for one or more reports. Depending on where the data is located, you can use the data source for Microsoft Dynamics AX, or you can define your own data source.

### Dynamics AX Data Source

The *Dynamics AX* data source is a data source that is provided for you. This data source connects to the Microsoft Dynamics AX database. It allows you to use queries and Report Data Provider classes that are defined within the AOT in Microsoft Dynamics AX, as well as data methods that you define within your reporting project in Visual Studio. The Dynamics AX data source does not display in the model along with the other report elements. However, it is available from the drop-down menus in the reporting tools.

The Dynamics AX data source can be used for a system that is working from a SQL database with no additional modifications needed for the reports.

When you select Dynamics AX as the data source for the report, you will point to the active Application Object Server (AOS). If you want to use an AOS from another machine that is not the active AOS, you must configure Visual Studio to point to another AOS.

### Defining Additional Data Sources

You can define additional data sources as needed. For example, you can create a data source to connect to data from a legacy system, online analytical processing (OLAP) data, or some other external database. A data source is defined in a model along with the other report elements. When you define a data source, you must specify a data provider and a connection string. The data provider serves as a bridge between a report and its data and is used to retrieve the data. There are two providers that you can choose from when defining a data source: SQL and OLAP. The connection string that you supply contains the information that is used when connecting to the data source. For example, if you are connecting to a SQL database, you can specify the server name, the database name, and the authentication method for validating a user. After you have defined a data source, it displays as an element in your model and is available as an option in drop-down menus in the reporting tools.

A data source can be shared by one or more reports. A report can use one or more data sources. For information about defining a data source, see [How to: Define a Report Data Source](how-to-define-a-report-data-source.md).

## Report Datasets

A report dataset identifies the data from a data source that displays in a report. When you define a dataset, you must specify the data source and the means used to retrieve the data, such as a query or data method. The following table describes the options for retrieving data for a report.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Data source</p></th>
<th><p>Options for data retrieval</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Dynamics AX</p></td>
<td><ul>
<li><p><a href="using-queries-to-access-report-data.md">Queries</a> that are defined in the AOT</p></li>
<li><p><a href="using-report-data-provider-classes-to-access-report-data.md">Report data provider</a> classes that are defined in the AOT</p></li>
<li><p><a href="using-business-logic-in-report-data-methods-to-access-report-data.md">Data methods</a> that are defined within a reporting project in Microsoft Visual Studio</p></li>
<li><p><a href="using-ax-enum-provider-to-access-report-data.md">AX enum provider</a> that is defined in a reporting project in Microsoft Visual Studio</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>SQL</p></td>
<td><ul>
<li><p>TSQL query</p></li>
<li><p>Stored procedure</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>OLAP</p></td>
<td><ul>
<li><p>MDX query</p></li>
</ul></td>
</tr>
</tbody>
</table>


If your report uses the Dynamics AX data source and a query that is defined in the AOT in Microsoft Dynamics AX, you must be especially careful when updating the query in the AOT. For example, if you remove a field in the query and the field displays in the report, the report will display an empty column for the field. Whenever you make updates to a query, be sure to consider how those updates may affect your reports. Updates to a query may also require updates to your reports.

A report can have multiple datasets. A dataset can be used by one or more data regions in a report. For more information about defining a dataset, see [How to: Define a Report Dataset](how-to-define-a-report-dataset.md).

## Security Considerations

When accessing data from the Microsoft Dynamics AX database, it is recommended that you use the Dynamics AX data source to ensure that appropriate security is enforced. When you use the Dynamics AX data source, you can use queries or Report Data Provider classes that are defined in the AOT, and all data access requests go through the MorphX security system. When you use an external SQL or OLAP data source, security from the MorphX security system is not applied when accessing data. In this case, you can use the role-based security features that are available from Microsoft SQL Server to secure the data. For more information about the security features from Microsoft SQL Server, see [Securing Reports and Resources](https://go.microsoft.com/fwlink/?linkid=110169) and [Securing Reporting Services](https://go.microsoft.com/fwlink/?linkid=110170) in SQL Server 2008 R2 Books Online.

## See also

[Defining Report Data](defining-report-data.md)


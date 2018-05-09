---
title: 'How to: Define a Report Dataset'
TOCTitle: 'How to: Define a Report Dataset'
ms:assetid: dbbc9c6c-8741-4709-8a1b-5b3125ea70dc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc621410(v=AX.60)
ms:contentKeyID: 28119597
ms.date: 04/17/2013
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.DataSetDefinition
---

# How to: Define a Report Dataset 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A report dataset identifies data that is displayed in a report. You can use a query, stored procedure, or a data method to retrieve data. The following procedure explains how to define a report dataset.

### To define a dataset

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Right-click the **Datasets** node, and then click **Add Dataset**.

3.  Select the node for the dataset.

4.  In the **Properties** window, set the following properties.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Data Source</strong></p></td>
    <td><p>The data source for the dataset. To access data from the Microsoft Dynamics AX database, select <strong>Dynamics AX</strong>.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you plan to use a data source other than the predefined Microsoft Dynamics AX data source, you must first define the data source in Model Editor before defining the dataset. For more information, see <A href="how-to-define-a-report-data-source.md">How to: Define a Report Data Source</A>.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p>The means of retrieving data from the data source. The options that display in the drop-down menu depend upon what you specify for the <strong>Data Source</strong> property. For example, if you select <strong>Dynamics AX</strong> you will have the following options for the <strong>Data Source</strong> property:</p>
    <ul>
    <li><p><strong>Query</strong> to use a query defined in the Application Object Tree (AOT).</p></li>
    </ul>
    <ul>
    <li><p><strong>Business Logic</strong> to use a data method defined in a reporting project.</p></li>
    </ul>
    <ul>
    <li><p><strong>Report Data Provider</strong> to use business logic defined in a Microsoft Dynamics AX X++ class.</p></li>
    </ul>
    <ul>
    <li><p><strong>AX Enum Provider</strong> to use an enum type.</p></li>
    </ul>
    <p>For more information, see <a href="guidance-for-choosing-the-data-source-type.md">Guidance for Choosing the Data Source Type</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p>The default data region type for the dataset. Specify a value for this property if you plan to use the dataset in an auto design report. For more information about data region types, see <a href="report-data-region-overview.md">Report Data Region Overview</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p>Set the <strong>Dynamic Filters</strong> property to True to create dynamic filters on your report. When this value is True, a dataset parameter and report parameter will be created. Both of which will have the same name. Dynamic filters allow the end user of the report to add filters based on any of the fields on the report.</p>
    <p>When the value is False, the dataset parameter and report parameter for the default ranges are created. The end user of the report cannot add additional filters. For more information about creating dynamic filters, see <a href="adding-interactive-features-to-reports.md">Adding Interactive Features to Reports</a>.</p>
    <div class="alert">

    > [!NOTE]
    > <P>When the <STRONG>Dynamic Filter</STRONG> property is set to <STRONG>False</STRONG>, the SrsReportDataContract object will not contain the query contract.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the dataset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>The query string that is used to retrieve the data for the dataset based on the given data source and data source type.</p>
    <ul>
    <li><p>If the <strong>Data Source Type</strong> property is set to <a href="how-to-use-a-query-in-a-report.md">Query</a>, do one of the following:</p>
    <ul>
    <li><p>If you are using the predefined <strong>Dynamics AX</strong> data source, click the ellipsis button (...) to open the <strong>Select a Microsoft Dynamics AX Query</strong> dialog box. This will allow you to select a query that is defined in the AOT, and which fields, display methods, and field groups are to be returned by the query. To improve the performance of the report, select only the data that is needed for the report to run.</p></li>
    <li><p>If you are using a data source other than the predefined <strong>Dynamics AX</strong> data source, click the ellipsis button. If your data source is a SQL data source, the SQL query builder displays where you can build a Transact SQL (TSQL) query string. If it is an Online Analytical Processing (OLAP) data source, the OLAP query builder displays where you can build a Multidimensional Expression (MDX) query string.</p></li>
    </ul></li>
    <li><p>If the <strong>Data Source Type</strong> property is set to <a href="how-to-bind-a-dataset-to-a-data-method.md">Business Logic</a>, type the name of the data method or click the ellipsis button to display the <strong>Select a Data Method</strong> window. Only data methods that have a return value of System.Data.DataTable can be used when defining a dataset. Data methods that do not return a System.Data.DataTable will not display in the window. If the data method that you select has parameters and you have not yet specified values for the parameters, you will be prompted to enter values for the parameters. For more information, see <a href="data-method-selector.md">Data Method Selector</a>.</p></li>
    <li><p>If the <strong>Data Source Type</strong> property is set to <a href="how-to-use-a-report-data-provider-class-in-a-report.md">Report Data Provider</a>, click the ellipses button (...) to open a dialog box where you can select a class from the AOT.</p></li>
    <li><p>If the <strong>Data Source Type</strong> property is set to <a href="how-to-use-an-enum-as-a-report-parameter.md">AX Enum Provider</a>, type the name of the enum or click the <strong>Query</strong> drop-down.</p>
    <p>The drop-down list contains the Microsoft Dynamics AX base and system enums.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If your report uses the predefined Dynamics AX data source and a query that is defined in the AOT in Microsoft Dynamics AX, you must be especially careful when updating the query in the AOT. For example, if you remove a field in the query and the field displays in the report, the report will display an empty column for the field. Whenever you make updates to a query, be sure to consider how those updates may affect your reports. Updates to a query may also require updates to your reports.</P>
    > <P>If your report uses an OLAP data source and the MDX query has the ability to return a variable number of data columns, your report may show empty columns. This could be due to a parameter that was passed to the query and is not recommended.</P>

    
    After you define a dataset, you can reference the dataset when setting the **Dataset** property for a data region in an auto design. Alternatively, in Model Editor, you can drag the dataset onto the **Designs** node. This will create an auto design for the report displaying the data for the dataset. For more information, see [How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md).
    
    If you create a precision design report, the dataset will be available in the **Report Data** window for SQL Report Designer. For more information, see [How to: Create a Precision Design for a Report](how-to-create-a-precision-design-for-a-report.md).

## See also

[Report Data Overview](report-data-overview.md)

[How to: Define a Report Data Source](how-to-define-a-report-data-source.md)


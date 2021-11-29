---
title: 'How to: Use a Query in a Report'
TOCTitle: 'How to: Use a Query in a Report'
ms:assetid: 1dc9040d-12ed-473a-9c09-242665ac8116
ms:mtpsurl: https://technet.microsoft.com/library/Hh456295(v=AX.60)
ms:contentKeyID: 36997721
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Use a Query in a Report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to retrieve data for a Microsoft Dynamics AX report by using an AX Query. An AX Query is a query defined in the AOT. In a Visual Studio [reporting project](working-with-reporting-projects.md) for Microsoft Dynamics AX, you can define a report in a report model. You will define a dataset with properties that describe how the query will be used to access report data.

## Retrieving Data by Using an AX Query

The following procedure describes how to retrieve data for a report by using an AX Query.

### To retrieve data by using an Ax Query

1.  In Visual Studio, create or open a project based on the Report template. In Solution Explorer, right-click the project, point to **Add**, and then click **Report**.

2.  In Model Editor, right-click the new report, click **Rename**, and then give the report a name.

3.  Right-click the **Datasets** node, and then click **Add Dataset**.

4.  Select the node for the dataset.

5.  In the **Properties** window, specify the following values.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Data Source</strong></p></td>
    <td><p><strong>Dynamics AX</strong> - The data source for the dataset must be set to <strong>Dynamics AX</strong> if you want to set the data source type to an AX Query.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong> indicates you will bind the dataset to an AX Query.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p>The default data region type for the dataset. Specify a value for this property if you plan to use the dataset in an auto design report. For more information about data region types, see <a href="report-data-region-overview.md">Report Data Region Overview</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p>Set the <strong>Dynamic Filters</strong> property to True to create dynamic filters on your report. A dynamic filter enables an end user to filter data in the tables in the dataset. When this value is True, a dataset parameter and report parameter will be created for the fields in the tables in the dataset. When the value is False, the dataset parameter and report parameter are created for the ranges that are set in the query. For more information about creating dynamic filters, see <a href="adding-interactive-features-to-reports.md">Adding Interactive Features to Reports</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Provide a name for the dataset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box is displayed with the queries that are defined in the AOT. Select a query that accesses the data you want to use for the report and then click <strong>Next</strong>. Expand the field nodes and select fields, field groups, <a href="how-to-use-display-methods-in-a-report.md">display methods</a> and dimensions that you want to use on the report.</p>
    <p>The following list describes the options in the <strong>Select Fields</strong> tab of the <strong>Select a Microsoft Dynamics AX Query</strong> window.</p>
    <ul>
    <li><p>Fields - list of fields for each of the tables accessed by the query. Fields are defined for a table to identify the name and type of data.</p></li>
    <li><p>Field Groups - list of field groups for each of the tables accessed by the query. Field groups are a grouping of fields for a table with similar characteristics or purposes, used to optimize the design of forms and reports.</p></li>
    <li><p>Display Methods – list of display methods accessed by the query. A display method is treated like a field in a query, even though the display method is retrieving the data from a different table.</p></li>
    <li><p>AX Dimensions – list of the dimensions accessed by the query. AX Dimensions – list of the dimensions accessed by the query. Dimensions are additional classifications defined in a table for financial, product, and cost attributes.</p></li>
    </ul>
    <p>Click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


Next, you can drag the dataset onto the **Designs** node. An auto design named **AutoDesign1** is created for the report. For the complete steps to create a report bound to an AX Query, see [Walkthrough: Creating an Auto Design Report](walkthrough-creating-an-auto-design-report.md).

## See also

[Defining Report Data](defining-report-data.md)

[Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md)


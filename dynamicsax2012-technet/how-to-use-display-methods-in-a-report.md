---
title: 'How to: Use Display Methods in a Report'
TOCTitle: 'How to: Use Display Methods in a Report'
ms:assetid: af93356c-b70f-440b-9bbb-cf6b5ace4e69
ms:mtpsurl: https://technet.microsoft.com/library/Gg724095(v=AX.60)
ms:contentKeyID: 35133453
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Use Display Methods in a Report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to retrieve data for a Microsoft Dynamics AX report from display methods. A display method is treated like a field in a query, even though the display method is retrieving the data from a different table. For information on how to create display methods, see [Using the display Method Modifier](https://technet.microsoft.com/library/aa595058\(v=ax.60\)). In a Visual Studio [reporting project](working-with-reporting-projects.md) for Microsoft Dynamics AX, you can define a report in a report model. You will define a dataset with properties that describe the data that will be used on the report and how it will be retrieved. To show data from a display method, you will bind the dataset to an AX Query. An AX Query is a query defined in the AOT.

## Retrieving Data from Display Methods

The following procedure describes how to retrieve data from display methods.

### To retrieve data from display methods

1.  In Solution Explorer, right-click the project, point to **Add**, and then click **Report**.

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
    <td><p>Set the <strong>Dynamic Filters</strong> property to True to create dynamic filters on your report. When this value is True, a dataset parameter and report parameter will be created. Both of which will have the same name. When the value is False, the dataset parameter and report parameter for the default ranges are created. For more information about how to create dynamic filters, see <a href="adding-interactive-features-to-reports.md">Adding Interactive Features to Reports</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Provide a name for the dataset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box is displayed with the queries that are defined in the AOT. Select a query and then click <strong>Next</strong>. Expand the <strong>All Display Methods</strong> node and select display methods that you want to use on the report. Click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


Next, you can drag the dataset onto the **Designs** node. An auto design named **AutoDesign1** is created for the report. For the complete steps to create a report that shows data from display methods, see [Walkthrough: Creating a Report with Parameters](walkthrough-creating-a-report-with-parameters.md).

## See also

[Defining Report Data](defining-report-data.md)

[Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md)


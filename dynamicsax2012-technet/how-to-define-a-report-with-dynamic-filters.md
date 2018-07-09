---
title: 'How to: Define a Report with Dynamic Filters'
TOCTitle: 'How to: Define a Report with Dynamic Filters'
ms:assetid: 35832fa4-e07b-4ead-ad53-87fb41a8939e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee873252(v=AX.60)
ms:contentKeyID: 28119340
ms.date: 10/12/2013
mtps_version: v=AX.60
---

# How to: Define a Report with Dynamic Filters [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to define a report that will enable an end user to filter data on any of the fields in the tables in the dataset. A dynamic filter is a filter that is created at runtime. Filters are created using the SySQuery form in the Microsoft Dynamics AX client.

For an example of a report with dynamic filters, go to **Accounts receivable** \> **Reports** \> **Customers**. Click the **Select** button to filter the report based the **Customer account**. The end-user can add filters to the report. For more information on how to use reports with dynamic filters, see [Filter the data on a report](filter-the-data-on-a-report.md).

### To Define a Report with Dynamic Filters Bound to a Query

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Right-click the **Datasets** node and then click **Add Dataset**.

3.  Select the node for the dataset.

4.  The following table shows the properties for a dataset in the **Properties** window. Specify the following property values.
    
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
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><ul>
    <li><p>True – The end-user of the report can add additional filters when they run the report. A single dataset parameter and report parameter are created to transport the dynamic filters that are set at runtime for the report. A dataset parameter references the report parameter and is set in the <strong>Properties</strong> window of the dataset parameter in the <strong>Report Parameter</strong> property. When the <strong>Dynamic Filters</strong> property is set to True, the default ranges are not created for the report.</p>
    <p>--or--</p></li>
    <li><p>False – The filters are static, meaning they are defined in the report model. Dataset parameters and report parameters are created for every range defined in the AX query. The end user of the report will identify the ranges when they view the report. For information about how to define a set range for a filter on a report, see <a href="how-to-define-a-report-filter.md">How to: Define a Report Filter</a>.</p>
    <p>When the <strong>Dynamic Filters</strong> property is set to False and the query has tables which have date effective columns, the date effective fields appear as ranges automatically. To disable the date effective fields, set the report parameter <strong>Visibility</strong> property to <strong>Hidden</strong>.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (...) to open the <strong>Select an AX Query</strong> dialog box where you can select a query that is defined in the AOT. In this dialog box, you can also select fields, field groups, display methods and dimensions to be returned by the query.</p></td>
    </tr>
    </tbody>
    </table>


After you define a dataset, you can drag the dataset onto the **Designs** node. This will create an auto design for the report displaying the data for the dataset. For more information, see [How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md). If you add a precision design report, the **Report Data** window will contain the datasets that you defined in the model when you edit in SQL Report Designer. For more information, see [How to: Create a Precision Design for a Report](how-to-create-a-precision-design-for-a-report.md).

## See also

[Report Data Overview](report-data-overview.md)

[How to: Define a Report Data Source](how-to-define-a-report-data-source.md)


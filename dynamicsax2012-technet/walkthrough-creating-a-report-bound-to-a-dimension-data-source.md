---
title: 'Walkthrough: Creating a Report Bound to a Dimension Data Source'
TOCTitle: 'Walkthrough: Creating a Report Bound to a Dimension Data Source'
ms:assetid: b692d6ad-bcad-41fa-a74f-2ab3bb7030f1
ms:mtpsurl: https://technet.microsoft.com/library/Gg724097(v=AX.60)
ms:contentKeyID: 35133455
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Creating a Report Bound to a Dimension Data Source 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough provides the steps to create a report that uses dimensions. Dimensions are additional classifications defined in a table for financial, product, and cost attributes. You will create a report that displays a dimension string, dimension attributes, and a report parameter based on a dimension. When you run the report, you can filter the report by the dimension.


> [!NOTE]
> <P>The data that displays in your report will vary depending on the sample data that is available to you.</P>



This walkthrough illustrates the following tasks:

  - Defining a query

  - Creating a reporting project

  - Adding a dataset bound to a dimension data source

  - Designing and previewing a report

  - Adding a dimension report parameter and filter

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the LedgerJournalTrans table. To view data in the report, this table must be populated with data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

## Defining a Query

There are several ways to retrieve data for reports. In this walkthrough, you will use a query that is defined in the AOT within Microsoft Dynamics AX development workspace. The following procedure explains how to define a query that will retrieve ledger data.

### To define a query

1.  Open Microsoft Dynamics AX development workspace.

2.  In the AOT, right-click the **Queries** node, and then click **New Query**.

3.  Right-click the node for the query, click **Rename**, and then type **DimensionReportQuery**.

4.  Expand the **DimensionReportQuery** node.

5.  At the top level of the AOT, right-click the **Data Dictionary** node, and then click **Open New Window**.

6.  In the new AOT window, expand the Tables node.

7.  Locate the **LedgerJournalTrans** table and drag it onto the **Data Sources** node for the **DimensionReportQuery** query.

8.  Expand the **Data Sources** node, expand the **LedgerJournalTrans** data source that you added, right-click **Fields**, and then click **Properties**.

9.  In the Properties window, set the **Dynamic** property to **Yes**.

10. Save the query.

## Creating a Reporting Project

In this section, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box is displayed.

3.  In the **Installed Templates** pane, click **Microsoft Dynamics AX**. In the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleDimensionsReport. In the **Location** box, type a location.

5.  Click **OK**.

## Adding a Dataset Bound to a Dimension Data Source

Now that you have created a reporting project, you are ready to add a dataset to the report design that will bind the report to specific data. In this example, you will bind the report to a query. You will use the DimensionReportQuery query that you created because it has the LedgerJournalTrans table as a data source, and that table has dimension strings and dimension attributes. The following procedure explains how to add a dataset to a report that is bound to a Microsoft Dynamics AX query.

### To add a dataset bound to a dimension data source

1.  In Solution Explorer, right-click the **SampleDimensionReport** project, point to **Add**, and then click **Report**.

2.  In Model Editor, right-click the new report and then click **Rename**. Type DimensionReport as the name.

3.  Right-click the **Datasets** node and then click **Add Dataset**.

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
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p><strong>Table</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p>False</p>
    <p>When the value is <strong>False</strong>, the filters that are defined in the report model are static. The end-user of the report cannot add additional filters.</p>
    <p>Set the <strong>Dynamic Filters</strong> property to <strong>True</strong> to create dynamic filters on your report. Dynamic filters allow the end user of the report to add filters based on any of the fields on the report, including dimensions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>LedgerDimension</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays that you can use to select a query that is defined in the AOT and identify the fields that you want to use.</p>
    <ol>
    <li><p>Select the <strong>DimensionReportQuery</strong> query and then click <strong>Next</strong>.</p></li>
    <li><p>Under the <strong>LedgerJournalTrans</strong> node, expand the <strong>All Fields</strong> node and select <strong>JournalNum</strong>, <strong>Txt</strong>, and <strong>LedgerDimension_String</strong>. <strong>LedgerDimension_String</strong> is a combination of dimension attributes and it will display as a string on the report.</p></li>
    <li><p>Expand the <strong>AX Dimensions</strong> node. The AX Dimensions node provides a list of the dimensions that can be accessed for the query. Expand the <strong>LedgerDimension</strong> node, and then select <strong>CostCenter</strong> and <strong>Department</strong>.</p></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


## Design and Preview a Report

Next, you will add an auto design report. You will specify layout and style templates for the report, and then preview the report in Visual Studio. A layout template is used to define the placement of the headers and footers in a report. Style templates are used to adjust the style settings for the data regions that are displayed in a report, such as the size of the text, borders, and background color. Layout and style templates are useful for defining reusable layout and style settings. A template can be applied to many reports to maintain consistent appearance for all of the reports.

The following procedures explain how to add an auto design report, how to apply a layout template and a style template, and how to preview the report.

### To add an auto design report

  - In Model Editor, select the **LedgerDimension** dataset node and drag it onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

### To apply layout and style templates

1.  In Model Editor, select the **AutoDesign1** node.

2.  In the **Properties** window, set the **Layout Template** property to **ReportLayoutStyleTemplate**. Also, type Ledger Listing for the **Title** property.

3.  In Model Editor, expand the **AutoDesign1** node, and then select the node for the LedgerDimensionTable data region.

4.  In the **Properties** window, set the **Style Template** property to **TableStyleTemplate**.

### To preview the report

1.  In Model Editor, select the **AutoDesign1** node.

2.  From the Model Editor toolbar, click **Preview**.

3.  In the **Preview** window, select the **Report** tab to view the report. The report displays the dimension string in the **Account** column and the dimension attributes in the **CostCenter** and **Department** columns.

4.  Close the **Preview** window.

## Adding a Dimension Report Parameter and Filter

In this section, you will add a report parameter to specify which **Department** data to use in the report. You will use the report parameter to define an expression for a report filter that is based on **Department**. When the report is run, the **Department** report parameter will display on the parameter form to prompt the end user to select the **Department** for which to show data.

### To add a dimension report parameter

1.  Right-click the **Parameters** node, point to **Add**, and then click **Parameter**. A node for the parameter is displayed.

2.  Select the node for the parameter.

3.  In the **Properties** window, specify property values for the parameter.
    
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
    <td><p><strong>Allow Blank</strong></p></td>
    <td><p><strong>False</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Type</strong></p></td>
    <td><p><strong>String</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Value</strong></p></td>
    <td><p>Provide a default value that is in your data for the Department dimension attribute, such as <strong>OU_160</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Multi Value</strong></p></td>
    <td><p><strong>False</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>DepartmentParameter</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Nullable</strong></p></td>
    <td><p><strong>False</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Prompt String</strong></p></td>
    <td><p>Department</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Values</strong></p></td>
    <td><p>Click the ellipsis button (...). The <strong>Select values</strong> dialog is displayed.</p>
    <ol>
    <li><p>Select the <strong>From dataset</strong> radio button and set the following properties.</p>
    <div class="caption">
    
    </div>
    <div class="tableSection">
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
    <td><p><strong>Dataset</strong></p></td>
    <td><p><strong>LedgerDimension</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value Field</strong></p></td>
    <td><p><strong>Department</strong></p>
    <p><strong>Department</strong> displays in the drop-down list because it is one of the dimension attributes you selected when you created the <strong>LedgerDimension</strong> dataset. The <strong>Value Field</strong> value will be used in the filter.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Label Field</strong></p></td>
    <td><p><strong>Department</strong></p>
    <p>The <strong>Label Field</strong> value displays to the end user.</p></td>
    </tr>
    </tbody>
    </table>

    </div></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Visibility</strong></p></td>
    <td><p><strong>Visible</strong></p></td>
    </tr>
    </tbody>
    </table>


### To add a filter that is based on a dimension

1.  In Model Editor, expand the **Designs** \> **AutoDesign1** \> **LedgerDimensionTable** node.

2.  Right-click the **Filters** node, and then click **Add Filter**. A node for the filter is displayed.

3.  Select the node for the filter.

4.  In the **Properties** window, specify the following properties to set the **Department** filter based on the **Department** report parameter.
    
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
    <td><p><strong>Expression</strong></p></td>
    <td><p>=Fields!Department.Value</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>DepartmentFilter</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Operator</strong></p></td>
    <td><p>Equals</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value</strong></p></td>
    <td><p>=Parameters!DepartmentParameter.Value</p></td>
    </tr>
    </tbody>
    </table>


### To preview the report

1.  In Model Editor, select the **AutoDesign1** node.

2.  From the Model Editor toolbar, click **Preview**.

3.  In the preview window, the **Department** report parameter was added to the **Parameters** tab. The default value that you set for the **Department** report parameter is displayed, such as **OU\_160** or use the drop-down to select a value.

4.  Select the **Report** tab to view the report. The report displays the journal batch number and descriptions for the department you specified.

5.  Close the **Preview** window.

Next you can deploy the report, add the report to the AOT, and access it from a menu item. For more information, see [How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md) and [How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md).


> [!NOTE]
> <P>To create a report that has a static report parameter using the dimension combination ID and the segmented entry control for an account number, you must create a custom report run UI. For more information, see <A href="https://technet.microsoft.com/library/hh300646(v=ax.60)">Segmented Entry</A> and the <A href="report-programming-guide.md">Report Programming Guide</A>.</P>



## See also

[Creating Reports Overview](creating-reports-overview.md)


---
title: 'Walkthrough: Using AX Enum Provider in a Column Chart Report'
TOCTitle: 'Walkthrough: Using AX Enum Provider in a Column Chart Report'
ms:assetid: 5e5b6325-f634-4831-b509-040144c9444a
ms:mtpsurl: https://technet.microsoft.com/library/Cc554854(v=AX.60)
ms:contentKeyID: 28119364
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Using AX Enum Provider in a Column Chart Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A chart provides a graphical representation of data. Displaying data in a chart makes it easy for users to see comparisons, patterns, and trends in the data. In this walkthrough, you will create a report to display customer transaction data in a column chart.

This walkthrough illustrates the following tasks:

  - Defining a query

  - Creating a reporting project

  - Creating a report that has a column chart

  - Creating and configuring report parameters and filters

  - Applying layout and style templates

  - Changing the format of a report to display as a bar or line chart

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the CustTable, CustTrans, and CustGroup tables. In order to view data in the report, these tables must contain data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

## Defining a Query

There are several ways to retrieve data for reports. In this walkthrough, you will use a query that is defined in the Microsoft Dynamics AX Developer Workspace. You will create a query using the CustTable table as the data source. In the report, you will filter the data that is displayed based on the TransType field. The TransType field is from the CustTrans table, so you will add the CustTrans table as a data source. The following procedure explains how to define the query that will be used to retrieve customer transaction data.

### To define a query

1.  Open the Microsoft Dynamics AX Development Workspace.

2.  In the AOT, right-click the **Queries** node, and then click **New Query**.

3.  Right-click the node for the new query, click **Rename**, and then type CustTransactionData. Expand the node for the CustTransactionData query.

4.  In the AOT, right-click the **Data Dictionary** node, and then click **Open New Window**.

5.  In the new window, expand the **Tables** node.

6.  Locate the **CustTable** table and drag it onto the **Data Sources** node for the query.

7.  In the **CustTable\_1** data source node, select the **Fields** node, in the Properties window, set the **Dynamic** property to **No**. You will select the specific fields that will be used on the report instead of sending all data in the table. This will produce faster running reports.

8.  Locate the **CustTrans** table and drag it onto the **Data Sources** node located below the **CustTable** data source.

9.  In the **CustTrans\_1** data source node, select the **Fields** node, in the Properties window, set the **Dynamic** property to **No**.

10. In the separate window, expand the node for the **CustTrans** table \> **Fields**, drag the **AmountMST** field to the **Fields** node of the **CustTrans\_1** data source.

11. Right-click the **Relations** node for the **CustTrans\_1** data source, and then click **New Relation**.

12. Select the node for the relation and verify the following default values in the **Properties** window.
    
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
    <td><p><strong>JoinDataSource</strong></p></td>
    <td><p><strong>CustTable_1</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Field</strong></p></td>
    <td><p><strong>AccountNum</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Related Field</strong></p></td>
    <td><p><strong>AccountNum</strong></p></td>
    </tr>
    </tbody>
    </table>


13. In the AOT, right-click the **Ranges** node for the **CustTrans\_1** data source, and then click **New Range**.

14. Select the node for the range, and in the **Properties** window, select the **TransType** field from the drop-down menu for **Field**.
    

    > [!NOTE]
    > <P>A report parameter is automatically generated for the range when the query is used in a report dataset and the <STRONG>Dynamic Filters</STRONG> property for the report dataset is set to False.</P>



15. The TransType field is an enum type. When you define the report, you must know the value of the **EnumType** property when you define the AX Enum Provider data source. To find the property value, in the AOT, click **Data Dictionary** \> **Tables** \> **CustTrans** \> **Fields** \> **TransType**. In the **Properties** window, notice that the **EnumType** property is set to **LedgerTransType**.

16. Locate the **CustGroup** table and drag it onto the **Data Sources** node located below the **CustTrans\_1** data source.

17. In the **CustGroup\_1** data source node, select the **Fields** node, in the Properties window, set the **Dynamic** property to **No**.

18. In the separate window, expand the **CustGroup** table \> **Fields** node. Drag the **Name** field to the **Fields** node of the **CustGroup\_1** data source.

19. Right-click the **Relations** node for the **CustGroup\_1** data source, and then click **New Relation**.

20. Select the node for the relation and specify the following values in the **Properties** window.
    
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
    <td><p><strong>JoinDataSource</strong></p></td>
    <td><p><strong>CustTable_1</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Field</strong></p></td>
    <td><p><strong>CustGroup</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Related Field</strong></p></td>
    <td><p><strong>CustGroup</strong></p></td>
    </tr>
    </tbody>
    </table>


21. Save the query.

## Creating a Reporting Project

Next, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box is displayed.

3.  In the **Installed Templates** pane, click **Microsoft Dynamics AX** node, and in the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleChartReport, and in the **Location** box, type a location.

5.  Click **OK**.

## Creating a Report with a Column Chart

Before you create a chart, you must decide what type of chart to create. There are two types of charts: *XY charts* and *pie or doughnut charts*. An XY chart is a column, line, or bar chart. During design, you can switch between related chart types. For example, you can create a column chart and then later change it to a bar or line chart. In this walkthrough, you will begin by creating a column chart. Later in the walkthrough, you will change the design so that the data displays in a bar chart and then in a line chart. You will use the predefined layout and style templates provided by the Visual Studio tools for Microsoft Dynamics AX. You will use the template **ColumnChartStyleTemplate** to provide the layout for the column chart report. For the following example, you will create two datasets. The first will be bound to the **CustTransactionsData** query and the second will be used to display the transaction type that is an Enum type.

### To create a report that has a column chart

1.  In Solution Explorer, right-click the **SampleChartReport** project, point to **Add**, and then click **Report**.

2.  In Model Editor, right-click the **Report1** node, and then click **Rename**.

3.  Type ColumnChartReport as the name.

4.  Expand the **ColumnChartReport** node if it is not already expanded.

5.  Right-click the **Datasets** node, and then click **Add Dataset**.

6.  Select the node for the dataset.

7.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>ColumnChart</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p>False</p></td>
    </tr>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>CustomerTransactions</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><ol>
    <li><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use.</p></li>
    <li><p>Select the <strong>CustTransactionData</strong> query and then click <strong>Next</strong>.</p></li>
    <li><p>Expand the <strong>CustTrans_1</strong> node and select the <strong>All Fields</strong> check box. This will select the <strong>AmountMST</strong> field.</p></li>
    <li><p>Expand the <strong>CustGroup_1</strong> node and select the <strong>All Fields</strong> check box. This will select the <strong>Name</strong> field.</p></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


8.  In Model Editor, expand the node for **CustomerTransactions** \> **Fields**.

9.  Select the **AmountMST** field, and in the **Properties** window, set the **Aggregate Function** property to **Sum** and the **Format String** property to **Currency**.

10. Right-click the **Datasets** node, and then click **Add Dataset**. You will create a dataset with an AX Enum Provider data source for the **TransType** enum field. This will let you filter the report to show specific transaction types.

11. Select the node for the dataset.

12. In the **Properties** window, specify the following values.
    
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
    <td><p><strong>AX Enum Provider</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>LedgerTransTypeEnum</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>LedgerTransType</p></td>
    </tr>
    </tbody>
    </table>


13. Drag the **CustomerTransactions** node onto the **Designs** node for the report. An auto design called **AutoDesign1** is created for the report.

14. Expand the **AutoDesign1** node, expand the node for the chart data region, and then expand the **Data** node.

15. Drag the **Name** field to the **Categories** node.
    

    > [!NOTE]
    > <P>The <STRONG>AmountMST</STRONG> field should be the only field that remains below the <STRONG>Data</STRONG> node.</P>



## Configuring a Report Parameter

Next, you will configure a parameter for the report. The report contains a parameter for the TransType field because a range based on this field was added to the query and you set the **Dynamic Filters** property for the dataset to False.

The TransType field is an Enum type. You will update the **Values** property on the **CustomerTransactions\_TransType** report parameter to reference the AX Enum Provider dataset that you created. By using the AX Enum Provider, the enum parameter can be accessed from Enterprise Portal and also the Microsoft Dynamics AX client.

The following procedure explains how to configure a report parameter.

### To configure a report parameter

1.  In Model Editor, expand the **Parameters** node for the report, and then select the **CustomerTransactions\_TransType** parameter.

2.  In the **Properties** window, set the following property values:
    
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
    <td><p>Allow Blank</p></td>
    <td><p>False</p></td>
    </tr>
    <tr class="even">
    <td><p>Data Type</p></td>
    <td><p>Integer</p></td>
    </tr>
    <tr class="odd">
    <td><p>Values</p></td>
    <td><p>Click the ellipsis button (...) to open the <strong>Select Values</strong> dialog box. Set the following values:</p>
    <ul>
    <li><p>Dataset: <strong>LedgerTransTypeEnum</strong></p></li>
    <li><p>Value field: <strong>Value</strong></p></li>
    <li><p>Label field: <strong>Label</strong></p></li>
    </ul>
    <p>Make sure that <strong>From dataset</strong> is marked, and then click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


## Applying Layout and Style Templates

Next, you will specify layout and style templates for the report. A layout template defines the general layout and style settings for a report. A style template contains the layout and style settings for a data region that displays in the body of a report. You will apply the predefined templates that are provided by the Microsoft Dynamics AX framework. These templates are the standard templates for Microsoft Dynamics AX reports. The following procedure explains how to apply layout and style templates to the report.

### To apply layout and style templates

1.  In Model Editor, select the **AutoDesign1** node.

2.  In the **Properties** window, set the **LayoutTemplate** property to **ReportLayoutStyleTemplate**. Also, type Customer transactions for the **Title** property.

3.  In Model Editor, expand the **AutoDesign1** node, and then select the node for the chart data region.

4.  In the **Properties** window, set the **Style Template** property to **ColumnChartStyleTemplate**.

5.  Delete the default text for the **Title** property so that it does not display a title for the data region.

6.  Set the **Value Axis Data Scale Minimum** property to **5**. This will set the starting value on the axis of your report to 5 instead of 0. This is one of many properties that will define the look of your report.

7.  In Model Editor, right-click the **AutoDesign1** node, and then click **Preview** to view the report. Specify a transaction type for the parameter, like **Customer**, and then click the **Report** tab to view the report.

8.  Close the **Preview** window.

## Changing the Format to a Line or Bar Chart

During design, you can switch between several related chart types. First, you will switch from a column chart to a bar chart. After that, you will switch it to a line chart. The following procedures explain how to switch between chart types.

### To switch the format to a bar chart

1.  In Model Editor, select the node for the **CustomerTransactionsXYChart** chart data region.

2.  In the **Properties** window, set the **Chart Type** property to **Bar**.

3.  In Model Editor, right-click the **AutoDesign1** node, and then click **Preview** to view the report. Specify a transaction type for the parameter, like **Customer**, and then click the **Report** tab to view the report.

### To switch the format to a line chart

1.  In Model Editor, select the node for the **CustomerTransactionsXYChart** chart data region.

2.  In the **Properties** window, set the **Chart Type** property to **Line**.

3.  In Model Editor, right-click the **AutoDesign1** node, and then click **Preview** to view the report. Specify a transaction type for the parameter, like **Customer**, and then click the **Report** tab to view the report.

You can use the additional properties to control the look of the report. For more information, see [Working with Data Regions](working-with-data-regions.md). The line chart report that has a report parameter based on an enumeration can now be accessed from a Microsoft Dynamics AX [menu item](how-to-create-a-menu-item-for-a-report.md) or [Enterprise Portal](https://technet.microsoft.com/library/cc571238\(v=ax.60\)).

## See also

[Creating Reports Overview](creating-reports-overview.md)

[Report Data Region Overview](report-data-region-overview.md)


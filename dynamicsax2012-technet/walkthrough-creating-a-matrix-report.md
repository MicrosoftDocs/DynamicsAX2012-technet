---
title: 'Walkthrough: Creating a Matrix Report'
TOCTitle: 'Walkthrough: Creating a Matrix Report'
ms:assetid: f5a517b4-cf20-4faf-b201-d03a70ee222c
ms:mtpsurl: https://technet.microsoft.com/library/Cc623805(v=AX.60)
ms:contentKeyID: 28119618
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Creating a Matrix Report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a report to display customer transaction data in a matrix data region. A matrix data region displays data in a two-dimensional grid of columns and rows that intersect at specific data points. When defining a matrix data region, you can specify column and row groupings. The data that appears in the detail cells are aggregates based on the intersections of columns and rows.

This walkthrough illustrates the following tasks:

  - Defining a query

  - Creating a reporting project

  - Creating a report with a matrix data region

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the CustTable, CustTrans, and CustGroup tables. In order to view data in the report, these tables must contain data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Dynamics AX tools for Microsoft Visual Studio

## Defining a Query

There are several ways to retrieve data for reports. In this walkthrough, you will use a query that is defined in the Microsoft Dynamics AX development workspace. The following procedure explains how to define the query that will be used to retrieve customer transaction data.

### To define a query

1.  In the Microsoft Dynamics AX development workspace, open the AOT.

2.  In the AOT, right-click the **Queries** node, and then click **New Query**.

3.  Right-click the node for the query, click **Rename**, and then type CustTransactions.

4.  Expand the CustTransactions query.

5.  In the AOT, right-click the **Data Dictionary** node, and then click **Open New Window**.

6.  In the new window, expand the **Tables** node.

7.  Locate the **CustTable** table and drag it onto the **Data Sources** node for the query.

8.  Expand the node for the **CustTable\_1** data source.

9.  Select the **Fields** node, in the Properties window, set the **Dynamic** property to **Yes**.

10. Locate the **CustTrans** table and drag it onto the **Data Sources** node located within the **CustTable\_1** data source.

11. Expand the node for the **CustTrans\_1** data source.

12. Select the **Fields** node, in the Properties window, set the **Dynamic** property to **Yes**.

13. Locate the **CustGroup** table and drag it onto the **Data Sources** node located within the **CustTrans\_1** data source. This will be three levels down the hierarchy.

14. Expand the node for the **CustGroup\_1** data source.

15. Select the **Fields** node, in the Properties window, set the **Dynamic** property to **Yes**.

16. Right-click the **Relations** node for the **CustTrans\_1** data source, and then click **New Relation**.

17. Select the node for the relation and specify the following values in the **Properties** window.
    
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


18. Expand the node for the **CustGroup\_1** data source.

19. Right-click the **Relations** node for the **CustGroup** data source, and then click **New Relation**.

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

Next, you will create a reporting project. In this walkthrough, you will use the Report Model template. This will give you access to several predefined layout and style templates that you will use to define the layout of your reports. These templates are the standard templates for Microsoft Dynamics AX reports.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New** and then click **Project**. The **New Project** dialog box is displayed.

3.  In the **Installed Templates** pane, click the **Microsoft Dynamics AX** node. In the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleMatrixReport, and in the **Location** box, type a location.

5.  Click **OK**.

## Creating a Report with a Matrix Data Region

Next, in the reporting project, you will create a report that displays customer transaction data in a matrix data region. You will define a column grouping based on the TransDate field and two row groupings based on the Name and AccountNum fields. The following procedure explains how to create the report.

### To create a report with a matrix data region

1.  In Solution Explorer, right-click the project, point to **Add**, and then click **Report**.

2.  In Model Editor, right-click the **Report1** node and then click **Rename**.

3.  Type SampleMatrixReport as the name.

4.  Right-click the **Datasets** node for the report, and then click **Add Dataset**.

5.  Select the node for the dataset.

6.  In the **Properties** window, specify the following property values.
    
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
    <td><p><strong>Matrix</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p><strong>CustTransactions</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Query</strong></p></td>
    <td><ol>
    <li><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use.</p></li>
    <li><p>Select the <strong>CustTransactions</strong> query and then click <strong>Next</strong>.</p></li>
    <li><p>Expand the <strong>All Fields</strong> node for <strong>CustTable</strong>.</p></li>
    <li><p>Select the <strong>AccountNum</strong> field from the <strong>CustTable</strong> table.</p></li>
    <li><p>Expand the <strong>CustTrans</strong> &gt; <strong>All Fields</strong> node, select the <strong>AmountMST</strong> and <strong>TransDate</strong> fields from the <strong>CustTrans</strong> table.</p></li>
    <li><p>Expand the <strong>CustGroup</strong> &gt; <strong>All Fields</strong> node, select the <strong>Name</strong> field from the <strong>CustGroup</strong> table.</p></li>
    <li><p>Click OK to save the field selection.</p></li>
    </ol>
    <p>The Query field is now</p>
    <p>SELECT CustTable.1.AccountNum,CustTrans.1.TransDate,CustTrans.1.AmountMST,CustGroup.1.Name FROM CustTransactions</p></td>
    </tr>
    </tbody>
    </table>


7.  In Model Editor, select the **Datasets** \> **CustTransactions** \> **Fields** \> **AmountMST** node.

8.  In the **Properties** window, set the **Aggregate Function** property to **Sum** and set the **Format String** property to **Currency**.

9.  In Model Editor, drag the **CustTransactions** node onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

10. Expand the **AutoDesign1** node, expand the node for the matrix data region, and then expand the **Data** node.

11. Drag the **TransDate** field from the **Data** node onto the **Column Groupings** node.

12. Select the **TransDate** node.

13. In the **Properties** window, type the expression =Year(Fields\!TransDate.Value) for the **Label** property.

14. In Model Editor, expand the **TransDate** node, expand the **Group on** node, and then select the **TransDate** node that is located below the **Group on** node.

15. In the **Properties** window, type the expression =Year(Fields\!TransDate.Value) for the **Expression** property.

16. In Model Editor, drag the **Name** field from the **Data** node onto the **Row Groupings** node.

17. Select the **Name** node.

18. In the **Properties** window, set the **Display Width** property to 1in and set the **Display Subtotals** property to **False**.

19. In Model Editor, drag the **AccountNum** field from the **Data** node onto the **Row Groupings** node.

20. Select the **AccountNum** node.

21. In the **Properties** window, set the **Display Width** property to 1in and set the **Display Subtotals** property to **False**.

22. In Model Editor, select the **AmountMST** node that is located below the **Data** node.

23. In the **Properties** window, set the **Display Width** property to 1in, and set the **Text Align** property to **Right**.

### To apply layout and style templates

1.  In Model Editor, select the **AutoDesign1** node.

2.  In the **Properties** window, set the **Layout Template** property to **ReportLayoutStyleTemplate**. Also, type Customer transactions for the **Title** property.

3.  In Model Editor, expand the **AutoDesign1** node, and then select the **CustTransactionMatrix** node.

4.  In the **Properties** window, set the **Style Template** property to **MatrixStyleTemplate**. Also, delete the default text for the **Title** property so that it does not display a title for the data region.

5.  In Model Editor, right-click the **AutoDesign1** node, and then click **Preview**. Click the **Report** tab to see the report. The report displays a list of customer transactions with customer groups down the left side and years across the top.

6.  Close the **Preview** window.

The next step is to [create a menu item](how-to-create-a-menu-item-for-a-report.md) for the report or access the report from [Enterprise Portal](https://technet.microsoft.com/library/cc571238\(v=ax.60\)).

## See also

[Creating Reports Overview](creating-reports-overview.md)

[Report Data Region Overview](report-data-region-overview.md)

[How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md)


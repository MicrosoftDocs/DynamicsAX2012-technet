---
title: 'Walkthrough: Creating an Auto Design Report'
TOCTitle: 'Walkthrough: Creating an Auto Design Report'
ms:assetid: ed2cd6d5-d030-4a6c-bb41-68a36e7074a2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc622728(v=AX.60)
ms:contentKeyID: 28119613
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Creating an Auto Design Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a basic report that displays a list of inventory items. You will use an auto design report. In this type of report, the report design is automatically generated for you based on the report data. After you have created the report, you will add some interactive features, such as drill down capability and a document map. The following illustration shows the report that you will create in this walkthrough.

![Auto design report](images/Cc622728.AutoDesignReport(AX.60).gif "Auto design report")


> [!NOTE]
> <P>The data that displays in your report may vary depending upon the sample data that is available to you.</P>



This walkthrough illustrates the following tasks:

  - Defining a query

  - Creating a reporting project

  - Creating an auto design report

  - Modifying the look of a report

  - Adding interactive features to a report

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the InventTable table. In order to view data in the report, this table must be populated with data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

## Defining a Query

There are several ways to retrieve data for reports. In this walkthrough, you will use a query that is defined in the AOT within Microsoft Dynamics AX development environment. The following procedure explains how to define a query that will be used to retrieve item data.

### To define a query

1.  Open Microsoft Dynamics AX.

2.  In the AOT, right-click the **Queries** node, and then click **New Query**.

3.  Right-click the node for the query, click **Rename**, and then type Items.

4.  Expand the Items node.

5.  Right-click the **Data Dictionary** node, and then click **Open New Window**.

6.  In the new window, expand the **Tables** node.

7.  Locate the **InventTable** table and drag it onto the **Data Sources** node for the **Items** query.

8.  Expand the **Data Sources** node, click the data source that you added in step 7, right-click **Fields**, and then click **Properties**.

9.  In the Properties window, set the **Dynamic** property to **Yes**.

10. Save the query.

## Creating a Reporting Project

Next, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box displays.

3.  In the **Installed Templates** pane, click **Microsoft Dynamics AX**, and in the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleItemReport. In the **Location** box, type a location.

5.  Click **OK**.

## Creating an Auto Design Report

Now that you have created a reporting project, you are ready to define an auto design report that will display data from the Items query. The following procedure explains how to create an auto design report.

### To create an auto design report

1.  In Solution Explorer, right-click the **SampleItemReport** project, point to **Add**, and then click **Report**.

2.  In Model Editor, right-click the new report and click **Rename**. Type ItemReport as the name.

3.  Expand the **ItemReport** node if it is not already expanded.

4.  Right-click the **Datasets** node, and then click **Add Dataset**.

5.  Select the node for the dataset.

6.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>Items</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use. Select the <strong>Items</strong> query, expand the <strong>All Fields</strong> node, select <strong>ItemId</strong>, <strong>ItemType:NAME</strong>, <strong>ItemType:LABEL</strong>, <strong>NameAlias</strong> and then click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


7.  In Model Editor, select **Items** \> **Fields** \> **ItemType**.

8.  In the **Properties** window, set the **Display Width** property to 2.5in.

9.  In Model Editor, select the **Items** node and drag it onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

## Modifying the Look of a Report

Next, you will specify layout and style templates for the report. A layout template is used to define the placement of the headers and footers in a report. Style templates are used to adjust the style settings for the data regions that are displayed in a report, such as the size of the text, borders, and background color. Layout and style templates are useful for defining reusable layout and style settings. A template can be applied to many reports to maintain consistency across reports.

A style template is specific to a data region type. So, if you define a style template for a table, it can only be applied to table data regions. It cannot be applied to list or matrix data regions. In this example, the data will be displayed in a table data region since you specified **Table** for the **Default Layout** property for the dataset. The following procedures explain how to apply layout and style templates for the report.

### To apply layout and style templates

1.  In Model Editor, select the **AutoDesign1** node.

2.  In the **Properties** window, set the **Layout Template** property to **ReportLayoutStyleTemplate**. Also, type Inventory items for the **Title** property.

3.  In Model Editor, expand the **AutoDesign1** node, and then select the node for the ItemsTable data region.

4.  In the **Properties** window, set the **Style Template** property to **TableStyleTemplate**.

5.  From the Model Editor toolbar, click **Preview**.

6.  In the preview window, select the report tab to view the style settings for the report.

7.  Close the **Preview** window.

## Adding Interactive Features to a Report

Next, you will add some interactive features to the report. You will start by adding a data grouping to the report to group items according to the item group. After that, you will change the order that the groups are displayed. Finally, you will modify the report so that it displays a document map.

### To add a grouping

1.  In Model Editor, expand the **AutoDesign1** node, expand the node for the ItemsTable data region, and then expand the **Data** node.

2.  Drag the **ItemType1** field that is located below the **Data** node onto the **Groupings** node.

3.  From the Model Editor toolbar node, click **Preview**.

### To add a sort order

1.  In Model Editor, expand the **ItemsTable** data region, right-click **Sorting** and then click **Add Sort**.

2.  In the **Properties** window, set the **Sort By** property to **=Fields\!ItemType1.Value** and the **Sort Order** property to **Descending**.

3.  Click the tab for the **Preview** window to view the report.
    
    The report display will refresh.

### To add a document map

1.  In Model Editor, select the node for the ItemsTable data region.

2.  In the **Properties** window, set the **Data Navigation Style** property to **DocumentMap**.

3.  Click the tab for the **Preview** window to view the report.
    
    The report display will refresh. Notice the document map on the left side of the report. You can click an item group in the document map and the report displays the data for the items in that group.

### To add a report to the AOT

  - In Solution Explorer, right-click the **SampleItemReport** project and then click Add **SampleItemReport** to AOT.

The new report has been added to the AOT. For information about how to integrate new reports into Microsoft Dynamics AX, see [Walkthrough: Integrating New Reports into Microsoft Dynamics AX](walkthrough-integrating-new-reports-into-microsoft-dynamics-ax.md).

## See also

[Creating Reports Overview](creating-reports-overview.md)

[How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md)

[Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report](walkthrough-referencing-a-report-parameter-from-multiple-datasets-in-a-precision-design-report.md)


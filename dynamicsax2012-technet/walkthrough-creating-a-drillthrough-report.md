---
title: 'Walkthrough: Creating a Drillthrough Report'
TOCTitle: 'Walkthrough: Creating a Drillthrough Report'
ms:assetid: d5391a59-c7a5-46ca-881b-34b10cbe5943
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc639019(v=AX.60)
ms:contentKeyID: 28119592
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Creating a Drillthrough Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough you will create a drillthrough report. A drillthrough report is a report that a user opens by clicking a linked item in another report. It allows users to drill through to additional data.

This walkthrough illustrates the following tasks:

  - Defining a query

  - Creating a reporting project

  - Creating a top-level report and a drillthrough report

  - Adding a report drill through action

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the AssetTable table. In order to view data in the reports, this table must be populated with data.</P>



  - Microsoft Visual Studio 2010

  - Visual Studio tools for Microsoft Dynamics AX

## Defining a Query

There are several ways to retrieve data for reports. In this walkthrough, you will use a query that is defined within the Microsoft Dynamics AX development environment. This query will be based on the AssetTable table. Both the top-level report and the drillthrough report will be based on the same query; however, the drillthrough report will display more fields to show detailed information about a selected asset. The following procedure explains how to define the query that will be used to retrieve data for the reports.

### To define a query

1.  In Microsoft Dynamics AX, open a **New Development Workspace**.

2.  In the AOT, right-click the **Queries** node, and then click **New Query**.

3.  Right-click the node for the query, click **Rename**, and then type Assets.

4.  Expand the node for the Assets query.

5.  Right-click the **Data Dictionary** node, and then click **Open New Window**.

6.  In the new window, expand the **Tables** node.

7.  Locate the **AssetTable** table and drag it onto the **Data Sources** node for the **Assets** query.

8.  In the **Assets** query node, expand the **Data Sources** node, expand the **AssetTable\_1** node, select the **Fields** node, in the Properties window, set the **Dynamic** property to **Yes**.

9.  Save the query.

## Creating a Reporting Project

Next, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box displays.

3.  In the **Installed Templates** pane, click **Microsoft Dynamics AX**, and in the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleDrillthroughReport. In the **Location** box, type a location.

5.  Click **OK**.

## Creating Reports

Next, you will create two reports: a top-level report and a drillthrough report. The top-level report will be a basic list of all assets in the AssetTable table. The drillthrough report will be a more detailed report that will display information about the asset that is selected in the top-level report. You will add a parameter and filter to the drillthrough report. The parameter will be used to pass data from the top-level report to the drillthrough report. The filter will filter the data in the drillthrough report based on the value of the parameter. The following procedures explain how to create the reports.

### To create a top-level report

1.  In Solution Explorer, right-click the SampleDrillThroughReports project, point to **Add** and then click **Report**.

2.  In the Properties window, for the **Name** property type **AssetList**. The model displays in Model Editor with a report named **AssetList**.

3.  In Model Editor, right-click the **Datasets** node, and then click **Add Dataset**.

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
    <td><p><strong>False</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Assets</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use. Select the <strong>Assets</strong> query, click <strong>Next</strong>, expand the node for <strong>All Fields</strong>, and then select the <strong>AssetId</strong>, and <strong>Name</strong> fields. When you are finished selecting the fields, click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


6.  In Model Editor, select the **Assets** dataset node and drag it onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

7.  Select the **AutoDesign1** node.

8.  In the **Properties** window, set the **LayoutTemplate** property to **ReportLayoutStyleTemplate** and type Assets for the **Title** property.

9.  In Model Editor, expand the **AutoDesign1** node, and then select the node for the **AssetsTable** data region.

10. In the **Properties** window, set the style template to **TableStyleTemplate** and type Asset list for the **Title** property.

### To create a drillthrough report

1.  In Solution Explorer, right-click the **SampleDrillThroughReports** project, point to **Add**, and then click **Report**.

2.  In the Properties window, for the **Name** property type **AssetDetails**. The model displays in Model Editor with a report named **AssetDetails**.

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
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p><strong>TopDownList</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p><strong>False</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Details</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use. Select the <strong>Assets</strong> query, click <strong>Next</strong>, expand the node for <strong>All Fields</strong>, and then select the <strong>AssetId</strong>, <strong>Name</strong>, <strong>SerialNum</strong>, <strong>InsuredValue</strong>, <strong>Make</strong>, <strong>Model</strong>, <strong>AssetReplaceCost</strong>, and <strong>TechInfo1</strong> Fields. When you are finished selecting the fields, click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


6.  In Model Editor, in the **Details** dataset, expand the **Fields** node, select the node for the **AssetReplaceCost** field, and in the **Properties** window, set the **FormatString** property to **Currency**.

7.  In the **Fields** node, select the node for the **InsuredValue** field, and in the **Properties** window, set the **FormatString** property to **Currency**.

8.  In the **Fields** node, select the node for the **Name** field and then click the **Move up** button on the Model Editor toolbar until it is first in the list.
    

    > [!NOTE]
    > <P>You can also press ALT+UP ARROW or ALT+DOWN ARROW to move an element up or down in a collection in Model Editor.</P>



9.  Select the **Details** node and drag it onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

10. Select the **AutoDesign1** node.

11. In the **Properties** window, set the **LayoutTemplate** property to **ReportLayoutStyleTemplate** and type Assets for the **Title** property.

12. In Model Editor, expand the **AutoDesign1** node, and then select the node for the **DetailsList** data region.

13. In the **Properties** window, set the style template to **ListStyleTemplate** and type Asset details for the **Title** property.

### To create a parameter that will be used to pass data to the drillthrough report

1.  In Model Editor, right-click the **Parameters** node for the **AssetDetails** report, point to **Add**, and then click **Parameter**.

2.  Select the node for the parameter.

3.  In the **Properties** window, set the **Data Type** property to **String**, type SelectedAssetID for the **Name** property, and type Asset ID: for the **Prompt String** property.

### To define a filter for the drillthrough report

1.  In the **AssetDetails** design, right-click the node for the **DetailsList** data region, point to **Add**, and then click **Filter**.

2.  Select the node for the filter.

3.  In the **Properties** window, specify =Fields\!AssetId.Value for the **Expression** property, specify **Equals** for the **Operator** property, and specify =Parameters\!SelectedAssetID.Value for the **Value** property.

## Adding a Report Drill Through Action

Now that you have created a top-level report and a drillthrough report, you are ready to add a report drill through action to link the two reports together. A report drill through action is defined on the top-level report. The following procedure explains how to add a drill through action.

### To add a report drill through action

1.  In Solution Explorer, double-click **AssetList** to open the model in Model Editor.

2.  Expand the **Designs** node for the **AssetList** report, expand the **AutoDesign1** node, expand the node for the **AssetsTable** data region, and then expand the **Data** node.

3.  Right-click the **Name** node, point to **Add**, and then click **Report Drill Through Action**.

4.  Select the node created for the report drill through action.

5.  In the **Properties** window, click the ellipsis button (…) for the **Report Design** property. A dialog box displays.

6.  In the dialog box, expand the **AssetDetails** report, select the **AutoDesign1** node for that report, and then click **OK**.
    

    > [!NOTE]
    > <P>After you select a design, the parameters for the drillthrough report display below the node for the drill through action in Model Editor.</P>



7.  In Model Editor, select the node for the **SelectedAssetID** parameter that is located below the node for the drill through action.

8.  In the **Properties** window, specify =Fields\!AssetId.Value for the **Value** property.

9.  In Model Editor, select the node for the **AX\_CompanyName** parameter that is located below the node for the drill through action.

10. In the **Properties** window, specify =Parameters\!AX\_CompanyName.Value for the **Value** property.

### To preview the drillthrough report

1.  In Model Editor, right-click the **AutoDesign1** node for the **AssetList** report, and then click **Preview**. The **AssetList** report displays.

2.  You will see links in the report that indicate the drillthrough was created but you must verify the link to the report detail in the client. For more information, see [How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md).

## See also

[How to: Add a Report Drill Through Action on a Report](how-to-add-a-report-drill-through-action-on-a-report.md)

[How to: Add a URL Drill Through Action on a Report](how-to-add-a-url-drill-through-action-on-a-report.md)


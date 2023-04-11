---
title: 'Walkthrough: Creating a cube'
TOCTitle: 'Walkthrough: Creating a cube'
ms:assetid: dfe52292-1b9b-4374-a78c-27f89f49707c
ms:mtpsurl: https://technet.microsoft.com/library/Cc622026(v=AX.60)
ms:contentKeyID: 28119602
author: tonyafehr
ms.date: 12/19/2013
mtps_version: v=AX.60
---

# Walkthrough: Creating a cube 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a cube that enables you to analyze data from Microsoft Dynamics AX. You will use the Business Intelligence (BI) properties in Microsoft Dynamics AX to specify measures and attributes for the cube, and then generate an Analysis Services project so that you can work with the cube in SQL Server Business Intelligence Development Studio (BIDS).

In this walkthrough you will create an analysis cube called Sales analysis that will allow you to analyze the following data for the Contoso company:

  - Sales revenue by quarter, months, and weeks

  - Sales revenue by payment mode

  - Average sales by customer group

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Cc622026.TopicIcons_Walkthrough(AX.60).png" title="Walkthrough" alt="Walkthrough" />
<p>Prerequisites</p>
<p>Create a perspective for a cube</p>
<p>Specify cube measure and attributes</p>
<p>Generate and deploy the Analysis Services project</p>
<p>Browse cube data</p></td>
<td><img src="images/Cc617589.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="http://www.youtube.com/watch?v=latzrx75_94%26list=uufgiuxwmd1za11nb8fgvwpw%26index=8">How to create a cube in Microsoft Dynamics AX 2012 (video)</a></p>
</td>
</tr>
</tbody>
</table>


## Prerequisites

Before you can complete the procedures in this topic, you must make sure that the following prerequisites are in place.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required software</p></td>
<td><p>Microsoft Dynamics AX with sample data and Analysis Services configured</p>
<p>SQL Server Business Intelligence Development Studio or SQL Server Data Tools</p></td>
<td><p><a href="system-administrators.md">System administrators</a></p>
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p></td>
</tr>
</tbody>
</table>


## Create a perspective for a cube

A cube is defined by its measures and dimensions. A measure is quantifiable, like sales, receivables, or item quantities. Dimensions are used to slice measures. For example, sales by quarter, sales by payment group, or sales by customer group. You can specify measures and dimensions to model a cube in the Application Object Tree (AOT). A perspective is a container for the tables and views that contain the measures and dimensions for a cube. For this walkthrough, you will create a perspective, add Microsoft Dynamics AX tables and views to the perspective, and then define measures and dimensions by using the views and table in the perspective.

The following procedures explain how to create a perspective for the cube and how to add views and tables to the perspective.

## Create a perspective for the cube

1.  In the AOT, expand the **Data Dictionary** node. Right-click the **Perspectives** node, and then click **New Perspective**.

2.  Select the node of the perspective. In the **Properties** sheet, specify the following property values:
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>SalesAnalysis</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Label</strong></p></td>
    <td><p>Sales analysis</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Usage</strong></p></td>
    <td><p><strong>OLAP</strong></p></td>
    </tr>
    </tbody>
    </table>
    
    Setting the **Usage** property to **OLAP** indicates that the perspective will be used to generate an Analysis Services project.

## Add views to the perspective

1.  In the AOT, right-click the **Data Dictionary** node, and then click **Open New Window**.

2.  In the new window, expand the **Views** node. Drag the following views onto the **Views** node of the **SalesAnalysis** perspective:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>View</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>CustTransTotalSales</p></td>
    <td><p>Contains sales invoice details.</p></td>
    </tr>
    <tr class="even">
    <td><p>CustTableCube</p></td>
    <td><p>Contains master customer data.</p></td>
    </tr>
    </tbody>
    </table>


3.  In the AOT, right-click the **SalesAnalysis** perspective, and then click **Save**.

## Add a table to the perspective

1.  In the second AOT, expand the **Tables** node. Drag the following table onto the **Tables** node of the **SalesAnalysis** perspective:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>View</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>CustPaymModeTable</p></td>
    <td><p>Contains payment mode information.</p></td>
    </tr>
    </tbody>
    </table>


2.  In the AOT, right-click the **SalesAnalysis** perspective, and then click **Save**.

## Specify cube measure and attributes

You must specify measures and attributes to analyze the desired sales information. To do this, you need to set properties on each view and table in the SalesAnalysis perspective.

The following procedures explain how to set BI properties on the views and table.

## Set properties on the CustTransTotalSales view

1.  In the **SalesAnalysis** perspective, select the **CustTransTotalSales** view.

2.  In the **Properties** sheet, specify the following values.
    
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
    <td><p><strong>AnalysisDimensionType</strong></p></td>
    <td><p><strong>Transaction</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AnalysisDimensionLabel</strong></p></td>
    <td><p>Sales type</p></td>
    </tr>
    </tbody>
    </table>


3.  In the **Properties** sheet, set the following values for each field on the **CustTransTotalSales** view in the **SalesAnalysis** perspective.
    
    <table>
    <colgroup>
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>AnalysisUsage</p></th>
    <th><p>AnalysisDefaultTotal</p></th>
    <th><p>ExchangeRateDateField</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>AmountMST</p></td>
    <td><p>Measure</p></td>
    <td><p>Sum</p></td>
    <td><p>TransDate</p>
    <div class="alert">

    > [!NOTE]
    > <P>The AmountMST value is in the accounting currency of the company. Microsoft Dynamics AX converts that amount to the analysis currency using Microsoft Dynamics AX exchange rates.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p>TransType</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p>TransDate</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    <td><p></p></td>
    </tr>
    <tr class="even">
    <td><p>All other fields</p></td>
    <td><p>Auto</p></td>
    <td><p>Auto</p></td>
    <td><p></p></td>
    </tr>
    </tbody>
    </table>


## Set properties on the CustTableCube view

1.  In the **SalesAnalysis** perspective, select the **CustTableCube** view.

2.  In the **Properties** sheet, specify the following values.
    
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
    <td><p><strong>AnalysisDimensionType</strong></p></td>
    <td><p><strong>Auto</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AnalysisDimensionLabel</strong></p></td>
    <td><p>Customer information</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AnalysisMeasureGroupLabel</strong></p></td>
    <td><p>Customer details</p></td>
    </tr>
    </tbody>
    </table>


3.  In the **Properties** sheet, set the following values for each field on the **CustTableCube** view in the **SalesAnalysis** perspective.
    

    > [!TIP]
    > <P>You can select several fields and set their property values at the same time.</P>

    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>AnalysisUsage</p></th>
    <th><p>AnalysisDefaultTotal</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>AccountNum</p></td>
    <td><p>Measure</p></td>
    <td><p>Count</p></td>
    </tr>
    <tr class="even">
    <td><p>Blocked</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="odd">
    <td><p>GroupName</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="even">
    <td><p>City</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="odd">
    <td><p>County</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="even">
    <td><p>Name</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="odd">
    <td><p>State</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="even">
    <td><p>MainContactWorker</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="odd">
    <td><p>All other fields</p></td>
    <td><p>Auto</p></td>
    <td><p>Auto</p></td>
    </tr>
    </tbody>
    </table>


## Set properties on the CustPaymModeTable table

1.  In the **SalesAnalysis** perspective, select the **CustPaymModeTable** table.

2.  In the **Properties** sheet, specify the following values.
    
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
    <td><p>IsLookup</p></td>
    <td><p>No</p></td>
    </tr>
    <tr class="even">
    <td><p>AnalysisDimensionType</p></td>
    <td><p>Auto</p></td>
    </tr>
    </tbody>
    </table>


3.  In the **Properties** sheet, set the following values for each field on the **CustPaymModeTable** table in the **SalesAnalysis** perspective.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>AnalysisUsage</p></th>
    <th><p>AnalysisDefaultTotal</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="even">
    <td><p>PaymMode</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="odd">
    <td><p>TypeOfDraft</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="even">
    <td><p>AccountType</p></td>
    <td><p>Attribute</p></td>
    <td><p>Auto</p></td>
    </tr>
    <tr class="odd">
    <td><p>All other fields</p></td>
    <td><p>Auto</p></td>
    <td><p>Auto</p></td>
    </tr>
    </tbody>
    </table>


## Generate and deploy the Analysis Services project

Now that you have created a perspective and specified the measures and attributes for the cube, generate an Analysis Services project so that you can work with the analysis cube in BIDS (or SQL Server Data Tools).

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **SQL Server Analysis Services project wizard**. The **SQL Server Analysis Services project wizard** form appears.

2.  Click **Next**.

3.  Select **Create**. In the **Project name** field, type Dynamics AX SalesAnalysis. Click **Next**.

4.  Select **Sales analysis** from the **Available** list and move it to the **Selected** list and then click **Next**.

5.  On the **Select Microsoft Dynamics AX dimensions** page, click **Next**.

6.  Select **Date** from the **Available** list and move it to the **Selected** list and then click **Next**.

7.  Select **Arabic**, **Chinese (Simplified)**, and **English (United States)** from the **Available** list and move them to the **Selected** list and then click **Next**.

8.  Select **Add foreign currency support to the Analysis Services project** and then click **Next**. After the project is generated, click **Next** again.

9.  Select **Save to AOT**. Select **\[New\]** from the list to create a new AOT node. Select **Save to disk**, type the location to which to save the project, and then click **Next**.

10. On the **Deployment options** page, Select **Deploy the project**. Specify the server name. For example, localhost. Select **Create new database**. Type Dynamics AX SalesAnalysis. Select **Process the project after it is successfully deployed** and then click **Next**. Click **Next** and then click **Finish**.
    

    > [!NOTE]
    > <P>If you are using Microsoft Dynamics AX 2012 R2, select the database to deploy, select <STRONG>Deploy</STRONG>, select <STRONG>Process the project after it is successfully deployed</STRONG>, and then click <STRONG>Next</STRONG>. After the project deploys, click <STRONG>Next</STRONG> and then <STRONG>Finish</STRONG>.</P>



## Browse cube data

Now that the SalesAnalysis cube has been deployed and processed, you can browse the cube data within the Analysis Services project. The following procedure explains how to browse the cube data.

## Browse the analysis cube data

1.  In BIDS, open the **Dynamics AX SalesAnalysis** Analysis Services project. If you are using Microsoft Dynamics AX 2012 R2, the project is called **Dynamics AX SalesAnalysis initial**.
    

    > [!NOTE]
    > <P>You can open the project from the AOT. To open the project from the AOT, right-click <STRONG>Visual Studio Projects</STRONG> &gt; <STRONG>Analysis Services Projects</STRONG> &gt; <STRONG>Dynamics AX SalesAnalysis</STRONG> and then click <STRONG>Edit</STRONG>. You must deploy and process the project before you can browse the cube data.</P>



2.  In Solution Explorer, double-click **SalesAnalysis.cube**.

3.  Click the **Browser** tab.

4.  Expand the **Measures** node, expand the **Total customer sales** node, and then drag **Amount** onto the data area..

5.  Expand the **Customers** node, and then drag **State** onto the row area.

6.  Expand the **Customers** node, and then drag **Customers – Name** onto the row area.

7.  Browse the data. You can modify the rows and columns that display in the table or add other dimensions to further slice the data.

## View cube objects in the generated project

1.  Expand the **Data Sources** node. A data source that connects to the Microsoft Dynamics AX OLTP database is displayed.
    
    A data source is used to source and refresh cube data.

2.  Expand the **Data Source Views** node, and then double-click **Dynamics AX SalesAnalysis**.
    
    A data source view provides a unified view of the tables and their relationships.

3.  In Solution Explorer, expand the **Cubes** node, and then double-click **SalesAnalysis.cube** to display Cube Designer.
    
    Cube Designer allows you to view and edit various properties of a cube. There are several tabs that display different views of the cube. For example, click the **Dimension Usage** tab to display the mappings between dimensions and measure groups.
    

    > [!NOTE]
    > <P>Notice that the relationships between the measures and dimensions have been inferred by using the relationships in Microsoft Dynamics AX.</P>

    
    Click the **Translations** tab to view the translations that exist for the cube. The **SalesAnalysis** cube has three translations, Arabic (Saudi Arabia) English (United States) and Chinese (People’s Republic of China).

4.  In Solution Explorer, expand the **Dimensions** node to view the dimensions for the cube.

## Next steps

After you have defined an analysis cube and created an Analysis Services project, you can add features to the cube in BIDS. For more information, see [Walkthrough: Defining KPIs for a Cube](walkthrough-defining-kpis-for-a-cube.md). You can also view the cube data in Microsoft Office Excel or Microsoft SQL Server Management Studio. For more information, see [Walkthrough: Analyzing Cube Data in Excel](walkthrough-analyzing-cube-data-in-excel.md).

## See also

[How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md)

[How to: Specify Dimensions and Attributes for a Cube](how-to-specify-dimensions-and-attributes-for-a-cube.md)

[Create a perspective for a cube](create-a-perspective-for-a-cube.md)

[Create a New SQL Server Analysis Services Project](create-a-new-sql-server-analysis-services-project.md)

[Deploy an Existing SQL Server Analysis Services Project](how-to-deploy-an-existing-sql-server-analysis-services-project.md)


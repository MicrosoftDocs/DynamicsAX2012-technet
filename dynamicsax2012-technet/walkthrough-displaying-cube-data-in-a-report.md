---
title: 'Walkthrough: Displaying Cube Data in a Report'
TOCTitle: 'Walkthrough: Displaying Cube Data in a Report'
ms:assetid: 3147f042-ae36-4c41-894d-1ac64e2ece77
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd252605(v=AX.60)
ms:contentKeyID: 28119334
ms.date: 07/17/2013
mtps_version: v=AX.60
dev_langs:
- sql
---

# Walkthrough: Displaying Cube Data in a Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a report that displays data from an analysis cube.

This walkthrough illustrates the following tasks:

  - Creating a reporting project

  - Defining a data source to connect to an Analysis Services database

  - Creating a report to display cube data

  - Accessing the report through a menu item

  - Displaying the report in an Enterprise Portal Role Center

## Prerequisites

To complete this walkthrough, you will need:

  - The default Analysis Services project, deployed and processed

  - Visual Studio 2010

  - Reporting Services extensions for Microsoft Dynamics AX

  - Visual Studio Tools

## Creating a Reporting Project

Use the Report Model template in Visual Studio to create a new reporting project. For more information about reporting projects, see [Reporting Project Overview](reporting-project-overview.md).

### To create a reporting project

1.  Start Visual Studio. If User Account Control (UAC) is active, be sure you start Visual Studio with administrative privileges.

2.  In Visual Studio, click **File** \> **New** \> **Project**. The **New Project** dialog box is displayed.

3.  In the **Installed Templates** section, click the **Microsoft Dynamics AX** and then click **Report Model**.

4.  In the **Name** box, type SampleCubeReport, and in the **Location** box, specify the location where you want to save the project.

5.  Click **OK**.

## Defining a Data Source to Connect to an Analysis Services Database

A data source contains information about a connection to a database. This includes information such as the server name, the database name, and user credentials. The following procedure explains how to define a data source so that you can access the data from the Analysis Services database that contains the data for the General ledger cube.

### To define a data source for the Analysis Services database

1.  In Solution Explorer, right-click the **SampleCubeReport** project, point to **Add**, and then click **Report Datasource**. The model opens in Model Editor.

2.  In Model Editor, select the node for the data source.

3.  In the **Properties** window, specify the following values:
    
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
    <td><p><strong>Connection String</strong></p></td>
    <td><p>Data Source=[YourServerName];Initial Catalog=Dynamics AX;Integrated Security=SSPI</p>
    <div class="alert">

    > [!NOTE]
    > <P>Insert the name of your server for <STRONG>[YourServerName]</STRONG>. It must be the name of the server that contains the Analysis Services database that has the General ledger cube. The Initial Catalog attribute specifies the name of the Analysis Services database to connect to. <STRONG>Dynamics AX</STRONG> is the default name of the Analysis Services database. The Integrated Security attribute specifies that Support Provider Interface (SSPI) is using Microsoft&nbsp;Windows user credentials for authentication.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p><strong>ProfitAnalysisOLAPData</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Provider</strong></p></td>
    <td><p><strong>Olap</strong></p></td>
    </tr>
    </tbody>
    </table>


## Creating a Report to Display Cube Data

Next, create a report to display data from the General ledger cube. This process involves creating a dataset based on a multidimensional expression (MDX) query to retrieve data from the General ledger cube, creating a column chart report based on the dataset, and then applying layout and style templates to the report.

### To create a report

1.  In Solution Explorer, right-click **SampleCubeReport**, point to **Add**, and then click **Report**.

2.  Select the **Report1** node.

3.  In the **Properties** window, type **ProfitChart** as the value for the **Name** property.

4.  Expand the node for the report if it is not already expanded.

5.  Right-click the **Datasets** node, and then click **Add Dataset**.

6.  Select the node for the dataset.

7.  In the **Properties** window, specify the following values:
    
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
    <td><p><strong>ProfitAnalysisOLAPData</strong></p></td>
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
    <td><p><strong>Name</strong></p></td>
    <td><p><strong>Profit</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Query</strong></p></td>
    <td><pre class="sourceCode sql" id="cb1"><code class="sourceCode sql"><a class="sourceLine" id="cb1-1" data-line-number="1"><span class="kw">SELECT</span> {[Measures].[General ledger gross profit - accounting currency]} <span class="kw">ON</span> <span class="kw">COLUMNS</span>,</a>
    <a class="sourceLine" id="cb1-2" data-line-number="2">{[<span class="kw">Transaction</span> <span class="dt">date</span>].[<span class="dt">Year</span>].&amp;[<span class="dv">2008-01</span>-01T00<span class="ch">:00:00</span>],[<span class="kw">Transaction</span> <span class="dt">date</span>].[<span class="dt">Year</span>].&amp;[<span class="dv">2009-01</span>-01T00<span class="ch">:00:00</span>],</a>
    <a class="sourceLine" id="cb1-3" data-line-number="3">[<span class="kw">Transaction</span> <span class="dt">date</span>].[<span class="dt">Year</span>].&amp;[<span class="dv">2010-01</span>-01T00<span class="ch">:00:00</span>]} <span class="kw">ON</span> <span class="kw">ROWS</span></a>
    <a class="sourceLine" id="cb1-4" data-line-number="4"><span class="kw">FROM</span> <span class="ot">&quot;General ledger cube&quot;</span></a></code></pre>
    <div class="alert">

    > [!NOTE]
    > <P>You may have to modify the MDX query depending on the data that is available in your cube. For example, you may not have data for all the years listed in the query. This query retrieves the profit for 2008, 2009, and 2012. You can use SQL Server Management Studio to help you create an MDX query. In Object Explorer, right-click the database, point to <STRONG>New Query</STRONG>, and then click <STRONG>MDX</STRONG>. You can use the metadata and functions to help you write the query.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


8.  In Model Editor, expand the Fields group for the Profit dataset. Select the **Year** field.

9.  In the **Properties** window, make sure that the **Field Type** property is set to **Grouping** and the **Grouping Type** property is set to **Category**.

10. In Model Editor, select the **Measures\_General\_ledger\_gross\_profit\_** field.

11. In the **Properties** window, make sure that the **Field Type** property is set to **Data**. Type Gross profit in the **Caption** property.

12. In Model Editor, drag the **Profit** dataset onto the **Designs** node for the report.
    
    An auto design is generated for the report. Expand the node for the auto design and notice that it contains a category based on the **Year** field.

### To apply layout and style templates

1.  In Model Editor, select the **AutoDesign1** node.

2.  In the **Properties** window, set the **LayoutTemplate** property to **ReportLayoutStyleTemplate**. Type Gross profit for the **Title** property.

3.  In Model Editor, expand the **AutoDesign1** node, and then select the **ProfitXYChart** node.

4.  In the **Properties** window, set the **Style Template** property to **ColumnChartStyleTemplate**. Delete the text for the **Title** property so that it does not display a title for the data region.

5.  In Model Editor, right-click the **AutoDesign1** node, and then click **Preview** to preview the report. Close the preview and save your changes.

### To deploy and save the report

1.  On the **Build** menu, click **Deploy SampleCubeReport**. After a few moments, the report will be deployed to the Reports Server that has been set up for Microsoft Dynamics AX.

2.  Right-click the **SampleCubeReport** project and then click **Add SampleCubeReport to AOT**. Close Visual Studio.

## Accessing the Report through a Menu Item

You can display a link to the report in a Microsoft Dynamics AX menu by creating an output menu item that generates the report. Then you can add the menu item to the **General ledger** module.

### To display the report in a menu

1.  Open the development workspace in Microsoft Dynamics AX. If it was already open, close and re-open it to refresh the metadata.

2.  Open the AOT. Expand the **Menu Items** node, right-click **Output**, and then click **New Menu Item**.

3.  On the properties sheet for the new menu item, set the following values:
    
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
    <td><p>Name</p></td>
    <td><p>SampleCubeReport</p></td>
    </tr>
    <tr class="even">
    <td><p>Label</p></td>
    <td><p>Gross profit</p></td>
    </tr>
    <tr class="odd">
    <td><p>Object Type</p></td>
    <td><p>SSRSReport</p></td>
    </tr>
    <tr class="even">
    <td><p>Object</p></td>
    <td><p>ProfitChart</p></td>
    </tr>
    </tbody>
    </table>


4.  Save the menu item.
    

    > [!NOTE]
    > <P>Under the <STRONG>Output</STRONG> node, right-click <STRONG>SampleCubeReport</STRONG> and then click <STRONG>Open</STRONG> to preview the report.</P>



5.  Open a second AOT. Expand the **Menus** node, expand the **GeneralLedger** node, and then drag the **SampleCubeReport** menu item from the first AOT onto the **Reports** node in the second AOT.

6.  Save the changes and restart the Microsoft Dynamics AX client. Navigate to the **General ledger** module and then click **Gross profit** to display the report.

## Displaying the Report in an Enterprise Portal Role Center

You can add the report to an Enterprise Portal Role Center page by adding a web part to the Role Center.

### To display the report in an Enterprise Portal Role Center

1.  With a web browser, navigate to the CEO role center that is located at http://\<server\>/sites/DynamicsAx/Enterprise%20Portal/RoleCenterCEO.aspx.

2.  On the **Site Actions** menu, click **Edit Page**. Locate the **Footer** section, and then click **Add a Web Part**

3.  Select **Microsoft Dynamics AX**, click **Report**, and then click **Add**.

4.  On the drop-down menu for the web part, click **Edit Web Part**. The properties for the web part are displayed.

5.  In the **Select a report** list, select **Gross profit**.

6.  For the **Toolbar size** and **Report drillthrough target toolbar size** properties, select **None**.

7.  For the **Should the Web Part have a fixed hight?** property, select **Yes** and set the height to 6 Inches. Click **OK**.

8.  Click **Stop Editing**. The page will update and display the report in the new web part you added.

## See also

[Development Tasks for Analytics](development-tasks-for-analytics.md)

[Development Tasks for Reporting](development-tasks-for-reporting.md)

[Reports in Enterprise Portal Overview](https://technet.microsoft.com/en-us/library/cc571238\(v=ax.60\))


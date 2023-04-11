---
title: 'Walkthrough: Creating a Report from an External Data Source'
TOCTitle: 'Walkthrough: Creating a Report from an External Data Source'
ms:assetid: 2d96bc1e-7703-4f6c-9d8d-e229f19b6876
ms:mtpsurl: https://technet.microsoft.com/library/Cc551711(v=AX.60)
ms:contentKeyID: 28119329
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- sql
---

# Walkthrough: Creating a Report from an External Data Source 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A data source is a facility for accessing data. You can use the predefined *Dynamics AX* data source, which connects to the Microsoft Dynamics AX application database. Or, you can define an external data source to retrieve data from a different location. In this walkthrough, you will create a report from data that is stored in a separate SQL database that you create. In your report model, you will define an external data source that specifies the connection information for the database so that you can retrieve data from that database to display in your report.

This walkthrough illustrates the following tasks:

  - Creating report data

  - Creating a reporting project

  - Defining an external data source

  - Creating a report

  - Modifying the appearance of a report

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

## Creating Report Data

You will start by creating a SQL database that will hold the data for your report. You will execute a set of SQL statements to create a database and a table that is populated with data.

### To create the data

1.  Open SQL Server Management Studio.

2.  When prompted to connect to a server, be sure to specify **Database Engine** for the **Server type** field and log in as a user who has administrative privileges to create databases and tables for the SQL Server.

3.  In SQL Server Management Studio, click **New Query** to display the query editor window.

4.  Copy the following SQL statements into the query editor.
    
    ``` sql
    CREATE DATABASE AXSampleData;
    GO
    USE AXSampleData
    CREATE TABLE [dbo].[Item](
        [ItemID] [int] NOT NULL,
        [Name] [nvarchar](50) NULL,
        [Description] [nvarchar](50) NULL,
        [Cost] [numeric](18, 2) NULL,
        [SellingPrice] [numeric](18, 2) NULL,
        [Status] [int] NULL)
    INSERT INTO Item VALUES (1734, 'Clamp', 'Workbench Clamp', 12.48, 17.99, 0);
    INSERT INTO Item VALUES (1258, 'Hammer', '10 oz Hammer', 7.25, '11.99', 0);
    INSERT INTO Item VALUES (2783, 'Hammer', '12 oz Hammer', 9.50, 15.89, 2);
    INSERT INTO Item VALUES (1983, 'Saw', 'Wooden Handle Saw', 7.89, 11.99, 1);
    INSERT INTO Item VALUES (4920, 'Nails', '10 oz Flat Top Nails', 3.45, 4.99, 0);
    INSERT INTO Item VALUES (6728, 'Screwdriver', 'Standard Screwdriver', 2.75, 3.99, 1);
    INSERT INTO Item VALUES (9283, 'Nails', 'Roofing Nails 5 lbs', 12.45, 15.99, 0);
    INSERT INTO Item VALUES (4829, 'Tape Measure', '25 foot Tape Measure', 12.87, 16.99, 2);
    INSERT INTO Item VALUES (2893, 'Nails', 'Finish Nails', 3.90, 5.59, 1);
    ```

5.  Click **Execute** to execute the SQL statements.

6.  Verify that the database and table have been added to your server.

7.  Close SQL Server Management Studio.

## Creating a Reporting Project

Next, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, click **New**, and then click **Project**. The **New Project** dialog box is displayed.

3.  In the **Installed Templates** pane, click the **Microsoft Dynamics AX** node, and in the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleExternalDataSourceReport, and in the **Location** box, type a location.

5.  Click **OK**.

## Defining a Data Source

A data source contains information about a connection to a database. This includes information such as the server name, the database name, and user credentials. Next, you will define a new data source in your model so that you can access the data in the AXSampleData database.

### To define the data source for the report

1.  In Solution Explorer, right-click the **SampleExternalDataSourceReport** project, point to **Add**, and then click **Report Datasource**.

2.  In Model Editor, select the node for the data source.

3.  In the **Properties** window, specify the following values.
    
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
    <td><p>Server=[YourServerName];Database=AXSampleData;Integrated Security=SSPI</p>
    <div class="alert">

    > [!NOTE]
    > <P>Insert the name of your SQL server for <STRONG>[YourServerName]</STRONG>. It must be the name of the SQL server that contains the database that you created in the previous procedure. In this statement, Security Support Provider Interface (SSPI) is using Microsoft Windows user credentials for authentication. You may need to use a different authentication mode depending upon how you have set up your SQL Server instance.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p><strong>AXSampleData</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Provider</strong></p></td>
    <td><p><strong>SQL</strong></p></td>
    </tr>
    </tbody>
    </table>


## Creating a Report

Next, you will create a report to display item data. You will start by creating a query for the report dataset using a Transact-SQL statement. After you define the dataset, you will format the data. The status of an item is indicated by an integer value between 0 and 2. The value 0 means that the item is *In Stock*. The value 1 means that the item is *On Order*. The value 2 means that the item is *Back Ordered*. You will add an expression to the report to convert the integer value to a text representation so that it is easy to read. You will also format the cost and selling prices as currency values. The following procedure explains how to create the report.

### To create the report

1.  

2.  In Solution Explorer, right-click the **SampleExternalDataSourceReport** project, point to **Add**, and then click **Report**.

3.  In Model Editor, right-click the **Report1** node, and then click **Rename**.

4.  Type ItemListReport as the name.

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
    <td><p><strong>AXSampleData</strong></p></td>
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
    <td><p>Item</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Query</strong></p></td>
    <td><p>Select ItemID, Name, Description, Cost, SellingPrice, Status from Item</p></td>
    </tr>
    </tbody>
    </table>


8.  In Model Editor, expand the **Fields** node for the **Item** dataset. Select the **Cost** node, and in the **Properties** window, set the **Format String** property to **Currency**.

9.  Select the **SellingPrice** node, and in the **Properties** window, set the **Format String** property to **Currency**.

10. Drag the **Item** dataset onto the **Designs** node for the report. This creates an auto design for the report based on the data in the dataset.

11. Expand the **AutoDesign1** node, expand the node for the table definition, and then expand the **Data** node.

12. Select the **Status** node, and in the **Properties** window, click **\<Expression…\>** from the drop-down menu for the **Expression** property.
    
    The **Edit Expression** dialog box is displayed. In this dialog box, you will enter an expression so that text displays for the item status.

13. In the **Edit Expression** dialog box, type the following expression =Switch(Fields\!Status.Value = 0, "In Stock", Fields\!Status.Value = 1, "On Order", Fields\!Status.Value = 2, "Back Ordered"), and then click **OK**.

14. In Model Editor, select the **AutoDesign1** node.

15. In the **Properties** window, set the **Layout Template** property to **ReportLayoutStyleTemplate**.

16. For the **Title** property, type Inventory items .

17. In Model Editor, expand the **AutoDesign1** node, and then select the table definition node.

18. In the **Properties** window, set the **Style Template** property to **ListStyleTemplate**.

19. To preview the layout of the report, right-click the **AutoDesign1** node, and then click **Preview**.

Next, you can [add a menu item to display the report](how-to-create-a-menu-item-for-a-report.md) in the Microsoft Dynamics AX client or [add additional interactive features](adding-interactive-features-to-reports.md) to the report.

## See also

[Creating Reports Overview](creating-reports-overview.md)

[Report Data Overview](report-data-overview.md)

[How to: Define a Report Data Source](how-to-define-a-report-data-source.md)

[How to: Define a Report Dataset](how-to-define-a-report-dataset.md)


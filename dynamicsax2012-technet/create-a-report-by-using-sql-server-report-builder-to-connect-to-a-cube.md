---
title: Create a report by using SQL Server Report Builder to connect to a cube
TOCTitle: Create a report by using SQL Server Report Builder to connect to a cube
ms:assetid: 0fe8ca70-c5af-4d3f-9019-27d769b80ba6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731902(v=AX.60)
ms:contentKeyID: 35132819
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a report by using SQL Server Report Builder to connect to a cube 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic helps you create a custom report that uses an online analytical processing (OLAP) cube as a data source. To complete the procedures in this topic, you must have access to Report Builder, which is a component of Microsoft SQL Server Reporting Services.

For more information about Report Builder and how to access it, see the SQL Server documentation.

## Open Report Builder

If Reporting Services is running in native mode, follow these steps to open Report Builder from the Report Manager website.

1.  Go to the Report Manager website. By default, the URL is http://\[SSRSServerName\]:80/Reports.

2.  Click the **Report Builder** button.
    
    Report Builder opens and displays the Getting Started wizard to help you design the report. For information about how to design a report by using the Getting Started wizard, see the next section of this topic.

If Reporting Services is running in SharePoint integrated mode, follow these steps to open Report Builder from the SharePoint website.

1.  Go to the SharePoint website.

2.  Go to the document library that contains the Microsoft Dynamics AX reports.

3.  Click the **Documents** tab.

4.  Click **New Document** \> **Report Builder Report**.
    

    > [!NOTE]
    > <P>If the <STRONG>Report Builder Report</STRONG> option is not available, your system administrator may need to add the Report Builder content type to the document library. This process is described in <A href="http://technet.microsoft.com/en-us/library/bb326289.aspx">Add Report Server Content Types to a Library (Reporting Services in SharePoint Integrated Mode)</A> in the SQL Server documentation.</P>

    
    Report Builder opens and displays the Getting Started wizard to help you design the report. For information about how to design a report by using the Getting Started wizard, see the next section on this topic.

## Design a report

When you open Report Builder, the Getting Started wizard is displayed. This wizard helps you design a report. Follow these steps to complete the wizard.

1.  On the first page of the Getting Started wizard, click **New Report**, and then select the type of report to design. This procedure explains how to create a table or matrix report.

2.  On the **Choose a dataset** page, click **Create a dataset**. Click **Next**.

3.  On the **Choose a connection to a data source** page, click **New**.

4.  In the **Data Source Properties** window, follow these steps:
    
    1.  In the **Name** field, enter a name for the data source.
    
    2.  From the **Select connection type** list, select **Microsoft SQL Server Analysis Services**.
    
    3.  Click **Build**.

5.  In the **Connection Properties** window, follow these steps:
    
    1.  In the **Server name** field, enter the name of the server that runs Analysis Services.
    
    2.  From the **Select or enter a database name** list, select the database that contains the Microsoft Dynamics AX cubes. By default, the name of this database is **Dynamics AX** or **Dynamics AX initial**.
    
    3.  Click **OK**.

6.  In the **Data Source Properties** window, click **Test Connection** to verify that the data source is configured correctly. After the test is successful, click **OK** to close the window.

7.  The **Choose a connection to a data source** page is redisplayed. Click **Next**.

8.  On the **Design a query** page, select the cube that contains the data to include on the report. Then select the dimensions, measures, or key performance indicators (KPIs) to include on the report.
    
    For example, to create a report that shows the balance of each General ledger account, you would follow these steps:
    
    1.  Select **General ledger cube**.
    
    2.  Expand the **Measures** \> **Ledger transactions** node. Then drag the **General ledger amount – accounting currency** measure onto the design surface.
    
    3.  Expand the **Chart of accounts** node. Then drag the **Account type and number** dimension onto the design surface.
    
    Click **Next**.

9.  On the **Arrange fields** page, specify whether the fields should be formatted as rows, columns, or values by dragging each field to the appropriate box.
    
    For example, to continue the example that was described in the previous step, you would follow these steps:
    
    1.  Drag the **Account\_type** field to the **Row groups** box.
    
    2.  Drag the **Main\_account\_name** field to the **Row groups** box.
    
    3.  Drag the **General\_ledger\_amount\_accounting\_currency** field to the **Values** box.
    
    Click **Next**.

10. On the **Choose the layout** page, select layout options for the report. Click **Next**.

11. On the **Choose a style** page, select a style to specify how the report will be formatted. Click **Finish**.
    
    The design for the report is displayed in Report Builder. For information about how to generate, or run, the report, see the next procedure.

## Generate a report

When you have finished designing a report, you can generate, or run, the report. Click the **Run** button in the Report Builder toolbar. The report will be displayed.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


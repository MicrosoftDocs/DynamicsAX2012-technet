---
title: Create a report by using the Excel data connection wizard to connect to a cube
TOCTitle: Create a report by using the Excel data connection wizard to connect to a cube
ms:assetid: ab93489c-4cd2-4b32-add5-9d7234b75ff3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243095(v=AX.60)
ms:contentKeyID: 35133451
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a report by using the Excel data connection wizard to connect to a cube [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following procedure explains how to use Microsoft Excel to create a custom report that uses a Microsoft SQL Server Analysis Services cube as a data source.

1.  Open Excel.

2.  Click the **Data** tab.

3.  Click **From Other Sources** \> **From Analysis Services**. The **Data Connection Wizard** is displayed.

4.  On the **Connect to Database Server** page, enter the name of the server that is running Analysis Services and then enter credentials to access that server. Click **Next**.

5.  On the **Select Database and Table** page, follow these steps:
    
    1.  Select the Analysis Services database that contains the cubes. By default, the database name is **Dynamics AX** of **Dynamics AX initial**.
    
    2.  Select the cube that contains the data to include on the report.
    
    3.  Click **Next**.

6.  On the **Save Data Connection File and Finish** page, follow these steps:
    
    1.  In the **File Name** field, enter a name for the data connection file that is created. This file can be used to connect to the cube in the future.
    
    2.  Click **Browse** to specify where to save the data connection file.
    
    3.  In the **Description** field, enter a description to help identify the type of data that this file connects to.
    
    4.  In the **Friendly Name** field, enter a user-friendly name for the data connection file.
    
    5.  Click **Finish** to close this wizard.

7.  The **Import Data** dialog box is displayed. Select whether you want to view the cube data in a PivotTable report, or in a PivotChart and PivotTable report. For more information about these options, see the Excel Help. Click **OK**.

8.  To add fields to the report, select the fields in the **PivotTable Field List** pane.
    
    For more information about how to create PivotTable and PivotChart reports, see the Excel documentation. To see an example of this procedure that uses the Microsoft Dynamics AX General ledger cube, see [Walkthrough: Analyzing Cube Data in Excel](walkthrough-analyzing-cube-data-in-excel.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


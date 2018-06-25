---
title: Tools used for analytics
TOCTitle: Tools used for analytics
ms:assetid: 499c97af-ab44-4815-8cb0-d4493e9c66ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731920(v=AX.60)
ms:contentKeyID: 35132848
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Tools used for analytics [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft SQL Server Analysis Services provides online analytical processing (OLAP) functionality for Microsoft Dynamics AX. Analysis Services lets you analyze large quantities of data. You can use it to design, create, and manage cubes that contain detailed and aggregated data from multiple data sources.

To use the Analysis Services cubes that are included with Microsoft Dynamics AX, or to create custom cubes, you must be familiar with Analysis Services and the following tools.

## Microsoft SQL Server Management Studio

Microsoft SQL Server Management Studio is an administrative environment that can be used to work with and manage the cubes in an Analysis Services database. You can use Management Studio to connect to an Analysis Services database and complete the following tasks:

  - Process Analysis Services objects, such as cubes and dimensions.

  - Browse Analysis Services objects.

  - Help secure Analysis Services objects.

  - Write scripts that create, modify, or delete Analysis Services objects.

  - Manage Analysis Services databases.

The following picture shows the cubes that are included with Microsoft Dynamics AX 2012 R2 in the SQL Server 2012 Management Studio.

![SQL Server Management Studio](images/Gg731920.BI_SQLManagementStudio(AX.60).png "SQL Server Management Studio")

For more information about how to work with Analysis Services objects in Management Studio, see the SQL Server documentation on TechNet or MSDN.

## Microsoft Visual Studio

The Microsoft Visual Studio environment can be used to modify the cubes in an Analysis Services database. If you are using SQL Server 2008, the Microsoft Visual Studio environment that you can use is called *SQL Server Business Intelligence Development Studio*. If you are using SQL Server 2012, the Visual Studio environment that you can use is called *SQL Server Data Tools*.

The following picture shows the Budget control cube that is included with Microsoft Dynamics AX 2012 R2 in SQL Server Data Tools.

![Visual Studio](images/Gg731920.BI_BIDS(AX.60).png "Visual Studio")

For more information about how to use the Visual Studio environment to modify cubes, see the SQL Server documentation on TechNet or MSDN.

## Microsoft Dynamics AX Analysis Services Project Wizard

The Analysis Services Project Wizard in Microsoft Dynamics AX is a tool that you can use to complete the following tasks:

  - Deploy the default cubes that are included with Microsoft Dynamics AX.

  - Configure an Analysis Services project after you disable a Microsoft Dynamics AX configuration key.

  - Update an existing Analysis Services project.

  - Create a new, custom Analysis Services project.

For more information, see [Working with Analysis Services Projects](working-with-analysis-services-projects.md).

## Microsoft Excel

Microsoft Excel is a spreadsheet application that you can use to create ad hoc analytical reports. To create a report, open Excel, select the cube data that you want to display on the report, and then format the data as a PivotTable or PivotChart report.

The following picture shows an ad hoc report in Excel.

![Excel PivotTable report](images/Gg731920.BI_ExcelPivotTable(AX.60).png "Excel PivotTable report")

For step-by-step instructions about how to create an ad hoc report in Excel, see [Create a report by using the Excel data connection wizard to connect to a cube](create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md).

## Microsoft Report Builder

Microsoft Report Builder is a component of Microsoft SQL Server Reporting Services that you can use to create ad hoc analytical reports. To create a report, open Report Builder, select the cube data that you want to display on the report, and then select the fields that you want to display on the report.

The following picture shows an ad hoc report in Report Builder.

![Report Builder](images/Gg731920.BI_ReportBuilderUsingCube(AX.60).png "Report Builder")

For step-by-step instructions about how to create an ad hoc report in Report Builder, see [Create a report by using SQL Server Report Builder to connect to a cube](create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


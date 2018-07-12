---
title: Analytics architecture
TOCTitle: Analytics architecture
ms:assetid: 5e94c4a3-c3d3-4655-a98e-6b91f8a0dc8f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309691(v=AX.60)
ms:contentKeyID: 35132658
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Analytics architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following diagram shows the Microsoft SQL Server Analysis Services cubes that are included with Microsoft Dynamics AX, and the components that are used to access them.

![Analytics architecture](images/Dd309691.BI_SSASArchitecture(AX.60).gif "Analytics architecture")

The following components are used to access cubes or display cube data. The numbers in the following list correspond to the components in the diagram.

1.  **Visual Studio** – Developers can use Microsoft Visual Studio tools to build Microsoft SQL Server Reporting Services reports that use cubes as a data source. In order for such a report to be displayed, the Analysis Services data extension retrieves data from a cube, and then the Microsoft Dynamics AX report definition customization extension formats the report. The report is then displayed in the Microsoft Dynamics AX client or in Enterprise Portal for Microsoft Dynamics AX. For information about how to create reports by using the Visual Studio tools, see [Walkthrough: Displaying Cube Data in a Report](walkthrough-displaying-cube-data-in-a-report.md).

2.  **Microsoft Dynamics AX client** – Users can access preconfigured analytical reports from the Microsoft Dynamics AX client. Analytical reports are typically displayed on Role Center pages. For more information about Role Centers, see [Using Role centers](using-role-centers.md).

3.  **Enterprise Portal** – Users can access preconfigured analytical reports from Enterprise Portal. Analytical reports are typically displayed on Role Center pages. For more information about Role Centers, see [Using Role centers](using-role-centers.md).

4.  **Excel** – Microsoft Excel has a data connection wizard that users can run to access cubes and design PivotTable or PivotChart reports. For more information, see [Create a report by using the Excel data connection wizard to connect to a cube](create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md).

5.  **Report Builder** – Microsoft Report Builder is a component of Reporting Services that users can use to design and format reports and charts. For more information, see [Create a report by using SQL Server Report Builder to connect to a cube](create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md).

  



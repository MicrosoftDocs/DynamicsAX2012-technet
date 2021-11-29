---
title: Automate the processing of cubes
TOCTitle: Automate the processing of cubes
ms:assetid: 4b5e2423-fefd-490f-8561-a09eccedcc78
ms:mtpsurl: https://technet.microsoft.com/library/Dd309669(v=AX.60)
ms:contentKeyID: 35132625
author: Khairunj
ms.author: daxcpft
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Automate the processing of cubes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a cube is processed, the data in the cube is updated with data from the online transaction processing (OLTP) database. Microsoft SQL Server Analysis Services provides several options that you can use to process cubes. This topic provides a high-level overview of some of the options that are available to automate the processing of cubes. This topic also includes information about how to manually process cubes.

For more information about the processing options that are available, see the [SQL Server documentation](https://technet.microsoft.com/library/ms174860\(v=sql.105\).aspx).

## Automated processing

The following tools are available to help you automate the processing of cubes:

  - **SQL Server Agent**
    
    SQL Server Agent is a Windows service that runs scheduled administrative tasks, or *jobs*. For example, you can create a job that processes a cube and then performs a backup of the cube. For more information, see [Automating Administrative Tasks (SQL Server Agent)](https://technet.microsoft.com/library/ms187061\(sql.105\).aspx).

  - **SQL Server Integration Services**
    
    SQL Server Integration Services is a platform that is used to build enterprise-level data integration and data transformation solutions. You can use an Integration Services package to automatically process cubes. The package that you create should include at least two **Analysis Services Processing** tasks. The first task should process the dimensions, and the second task should process the cubes. For more information, see the [Analysis Services Processing Task](https://technet.microsoft.com/library/ms141779.aspx) topic and the [Cube Processing](https://social.technet.microsoft.com/forums/en-us/sqldatawarehousing/thread/208d3553-f92a-4929-8747-9002fda68fb7) discussion.

## Manual processing

You can manually process an Analysis Services database and all the objects that it contains, such as cubes and dimensions. You can manually process a specific cube, as well.

To process an Analysis Services database and all the objects that it contains, follow these steps.

1.  In SQL Server Management Studio, connect to your Analysis Services instance.

2.  In the tree view, right-click the database, and then click **Process**. The **Process Database – \[Database Name\]** window is displayed.

3.  Click **OK** to process the database.

To process a specific cube, follow these steps.

1.  In SQL Server Management Studio, connect to your Analysis Services instance.

2.  In the tree view, right-click the cube, and then click **Process**. The **Process Cube – \[Cube Name\]** window is displayed.

3.  Click **OK** to process the cube.

## Processing options and settings

When you process objects in Analysis Services, you can select a processing option to control the type of processing that occurs for each object. You can also enable Analysis Services to determine the appropriate type of processing. Processing methods vary, depending on the type of object and on the change that has been made to the object since the last time that the object was processed. If you enable Analysis Services to automatically select a processing method, Analysis Services uses the method that returns the object to a fully processed state in the shortest time.

Processing settings let you control the objects that are processed and the methods that are used to process those objects.

For more information about the processing options and settings that are available, see [Processing Options and Settings](https://technet.microsoft.com/library/ms174774\(sql.105\).aspx).

  



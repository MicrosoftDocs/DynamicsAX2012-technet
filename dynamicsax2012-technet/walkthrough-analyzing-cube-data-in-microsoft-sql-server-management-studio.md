---
title: 'Walkthrough: Analyzing Cube Data in Microsoft SQL Server Management Studio'
TOCTitle: 'Walkthrough: Analyzing Cube Data in Microsoft SQL Server Management Studio'
ms:assetid: 83cf4a82-8385-456c-afb0-7bb47194701a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724059(v=AX.60)
ms:contentKeyID: 35133415
ms.date: 07/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Analyzing Cube Data in Microsoft SQL Server Management Studio 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can analyze data by using Microsoft SQL Server Management Studio to connect to a Microsoft Dynamics AX OLAP cube.

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data

  - The General Ledger default cube, deployed and processed. For more information, see [Deploy the default cubes](deploy-the-default-cubes.md).

  - Configure Analysis Services by running the Microsoft Dynamics AX Setup wizard

  - Microsoft SQL Server Management Studio

## Analyzing Cube Data in Microsoft SQL Server Management Studio

To analyze the General Ledger cube data by using Microsoft SQL Server Management Studio, you must connect to the cube data that is deployed and processed in a SQL Server Analysis Services (SSAS) database.

### To analyze cube data

1.  Open Microsoft SQL Server Management Studio.

2.  On the **Connect to Server** page, select **Analysis Services** for Server type. Enter the name of the server that contains the Analysis Services database for the General Ledger cube, enter credentials used to access the server, and then click **Connect**.

3.  Right-click **Databases** \> **Dynamics AX** \> **Cubes** \> **General ledger cube** and then click **Browse**.
    

    > [!NOTE]
    > <P>The name of the database that contains the General ledger cube may vary. For example, if you use Microsoft Dynamics AX 2012 R2, the database name is <STRONG>Dynamics AX initial</STRONG> by default.</P>



4.  In **General ledger cube \[Browse\]**, drag **Measures** \> **Ledger transactions** \> **General ledger amount – transaction currency** onto the data region area.

5.  Drag a financial dimension onto the row field area. If you included the Main account dimension in the Analysis Services project that contains the General ledger cube, use **Main account OLAPMAINACCOUNT** \> **Main account OLAPMAINACCOUNT.Main account**.
    

    > [!NOTE]
    > <P>The available dimensions will vary depending on your Analysis Services project.</P>



6.  Browse the data.

## See also

[Development Tasks for Analytics](development-tasks-for-analytics.md)


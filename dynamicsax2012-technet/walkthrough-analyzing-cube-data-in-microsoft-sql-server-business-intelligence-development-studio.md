---
title: 'Walkthrough: Analyzing Cube Data in Microsoft SQL Server Business Intelligence Development Studio'
TOCTitle: 'Walkthrough: Analyzing Cube Data in Microsoft SQL Server Business Intelligence Development Studio'
ms:assetid: 20c1c764-589b-42e3-8cff-7c9f2ce0d484
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731907(v=AX.60)
ms:contentKeyID: 35132829
ms.date: 07/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Analyzing Cube Data in Microsoft SQL Server Business Intelligence Development Studio [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can analyze data by using Microsoft SQL Server Business Intelligence Development Studio (BIDS) to analyze a Microsoft Dynamics AX analysis cube.


> [!NOTE]
> <P>In SQL Server 2012, BIDS is called SQL Server Data Tools.</P>



## Prerequisites

To complete this walkthrough, you will need:

  - The General Ledger default cube, deployed and processed.

  - Configure Analysis Services by running the Microsoft Dynamics AX Setup wizard

  - Microsoft SQL Server Business Intelligence Development Studio

## Analyzing Cube Data in Microsoft SQL Server Business Intelligence Develpment Studio

To analyze the General Ledger cube data by using BIDS you must open the Analysis Services project that contains the General Ledger cube.

### To analyze cube data

1.  In BIDS, open the Analysis Services project that contains the General Ledger cube.

2.  In Solution Explorer, double click **Dynamics AX** \> **Cubes** \> **LedgerCube.cube**.
    

    > [!NOTE]
    > <P>If you are using Microsoft Dynamics AX 2012 R2, double click <STRONG>Dynamics AX initial</STRONG> &gt; <STRONG>Cubes</STRONG> &gt; <STRONG>LedgerCube.cube</STRONG>.</P>



3.  Click the **Browser** tab.

4.  Drag **General ledger cube** \> **Measures** \> **Ledger transactions** \> **General ledger amount – transaction currency** onto the **Drop Totals or Detail Fields Here** area.

5.  Drag a financial dimension onto the **Drop Row Fields Here** area. If you included the Main account dimension in the Analysis Services project that contains the General ledger cube, use **Main account OLAPMAINACCOUNT** \> **Main account OLAPMAINACCOUNT.Main account**.
    

    > [!NOTE]
    > <P>The available dimensions will vary depending on your Analysis Services project.</P>



6.  Browse the data.

## See also

[Defining Cubes in Microsoft Dynamics AX](defining-cubes-in-microsoft-dynamics-ax.md)


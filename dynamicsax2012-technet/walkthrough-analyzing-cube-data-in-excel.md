---
title: 'Walkthrough: Analyzing Cube Data in Excel'
TOCTitle: 'Walkthrough: Analyzing Cube Data in Excel'
ms:assetid: b9abcaff-7ef6-4dd8-962b-608a833e7683
ms:mtpsurl: https://technet.microsoft.com/library/Dd261526(v=AX.60)
ms:contentKeyID: 28119575
author: tonyafehr
ms.date: 07/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Analyzing Cube Data in Excel 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can analyze data by using Microsoft Office Excel to connect to a Microsoft Dynamics AX analysis cube.

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data

  - The General Ledger default cube, deployed and processed.

  - Configure Analysis Services by running the Microsoft Dynamics AX Setup wizard

  - Microsoft Office Excel

## Analyzing Cube Data in a Pivot Table

To analyze the General Ledger cube data through a pivot table you must import the cube data from your Analysis Services database into Microsoft Office Excel.

### To analyze cube data in a pivot table

1.  Open Microsoft Office Excel. Click **Data** \> **From Other Sources** \> **From Analysis Services**. Data Connection Wizard opens.

2.  On the **Connect to Database Server** page, enter the name of the server that contains the Analysis Services database for the General Ledger cube, enter credentials used to access the server, and then click **Next**.

3.  On the **Select Database and Table** page, select the **Dynamics AX** database, select **General ledger cube**, and then click **Next**.
    

    > [!NOTE]
    > <P>If you are using Microsoft Dynamics AX 2012 R2, select <STRONG>General ledger cube</STRONG> from the <STRONG>Dynamics AX initial</STRONG> database.</P>



4.  On the **Save Data Connection File and Finish** page, enter a file name and friendly name, and then click **Finish**.
    

    > [!NOTE]
    > <P>After you set up a data connection to a cube, that connection can be reused to connect to the cube in the future.</P>



5.  In the **Import Data** dialog, select **PivotTable Report**, specify the location for the report within the spreadsheet, and then click **OK**.

6.  In the **Pivot Table Field List** pane, select **General ledger amount – accounting currency** located under the **∑ Ledger transactions** node. This adds the measure to the data region area in the pivot table.

7.  Select **Account type and number** located under the **Chart of accounts** node.
    

    > [!NOTE]
    > <P>The available dimensions will vary depending on your Analysis Services project.</P>



8.  Browse the data in the pivot table.


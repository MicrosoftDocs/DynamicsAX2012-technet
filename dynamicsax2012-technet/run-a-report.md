---
title: Run a report
TOCTitle: Run a report
ms:assetid: 71b1bc63-c175-4ca8-babe-75a318d0280b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549967(v=AX.60)
ms:contentKeyID: 36058069
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Run a report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are three different expense distribution sheet (EDS) reports:

  - Dimension statement

  - Cost statement, dimensions

  - Cost statement, hierarchy

## Generate an EDS

1.  Click **Cost accounting** \> **Setup** \> **Expense distribution sheet**. Open one of the EDS reports.

2.  On the **General** tab, use the **Identification** list to select the statement that you created in the EDS setup.

3.  In the **Calculation type** list, select either **Period calculation** or **Special calculation**. The calculation type is usually entered in the EDS setup, but you can modify it here before you generate the report. If you select **Special calculation**, you must select a calculation number in the **Calculation number** list.

4.  If you did not set up a specific date interval for each dimension in the EDS setup, you can configure date interval settings in the **Date interval** area before you generate the report.

5.  On the **Column definition** tab, you can modify the value type and budget model in the appropriate columns.

6.  Click **OK** to generate the report.

## Dimension statement

In addition to modifying settings that are common to the types of EDS, when you run a dimension statement, you can modify the dimension setup or the divisions for each column.

## Cost statement, dimensions

When you run a cost statement for dimensions, select any dimension type and the range of dimensions that you need.

## Cost statement, hierarchy

When you run a cost statement for hierarchies, select a hierarchy, if you have not already done this, and then select the range of divisions.

## See also

[Expense distribution sheet](expense-distribution-sheet.md)

[Create an expense distribution sheet](create-an-expense-distribution-sheet.md)

  



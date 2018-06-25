---
title: (ITA) Execute final fiscal LIFO report
TOCTitle: (ITA) Execute final fiscal LIFO report
ms:assetid: a8bfd8ba-3127-4101-ac7d-6ac9468443f2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550315(v=AX.60)
ms:contentKeyID: 36058890
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculate fiscal LIFO
- fiscal LIFO
---

# (ITA) Execute final fiscal LIFO report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The final calculation of fiscal LIFO covers the whole fiscal year, and the journal can be posted or closed only one time per year.

If the average value of the last month in the year is lower than the average of the year, you can specify to use the normal value. For more information about normal value, see [(ITA) About the calculation engine](ita-about-the-calculation-engine.md).

The report date of the final report is the day when the final calculation is run, and this date does not change if the report is printed again later.


> [!NOTE]
> <P>When you initiate the calculation of the final report, the last period of the fiscal year must be closed, and the inventory must be closed to make sure that the value of the inventory is not adjusted after the report is posted.</P>



## Calculate, close, and print the final report

1.  Click **Inventory management** \> **Journals** \> **Fiscal LIFO** \> **Fiscal LIFO annual municipal report**.

2.  Press CTRL+N to create a new line, or select the existing final journal line, and then click the **General** tab. If you create a new journal line, the dates are displayed in the **Start date** and the **End date** to show the first day and the last day, respectively, of the current year.

3.  To include work in progress (WIP) in the report, select the **Include work in progress** check box.

4.  To use the normal value as the basis for the calculation, select the **Use normal value** check box.

5.  Click **Calculate lines** to calculate the transaction lines for the final report.

6.  Click **Close final report** to close the report.

7.  Click **Print** to print the report.


> [!NOTE]
> <P>To apply the normal value or include work in progress (WIP) in the calculation of the inventory value, you must first set up the normal value and the WIP calculation. You must complete this setup before you process your journal lines. For more information about how to set up the calculation of normal value and WIP, see <A href="ita-calculate-fiscal-lifo-journal-lines.md">(ITA) Calculate fiscal LIFO journal lines</A>.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


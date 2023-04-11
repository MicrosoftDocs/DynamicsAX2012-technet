---
title: (RUS) Generate the inventory balance turnover report
TOCTitle: (RUS) Generate the inventory balance turnover report
ms:assetid: c627af2e-4f93-4b4b-8e28-4dea032af299
ms:mtpsurl: https://technet.microsoft.com/library/Dn126127(v=AX.60)
ms:contentKeyID: 52075431
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- warehouse
- trial balance
- generate trial balance
- warehouse trial balance
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate the inventory balance turnover report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Inventory balance turnover** form to generate the inventory balance turnover report. You can generate the report grouped by the following dimensions:

  - **Inventory profile**

  - **Warehouse**

  - **Site**

  - **Kind of activity**

  - **Balance account**

  - **Storno**

  - **Dimension**

You can also group the transactions by inventory turnover dimension. In the **Inventory and warehouse management parameters** form, in the **General** area, in the **Inventory turnover dimension** field, select the inventory turnover dimension that to use to group the transactions. In the **Inventory dimensions** area, you can select the inventory dimensions (**Inventory profile**, **Warehouse**, and **Site**) to want to work with, and to display for the journal lines. For more information, see [Inventory and warehouse management parameters (form)](https://technet.microsoft.com/library/aa587658\(v=ax.60\)). The total amount for each item is calculated and displayed in the report as a total amount of inventory transactions and inventory transaction adjustments for the period, for each inventory dimension.

## Generate the inventory balance turnover report

1.  Click **Inventory management** \> **Inquiries** \> **Transactions** \> **Inventory balance turnover**.

2.  In the **Start date** and **To date** fields, select the starting and ending dates of the period that the report is generated for.

3.  Select the **Expand turnovers** check box to include turnovers from internal transfers in the report.

4.  Select the **Show physical turnover** check box to include physical inventory turnovers in the report.

5.  Select the **Show totals** check box to calculate and display total turnover values in the report.

6.  Select the **Show zero turnover** check box to include transaction lines with zero turnover for the specified period.

7.  Select the **Show item name** check box to include the item name in the report.

8.  Click **Select**.

9.  In the **Criteria** field, select the condition that the **Inventory profile**, **Warehouse**, **Site**, **Kind of activity**, **Balance account**, **Storno**, or **Dimension** field must match to be returned by the query.

10. Click the **Dimensions** tab.

11. In the **Available fields** list, select the fields that you want to display in the report, and then move them to the **Selected fields** list.

12. Click **OK** to generate the report.

Some temporary data is generated when you generate the inventory balance turnover report. To remove this temporary data, click **Inventory and warehouse management** \> **Periodic** \> **Clean up** \> **Cleanup on-hand inventory calculation on date**. In the **Created until** field, select a date, and then click **OK** to delete the data that is created up until the specified date.

## Calculate on-hand inventory on inventory closing date

You can run a periodic job to calculate on-hand inventory on the inventory closing date. When the periodic job is run, transactions that are related to remaining items are generated and grouped by the **Inventory profile**, **Warehouse**, **Site**, **Kind of activity**, **Balance account**, **Storno**, and **Dimension** dimensions.


> [!NOTE]
> <P>When you cancel the on-hand inventory closing process, transactions that are related to remaining items are canceled.</P>



1.  Click **Inventory management** \> **Periodic** \> **On-hand inventory on date**.

2.  In the **Date of on-hand calculation** field, select an inventory closing date.

3.  Select the **Update calculation** check box to recalculate on-hand inventory.

4.  Click **OK** to run inventory closing.

## See also

[(RUS) Set up a dual warehouse layer](rus-set-up-a-dual-warehouse-layer.md)

  



---
title: (CHN) Generate the inventory summary reports
TOCTitle: (CHN) Generate the inventory summary reports
ms:assetid: 581800a9-5544-4041-8974-7021d4b38a63
ms:mtpsurl: https://technet.microsoft.com/library/JJ664041(v=AX.60)
ms:contentKeyID: 49384625
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Generate the inventory summary reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Organizations often use inventory summary reports to view the issue history or receipt history for inventory items, summaries of inventory status, and reports of detailed inventory status for a specific period. You can query the inventory summary details, with an option to set the inventory dimensions.

Use the following reports to check the inventory movement in a warehouse:

  - **Inventory status** report − Displays the opening balance, items received, items issued, and closing balance of inventory items for a specified period.

  - **Inventory in/out status** report − Displays a detailed issue and receipt status of inventory items for a specified period. For example, the **In** status displays the number of items received through a purchase order, production order, transfer order, physical count, and other receipt transactions. The **Out** status displays the number of items issued through a sales order, production order, transfer order, physical count, and other issue transactions.

  - **Issue/receive summary** report – Displays the issue and receipt history of inventory items for a specified period.

## Generate the Inventory status report

Use the **Inventory status** form to generate an **Inventory status** report.

1.  Click **Inventory management** \> **Inquiries** \> **Inventory status**.

2.  Click the **Parameters** FastTab.

3.  In the **Item group** and **Item number** fields, select the item group and item number for which the inventory transaction details are displayed.

4.  In the **Start date** and **End date** fields, select the starting date and the ending date of the reporting period.
    

    > [!NOTE]
    > <P>If you do not enter a starting date or an ending date, the first day of the current month is considered to be the starting date. The current date is considered to be the ending date.</P>



5.  Select the **Show zero lines** check box to display items without physical quantity or a dimension value.

6.  Click **Query** to retrieve the item details based on the filtering criteria selected on the **Parameters** tab.

7.  Click **Dimensions display**, and then select additional inventory dimensions to display on the report. Options include item color, configuration, size, batch number, serial number, and warehouse details.

8.  Click **Print** to generate the **Inventory status** report.

## Generate the Inventory in/out status report

Use the **Inventory in/out status** form to generate an **Inventory in/out status** report.

1.  Click **Inventory management** \> **Inquiries** \> **Inventory in/out status**.

2.  Repeat steps 2 through 6 in Generate the Inventory status report to retrieve the item details to print on the **Inventory in/out status** report.

3.  Click **Print** to generate the **Inventory in/out status** report.

## Generate the Issue/receive summary report

1.  Click **Inventory management** \> **Inquiries** \> **On-hand**. Click **Issue/receive summary**.

2.  In the **Physical date** field, select the date of the issue transaction or the receipt transaction.

3.  In the **Item number** field, enter the number of the item for which the inventory transaction details are displayed.

4.  In the **Received** field, enter the total received quantity of the item on a specified day.
    

    > [!NOTE]
    > <P>If several receipt transactions took place on the same day, the total received quantity is displayed. If inventory dimensions are set, the summary is displayed by dimension.</P>



5.  In the **Issued** field, enter the total issued quantity of the item on a specified day.
    

    > [!NOTE]
    > <P>If several issue transactions took place on the same day, the total issued quantity is displayed. If inventory dimensions are set, the summary is displayed by dimension.</P>



6.  In the **Accumulated received** field, enter the total accumulated received quantity of the item from the starting date until the transaction date.

7.  In the **Accumulated issued** field, enter the total accumulated issued quantity of the item from the starting date until the transaction date.

8.  In the **On-hand of the day** field, enter the on-hand quantity of the item on the transaction date.

## See also

[(CHN) Inventory status (form)](https://technet.microsoft.com/library/jj664055\(v=ax.60\))

[(CHN) Inventory in/out status (form)](https://technet.microsoft.com/library/jj664092\(v=ax.60\))

  



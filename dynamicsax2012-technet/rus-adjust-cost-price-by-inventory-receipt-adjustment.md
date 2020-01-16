---
title: (RUS) Adjust cost price by inventory receipt adjustment
TOCTitle: (RUS) Adjust cost price by inventory receipt adjustment
ms:assetid: f6b125bd-3378-42d0-a986-86653aff13a3
ms:mtpsurl: https://technet.microsoft.com/library/JJ678619(v=AX.60)
ms:contentKeyID: 49388101
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Adjust cost price by inventory receipt adjustment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can perform separate cost price adjustments in default and secondary currencies.

1.  Click **Inventory management** \> **Periodic** \> **Close and adjustment in currency**.

2.  Click **Adjustment** \> **Transactions**.

3.  Click **Select** to open the query form for setting up the selection criteria for the inventory receipt transactions to be adjusted.

4.  Click **OK**. After the selection is made, the **Adjust transactions** form displays a list of inventory receipts.

5.  Click **Delete** to delete the selection.

6.  Click **Select** to add new lines, and then select the transactions again by clicking **Select**.

7.  In the **Date financial** field, enter the financial date of a transaction.

8.  In the **Item number** field, enter an item number.

9.  In the **Warehouse**, **Configuration**, **Size**, **Color**, and **Number** fields, the codes for dimensions that are used to adjust the on-hand inventory are indicated.
    

    > [!NOTE]
    > <P>You can select the displayed dimensions in the <STRONG>Inventory dimensions</STRONG> form.</P>



10. In the **Posted quantity** field, enter the item quantity for the transaction.

11. In the **Posted value** field, enter the transaction amount.

12. In the **Adjustment** field, enter the previously posted cost price adjustment.

13. In the **Edit now** field, enter the amount to be used to adjust the inventory receipt value.

14. Click **Adjustment** to adjust values for all selected transactions.

15. Click **Post** to post the results of transaction adjustments in a similar way as the on-hand inventory adjustments.
    

    > [!NOTE]
    > <P>After posting, an additional ledger posting is generated and the cost price in the inventory transaction is adjusted. The adjustment amount is displayed in the <STRONG>Adjustment</STRONG> field in the <STRONG>Item operations</STRONG> form. When you use the <STRONG>Operations</STRONG> adjustment function, the adjustments will be posted to profit and loss accounts that are entered in the inventory posting settings for ledger accounts. A list of all completed cost price adjustment sessions is displayed in the <STRONG>Close and Adjustment - secondary currency</STRONG> form.</P>


  



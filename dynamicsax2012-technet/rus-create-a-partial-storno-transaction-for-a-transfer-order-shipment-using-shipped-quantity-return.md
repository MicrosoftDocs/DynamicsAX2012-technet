---
title: (RUS) Create a partial storno transaction for a transfer order shipment using shipped quantity return
TOCTitle: (RUS) Create a partial storno transaction for a transfer order shipment using shipped quantity return
ms:assetid: 6a41e258-fae5-4ec2-adfd-34ec507b769f
ms:mtpsurl: https://technet.microsoft.com/library/JJ678329(v=AX.60)
ms:contentKeyID: 49387560
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- storno
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a partial storno transaction for a transfer order shipment using shipped quantity return 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a partial storno transaction by specifying the return quantity for the inventory dimension value of an item.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create and post a transfer order shipment.
    

    > [!NOTE]
    > <P>For more information about transfer order shipments, see <A href="https://technet.microsoft.com/library/aa634530(v=ax.60)">Transfer orders (form)</A>, <A href="set-up-transfer-order-lines.md">Set up transfer order lines</A> and <A href="set-up-transfer-order-lines.md">Set up transfer order lines</A>.</P>



3.  Select a transfer order that has a transfer status of **Shipped**.

4.  Click **Posting** \> **Ship transfer order** to open the **Shipment** form. By default, the **Credit correction** check box is selected if you select the **Credit correction in transfer order** check box in the **Inventory and warehouse management parameters** form.

5.  In the **Update** field, select **Shipped quantity return** to create a return transaction. After you select **Shipped quantity return** in the **Update** field, the **Shipment voucher** field can be modified.

6.  In the **Shipment voucher** field, select the shipment voucher that is generated for the selected transfer order. After you select the shipment voucher, the item number and other inventory details from the referenced transaction are displayed in the lower pane. The shipped quantity is changed to a negative value.

7.  Select the **Edit lines** check box to modify the return quantity for an item.

8.  Select the **Explode lines** check box to modify the return quantity according to the inventory dimension of the transaction. This check box is available only when you select the **Edit lines** check box.

9.  In the **Ship quantity** field, modify the return quantity. The modified quantity should be negative and should not be more than the shipped quantity.

10. Click **OK** to post the shipment transaction. The following actions occur:
    
      - A voucher number is generated for the storno transaction.
    
      - The transfer status of the selected transfer order is updated to **Created** in the **Transfer orders** form.
    
      - The **Ship remain** value for the item is updated with the returned quantity in the **Transfer orders** form.

11. Click **Inventory management** \> **Inquiries** \> **Transfer orders** \> **Transfer order history**.

12. In the **Transfer order history** form, view the storno inventory transactions. If the **Credit correction** check box is cleared when you post the transfer order, only the **Goods return** check box is available for the record in the transfer order history.

13. Close the **Transfer order history** form.

14. In the **Transfer orders** form, click **Inventory** \> **Transactions** to open the **Inventory transactions** form. You can view the shipment transactions and return transactions for the selected item.
    

    > [!NOTE]
    > <P>You can generate the Inventory balance turnover report to validate the reversal entry of the transfer order. You can also view the ledger transactions that are received during transaction posting on the transfer order by using the <STRONG>Inquiry</STRONG> form.</P>



## See also

[(RUS) About storno transactions in transfer orders](rus-about-storno-transactions-in-transfer-orders.md)

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/library/jj733409\(v=ax.60\))

[(RUS) Transfer order shipment (modified form)](https://technet.microsoft.com/library/jj733191\(v=ax.60\))

[Transfer order history (form)](https://technet.microsoft.com/library/aa575833\(v=ax.60\))

[(RUS) Transfer order history (modified form)](https://technet.microsoft.com/library/jj856120\(v=ax.60\))

[Inventory transactions (form)](https://technet.microsoft.com/library/aa584374\(v=ax.60\))

[(RUS) Inventory transactions (modified form)](https://technet.microsoft.com/library/jj733410\(v=ax.60\))

  



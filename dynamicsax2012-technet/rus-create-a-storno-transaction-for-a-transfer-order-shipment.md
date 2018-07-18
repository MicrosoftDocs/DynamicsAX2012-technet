---
title: (RUS) Create a storno transaction for a transfer order shipment
TOCTitle: (RUS) Create a storno transaction for a transfer order shipment
ms:assetid: 1923b8cf-f4ac-4a7d-8bdb-ea9c6634032c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711441(v=AX.60)
ms:contentKeyID: 49387259
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- storno
- transfer order
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a storno transaction for a transfer order shipment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a transfer order and ship items from a source warehouse to a destination warehouse. If an error is found after the item is shipped, you can reverse the entry for the shipment from the warehouse and post the transfer order again with the corrected information.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create and post a transfer order shipment.
    

    > [!NOTE]
    > <P>For more information about transfer order shipments, see <A href="https://technet.microsoft.com/en-us/library/aa634530(v=ax.60)">Transfer orders (form)</A>,<A href="set-up-transfer-order-lines.md">Set up transfer order lines</A></P>



3.  Select a transfer order that has a transfer status of **Shipped**.

4.  Click **Posting** \> **Ship transfer order** to open the **Shipment** form. By default, the **Credit correction** check box is selected if you select the **Credit correction in transfer order** check box in the **Inventory and warehouse management parameters** form.

5.  In the **Update** field, select **Shipped quantity return** to create a return transaction. After you select **Shipped quantity return** in the **Update** field, the **Shipment voucher** field can be modified.

6.  In the **Shipment voucher** field, select the shipment voucher that is generated for the selected transfer order. After you select the shipment voucher, the lines in the lower pane are populated with the item number and other inventory details from the referenced transaction. The shipped quantity is changed to a negative value.

7.  Click **OK** to post the shipment transaction. The following actions occur:
    
      - A voucher number is generated for the storno transaction.
    
      - The transfer status of the selected transfer order is updated to **Created** in the **Transfer orders** form.
    
      - The **Ship remain** value for the item is updated with the returned quantity in the **Transfer orders** form.

8.  Click **Inventory management** \> **Inquiries** \> **Transfer orders** \> **Transfer order history**.

9.  In the **Transfer order history** form, view the storno inventory transactions.

10. Close the **Transfer order history** form.

11. In the **Transfer orders** form, click **Inventory** \> **Transactions** to open the **Inventory transactions** form. You can view the shipment transactions and return transactions for the selected item.
    

    > [!NOTE]
    > <P>You can generate the Inventory balance turnover report to validate the reversal entry of the transfer order. You can also view the ledger transactions that are received during transaction posting on the transfer order by using the <STRONG>Inquiry</STRONG> form.</P>



## See also

[(RUS) About storno transactions in transfer orders](rus-about-storno-transactions-in-transfer-orders.md)

[(RUS) Create a partial storno transaction for a transfer order shipment using negative shipped quantity](rus-create-a-partial-storno-transaction-for-a-transfer-order-shipment-using-negative-shipped-quantity.md)

[(RUS) Create a partial storno transaction for a transfer order shipment using shipped quantity return](rus-create-a-partial-storno-transaction-for-a-transfer-order-shipment-using-shipped-quantity-return.md)

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/en-us/library/jj733409\(v=ax.60\))

[(RUS) Transfer order shipment (modified form)](https://technet.microsoft.com/en-us/library/jj733191\(v=ax.60\))

[Transfer order history (form)](https://technet.microsoft.com/en-us/library/aa575833\(v=ax.60\))

[Inventory transactions (form)](https://technet.microsoft.com/en-us/library/aa584374\(v=ax.60\))

[(RUS) Inventory transactions (modified form)](https://technet.microsoft.com/en-us/library/jj733410\(v=ax.60\))

  



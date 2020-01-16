---
title: (RUS) Create a partial storno transaction for a transfer order receipt using received quantity return
TOCTitle: (RUS) Create a partial storno transaction for a transfer order receipt using received quantity return
ms:assetid: e992b44b-72b7-4f91-8016-897b6fca7af4
ms:mtpsurl: https://technet.microsoft.com/library/JJ711723(v=AX.60)
ms:contentKeyID: 49388046
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- storno
- receipt order
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a partial storno transaction for a transfer order receipt using received quantity return 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a partial storno transaction by specifying a negative receipt quantity according to the inventory dimension value of an item.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create and post a transfer order receipt.
    

    > [!NOTE]
    > <P>For more information about transfer order receipts, see <A href="https://technet.microsoft.com/library/aa634530(v=ax.60)">Transfer orders (form)</A>, <A href="set-up-transfer-order-lines.md">Set up transfer order lines</A>, and <A href="receive-transfer-orders.md">Receive transfer orders</A>.</P>



3.  Select a transfer order that has a transfer status of **Received**.

4.  Click **Posting** \> **Receive** to open the **Receive** form. By default, the **Credit correction** check box is selected if you have selected the **Credit correction in transfer order** check box in the **Inventory and warehouse management parameters** form.

5.  In the **Update** field, select **Received quantity return**.

6.  In the **Voucher reference** field, select the receipt voucher that is generated for the selected transfer order receipt. After you select the voucher reference, the lines in the lower pane are populated with the item number and other inventory details from the referenced transaction.

7.  Select the **Edit lines** check box to modify the return quantity for an item.

8.  Select the **Explode lines** check box to modify the return quantity according to the inventory dimension of the item. This check box is available only when you select the **Edit lines** check box.

9.  In the **Receive quantity** field, modify the return quantity. The modified quantity should be negative and should not be more than the shipped quantity.

10. Select the **Edit lines** check box, and then modify the received quantity, if the quantity requires modification.

11. Click **OK** to post the receipt transaction. The following actions occur:
    
      - A voucher number is generated for the storno transaction.
    
      - The transfer status of the selected transfer order is updated to **Shipped** in the **Transfer orders** form.
    
      - The **Receive remain** value for the item is updated with the returned quantity in the **Transfer orders** form.

12. Click **Inventory management** \> **Inquiries** \> **Transfer orders** \> **Transfer order history**.

13. In the **Transfer order history** form, view the storno inventory transactions. If the **Credit correction** check box is cleared when you post the transfer order, only the **Goods return** check box is selected.

14. Close the **Transfer order history** form.

15. In the **Transfer orders** form, click **Inventory** \> **Transactions** to open the **Inventory transactions** form. You can view the receipt transactions and return transactions for the selected item.
    

    > [!NOTE]
    > <P>You can generate the Inventory balance turnover report to validate the reversal entry of the transfer order. You can also view the ledger transactions that are received during transaction posting on the transfer order by using the <STRONG>Inquiry</STRONG> form.</P>



## See also

[(RUS) Generate a storno transaction for a transfer order receipt with scrap quantity](rus-generate-a-storno-transaction-for-a-transfer-order-receipt-with-scrap-quantity.md)

[Receive (form)](https://technet.microsoft.com/library/aa552649\(v=ax.60\))

[(RUS) Receive (modified form)](https://technet.microsoft.com/library/jj678418\(v=ax.60\))

[Transfer order history (form)](https://technet.microsoft.com/library/aa575833\(v=ax.60\))

[(RUS) Transfer order history (modified form)](https://technet.microsoft.com/library/jj856120\(v=ax.60\))

[Inventory transactions (form)](https://technet.microsoft.com/library/aa584374\(v=ax.60\))

[(RUS) Inventory transactions (modified form)](https://technet.microsoft.com/library/jj733410\(v=ax.60\))

  



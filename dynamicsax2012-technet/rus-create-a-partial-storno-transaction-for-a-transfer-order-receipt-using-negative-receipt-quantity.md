---
title: (RUS) Create a partial storno transaction for a transfer order receipt using negative receipt quantity
TOCTitle: (RUS) Create a partial storno transaction for a transfer order receipt using negative receipt quantity
ms:assetid: a1d57b7a-1b77-48e3-a751-a9d1f893a81d
ms:mtpsurl: https://technet.microsoft.com/library/JJ678554(v=AX.60)
ms:contentKeyID: 49387784
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- storno
- receipt order
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a partial storno transaction for a transfer order receipt using negative receipt quantity 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a partial storno transaction by specifying part of the received quantity as a negative value in the **Receive now** field in the **Transfer orders** form.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create and post a transfer order receipt.
    

    > [!NOTE]
    > <P>For more information about transfer order receipts, see <A href="https://technet.microsoft.com/library/aa634530(v=ax.60)">Transfer orders (form)</A>, <A href="set-up-transfer-order-lines.md">Set up transfer order lines</A>, and <A href="receive-transfer-orders.md">Receive transfer orders</A>.</P>



3.  Select a transfer order that has a transfer status of **Received**.

4.  In the lower pane, click the **Receive now** tab, and then, in the **Receive now** field, modify the receipt quantity. The modified quantity should be negative and should not be more than the received quantity.

5.  Click **Posting** \> **Receive** to open the **Receive** form. By default, the **Credit correction** check box is selected if you select the **Credit correction in transfer order** check box in the **Inventory and warehouse management parameters** form.

6.  In the **Update** field, select **Receive now** to create a return transaction.
    

    > [!NOTE]
    > <P>The lines in the lower pane are populated with the item number and other inventory details from the referenced transaction.</P>



7.  Select the **Edit lines** check box, and then modify the received quantity, if the quantity requires modification.

8.  Click **OK** to post the receipt transaction. The following actions occur:
    
      - A voucher number is generated for the storno transaction.
    
      - The transfer status of the selected transfer order is updated to **Received** in the **Transfer orders** form.
    
      - The **Receive remain** value for the item is updated with the returned quantity in the **Transfer orders** form.

9.  Click **Inventory management** \> **Inquiries** \> **Transfer orders** \> **Transfer order history**.

10. In the **Transfer order history** form, view the storno inventory transactions. If the **Credit correction** check box is cleared when you post the transfer order, only the **Goods return** check box is selected.

11. Close the **Transfer order history** form.

12. In the **Transfer orders** form, click **Inventory** \> **Transactions** to open the **Inventory transactions** form. You can view the receipt transactions and return transactions for the selected item.
    

    > [!NOTE]
    > <P>You can generate the Inventory balance turnover report to validate the reversal entry of the transfer order. You can also view the ledger transactions that are received during transaction posting on the transfer order by using the <STRONG>Inquiry</STRONG> form.</P>



## See also

[(RUS) Create a partial storno transaction for a transfer order receipt using received quantity return](rus-create-a-partial-storno-transaction-for-a-transfer-order-receipt-using-received-quantity-return.md)

[(RUS) Generate a storno transaction for a transfer order receipt with scrap quantity](rus-generate-a-storno-transaction-for-a-transfer-order-receipt-with-scrap-quantity.md)

[Receive (form)](https://technet.microsoft.com/library/aa552649\(v=ax.60\))

[(RUS) Receive (modified form)](https://technet.microsoft.com/library/jj678418\(v=ax.60\))

[Transfer order history (form)](https://technet.microsoft.com/library/aa575833\(v=ax.60\))

[(RUS) Transfer order history (modified form)](https://technet.microsoft.com/library/jj856120\(v=ax.60\))

[Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\))

  



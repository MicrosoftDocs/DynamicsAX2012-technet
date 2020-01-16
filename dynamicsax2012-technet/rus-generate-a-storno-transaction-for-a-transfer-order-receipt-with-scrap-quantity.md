---
title: (RUS) Generate a storno transaction for a transfer order receipt with scrap quantity
TOCTitle: (RUS) Generate a storno transaction for a transfer order receipt with scrap quantity
ms:assetid: 38bac527-3c16-44ef-aef3-854dccb236a2
ms:mtpsurl: https://technet.microsoft.com/library/JJ665287(v=AX.60)
ms:contentKeyID: 49387376
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- storno
- receipt order
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a storno transaction for a transfer order receipt with scrap quantity 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can write off the scrap quantity of an item when you receive the item after shipment. When you update the item receipt, you can specify the scrap quantity for the received quantity. You can also create a storno transaction to reverse the scrap entry if you find errors after posting.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create and post a transfer order shipment.
    

    > [!NOTE]
    > <P>For more information about transfer orders, see <A href="https://technet.microsoft.com/library/aa634530(v=ax.60)">Transfer orders (form)</A> and <A href="set-up-transfer-order-lines.md">Set up transfer order lines</A>.</P>



3.  Select a posted transfer order that has a transfer status of **Shipped**.

4.  Click **Posting** \> **Receive** to open the **Receive** form. By default, the **Credit correction** check box is selected if you select the **Credit correction in transfer order** check box in the **Inventory and warehouse management parameters** form.

5.  In the **Update** field, select **All** to receive the entire shipped quantity.

6.  Select the **Edit lines** check box. The item lines are displayed in the lower pane.

7.  In the **Scrap quantity** field, enter the quantity of received items to scrap. The quantity should be a positive amount. The modified quantity should not be more than the shipped quantity. If the quantity is a positive amount, credit correction is ignored during posting.

8.  Click **OK** to post the receipt transaction. The following actions occur:
    
      - A voucher number is generated for the receipt transaction.
    
      - The transfer status of the selected transfer order is updated to **Received** in the **Transfer orders** form.
    
      - The **Scrapped quantity** value is updated with the value that is specified in the **Receive** form.

9.  In the **Transfer orders** form, click **Inventory** \> **Transactions** to open the **Inventory transactions** form. You can view the shipment transactions and return transactions for the selected item.

10. For the received transfer order, click **Posting** \> **Receive** to open the **Receive** form.

11. Select the **Credit correction** check box. By default, the **Credit correction** check box is selected if you select the **Credit correction in transfer order** check box in the **Inventory and warehouse management parameters** form.

12. In the **Update** field, select **Received quantity return** to reverse the scrapped quantity.

13. In the **Voucher reference** field, select the voucher number that is generated for the receipt transaction.

14. Select the **Edit lines** check box to verify the received and scrap quantities of the item in the lower pane.

15. Click **OK** to post the storno transaction. The following actions occur:
    
      - A voucher number is generated for the storno transaction.
    
      - The transfer status of the selected transfer order is updated to **Shipped** in the **Transfer orders** form.
    
      - The **Scrapped quantity** value is reversed and updated in the **Transfer orders** form.

## See also

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/library/jj733409\(v=ax.60\))

[Receive (form)](https://technet.microsoft.com/library/aa552649\(v=ax.60\))

[(RUS) Receive (modified form)](https://technet.microsoft.com/library/jj678418\(v=ax.60\))

[Inventory transactions (form)](https://technet.microsoft.com/library/aa584374\(v=ax.60\))

[(RUS) Inventory transactions (modified form)](https://technet.microsoft.com/library/jj733410\(v=ax.60\))

  



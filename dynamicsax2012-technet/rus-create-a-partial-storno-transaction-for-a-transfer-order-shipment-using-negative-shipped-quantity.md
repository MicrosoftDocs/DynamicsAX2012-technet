---
title: (RUS) Create a partial storno transaction for a transfer order shipment using negative shipped quantity
TOCTitle: (RUS) Create a partial storno transaction for a transfer order shipment using negative shipped quantity
ms:assetid: 9f024815-25fc-4f11-afa5-7f071696f179
ms:mtpsurl: https://technet.microsoft.com/library/JJ678536(v=AX.60)
ms:contentKeyID: 49387766
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- storno
- transfer shipment order
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a partial storno transaction for a transfer order shipment using negative shipped quantity 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a partial storno transaction by specifying part of the shipped quantity as a negative value in the **Ship now** field in the **Transfer orders** form.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create and post a transfer order shipment.
    

    > [!NOTE]
    > <P>For more information about transfer order shipments, see <A href="https://technet.microsoft.com/library/aa634530(v=ax.60)">Transfer orders (form)</A> and <A href="set-up-transfer-order-lines.md">Set up transfer order lines</A>.</P>



3.  Select a transfer order that has a transfer status of **Shipped**.

4.  Click the **Ship now** tab, and then, in the **Ship now** field, modify the shipped quantity. The modified quantity should be negative and should not be more than the shipped quantity.

5.  Click **Posting** \> **Ship transfer order** to open the **Shipment** form. By default, the **Credit correction** check box is selected if you select the **Credit correction in transfer order** check box in the **Inventory and warehouse management parameters** form.

6.  On the **Overview** tab, in the **Update** field, select **Ship now** to create a return transaction.
    

    > [!NOTE]
    > <P>The lines in the lower pane are populated with the item number and other inventory details from the referenced transaction. The shipped quantity is changed to a negative value.</P>



7.  Click **OK** to post the shipment transaction. The following actions occur:
    
      - A voucher number is generated for the storno transaction.
    
      - The transfer status of the selected transfer order is updated to **Created** in the **Transfer orders** form.
    
      - The **Ship remain** value for the item is updated with the returned quantity in the **Transfer orders** form.

8.  Click **Inventory management** \> **Inquiries** \> **Transfer orders** \> **Transfer order history**.

9.  In the **Transfer order history** form, view the storno inventory transactions. If the **Credit correction** check box is cleared when you post the transfer order, only the **Goods return** check box is available for the record in the transfer order history.

10. Close the **Transfer order history** form.

11. In the **Transfer orders** form, click **Inventory** \> **Transactions** to open the **Inventory transactions** form. You can view the shipment transactions and return transactions for the selected item.
    

    > [!NOTE]
    > <P>You can generate the Inventory balance turnover report to validate the reversal entry of the transfer order. You can also view the ledger transactions that are received during transaction posting on the transfer order by using the <STRONG>Inquiry</STRONG> form.</P>



## See also

[(RUS) Create a partial storno transaction for a transfer order shipment using shipped quantity return](rus-create-a-partial-storno-transaction-for-a-transfer-order-shipment-using-shipped-quantity-return.md)

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/library/jj733409\(v=ax.60\))

[(RUS) Transfer order shipment (modified form)](https://technet.microsoft.com/library/jj733191\(v=ax.60\))

[Transfer order history (form)](https://technet.microsoft.com/library/aa575833\(v=ax.60\))

[(RUS) Transfer order history (modified form)](https://technet.microsoft.com/library/jj856120\(v=ax.60\))

[Inventory transactions (form)](https://technet.microsoft.com/library/aa584374\(v=ax.60\))

[(RUS) Inventory transactions (modified form)](https://technet.microsoft.com/library/jj733410\(v=ax.60\))

  



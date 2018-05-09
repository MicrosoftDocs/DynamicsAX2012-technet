---
title: (IND) Post received orders for transactions
TOCTitle: (IND) Post received orders for transactions
ms:assetid: 280d1b91-f460-41ab-830a-15753c622c74
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664579(v=AX.60)
ms:contentKeyID: 49385656
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post received orders for transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post transactions for orders that are received from a receiving warehouse in the **Transfer orders** form. For more information, see [(IND) Transfer orders (modified form)](https://technet.microsoft.com/en-us/library/jj677831\(v=ax.60\)).

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  On the **Overview** tab, select the posted shipment order for the stock transfer transaction.

3.  In the lower pane, on the **Lines** tab, in the **Unit price** field, modify the price of the item. If the item is transferred at a price that is higher than the cost price, a message displays indicating that the receipt order unit price is not equal to the dispatch order unit price. Click **OK**.
    

    > [!NOTE]
    > <P>Select the <STRONG>Load on inventory</STRONG> check box in the <STRONG>Item sales tax groups</STRONG> form to allocate the tax amount to the cost of the inventory.</P>



4.  On the **Receive now** tab, in the **Receive now** field, enter the quantity of the items that are received.

5.  Click **Posting** \> **Receive** to open the **Receive** form. For more information, see [(IND) Receive (modified form)](https://technet.microsoft.com/en-us/library/jj664949\(v=ax.60\)).

6.  On the **Overview** tab, select the **Edit lines** check box. The item lines that are updated in the **Receive now** field in the **Transfer orders** form are displayed on the **Lines** tab.

7.  In the **Scrap quantity** field, enter the quantity of the received items that are scrap.

8.  Click **OK** to post the receipt order for the specified quantity of items and return to the **Transfer orders** form.
    

    > [!NOTE]
    > <P>On the <STRONG>Overview</STRONG> tab, in the <STRONG>Transfer status</STRONG> field, the transfer status is changed to <STRONG>Received</STRONG>.</P>



9.  In the **Transfer orders** form, click **Inquiries** \> **Transfer order history** to open the **Transfer order history** form. Click **Ledger** \> **Voucher** to view the voucher entries. The price difference between the cost price and the transfer price of the item, along with the tax amount, is posted to the interim transit account. If ten units are received at the receiving warehouse and five units are considered to be scrap, then the voucher entries for the scrap quantity are posted to the scrap account. If an excise duty of 10 percent is applied to the transaction, then the tax amount on the scrap is posted to the expense with a corresponding liability in the excise duty payable account.

10. Click **Inventory management** \> **Reports** \> **Status** \> **Inventory value** \> **Potential conflicts - inventory and general ledger**. The Potential conflicts – inventory and general ledger report that is generated displays no discrepancy between the physical inventory value and the financial inventory value.

## See also

[(IND) Create and post shipment orders for transactions](ind-create-and-post-shipment-orders-for-transactions.md)

[(IND) Transfer order shipment (modified form)](https://technet.microsoft.com/en-us/library/jj917355\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


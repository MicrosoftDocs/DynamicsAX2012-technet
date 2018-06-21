---
title: (IND) Set up posting profiles for stock transfer
TOCTitle: (IND) Set up posting profiles for stock transfer
ms:assetid: 7d455eef-ce03-46de-8c29-f9ebc97646b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677967(v=AX.60)
ms:contentKeyID: 49385930
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up posting profiles for stock transfer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Posting** form to set up ledger account numbers for the automatic ledger transactions that are generated for receipt transactions and issue transactions in inventory. On the **Transfer order** tab, you can set up the account numbers for posting the items or item groups.


> [!NOTE]
> <P>Before you set up a posting profile for stock transfer transactions, you must select the <STRONG>Activate stock transfer</STRONG> check box in the <STRONG>Inventory and warehouse management parameters</STRONG> form. For more information, see <A href="https://technet.microsoft.com/en-us/library/jj664669(v=ax.60)">(IND) Inventory and warehouse management parameters (modified form)</A>.</P>



1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.

2.  On the **Transfer order** tab, in the **Select** field, set up the posting profile for the items and item groups for stock transfer transactions.
    
      - **Issue** – Post the issue amounts for goods in the supply warehouse.
    
      - **Receipt** – Post the receipt amounts for goods in the receiving warehouse.
    
      - **Unrealized gain** – Post the unrealized profit amounts for stock transfer transactions in the supply warehouse and the receiving warehouse. If the transfer price of the goods that are involved in a stock transfer operation is more than the cost price, the difference between the transfer price and the cost price is considered unrealized profit for the supply warehouse and unrealized loss for the receiving warehouse. The unrealized profit account is credited to the supply warehouse and debited from the receiving warehouse.
    
      - **Unrealized loss** – Post the unrealized loss amounts for stock transfer transactions in the supply warehouse and the receiving warehouse. If the transfer price of the goods that are involved in a stock transfer operation is less than the cost price, the difference between the transfer price and the cost price is considered unrealized loss for the supply warehouse and unrealized profit for the receiving warehouse. The unrealized loss account is debited from the supply warehouse and credited to the receiving warehouse.
    
      - **Goods in transit** – Post the offset entries for stock transfer transactions. When a stock transfer order is posted for the shipment or receipt of goods, the corresponding debit amount or credit amount is posted to the offset account, based on the cost price.
    
      - **Scrap** – Post the details of scrap that is generated in stock transfer transactions on the basis of cost price.
    
      - **Interim Transit** – Post the difference in value between the cost price and the transfer order price of goods that are in transit. Taxes are also posted to this account.

3.  Click **Add** or press CTRL+N to create a new line.

4.  In the **Item code** field, select one of the following options to set up the posting accounts group for the transaction type that is selected in the **Select** field.
    
      - **Table** – Set up a posting account for a specific item.
    
      - **Group** – Set up a posting account for a specific item group.
    
      - **All** – Set up a posting account for all items.

5.  In the **Item relation** field, select a specific item or item group to define the posting account for.
    

    > [!NOTE]
    > <P>If you selected <STRONG>All</STRONG> in the <STRONG>Item code</STRONG> field, you cannot select or enter any value in the <STRONG>Item relation</STRONG> field.</P>



6.  In the **Main account** field, select the ledger account to use to post the transaction type for the item.

## See also

[(IND) Purchase posting (modified form)](https://technet.microsoft.com/en-us/library/jj664475\(v=ax.60\))

[(IND) Posting (modified form)](https://technet.microsoft.com/en-us/library/jj664940\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


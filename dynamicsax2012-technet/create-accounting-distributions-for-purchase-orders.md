---
title: Create accounting distributions for purchase orders
TOCTitle: Create accounting distributions for purchase orders
ms:assetid: bfbf2a3f-9956-4b96-9fe5-323da44dd673
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242825(v=AX.60)
ms:contentKeyID: 36059259
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounting distributions
- create accounting distributions
- create distributions
- distributions
audience: Application User
ms.search.region: Global
---

# Create accounting distributions for purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Accounting distributions** form to create and modify distribution lines for purchase orders. For more information about distributions, see [About accounting distributions and subledger journal entries for purchase orders](about-accounting-distributions-and-subledger-journal-entries-for-purchase-orders.md).

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the purchase order that contains the line to create a distribution for.

3.  To distribute header amounts, on the **Action Pane**, click the **Purchase** tab. In the **Accounting** group, click **Distribute amounts**. Skip to step 5.

4.  To distribute line amounts, select the purchase order line to create a distribution for. In the **Purchase order lines** grid, click **Financials** \> **Distribute amounts**.

5.  In the **Accounting distributions** form, in the **Distributed by** field, select whether to distribute amounts by percentage, amount, or quantity.

6.  You can create distributions in the following ways:
    
      - To create multiple distributions that have the same quantity, percentage, or amount distribution, click **Split** for each distribution to create, select a ledger account for each distribution, and then click **Distribute equally**.
    
      - To create distributions one at a time, click **Split**. Select the ledger account to distribute the purchase order line to and then enter the quantity, percentage, or amount to distribute. For example, if you selected **Quantity** in the **Distributed by** field, enter an amount in the **Quantity** field.
        
        Repeat until you are finished creating distributions.

  



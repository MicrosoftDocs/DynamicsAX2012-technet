---
title: (RUS) Set up credit correction for transfer orders
TOCTitle: (RUS) Set up credit correction for transfer orders
ms:assetid: 780c6785-8eb2-4160-aa1d-4c86aa4134ab
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678378(v=AX.60)
ms:contentKeyID: 49387608
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- storno
- transfer order
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up credit correction for transfer orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To create storno transactions for transfer orders, you must enable credit correction.

You can use the **Inventory and warehouse management parameters** form to activate storno transactions in transfer orders.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  Select the **Credit correction in transfer order** check box to enable credit correction in transfer orders by default.
    

    > [!NOTE]
    > <P>If the <STRONG>Ship now</STRONG> and <STRONG>Receive now</STRONG> quantities on the transfer order lines are negative, and the <STRONG>Credit correction in transfer order</STRONG> check box is selected, the storno inventory transactions and ledger transactions are generated when transfer orders are posted. If the <STRONG>Ship now</STRONG> and <STRONG>Receive now</STRONG> quantities on the transfer order lines are negative, and the <STRONG>Credit correction in transfer order</STRONG> check box is cleared, the inventory return transactions and reverse ledger transactions are generated when transfer orders are posted. When the quantity in the <STRONG>Ship now</STRONG> or <STRONG>Receive now</STRONG> field of the <STRONG>Transfer orders</STRONG> form is positive, credit correction is ignored during posting.</P>



## See also

[(RUS) Inventory and warehouse management parameters (modified form)](https://technet.microsoft.com/en-us/library/jj733200\(v=ax.60\))

[Transfer orders (form)](https://technet.microsoft.com/en-us/library/aa634530\(v=ax.60\))

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/en-us/library/jj733409\(v=ax.60\))

  



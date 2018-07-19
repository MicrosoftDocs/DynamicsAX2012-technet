---
title: (RUS) Set up production control parameters for by-products accounting
TOCTitle: (RUS) Set up production control parameters for by-products accounting
ms:assetid: bb4936bf-5aca-46d5-87ce-691dfe731b78
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711548(v=AX.60)
ms:contentKeyID: 49387873
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up production control parameters for by-products accounting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Production control parameters** form to set up the methods that are used to calculate the cost of a production order. You also select the by-product journal that is used to register by-products and defective products. You can use normative or proportional methods to calculate the costs of work in process (WIP), defective products, and finished goods. For more information, see [(RUS) Calculate the cost of WIP and finished goods](rus-calculate-the-cost-of-wip-and-finished-goods.md).

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  In the left pane, click **General**.

3.  In the **General** area, select the **Do not post route transactions to GL** check box to indicate that transactions for route cards and job cards are not posted to the general ledger account.

4.  Select the **Do not post indirect costs** check box to indicate that indirect costs are not posted to the general ledger account.

5.  Select the **Use by-product journal** check box to use a by-product journal in production orders.
    

    > [!NOTE]
    > <P>This check box is available only when you select the <STRONG>Extended costing</STRONG> check box in the <STRONG>Standard update</STRONG> area.</P>



6.  Select the **Do not post by-product journal in ledger** check box to indicate that the posting of the by-product journal does not affect the ledger.

7.  In the left pane, click **Journals**.

8.  In the **Journals** area, in the **By-product** field, select the name of the by-product journal.

9.  In the left pane, click **Standard update**.

10. In the **Standard update** area, select the **Extended costing** check box to calculate the cost of by-products, defective products, WIP, and finished goods.

11. In the **Costing method** field, select the method that is used to calculate cost. The following options are available:
    
      - **Normative** – The costs of WIP and defective products are calculated based on normative costs, and the remaining costs are calculated based on actual costs.
    
      - **Proportional** – The actual costs are distributed by quantity between WIP, by-products, defective products, and finished goods.

## See also

[(RUS) Production control parameters (modified form)](https://technet.microsoft.com/en-us/library/jj678589\(v=ax.60\))

  



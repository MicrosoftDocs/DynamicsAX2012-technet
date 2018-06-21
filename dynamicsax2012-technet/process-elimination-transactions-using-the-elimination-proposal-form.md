---
title: Process elimination transactions using the Elimination proposal form
TOCTitle: Process elimination transactions using the Elimination proposal form
ms:assetid: 6141747b-d279-459e-a82f-6d9abe0681c1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231519(v=AX.60)
ms:contentKeyID: 36057648
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- proposal
- elimination
- elimination transactions
- elimination proposal
---

# Process elimination transactions using the Elimination proposal form [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Elimination proposal** form to process elimination transactions for elimination legal entities and consolidation legal entities.

You must create an elimination rule before you create elimination transactions. For more information, see [Set up elimination rules for transactions](set-up-elimination-rules-for-transactions.md).

## For elimination legal entities

1.  In the elimination legal entity, create a journal name in the **Journal names** form. (Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.)

2.  In the consolidation legal entity, create an elimination rule with the elimination legal entity as the destination legal entity. Define lines for the accounts for which transactions must be eliminated.

3.  Consolidate all subsidiary transactions into the eliminations legal entity using the **Consolidate** **\[** **Online** **\]** form. (Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Online\]**.)

4.  Process the elimination rule in the elimination legal entity using the **Elimination proposal** form. (Click **General ledger** \> **Journals** \> **Elimination**. Select a journal and then click **Lines**. Click **Proposals** \> **Elimination proposal**.)

5.  Post the eliminations journals in the **Post journals** form. (Click **General ledger** \> **Periodic** \> **Journals** \> **Post journals**.)

6.  If the elimination legal entity is not the same legal entity as the consolidation legal entity, use the **Consolidate** **\[** **Online** **\]** form in the consolidation legal entity to move the transactions from the elimination legal entity to the consolidation legal entity.

7.  Print the consolidated financial statements. For more information, see [About traditional financial statements](about-traditional-financial-statements.md).


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
> <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>



## For consolidation legal entities

1.  In the elimination legal entity, create a journal name in the **Journal names** form. (Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.)

2.  In the consolidation legal entity, create an elimination rule with the consolidation legal entity as the destination legal entity. Define lines for the accounts for which transactions must be eliminated.

3.  Consolidate all subsidiary transactions into the consolidation legal entity using the **Consolidate** **\[** **Online** **\]** form. (Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Online\]**.)

4.  Process the elimination rule in the elimination legal entity using the **Elimination proposal** form. (Click **General ledger** \> **Journals** \> **Elimination**.)

5.  Post the eliminations journals in the **Post journals** form. (Click **General ledger** \> **Periodic** \> **Journals** \> **Post journals**.)

6.  Print the consolidated financial statements. For more information, see [About traditional financial statements](about-traditional-financial-statements.md).

## See also

[Elimination proposal (form)](https://technet.microsoft.com/en-us/library/hh227620\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


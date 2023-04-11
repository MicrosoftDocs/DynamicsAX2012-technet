---
title: Process elimination transactions using the Consolidation, Online form
TOCTitle: Process elimination transactions using the Consolidation, Online form
ms:assetid: 69a51a3c-0a21-4a0a-b750-42672ebfea67
ms:mtpsurl: https://technet.microsoft.com/library/Gg231580(v=AX.60)
ms:contentKeyID: 36057972
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- online
- elimination
- elimination transactions
- consolidation
- consolidation transactions
- online consolidation
audience: Application User
ms.search.region: Global
---

# Process elimination transactions using the Consolidation, Online form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Consolidate** **\[** **Online** **\]** form to process elimination transactions for consolidation legal entities, if you prefer to complete the consolidations at one time and validate the information before processing eliminations.

If there are previous consolidation transactions for the legal entity, date range, and account range, the transactions will be removed and consolidated again.

You must create an elimination rule before you create elimination transactions. For more information, see [Set up elimination rules for transactions](set-up-elimination-rules-for-transactions.md).

1.  In the consolidation legal entity, create a journal name with an **Elimination** journal type in the **Journal names** form. (Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.)

2.  In the consolidation legal entity, create an elimination rule with the consolidation legal entity as the destination legal entity. Define lines for the accounts for which transactions must be eliminated.

3.  Consolidate transactions from the subsidiary legal entity into the consolidation legal entity using the **Consolidate** **\[** **Online** **\]** form. (Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Online\]**.)
    
    The selections in this form determine how the eliminations journal is posted:
    
      - If you select **Post only** in the **Proposal options** field, the eliminations journal will be posted when you click **OK** in the **Consolidate** **\[** **Online** **\]** form.
    
      - If you select **Proposal only** in the **Proposal options** field, you must post the eliminations journals in the **Post journals** form. (Click **General ledger** \> **Periodic** \> **Journals** \> **Post journals**.)
    

    > [!NOTE]
    > <P>If the destination legal entity for the elimination rule is not the same legal entity as the consolidation legal entity, you must post the elimination journal in the elimination legal entity, and then complete another consolidation for the elimination legal entity.</P>



4.  Print the consolidated financial statements. For more information, see [About traditional financial statements](about-traditional-financial-statements.md).
    

    > [!NOTE]
    > <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
    > <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>



## See also

[Consolidate (form)](https://technet.microsoft.com/library/aa618539\(v=ax.60\))

  



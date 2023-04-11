---
title: (BRA) Transfer subsidiary legal entity transactions to a consolidated legal entity
TOCTitle: (BRA) Transfer subsidiary legal entity transactions to a consolidated legal entity
ms:assetid: 8d0c6d63-d560-40b1-8370-4ec8174f3c74
ms:mtpsurl: https://technet.microsoft.com/library/JJ710563(v=AX.60)
ms:contentKeyID: 49384453
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- company account
- BRA
- Brazil
- consolidated company account
- company transactions
- subsidiary company transactions
- transfer subsidiary company transactions
audience: Application User
ms.search.region: Brazil
---

# (BRA) Transfer subsidiary legal entity transactions to a consolidated legal entity 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up a consolidated legal entity, you can use the **Consolidate** form to transfer all of the transactions in a selected period from subsidiary legal entities to the consolidated legal entity. The consolidated legal entity and the subsidiary legal entities must use the same currency. Before you transfer transactions, you must select the **Use for financial consolidation process** check box on the **General** FastTab in the **Legal entities** form.

1.  Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Online\]**.

2.  Select the **Transfer transactions only** check box to indicate that only transactions are transferred and consolidated. The transaction amounts are not consolidated.

3.  In the **From:** and **To:** fields in the **Consolidation period** field group, enter the starting and ending dates of the period for the transactions to include in the consolidation.

4.  Select the **Include actual amounts** check box to include general ledger journal entries when you transfer transactions.
    

    > [!NOTE]
    > <P>To transfer the budget details, select the <STRONG>Include budget amounts</STRONG> check box, and then in the <STRONG>From:</STRONG> and <STRONG>To:</STRONG> fields in the <STRONG>Budget models</STRONG> field group, select the budget models. The budget model must be the same for the consolidated and subsidiary legal entities.</P>



5.  Click the **Financial dimensions** tab, and then in the **Specification** field, select the type of data that is transferred to the **Financial dimension** field of the consolidated legal entity. For example, if you select **Company accounts** in the **Specification** field for the consolidated legal entity, you can identify the subsidiary origin of each transaction in the consolidated legal entity. The other dimension information is not transferred. For more information, see [Consolidate (form)](https://technet.microsoft.com/library/aa618539\(v=ax.60\)).

6.  In the **Segment order** field, enter a number to indicate the order of financial dimensions in the consolidated legal entity. Enter 0 for the dimensions that have a specification of **None**.
    

    > [!NOTE]
    > <P>The segment order number must be sequential for all fields for which the specification is not <STRONG>None</STRONG>.</P>



7.  Click the **Legal entities** tab, and then select a subsidiary legal entity, or click **New** to add the subsidiary legal entity to consolidate transactions for. You can add multiple subsidiary legal entities for consolidation.

8.  Click **OK** to transfer the transactions.

After you transfer the subsidiary legal entity transactions to a consolidated legal entity, you can view the transactions that are transferred in the **Voucher transactions** form. For more information, see [Voucher transactions (form)](https://technet.microsoft.com/library/aa583215\(v=ax.60\)). You can also generate the following reports:

  - **Financial statement** – Generate the financial statement report to analyze transactions in a subsidiary legal entity by using one or more dimensions of the consolidated account. For more information, see [Financial statement report (form)](https://technet.microsoft.com/library/aa585230\(v=ax.60\)) and [Generate, print, and export a traditional financial statement](generate-print-and-export-a-traditional-financial-statement.md).

  - **Analytical ledger** – Generate an analytical ledger report that contains the original legal entity and voucher transactions from the consolidated legal entity. For more information, see [(BRA) Analytical ledger report (LedgerJournalAnalytReasonReport\_BR)](https://technet.microsoft.com/library/jj710455\(v=ax.60\)).

  - **Day book** – Generate a day book report that contains the daily transactions, sorted by date, for a specified period. For more information, see [(BRA) Day book report (LedgerJournalDayBookReport\_BR)](https://technet.microsoft.com/library/jj710413\(v=ax.60\)).

## See also

[(BRA) Verify subsidiary legal entity transactions](bra-verify-subsidiary-legal-entity-transactions.md)

[(BRA) Export and import legal entity transactions](bra-export-and-import-legal-entity-transactions.md)

  



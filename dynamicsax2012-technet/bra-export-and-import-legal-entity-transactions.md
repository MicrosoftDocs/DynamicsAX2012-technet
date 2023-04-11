---
title: (BRA) Export and import legal entity transactions
TOCTitle: (BRA) Export and import legal entity transactions
ms:assetid: f30c7592-8a49-4bd9-8bd8-85f3acfc05ec
ms:mtpsurl: https://technet.microsoft.com/library/JJ663968(v=AX.60)
ms:contentKeyID: 49384553
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- company transactions
- export and import
audience: Application User
ms.search.region: Brazil
---

# (BRA) Export and import legal entity transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can export transactions of a subsidiary legal entity to a .txt file and import transactions of a consolidated legal entity to subsidiary legal entities. A consolidated legal entity can contain multiple subsidiary legal entities with different file names for each subsidiary legal entity. The consolidated legal entity and the subsidiary legal entities must use the same currency. Before you import transactions, you must select the **Use for financial consolidation process** check box on the **General** FastTab in the **Legal entities** form. You can also set up the export and import process to run periodically by clicking the **Batch** button.

## Export general ledger transactions to a .txt file

1.  Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Export to\]**.

2.  Select the **Transfer transactions only** check box to indicate that only transactions in the selected period are transferred and consolidated. The transaction amounts are not consolidated.

3.  In the **From:** and **To:** fields in the **Consolidation period** field group, enter the starting and ending dates of the period for the transactions to include in the consolidation.

4.  Select the **Include actual amounts** check box to include general ledger journal entries when transferring transactions.
    

    > [!NOTE]
    > <P>To transfer the budget details, select the <STRONG>Include budget amounts</STRONG> check box, and then in the <STRONG>From:</STRONG> and <STRONG>To:</STRONG> fields in the <STRONG>Budget models</STRONG> field group, select the budget models. The budget model must be the same for the consolidated and subsidiary legal entities.</P>



5.  Click the **Financial dimensions** tab, and then in the **Specification** field, select the type of data that is transferred to the **Financial dimension** field of the consolidated legal entity when the subsidiary legal entity transactions are transferred.
    
    For example, if you select **Company accounts** as a financial dimension for the consolidated legal entity, you can identify the subsidiary origin of each transaction in the consolidated legal entity. However, the other dimension information is not transferred. For more information, see [Consolidate (form)](https://technet.microsoft.com/library/aa618539\(v=ax.60\)).

6.  In the **Segment order** field, enter a number to indicate the order of dimensions in the consolidated legal entity. Enter **0** for the dimensions that have a specification of **None**.
    

    > [!NOTE]
    > <P>The segment order number must be sequential for all fields that do not have a <STRONG>None</STRONG> specification.</P>



7.  Click the **Legal entities** tab, and then select a subsidiary legal entity, or click **New** to add the subsidiary legal entity to export transactions for. You can add multiple subsidiary legal entities to export.

8.  In the **File name** field, enter the path and file name, including the .txt extension, where the transactions are saved.

9.  Click **OK** to export the transactions.

## Import general ledger transactions from a .txt file

1.  Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Import from\]**.

2.  Select the **Include actual amounts** check box to include general ledger journal entries when you import transactions.
    

    > [!NOTE]
    > <P>To transfer the budget details, select the <STRONG>Include budget amounts</STRONG> check box, and then in the <STRONG>From:</STRONG> and <STRONG>To:</STRONG> fields, select the budget models. The budget model must be the same for the consolidated and subsidiary legal entities.</P>



3.  Click the **Legal entities** tab, and then select a subsidiary legal entity or click **New** to add the subsidiary legal entity to consolidate transactions for. You can add multiple subsidiary legal entities for consolidation.

4.  In the **File name** field, select the path and file name where the transactions are imported from.

5.  Click **OK** to import the transactions.

## See also

[(BRA) Consolidate (modified form)](https://technet.microsoft.com/library/jj710487\(v=ax.60\))

[(BRA) Updates to consolidated legal entity transactions](bra-updates-to-consolidated-legal-entity-transactions.md)

  



---
title: Enable interunit accounting
TOCTitle: Enable interunit accounting
ms:assetid: 3f564ba6-4509-4fa1-898f-875591af9fe5
ms:mtpsurl: https://technet.microsoft.com/library/JJ729752(v=AX.60)
ms:contentKeyID: 49564918
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Enable interunit accounting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Interunit accounting is the requirement that you generate a balanced balance sheet for a specific financial dimension. Therefore, all accounting entries that are made to General ledger must be balanced for the values of the financial dimension. This financial dimension is referred to as the balancing financial dimension.

The balancing financial dimension that is used for interunit accounting is selected in the **Ledger** form. When you enter that financial dimension in the system, every accounting entry must balance both at the total level and at the level of the financial dimension values. If the accounting entry does not balance at the level of the financial dimension values, additional account entries are created automatically to balance the accounting entry.

For more information, see [Example: Balanced accounting entry for interunit accounting](example-balanced-accounting-entry-for-interunit-accounting.md).

## Set up accounts for automatic transactions for interunit accounting

Use the **Accounts for automatic transactions** form to specify accounts that are not set up elsewhere for automatic transactions. If these accounts are not set up, posting is stopped.

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Accounts for automatic transactions**.

2.  Click **New**. In the **Posting type** field, select **Interunit - debit**.

3.  Enter the main account where transactions that have the **Interunit - debit** posting type are posted.

4.  Click **New**. In the **Posting type** field, select **Interunit - credit**.

5.  Enter the main account where transactions that have the **Interunit - credit** posting type are posted.

## Select the balancing financial dimension for interunit accounting

Use the **Ledger** form to select the balancing financial dimension, which is the financial dimension that must be balanced for interunit accounting. Before you select the balancing financial dimension, you must verify that the balance sheet is already balanced for the financial dimension values. When you select a balancing financial dimension, the existing transactions might not already be balanced. If the transactions are not balanced, you must create adjusting journal entries to balance the balance sheet.

When you select a balancing financial dimension, all new accounting entries must be balanced for each value of this financial dimension. Automatic transactions are created to balance the entries. These transactions use the main accounts that are identified in the **Accounts for automatic transactions** form.

1.  Click **General ledger** \> **Setup** \> **Ledger**.

2.  In the **Balancing financial dimension** field, select the financial dimension that must be balanced in all accounting entries that contain the financial dimension.
    

    > [!NOTE]
    > <P>You must select a financial dimension that is included in all account structures that are assigned to the ledger. Additionally, the balancing financial dimension must not allow for blank spaces as dimension values.</P>


  



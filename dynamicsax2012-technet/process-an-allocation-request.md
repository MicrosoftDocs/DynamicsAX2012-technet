---
title: Process an allocation request
TOCTitle: Process an allocation request
ms:assetid: db873fae-db65-4c42-b6f4-4b2c7c0723bc
ms:mtpsurl: https://technet.microsoft.com/library/Ff395362(v=AX.60)
ms:contentKeyID: 36059667
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Process an allocation request 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Process allocation request** form to process an allocation rule and create an allocation journal. You can create a journal to group a chronological list of transactions, in the form of debits and credits, for a particular account or group of accounts.

Before you can process an allocation rule and create an allocations journal, you must create the allocation rule using the **Ledger allocation rule** form. For more information, see [Create an allocation rule](create-an-allocation-rule.md).

With allocation journals selected for budget control and with budget control turned on, any journal entry that exceeds the available budget will prevent the allocation request from being posted to the ledger. The allocation journal will still be generated and the voucher lines will show the budget check failures so that you can make any necessary adjustments. For more information, see [About budget control](about-budget-control.md).

1.  Click **General ledger** \> **Periodic** \> **Process allocation request**.

2.  Select an allocation rule for processing.

3.  Select the date from which to use ledger amounts for allocating.

4.  Select the date to post the allocation to the general ledger.

5.  In the **Zero source** field, select the action to occur when the allocation process produces a zero amount to be allocated.
    
      - Select **Process** to continue with the allocation process and create destination distributions, where applicable.
    
      - Select **Stop** to stop the allocation process and display a message that states that a zero source amount is selected.

6.  Select a proposal option to save journal details or to post the allocation results to the ledger.
    
      - Select **Proposal only** to save journal details. You can view the allocation journal before you post in the **Journal** form. (Click **General ledger** \> **Journals** \> **Allocation**.)
    
      - Select **Post only** to post the allocation results to the ledger.

7.  Click **OK** to create an allocation journal.

## See also

[About allocation rules](about-allocation-rules.md)

[Process allocation request (form)](https://technet.microsoft.com/library/ff395361\(v=ax.60\))

  



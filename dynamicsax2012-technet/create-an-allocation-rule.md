---
title: Create an allocation rule
TOCTitle: Create an allocation rule
ms:assetid: 96b6dbbf-d3a9-4bea-a549-7b625a6dc247
ms:mtpsurl: https://technet.microsoft.com/library/Ff395359(v=AX.60)
ms:contentKeyID: 36058639
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- allocation rule
- create allocation rule
audience: Application User
ms.search.region: Global
---

# Create an allocation rule 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to set up ledger allocation rules. Allocation is the distribution of amounts to one or more accounts or account and dimension combinations.

Use the **Ledger allocation rule** form to set up an allocation rule that you can use to define the rules and methods by which ledger balances are to be allocated. For example, you can set up an allocation rule to divide corporate advertising costs based on each department's sales in proportion to total departmental sales.

Starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can also use ledger allocation rules for budget plans. For more information about how to work with budget plans, see [Set up budget allocation terms](set-up-budget-allocation-terms.md).

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Ledger allocation rule**.

2.  Enter a unique ID for the allocation rule.

3.  Select the effective starting and ending dates for the rule.

4.  Select the **Active** check box to make the allocation rule active and available for processing.

5.  Click the **General** tab to enter additional information for the rule.

6.  You can select the **Intercompany rule** check box to use the rule to process allocations across multiple legal entities.

7.  Select the allocation method to use for the rule. For more information, see [About allocation rules](about-allocation-rules.md).

8.  Select the data source.
    
      - If you select **Fixed value**, enter the fixed value amount to allocate.
    
      - If you select **Ledger**, you can select a mathematical operation to process on the source value. Enter an amount if you select **Multiply** or **Divide**.

9.  Select the date interval code to determine the fiscal periods for the allocation rule source.

10. Select the allocation journal name.

11. If you selected **Distribute the source document amount equally** as the allocation method, you can select to use either the source destination account and dimension, a user-specified destination account and dimension, or a combination.

12. Click the **Offset** tab to enter offset accounts and dimensions to balance the destination distribution lines.

13. Select the origin of the offset account.
    
      - If you select **User specified**, select an offset account to use instead of the source account.
    
      - If you select **Source**, the respective account that is defined in the source is used during the allocation process.

14. Select the dimension to associate to the allocation rule.
    
      - If you select **Source** in the **Offset dimension from** field, the respective dimension that is defined when you click **Source** is used during the allocation process.
    
      - If you select **User specified**, select a dimension to use instead of the source dimension.

15. To create ledger allocation rule source information, click the **Source** button. To create ledger allocation rule destination information, click the **Destination** button.
    
    For more information, see [Create allocation rule source and destination information](create-allocation-rule-source-and-destination-information.md).

## See also

[Ledger allocation rule source (form)](https://technet.microsoft.com/library/ff395365\(v=ax.60\))

[Ledger allocation rule destination (form)](https://technet.microsoft.com/library/ff395369\(v=ax.60\))

[Date intervals (form)](https://technet.microsoft.com/library/aa558459\(v=ax.60\))

  



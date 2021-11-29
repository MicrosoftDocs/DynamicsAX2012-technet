---
title: About prerequisites for a standard cost conversion
TOCTitle: About prerequisites for a standard cost conversion
ms:assetid: ed2c01b0-3cab-40bc-b750-caf90a7b10ee
ms:mtpsurl: https://technet.microsoft.com/library/Gg243259(v=AX.60)
ms:contentKeyID: 36059902
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About prerequisites for a standard cost conversion 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic discusses tasks to perform before you run a standard cost conversion.

Before you run a standard cost conversion, follow these steps.

1.  Define an item model group for standard costs.
    
    Use the **Item model groups** form to create an item model group that uses a standard cost inventory model. When setting up a standard cost conversion, you assign this item model group to the items that are being converted.

2.  Assign a cost group to each item.
    
    1.  The cost group that is assigned to a purchased item can act as the basis for assigning ledger accounts that are related to standard costs. This can include assigning ledger accounts for purchase price variances. In a manufacturing environment, the cost group that is assigned to purchased components also provides cost segmentation in the calculated costs of a manufactured item.
    
    2.  The cost group that is assigned to a manufactured item can act as the basis for assigning ledger accounts that are related to standard costs, such as assigning ledger accounts for production variances.

3.  Assign a standard order quantity to a manufactured item when it has constant costs.
    
    The standard order quantity for a manufactured item acts as an accounting lot size for amortizing, or prorating, constant costs. These can include setup times in routing operations or a constant component quantity in a bill of material (BOM).

4.  Assign general ledger accounts that are related to standard costs, especially the revaluation variance.
    
    Use the **Posting** form to assign general ledger accounts that are related to standard costs. As a minimum for the standard cost conversion process, you must assign the account for the revaluation variance for all items and all cost groups.
    
    Use the **Chart of accounts** form to define the general ledger accounts that will be needed for standard costs.
    
    Use the **Transaction combinations** form to enable cost relations (for tables, groups, and all) before you define the item posting rules.

5.  Define the inventory parameters that are related to standard costs.
    
    Use the **Number sequences** tab on the **Inventory parameters** form to assign a number sequence to revaluation vouchers. A revaluation voucher is generated when the standard cost conversion creates a change of an item's inventory value.
    
    Use the **Inventory parameters** form to define cost control parameters (on the **Bills of materials** tab) to define two parameters that are related to standard costs.
    
      - Use the **Cost breakdown** field to select **No** or **Sub ledger**. The selection of **Sub ledger** is termed an active cost breakdown. An active cost breakdown is very important for calculating, retaining, and viewing cost group segmentation across a multilevel product structure for standard cost items.
        
        When the cost breakdown is active, you can report and analyze the following in a single level, multi-level, or total format:
        
        1.  Inventory
        
        2.  Work in process (WIP)
        
        3.  Cost of goods sold (COGS) per cost group
        
        An active cost breakdown means that if you enable a manufactured item's cost, the result will be stored in the cost group segmentation in the item's cost record.
        
        If you put no value in the **Cost breakdown** field, the cost group segmentation will not be maintained for standard cost items. That is, a manufactured item's standard cost will be calculated and maintained as a single amount without cost group segmentation, and the cost contributions of manufactured components will be aggregated into the single amount.
    
      - Use the **Variances to standard** field to select summarized or per cost group. The selection of per cost group enables you to identify purchase price variances and production variances by cost group. This also enables you to identify the four types of production variances (the lot size, quantity, price, and substitution variances). If you select summarized, you cannot identify variances by cost group, and you cannot identify the four types of production variances. You can only view a summarized production variance.
        
        The policy about variance to standard is independent of the cost breakdown policy. That is, you can select a cost breakdown policy of none, and select variances per cost group, so that production variances by cost group will still be captured.

## See also

[Standard cost conversion (form)](https://technet.microsoft.com/library/hh208816\(v=ax.60\))

[About standard cost conversion](about-standard-cost-conversion.md)

[Set up and run a standard cost conversion](set-up-and-run-a-standard-cost-conversion.md)

  



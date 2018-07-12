---
title: Prerequisites for standard costs
TOCTitle: Prerequisites for standard costs
ms:assetid: 32d2dae5-53a6-4572-8d67-301680c12eb1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231038(v=AX.60)
ms:contentKeyID: 36056537
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- costs
- costing
- standard cost
- standard costs
audience: Application User
ms.search.region: Global
---

# Prerequisites for standard costs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic covers the basic steps for using standard costs. Subsequent steps depend on the company’s operations, such as a nonmanufacturing environment, a manufacturing environment without routings, and a manufacturing environment with routings.

To set up standard costs, follow these steps:

1.  Create an item model group for standard costs.
    
    Use the **Item model groups** form to create a new group for standard costs and to assign an inventory model of **Standard cost**. The identifier for the item model group should be meaningful, such as Std Cost. Select the check boxes to indicate that the group should allow financial negative inventory, post physical inventory, and post financial inventory. This standard cost group will be assigned to items.

2.  Define ledger accounts that are related to standard cost variances.
    
    Use the **Chart of accounts** form to define ledger accounts that are related to standard cost variances. These ledger accounts must be defined before they can be assigned in the **Posting** form. The ledger accounts can reflect item groups and cost groups.

3.  Assign ledger accounts to item postings that are related to standard cost variances.
    
    Use the **Posting** form to assign the ledger accounts that are related to standard cost variances. You can choose whether to specify a variance’s ledger account by item (or item group) and by cost group (or cost group type), or to specify that the ledger account applies to all items and all cost groups. These choices correspond to cost relations for tables, groups, and all.
    
    Use the **Transaction combinations** form to enable the use of cost relations (for tables, groups, and all) before you define the item posting rules.

4.  Define inventory parameters that are related to standard costs.
    
    Use the **Inventory parameters** form to define cost control parameters (on the **Bills of materials** tab) to define two parameters that are related to standard costs.
    
      - Use the **Cost breakdown** field to select **No** or **Sub ledger**. The selection of **Sub ledger** is termed an active cost breakdown. An active cost breakdown is critical for calculating, retaining and viewing cost group segmentation across a multilevel product structure for standard cost items. When the cost breakdown is active, you can report and analyze inventory, work in process (WIP), and cost of goods sold (COGS) per cost group in a single level, multilevel or total format. An active cost breakdown means that activating a manufactured item’s cost will result in storing the cost group segmentation within the item’s cost record.
        
        The selection of none for the **Cost breakdown** field means that cost group segmentation will not be maintained for standard cost items. That is, a manufactured item's standard cost will be calculated and maintained as a single amount without cost group segmentation, and the cost contributions of manufactured components will be aggregated into the single amount.
    
      - Use the **Variances to standard** field to select summarized or per cost group. The selection of per cost group enables you to identify purchase price variances and production variances by cost group, and also identify the four types of production variances: the lot size, quantity, price and substitution variances. The selection of summarized means that you cannot identify variances by cost group, and you cannot identify the four types of production variances. You can only view a summarized production variance.
        
        The policy about variance to standard works independently of the cost breakdown policy. That is, you can select a cost breakdown policy of none, and select variances per cost group, so that production variances by cost group will still be captured.

5.  Create costing versions for standard costs.
    
    Use the **Costing version setup** form to create one or more costing versions for standard costs. Each costing version must be designated with a costing type of standard costs and allow content to include cost data.

6.  Prepare an existing Microsoft Dynamics AX customer to use standard costs.
    
    Customers who want to change their existing items to a standard cost inventory model must use the **Standard cost conversions** form.

## See also

[Maintaining standard costs in a nonmanufacturing environment](maintaining-standard-costs-in-a-nonmanufacturing-environment.md)

[Preparing to maintain standard costs in a manufacturing environment with routings](preparing-to-maintain-standard-costs-in-a-manufacturing-environment-with-routings.md)

[Preparing to maintain standard costs in a manufacturing environment](preparing-to-maintain-standard-costs-in-a-manufacturing-environment.md)

[Calculating standard costs for manufactured items](calculating-standard-costs-for-manufactured-items.md)

[Maintaining standard costs in a manufacturing environment](maintaining-standard-costs-in-a-manufacturing-environment.md)

[About costing versions](about-costing-versions.md)

  



---
title: Set up initial standard costs in a manufacturing environment
TOCTitle: Set up initial standard costs in a manufacturing environment
ms:assetid: dd1e620c-6ad6-47da-8907-f7c29dc547d5
ms:mtpsurl: https://technet.microsoft.com/library/Gg243197(v=AX.60)
ms:contentKeyID: 36059680
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up initial standard costs in a manufacturing environment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Manufacturing environments involve maintaining standard costs for purchased items and manufactured items, which includes the first time setting standard costs. Additional steps are required in manufacturing environments that use routing information for costing purposes. These guidelines assume the use of a single costing version when you set standard costs for the first time. This costing version will contain standard costs for the current period. Pending cost records for all items will be entered in this costing version.

1.  Define the costing version by using the **Costing versions** form. Guidelines for this costing version include the following:
    
      - Assign a costing type of standard costs.
    
      - Assign a meaningful identifier for the costing version, such as 2008-STANDARD.
    
      - Ensure that the content includes cost records.
    
      - Allow the entry of cost records. Do not block the entry of pending costs.
    
      - Allow the entry of cost records for all sites. Assigning a site will limit the entry of cost records to the specified site.
    
      - Prevent the change to active status. The change to active status will be enabled after pending costs have been accurately defined.
    
      - Optionally enter a from-date. As a general guideline, use a future date that represents the planned cutover date or the first day in the frozen period when you prepare cost data beforehand.
    
      - Indicate a fallback principle of none.

2.  Use the **Price** form to enter item cost records for purchased items in the costing version. A separate cost record must be entered for each site that purchases or stocks the item. The cost should reflect the standard costs for the period. If a cost was entered incorrectly, change the pending cost for the item. A pending cost can also be deleted.
    
    Verify item cost records in the costing version for completeness and accuracy. Use the **Item price** report to review a list of item cost records.

3.  When you use routing information for costing purposes, use the **Price** form to enter cost records. This must be in the costing version to define the hourly rate or piece rate that applies to each cost category. The cost record can reflect a company-wide hourly rate or a site-specific hourly rate. The cost should reflect the standard costs for the period. If a cost was entered incorrectly, change the pending cost for the cost category. A pending cost can also be deleted.
    
    Verify cost records in the costing version for completeness and accuracy.

4.  When you must calculate manufacturing overheads, use the **Costing sheet setup** form to enter the indirect cost calculation formulas for surcharge and rate nodes. The cost record can reflect a company-wide calculation formula or a site-specific calculation formula, and it can reflect item-specific calculation formulas. If a cost record was entered incorrectly, change the pending cost record or delete it.
    
    Validate and save the costing sheet setup. Correct any errors that are identified by the validation process.
    
    Verify cost records in the costing version for completeness and accuracy. Use the **Indirect cost rate and ratio** report to review a list of cost records.

5.  Calculate the cost of all manufactured items by using the **Calculation** form. You can access the **Calculation** form from the **Costing version setup** form, and by selecting the current period’s costing version.
    
    Verify the calculated costs for manufactured items for completeness and accuracy. Use the **Complete** form to review the calculated costs for each item cost record, and any Infolog warning messages. Alternatively, use the **Calculation** report to review a list of the calculated costs.

6.  Use the **Costing versions** form to change the blocking flag so that the status of pending cost records can be changed to active.

7.  Change the status to active for all pending item cost records in the costing version on the cutover date. Use the **Activate prices** form to change status all cost records. You can access the **Activate prices** form from the **Costing version setup** form for the current period’s costing version.
    
    Alternatively, change the status of individual cost records in the costing version. Use the **Price** form to change the status of pending cost records for individual items. Use the **Price** form to change the status of pending costs for individual cost categories. Use the **Costing sheet setup** form to change the status of individual calculation formulas for indirect costs.

8.  Use the **Costing versions** form to change the blocking flags in the second costing version to prevent additional data maintenance.

Repeat the steps in this procedure for separate costing versions when they contain site-specific costs for a multisite operation.

## See also

[About updating standard costs in a manufacturing environment](about-updating-standard-costs-in-a-manufacturing-environment.md)

[Update standard costs in a manufacturing environment](update-standard-costs-in-a-manufacturing-environment.md)

  



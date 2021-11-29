---
title: Update standard costs in a manufacturing environment
TOCTitle: Update standard costs in a manufacturing environment
ms:assetid: 9b368822-b76e-48c4-8f79-8240ce6258d4
ms:mtpsurl: https://technet.microsoft.com/library/Gg213358(v=AX.60)
ms:contentKeyID: 36058711
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Update standard costs in a manufacturing environment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Manufacturing environments maintain standard costs for purchased and manufactured items. This maintenance includes periodically updating standard costs. Periodic updates reflect a new frozen period and the need to update standard costs for all items. Additional steps are required in manufacturing environments that use routing information for costing purposes. The following guidelines assume the use of a separate costing version to contain the next period's standard costs. Pending cost records for all items are entered in this costing version.

1.  Use the **Costing version setup** form to define the costing version for the next period. Guidelines for this costing version include the following:
    
      - Assign a costing type of standard costs.
    
      - Assign a meaningful identifier to the next period's costing version. For example, if 2012 is the next frozen period, you might use 2012-STANDARD.
    
      - Ensure that the content includes cost records.
    
      - Allow the entry of cost records. Do not block the entry of pending costs.
    
      - Allow the entry of cost records for all sites. If you specify a site, you limit the entry of cost records to that site.
    
      - Prevent the activation of pending costs. The status of cost records will be changed to active after pending costs have been completely and accurately defined.
    
      - Enter a from-date. As a general guideline, use a future date that represents the first day of the next frozen period.
    
      - Indicate a fallback principle of none.

2.  Analyze the need to change standard costs for items. Use the **Standard cost variance analysis** report to analyze the historical purchase price and production variances, and to suggest a new standard cost.

3.  Use the **Price** form to enter item cost records for purchased items in the next period's costing version. A separate cost record must be entered for each site that purchases or stocks the item. The cost should reflect the standard costs for the period. If a cost was entered incorrectly, change the pending cost for the item. A pending cost can also be deleted.
    
    Alternatively, you can automatically enter costs by copying item cost records. The cost records can then be maintained by using the **Price** form. Use the **Copy item prices** form to copy active item cost records for standard costs into the next period's costing version. You should copy active costs if you used a two-version approach to cost data updates for the current period, because active cost records will be located in more than one costing version.
    
    You can selectively copy item cost records to populate the next period's costing version, and you can copy them multiple times. Existing costs can be selectively changed by a factor or an amount. Existing charges can also be changed by a factor or an amount.

4.  Use the **Item prices** report to review the completeness and accuracy of the item cost records in the costing version.

5.  When you use routing information for costing purposes, use the **Cost category price** form to enter cost records in the next period's costing version. Also define the hourly rate or piece rate that applies to each cost category. The cost record can reflect a company-wide or site-specific hourly rate. The cost should reflect the standard costs for the next period. If a cost was entered incorrectly, change the pending cost for the cost category. A pending cost can also be deleted.

6.  Review the completeness and accuracy of the cost records in the next period's costing version.

7.  When you calculate manufacturing overhead, use the **Costing sheet setup** form to enter the calculation formulas for indirect costs for surcharge or rate nodes. The cost record can reflect a company-wide or site-specific calculation formula. The cost record can also reflect item-specific calculation formulas. If a cost record was entered incorrectly, change the pending cost record or delete it.

8.  Validate and save the setup of the costing sheet. Correct any errors that the validation process identifies.

9.  Review the completeness and accuracy of the cost records in the next period's costing version. Use the **Indirect cost rate and ratio** report to review a list of item cost records.

10. Use the **Calculation** form to calculate the cost of all manufactured items. You can open the **Calculation** form from the **Costing version setup** form. You can also open it by selecting the next period's costing version.

11. Review completeness and accuracy of the calculated costs for manufactured items. Use the **Complete** form to review the calculated costs for each item cost record, and to review any Infolog messages. Alternatively, use the **Calculation** report to review a list of the calculated costs.

12. Use the **Costing version setup** form to change the blocking flag for the next period's costing version to allow activation of pending cost records.

13. Activate all pending item cost records in the next period's costing version no earlier than the first day of the next period. Use the **Activate prices** form for the next period's costing version. You can open the **Activate prices** form from the **Costing version setup** form. You can also activate the pending cost records for individual items by clicking the **Activate** button in the **Price** form.
    
    Alternatively, you can activate individual cost records in the costing version. Use the **Price** form to activate pending cost records for individual items and individual cost categories. Use the **Costing sheet setup** form to activate individual calculation formulas for indirect costs.

14. Use the **Costing version setup** form to change the blocking flags in the next period's costing version to prevent additional data maintenance.

Repeat the steps in this process every time that you must enter and activate costs for a new period.

## See also

[Set up initial standard costs in a manufacturing environment](set-up-initial-standard-costs-in-a-manufacturing-environment.md)

[About updating standard costs in a manufacturing environment](about-updating-standard-costs-in-a-manufacturing-environment.md)

  



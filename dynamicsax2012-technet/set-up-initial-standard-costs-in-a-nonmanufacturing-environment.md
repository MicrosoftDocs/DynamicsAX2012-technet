---
title: Set up initial standard costs in a nonmanufacturing environment
TOCTitle: Set up initial standard costs in a nonmanufacturing environment
ms:assetid: cc5882e8-5f55-41e0-a050-94051c4c8a9a
ms:mtpsurl: https://technet.microsoft.com/library/Gg213669(v=AX.60)
ms:contentKeyID: 36059451
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- costs
- costing
- standard cost
- standard costs
- nonmanufacturing
audience: Application User
ms.search.region: Global
---

# Set up initial standard costs in a nonmanufacturing environment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Nonmanufacturing and distribution environments maintain standard costs for purchased items. This includes setting up the standard costs for the first time. The following guidelines assume the use of a single costing version when you set up the standard costs for the first time. This costing version contains standard costs for the current period. Pending cost records for all items are entered in this costing version, and the status is changed to active.

1.  Define the costing version in the **Costing versions** form. Guidelines for this costing version include the following:
    
      - Assign a costing type of standard costs.
    
      - Assign a meaningful identifier for the costing version, such as 2012-STANDARD.
    
      - Ensure that the content includes cost records.
    
      - Allow the entry of cost records. Do not block the entry of pending costs.
    
      - Allow the entry of cost records for all sites. Assigning a site limits the entry of cost records to the specified site.
    
      - Optionally prevent the ability to change the status of item cost records from pending to active. The status change will be enabled after the pending costs have been completely and accurately defined.
    
      - Optionally define a from-date. As a general guideline, use a future date that represents the planned cutover date, or the first day in the frozen period if you prepare cost data beforehand.
    
      - Indicate a fallback principle of none, because the fallback principle applies to BOM calculations in manufacturing environments.

2.  Enter item cost records in the costing version in the Item price form. A separate cost record must be entered for each site that purchases or stocks the item. The cost reflects the standard costs for the period. If a cost is entered incorrectly, change the pending cost for the item. A pending cost can also be deleted.

3.  Verify item cost records in the costing version for completeness and accuracy. Use the **Item prices** report to review a list of item cost records.

4.  Use the **Costing version setup** form to change the blocking flag to allow the status change of pending cost records.

5.  Change the status to active for all pending item cost records in the costing version on the cutover date. Use the **Activate prices** form to change the status for multiple cost records. You can open the **Activate prices** form from the **Costing version setup** form. The status of individual cost records can be changed in the **Item price** form by clicking **Activate**.

6.  Use the **Costing version setup** form to change the blocking flags in the second costing version to prevent additional data maintenance.

Repeat the steps in this procedure for separate costing versions when they contain site-specific costs for a multisite operation.

## See also

[Update standard costs in a nonmanufacturing environment](update-standard-costs-in-a-nonmanufacturing-environment.md)

  



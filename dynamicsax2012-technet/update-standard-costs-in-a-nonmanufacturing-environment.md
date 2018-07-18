---
title: Update standard costs in a nonmanufacturing environment
TOCTitle: Update standard costs in a nonmanufacturing environment
ms:assetid: ca474ba1-416f-4eb2-a6a2-3b10d008fc64
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213658(v=AX.60)
ms:contentKeyID: 36059332
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Update standard costs in a nonmanufacturing environment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Nonmanufacturing and distribution environments maintain standard costs for purchased items. Maintaining standard costs includes updating the standard costs throughout the frozen period. Updates may reflect new items, corrections, or cost changes. The following guidelines assume the use of a two-version approach to updating standard cost. One costing version contains the originally defined standard costs for the frozen period, and the second costing version contains the incremental updates. Each update is entered as a cost record that is enclosed in the second costing version, and eventually it is enabled. An alternative, one-version approach uses the originally defined set of standard costs.

The two-version approach requires the definition of a second costing version. The guidelines for defining this costing version include the following:

  - Assign a costing type of standard costs.

  - Assign the costing version a meaningful identifier that indicates the contents, such as 2012-UPDATES.

  - Ensure that the content includes cost records.

  - Allow the entry of cost records for all sites. If you specify a site, you limit the entry of cost records to that site.

  - Indicate a fallback principle of none. The fallback principle only applies to cost calculations for manufactured items.

To correct, adjust, or update standard costs for new items, follow these steps:

1.  Use the **Costing version setup** form to enable the entry of cost data into the second costing version. Optionally, prevent the activation of pending costs, so that the activation will be allowed after pending costs have been completely and accurately defined. Optionally, enter a date in the **From date** field. As a general guideline, use a date that represents when you intend to enable the incremental updates. Alternatively, leave the **From date** field blank for the costing version, and then enter a date in the **From date** field for each cost record.

2.  Use the **Item price** form to enter updates as item cost records that are enclosed in the second costing version.

3.  Use the **Item prices** report to verify the completeness and accuracy of the item cost records that are enclosed in the second costing version.

4.  Use the **Costing versions** form to change the blocking flag to allow the activation of pending cost records that are enclosed in the second costing version.

5.  Use the **Activate prices** form to activate all pending item cost records that are enclosed in the second costing version. You open the **Activate prices** form from the **Costing versions** form. You can also enable the pending cost records for individual items by clicking the **Activate** button in the **Item price** form.

6.  To prevent additional data maintenance, use the **Costing version setup** form to change the blocking flags that are enclosed in the second costing version. The blocking policies will prevent the entry of new pending costs and the activation of pending costs.

## See also

[Set up initial standard costs in a nonmanufacturing environment](set-up-initial-standard-costs-in-a-nonmanufacturing-environment.md)

  



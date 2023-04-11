---
title: About common issues related to standard cost conversion checks
TOCTitle: About common issues related to standard cost conversion checks
ms:assetid: 9d130481-023d-4b9b-8c7a-eb8b29719380
ms:mtpsurl: https://technet.microsoft.com/library/Gg213370(v=AX.60)
ms:contentKeyID: 36058741
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About common issues related to standard cost conversion checks 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Several issues are frequently identified by the **Standard cost conversion checks** report that would prevent converting items to a standard cost inventory model. The report applies to a standard cost conversion record and the items associated with the conversion record. The report displays the issues associated with each item. The issues must be resolved to convert the item. The common issues can be grouped into four categories about items, model groups, standard costs, and other. This topic describes common issues that are identified by the **Standard cost conversion checks** report.

## Common issues related to an item

  - A service item cannot have a standard cost inventory model. Delete the item from the conversion record.

  - The posting profile for the item does not have a valid cost revaluation account. Use the **Posting** form to assign a general ledger account number to the revaluation account.

  - The item already has a standard cost inventory model, and it does not require a conversion. Delete the item from the conversion record.

## Common issues related to the model group assigned to an item

  - A standard cost inventory model is not assigned to the item. Create an item model group that has a standard cost inventory model, and assign it to the item.

  - The negative inventory policy is different for the item's old item model group and the new item model group. Change the negative inventory policy in one group so that it matches the policy in the other group.

## Common issues related to the standard costs assigned to an item

  - The item's pending standard costs have not been entered for each site. Enter a standard cost for each site.

  - The item's pending standard costs have not been entered for each combination of inventory or product dimensions. Enter a standard cost for each combination.

  - The item's pending standard cost has a from date that differs from the conversion date. To fix this, change the from date on the item cost record.

## Common issues related to other aspects of the standard cost conversion process

  - An item has an open production order at a status of **Release**, **Start**, or **Report as finished**. Complete the open production order so that the status is **End**, or reset the status so that it is **Schedule**, **Estimate**, or **Create**.

  - An item's inventory transactions cannot exist on or after the planned conversion date for the conversion record. Change the planned conversion date so that it occurs after the dates of existing transactions.

  - The item has inventory transactions that are not yet posted. Post the inventory transactions.

  - An inventory close has not been performed one day before the planned conversion date. You can perform the inventory close as part of performing the conversion process.

## See also

[About standard cost conversion](about-standard-cost-conversion.md)

[Set up and run a standard cost conversion](set-up-and-run-a-standard-cost-conversion.md)

  



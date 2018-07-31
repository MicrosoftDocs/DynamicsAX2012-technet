---
title: About standard cost conversion
TOCTitle: About standard cost conversion
ms:assetid: 3f2f555d-7d73-434e-b491-a697c815bf05
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231170(v=AX.60)
ms:contentKeyID: 36056702
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- costs
- costing
- standard cost
- standard costs
- cost conversion
audience: Application User
ms.search.region: Global
---

# About standard cost conversion 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In a standard cost conversion, the valuation method for an item's inventory is changed so that it is based on standard cost instead of actual cost. Use the **Standard cost conversions** form to convert the inventory model for a batch of selected items from an actual costing approach to a standard costing approach. The conversion process involves a prerequisite inventory close, several steps during a transition period, which is defined by a transition start date and a planned conversion date, and then the conversion and an associated inventory close.

  - Inventory close before the transition period – An inventory close represents a prerequisite step, because it settles an item's open transactions under the old valuation method. During the transition period, you can enter and post backdated transactions, such as invoices, so that you can close the previous period. The inventory close date must be one day before the transition start date to ensure a clean break with the old valuation method.

  - Conversion steps during the transition period – Use the **Standard cost conversions** form to create a conversion record that also contains the user-defined identifier for a new costing version. You identify the items that require conversion, and then enter the items' pending standard costs in the new costing version. You perform a check of the selected items to identify issues that might prevent conversion, resolve the issues, and then perform another check. After the items have successfully passed the checks, you change the status of the conversion record to **Ready**. On the planned conversion date, you perform the conversion and optionally include an inventory close.
    
    An item's inventory movements during the transition period are posted and valued according to the old inventory model. Then, after the conversion is successfully completed, the inventory movements are revalued to standard cost.

  - Inventory close before the conversion – The inventory close can be included as part of the conversion on the planned conversion date, or it can be performed as a separate step before the conversion.

After the conversion process is successfully completed, the inventory model for each item is based on standard cost, and the item's standard cost is enabled. Subsequent inventory transactions will be valued at the item's standard cost. In addition, the system converts the item's physical inventory transactions for receipts and issues to standard cost based on the conversion date. The system also converts the item's financial on-hand inventory to standard cost, and it posts the difference in value as an inventory revaluation.

Any transactions that occur after the conversion are valued at the item's standard cost. You cannot enter backdated transactions before the conversion date, because an inventory close must be performed one day before the conversion date. In other words, a conversion can only be performed if an inventory close was performed one day earlier. This inventory close cannot be canceled.

## See also

[About prerequisites for a standard cost conversion](about-prerequisites-for-a-standard-cost-conversion.md)

[Set up and run a standard cost conversion](set-up-and-run-a-standard-cost-conversion.md)

[About common issues related to standard cost conversion checks](about-common-issues-related-to-standard-cost-conversion-checks.md)

[Standard cost conversion (form)](https://technet.microsoft.com/en-us/library/hh208816\(v=ax.60\))

[About inventory close](about-inventory-close.md)

  



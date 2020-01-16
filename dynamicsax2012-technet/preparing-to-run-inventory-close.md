---
title: Preparing to run inventory close
TOCTitle: Preparing to run inventory close
ms:assetid: e0268068-6780-4060-93f9-791a83ae92ea
ms:mtpsurl: https://technet.microsoft.com/library/Gg243205(v=AX.60)
ms:contentKeyID: 36059703
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Preparing to run inventory close 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you perform inventory close, we recommend completing the following tasks.

1.  Validate that the inventory model that is assigned to the item on the **Inventory model** tab of the **Item model groups** form is accurate. Inventory close will settle transactions to each other based on the current inventory valuation method assigned to the item.

2.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Close procedure**, then **1. Check open quantities**. This report will print a list of inventory transactions that will remain open after the inventory close is performed.
    
    For example, you have an item that includes the following transactions:
    
      - Inventory physical receipt for a quantity of 10
    
      - Inventory financial issue for a quantity of 3
    
    In this case, the report will show an open quantity of 3 because this financial issue cannot be settled to any transactions.
    
    The **Open quantity** report also includes a **Show receipts** option that lets you view all the physical receipts posted for an item and all the open quantities that will remain after an inventory close for the date specified.

3.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click **Close procedure**, then **2. Check cost prices**. This report lets you enter a maximum deviation percentage. Items that appear on this report will exceed the maximum deviation percentage. The deviation is based on the item cost price, item or median cost price, or median.
    
    For example:
    
      - An item contains a cost price of USD 5.00. When a vendor invoice was posted for this item, the cost price entered was USD 15.00.
    
      - When you print this report, the maximum deviation percentage is set to be 30%. Use the item cost price as the base price. This purchase order will appear on the report because the cost of the item posted, USD 15.00 is more than 30% larger than the item cost price, USD 5.00.

## See also

[About inventory close](about-inventory-close.md)

[Run inventory close](run-inventory-close.md)

  



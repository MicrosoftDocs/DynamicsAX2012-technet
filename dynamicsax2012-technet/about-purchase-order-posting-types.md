---
title: About purchase order posting types
TOCTitle: About purchase order posting types
ms:assetid: ec431d61-43ba-4a83-899b-dae5b3cea030
ms:mtpsurl: https://technet.microsoft.com/library/Aa551524(v=AX.60)
ms:contentKeyID: 44081060
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About purchase order posting types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can specify posting accounts for inventory transactions that are associated with purchase orders. You can also specify posting definitions or posting profiles for purchase order encumbrances.

## Item posting accounts for purchase orders

When you process purchase orders, inventory information and related amounts are updated. Use the **Posting** form to specify the purchase order posting accounts. (Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**. Click **Posting**. Click the **Purchase order** tab.) You can specify the following accounts:

  - **Product receipt**

  - **Purchase expenditure, un-invoiced**

  - **Purchase, inventory receipt**

  - **Purchase expenditure for product**

  - **Discount**

  - **Fixed receipt price profit**

  - **Fixed receipt price loss**

  - **Fixed receipt price offset**

  - **Charge**

  - **Stock variation**

  - **Purchase, accrual**

  - **Accrued sales tax on receipt**

  - **Fixed asset receipt**

  - **Purchase expenditure for expense**

  - **Prepayment**

When you create a purchase order line (**Ordered** status), an inventory transaction is generated with the quantity specified, but without any cost values.

When the item is received (**Received** status), transactions that are based on the cost of the items that are recorded in the purchase order line are generated in the **Product receipt** account.

For the inventory posting to occur when the product receipt is posted, you must select the following two check boxes:

  - **Post physical inventory** in the **Item model groups** form. (Click **Inventory management** \> **Setup** \> **Inventory** \> **Item model groups**.)

  - **Post product receipt in ledger** in the **Accounts payable parameters** form. (Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.)

If an account for discounts is specified, the product receipt amount includes the whole line amount. The line discount is not deducted from the product receipt amount. Instead, the line discount is credited in the separate account for discounts. If you do not specify an account for the line discount, the product receipt amount is reduced by the line discount amount, and the line discount amount is not recorded directly in a ledger account.

To specify that a purchase is for the internal use of a fixed asset, select the **Fixed asset receipt** check box on the **Fixed assets** tab on the **Line details** FastTab in the **Purchase order** form. For more information, see [About fixed assets integration](about-fixed-assets-integration.md).

For information about inventory and financial posting for stocked items, see the white paper titled [Accounting for stocked items on product receipts and vendor invoices](https://go.microsoft.com/fwlink/?linkid=233756).

## Set up offset accounts and encumbrance processing

You can use either posting profiles or posting definitions for offset accounts. Each posting profile is associated with only one offset account. Posting definitions can be associated with multiple offset accounts.

Posting definitions are used to support encumbrance accounting for purchase orders and pre-encumbrance accounting for purchase requisitions. Posting profiles cannot be used for encumbrance and pre-encumbrance accounting.

Posting definitions are available only when the **Use posting definitions** check box is selected in the **General ledger parameters** form. Also, posting definitions are available only for the transaction posting types that are shown in the **Transaction posting definitions** form. Transaction posting types that are not shown in the **Transaction posting definitions** form always use posting profiles.

## See also

[Item posting (form)](https://technet.microsoft.com/library/aa589971\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

[Purchase posting (form)](https://technet.microsoft.com/library/aa587152\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

[Transaction posting definitions (form)](https://technet.microsoft.com/library/hh242550\(v=ax.60\))

[About posting definitions](about-posting-definitions.md)

[About posting profiles](about-posting-profiles.md)

[Encumber purchase orders](encumber-purchase-orders.md)

  



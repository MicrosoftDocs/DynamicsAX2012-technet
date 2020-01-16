---
title: About sales order posting types
TOCTitle: About sales order posting types
ms:assetid: ad7875e1-45b2-4c48-9850-35490c808485
ms:mtpsurl: https://technet.microsoft.com/library/Aa498586(v=AX.60)
ms:contentKeyID: 44081023
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About sales order posting types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can specify posting accounts for inventory transactions that are associated with sales orders.

## Item posting accounts for sales orders

When you process sales orders, inventory information and related amounts are updated. Use the **Posting** form to specify the sales order posting accounts. (Click **Inventory management** \> **Setup** \> **Inventory** \> **Item groups**. Click **Posting**.) You can specify the following accounts:

  - **Packing slip**

  - **Packing slip offset**

  - **Issue**

  - **Consumption**

  - **Revenue**

  - **Discount**

  - **Commission**

  - **Commission offset**

  - **Deferred revenue on delivery**

  - **Deferred revenue offset on delivery**

  - **Deferred sales tax on delivery**

When you create an order line (**On order** status), an inventory transaction is generated with the quantity specified, but without any financial costs.

When you update the packing slip for the item (**Deducted** status), transactions that are based on the cost of the items when the packing slip is updated are generated in the packing slip account. The packing slip offset account is also updated with the packing slip update.

For the posting to occur, you must select the following two setup check boxes:

  - **Post physical inventory** in the **Item model groups** form. (Click **Inventory management** \> **Setup** \> **Inventory** \> **Item model groups**.)

  - **Post packing slip in ledger** in the **Accounts receivable parameters** form. (Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.)

When you invoice (**Sold** status) the sales order line, the two packing slip transactions for an item are reversed. The cost of the item is credited to the account for inventory issues, and the account for item consumption is debited.

The sale of the item, excluding any taxes, such as sales tax, is credited to the revenue account. Tax is credited to the tax codes account. The sale, including any taxes such as sales tax, is debited to the customer summary account that is set up in the customer's posting profile.

  - For the **Discount** posting type, the sales order is posted before the line discount is deducted, and the line discount is debited in the account for discounts. If no account is specified for discounts, the revenue is posted after the line discount is deducted, and the line discount is not recorded directly in a ledger account.

  - If an account is specified for the **Discount** posting type, the packing slip amount includes the whole line amount. The line discount is not deducted from the packing slip amount. Instead, the line discount is debited in the account for discounts. If no account is specified for discounts, the packing slip revenue amount is reduced by the line discount amount, and the line discount amount is not recorded directly in a ledger account.

  - If an account is specified for the **Commission** posting type, a commission account and a commission offset account, which provide an overview of the ledger-posting of commissions, are updated. When you invoice a sales order, the commission on the posted amount is debited to the commission account and credited to the commission offset account.

## See also

[Item posting (form)](https://technet.microsoft.com/library/aa589971\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

[Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\))

  



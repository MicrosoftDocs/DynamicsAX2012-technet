---
title: (RUS) Set up the posting type and number sequences to transfer proprietary rights
TOCTitle: (RUS) Set up the posting type and number sequences to transfer proprietary rights
ms:assetid: 1e6bc95a-03aa-4bc2-9eb1-387eaac0b1f7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ870988(v=AX.60)
ms:contentKeyID: 50492707
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the posting type and number sequences to transfer proprietary rights 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you ship items to a customer and post a sales invoice for the shipment, the ownership or proprietary rights of the items are transferred to the customer. If the proprietary rights cannot be transferred on the date of shipment for a reason such as the terms of a trade agreement, you can indicate this fact in the sales invoice. The customer becomes liable for the items only when ownership is transferred. If the transfer is delayed, you remain responsible for calculating and paying sales tax at the time of shipment. You can calculate and pay sales tax on items that are shipped to a customer, and you can register the items that are in transit in a specific general ledger account. You can set up revenue, consumption, and transit general ledger accounts to post miscellaneous sales charges for the items that are shipped. You can also allocate and post miscellaneous charges for a sales invoice.

Complete the following setup tasks before you transfer proprietary rights to a customer:

  - Set up currency and exchange rates. For more information, see [(RUS) Set up exchange rates for a currency transaction](rus-set-up-exchange-rates-for-a-currency-transaction.md).

  - Create an item, and assign a dimension group to the item. For more information, see [Create items](create-items.md) and [Create and maintain product dimensions](create-and-maintain-product-dimensions.md).

  - Set up a sales tax code, sales tax group, and item sales tax group. For more information, see [(RUS) Set up sales tax codes for tax calculation](rus-set-up-sales-tax-codes-for-tax-calculation.md), [(RUS) Set up sales tax groups for tax calculation](rus-set-up-sales-tax-groups-for-tax-calculation.md), and [(RUS) Set up item sales tax groups for tax calculation](rus-set-up-item-sales-tax-groups-for-tax-calculation.md).

  - Create a warehouse for shipped items. For more information, see [Create warehouses](create-warehouses.md).

Use this procedure to set up the posting type and number sequences, so that you can transfer proprietary rights. Use the **Accounts receivable parameters** form to set up the parameters for transferring proprietary rights to a customer.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  On the **General** page, on the **Sales** FastTab, in the **Posting type** field, select the type of posting from the following options:
    
      - **Standard** – The property rights are transferred to a customer when the sales invoice is posted.
    
      - **Postponed passing of property** – Transfer of the property rights to a customer is delayed when the sales invoice is posted.

3.  Click **Number sequences**.

4.  In the **Number sequences** field, select the number sequence for the following references:
    
      - **Journal of passing of property** – The number sequence reference for the journal that is used for property transfer.
    
      - **Charges voucher** – The number sequence reference for a voucher that is used for miscellaneous charges.
    
      - **Voucher of passing of property** – The number sequence reference for a voucher that is used for property transfer.

## See also

[(RUS) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj733289\(v=ax.60\))

  



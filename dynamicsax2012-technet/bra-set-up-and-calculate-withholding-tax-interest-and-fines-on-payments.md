---
title: (BRA) Set up and calculate withholding tax, interest, and fines on payments
TOCTitle: (BRA) Set up and calculate withholding tax, interest, and fines on payments
ms:assetid: 752fc02b-5dce-443a-85ef-11d476dd3cc9
ms:mtpsurl: https://technet.microsoft.com/library/Dn126103(v=AX.60)
ms:contentKeyID: 52075254
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- withholding tax
- interest
- delayed payments
- fines
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up and calculate withholding tax, interest, and fines on payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use Microsoft Dynamics AX to perform the following tasks:

  - Calculate and deduct withholding tax from customer payments for the sale of services, and from vendor payments for the purchase of services. You can calculate withholding tax by applying a threshold amount to payments that are made to a vendor or received from a customer by a legal entity each month. You can also calculate withholding tax by applying a threshold amount to centralized payments that are made to a vendor or received from a customer by a group of legal entities each month. The group of legal entities is set up for the purpose of making centralized payments in the organization. For more information, see [(BRA) Calculate withholding tax for the sale of services](bra-calculate-withholding-tax-for-the-sale-of-services.md) and [(BRA) Calculate withholding tax for the purchase of services](bra-calculate-withholding-tax-for-the-purchase-of-services.md).

  - Calculate interest and fines for delayed customer payments or vendor payments. You can calculate and deduct interest and fine amounts for a vendor when you make a payment to that vendor. You can calculate and collect interest and fine amounts for a customer when you receive a payment from that customer. For more information, see [(BRA) Calculate interest and fines on customer payments](bra-calculate-interest-and-fines-on-customer-payments.md) and [(BRA) Calculate interest and fines on vendor payments](bra-calculate-interest-and-fines-on-vendor-payments.md).

Perform the following tasks to set up and post withholding tax, interest, and fines on payments. When you post customer payment journals or vendor payment journals, the withholding tax group, interest, and fines that are set up for the customer or vendor are used to calculate the withholding tax, interest, and fines on the transaction.

1.  Set up withholding tax codes and withholding tax groups. For more information, see [Set up withholding tax in System administration and General ledger](set-up-withholding-tax-in-system-administration-and-general-ledger.md) and [(BRA) Set up a withholding tax](bra-set-up-a-withholding-tax.md).

2.  Set up a withholding tax settlement period and associate it with one or more withholding tax codes. For more information, see [(BRA) Set up a withholding tax settlement period](bra-set-up-a-withholding-tax-settlement-period.md).

3.  Set up an item withholding tax group and associate withholding tax codes with it. For more information, see [(BRA) Set up an item withholding tax group](bra-set-up-an-item-withholding-tax-group.md).

4.  Set up a withholding tax group and associate it with a customer or a vendor. For more information, see [(BRA) Set up a withholding tax group and attach it to a customer or vendor](bra-set-up-a-withholding-tax-group-and-attach-it-to-a-customer-or-vendor.md).

5.  Set up interest codes and fine codes for customer and vendor payments. For more information, see [(BRA) Set up interest and fines for customer payments](bra-set-up-interest-and-fines-for-customer-payments.md) and [(BRA) Set up interest and fines for vendor payments](bra-set-up-interest-and-fines-for-vendor-payments.md).

6.  Set up a default description and transaction text for withholding tax, interest, and fine payments that are made to customers and vendors. For more information, see [(BRA) Set up a default description for withholding tax, interest, and fine payments](bra-set-up-a-default-description-for-withholding-tax-interest-and-fine-payments.md).

7.  Create and post a general journal that has a default description for withholding tax, interest, and fine payments that are made to a customer. For more information, see [(BRA) Set up journal descriptions for withholding tax, interest, and fine payments](bra-set-up-journal-descriptions-for-withholding-tax-interest-and-fine-payments.md) and [(BRA) Create and post a general journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-general-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md).

8.  Create and post a payment journal that has a default description for withholding tax, interest, and fine payments that are made to a customer or a vendor. For more information, see [(BRA) Create and post a customer payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-customer-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md) and [(BRA) Create and post a vendor payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-vendor-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md).

## See also

[(BRA) Customers (modified form)](https://technet.microsoft.com/library/jj933537\(v=ax.60\))

[(BRA) Vendors (modified form)](https://technet.microsoft.com/library/jj933505\(v=ax.60\))

[Withholding tax groups (form)](https://technet.microsoft.com/library/aa591973\(v=ax.60\))

[(BRA) Withholding tax codes (modified form)](https://technet.microsoft.com/library/dn126109\(v=ax.60\))

[(BRA) Setting up standard text in accounting transactions](bra-setting-up-standard-text-in-accounting-transactions.md)

  



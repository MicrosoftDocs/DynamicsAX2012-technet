---
title: (RUS) Generate a payment order for a foreign vendor
TOCTitle: (RUS) Generate a payment order for a foreign vendor
ms:assetid: 1deebcb0-b6b5-4f1d-87be-d6017a56da7d
ms:mtpsurl: https://technet.microsoft.com/library/JJ711452(v=AX.60)
ms:contentKeyID: 49387269
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a payment order for a foreign vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Generate payments** form to generate a payment order for payments that are made to the foreign bank account of a vendor. Before you generate a payment order, you can use the **Journal voucher** form to register a line in the payment journal to record the vendor payments. For more information, see [Generate payments - vendor (class form)](https://technet.microsoft.com/library/aa586980\(v=ax.60\)).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a vendor payment journal, and then click **Lines** to open the **Journal voucher** form.

3.  In the **Method of payment** field, select the payment method for the current payment.

4.  Click the **Bank** tab, and then, in the **Account identification** field, enter the foreign bank account of the vendor.

5.  In the **Payment documented on** field, select the vendor account that the payments are made to.

6.  Click **Functions** \> **Generate payments** to open the **Generate payments** form. For more information, see [(RUS) Generate a payment order in rubles](rus-generate-a-payment-order-in-rubles.md).

7.  Click **OK** to generate the payment order.

## See also

[(RUS) Set up a customer bank account for payment returns from a foreign vendor](rus-set-up-a-customer-bank-account-for-payment-returns-from-a-foreign-vendor.md)

[(RUS) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/library/jj733511\(v=ax.60\))

  



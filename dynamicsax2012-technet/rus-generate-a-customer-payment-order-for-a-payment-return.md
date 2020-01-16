---
title: (RUS) Generate a customer payment order for a payment return
TOCTitle: (RUS) Generate a customer payment order for a payment return
ms:assetid: 340abc9e-3d38-4c09-90ba-18407fca5907
ms:mtpsurl: https://technet.microsoft.com/library/JJ665265(v=AX.60)
ms:contentKeyID: 49387354
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a customer payment order for a payment return 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you send a payment return to the foreign bank account of a customer, you can generate a payment order to make the payment. You can use the **Journal voucher** form to register a line in the payment journal to record the customer payment.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a customer payment journal, and then click **Lines** to open the **Journal voucher** form.

3.  In the **Method of payment** field, select the payment method for the current payment.

4.  Click the **Bank** tab, and then, in the **Account identification** field, enter the bank account number of the customer account that receives the payment return.

5.  In the **Payment documented on** field, select the customer account that receives the payment return.

6.  Click **Functions** \> **Generate payments** to open the **Generate payments** form. For more information, see [Generate payments - customer (class form)](https://technet.microsoft.com/library/aa554105\(v=ax.60\)).

7.  Click **OK** to generate the payment order.

## See also

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/library/aa556141\(v=ax.60\))

  



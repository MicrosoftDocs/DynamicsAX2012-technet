---
title: (RUS) Settle partial payments for customers
TOCTitle: (RUS) Settle partial payments for customers
ms:assetid: f8e48625-cf7d-45f6-9a0a-7ebbb849241e
ms:mtpsurl: https://technet.microsoft.com/library/JJ735282(v=AX.60)
ms:contentKeyID: 49693283
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Settle partial payments for customers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to settle partial payment transactions for a customer. You can settle a partial payment against a particular invoice line, and you can settle open transactions by using a periodic settlement for customers. Exchange adjustment factures are created for the invoice lines that are settled.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create or select a payment journal line, and then click **Lines** to open the **Journal voucher** form. For more information, see [Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md).

3.  Click **Mark invoice lines** to open the **Mark invoice lines** form.

4.  Select the **Mark** check box to mark the transaction line for settlement.
    

    > [!NOTE]
    > <P>The <STRONG>Mark lines on free text invoices and interest notes</STRONG> check box must be selected on the <STRONG>Settlement</STRONG> link in the <STRONG>Accounts receivable parameters</STRONG> form.</P>



5.  In the **Amount to settle** field, view or modify the partial payment that has to be settled.

6.  Click **OK** to settle the partial settlement for the customer.

7.  Click **Post** \> **Post** to post the customer payment journal and settle the payment amount.
    

    > [!NOTE]
    > <P>To verify that the exchange adjustment facture that is created has the same settled invoice amount in the <STRONG>Facture journal</STRONG> form, select the facture.</P>



8.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Sales books journal**.

9.  Create a new sales book that includes the settled facture amount and the exchange adjustment facture. You can verify that the invoice facture is included in the sales book for the settled amount.

## See also

[About partial customer payments](about-partial-customer-payments.md)

[Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md)

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/library/aa556141\(v=ax.60\))

  



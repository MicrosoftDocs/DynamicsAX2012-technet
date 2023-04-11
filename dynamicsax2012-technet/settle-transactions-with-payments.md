---
title: Settle transactions with payments
TOCTitle: Settle transactions with payments
ms:assetid: b01e2c2a-c970-4491-9d8e-8e5adfa73d34
ms:mtpsurl: https://technet.microsoft.com/library/Aa498639(v=AX.60)
ms:contentKeyID: 36058959
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payments
- transactions
- transaction
- payment
audience: Application User
ms.search.region: Global
---

# Settle transactions with payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If a payment was entered and posted, but not yet settled with an invoice or other transaction, you can settle the payment and invoice by opening the **Settle open transactions** form from the **Customers** or **Vendors** forms.

When you click the **Update** button, the selected payment and invoice transactions are settled. If the payment and invoice transactions are in the same legal entity, the transactions change status according to the following rules:

  - If an invoice is not settled in full, it remains open.

  - If the amount paid is greater than the amount due, the invoice is settled and closed. The payment transaction for the customer remains open for the amount by which the payment exceeds the amount due.

  - If the payment amount is less than the amount due, the payment amount is subtracted from the amount due, and the invoice remains open. The payment transaction is fully settled and is closed.

  - If the amount paid equals the amount due, the payment and invoice transactions are closed.


> [!NOTE]
> <P>(FRA) Invoice holds are available to French public sector entities. If a hold is placed on an invoice, the invoice cannot be settled until either the hold is removed or the time period for the hold has passed. For more information, see <A href="fra-place-or-release-vendor-invoice-payment-holds-public-sector.md">(FRA) Place or release vendor invoice payment holds (Public sector)</A>.</P>



For information about cross-company settlements, see [About cross-company payment settlements](about-cross-company-payment-settlements.md).

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select the customer or vendor whose open transactions you want to settle.

3.  To settle open customer transactions, on the **Action Pane**, click the **Collect** tab, and then click **Settle open transactions**.
    
    –or–
    
    To settle open vendor transactions, on the **Action Pane**, click the **Invoice** tab, and then click **Settle open transactions**.

4.  In the **Settlement posting date** field, select whether to post settlement transactions using the date of the most recent transaction, today's date, or a date that you specify.

5.  Optional: To designate one of the transactions as the primary payment transaction, select the transaction and then click **Mark payment**.
    
    The purpose of a primary payment is to settle all the other transactions that are selected. The transaction date of the primary payment is used in cash discount calculations and exchange rate calculations. If a primary payment is selected, the cross rate can be entered.

6.  Select the **Mark** check box on the other open transactions to be settled. A red icon indicates that a transaction is already marked for settlement.

7.  Optional: If the **Mark by priority** button is available, you can click this button to mark all debit transactions according to the settlement priority that is specified in the **Accounts receivable parameters** form. For more information about this button, see [Settle open transactions - customer (form)](https://technet.microsoft.com/library/aa558602\(v=ax.60\)).

8.  Optional: If the **Mark invoice lines** button is available when you select an invoice, you can click this button to open the **Mark invoice lines** form. Use this form to select individual transaction lines for settlement and modify the amounts to settle for those lines. For more information, see [Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md).

9.  You can enter the cross rate for each transaction that you selected to be settled with a primary payment transaction in step 5.

10. Click **Update**. The marked transactions are offset against each other.

## See also

[Reverse settlements](reverse-settlements.md)

[Specify the cross rate](specify-the-cross-rate.md)

  



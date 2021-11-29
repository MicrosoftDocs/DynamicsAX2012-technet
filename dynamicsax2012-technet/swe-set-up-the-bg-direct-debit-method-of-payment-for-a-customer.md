---
title: (SWE) Set up the BG direct debit method of payment for a customer
TOCTitle: (SWE) Set up the BG direct debit method of payment for a customer
ms:assetid: 8c2dbb45-dc52-4dd3-a5f6-3b31fa8e8036
ms:mtpsurl: https://technet.microsoft.com/library/Hh209347(v=AX.60)
ms:contentKeyID: 36058477
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Sweden
- Bankgirot
- direct debit
audience: Application User
ms.search.region: Sweden
---

# (SWE) Set up the BG direct debit method of payment for a customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Customers** form to set up a Bank giro (BG) direct debit method of payment for an existing or new customer.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  On the **General** tab, press CTRL+N or click **New** in the **Customer** action group to create a new customer details. You can also view details for the selected customer account. For more information, see [Create a customer record](create-a-customer-record.md) and [Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\)).

3.  In the **Name** and **Customer group** fields, select the name of the customer and the group that the customer belongs to.

4.  Click the **Details** tab, and in the **Currency** field, select SEK. The Bank Giro Centralen (BGC) manages direct debit payments only in Swedish Krona (SEK).

5.  Press CTRL+S to save the details and activate **New** on the **Address** tab.

6.  On the **Address** tab, click **New**, and select Sweden as the primary address. For more information, see [Address setup (form)](https://technet.microsoft.com/library/hh209301\(v=ax.60\)).

7.  Click the **Payment** tab.

8.  In the **Method of payment** field, select a method of payment that is set up to use the Bank giro Autogiro (SE) export format.

9.  In the **Bank account** field, select the bank account that the customer has authorized your company to draw direct debits from.

10. Close the form to save your changes.

## See also

[(SWE) Set up the method of payment for BG direct debit payments](swe-set-up-the-method-of-payment-for-bg-direct-debit-payments.md)

  



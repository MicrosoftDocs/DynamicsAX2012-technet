---
title: Set up centralized customer payments
TOCTitle: Set up centralized customer payments
ms:assetid: fe5e2c78-814b-4ffe-8256-c7d4b7895b5b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243312(v=AX.60)
ms:contentKeyID: 36060116
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- organization
- payments
- payment
- centralized
- intercompany
- behalf
- hierarchy
- organizational
- shared service
- shared services
audience: Application User
ms.search.region: Global
---

# Set up centralized customer payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to prepare to process payments in one legal entity on behalf of other legal entities in your organization. For an overview of centralized customer payment processing that includes examples, see [About centralized customer payments](about-centralized-customer-payments.md).

Before you begin, the following setup procedures must be complete:

  - Create legal entities

  - Set up General ledger parameters

  - Set up Accounts receivable parameters

  - Set up intercompany accounting

## Set up an organizational hierarchy for centralized payments

You must set up an organizational hierarchy for centralized payments. The same organizational hierarchy is used to process centralized vendor payments and centralized customer payments.


> [!NOTE]
> <P>The structure of the hierarchy does not matter for centralized payments. Any legal entity will be able to process payments on behalf of any other legal entity in the hierarchy.</P>



1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Organization hierarchies**.

2.  Click **New**.

3.  Enter a name for the organizational hierarchy, such as Centralized payments.

4.  On the **Purposes** FastTab, click **Assign purpose**.

5.  In the **Organization hierarchy purposes** form, in the **Purposes** column, select **Centralized payments** and then click **Add**.

6.  In the form that appears, select the organizational hierarchy that you are working with, and then click **OK**. Close the **Organization hierarchy purposes** form.

7.  In the **Organization hierarchies** form, click **View**. In the form that appears, click **Edit**.

8.  Click **Insert** and select **Legal entity**. In the form that appears, select a legal entity and then click **OK**.
    
    Repeat this step for the other legal entities to include in this organizational hierarchy.

9.  When you are finished making changes, save the hierarchy. To save a draft, click **Save as draft**. Your changes will be saved, but the hierarchy will not be in active use. To use the hierarchy immediately, click **Publish and close**.

## Set up intercompany accounting for centralized payments

When payment transactions in the current legal entity are settled with invoices in other legal entities, appropriate due-to and due-from transactions are created for each legal entity. You must specify the legal entity where any applicable cash discount amounts and any realized gain or loss amounts are posted. For more information, see [About cross-company payment settlements](about-cross-company-payment-settlements.md). Before you begin, decide which legal entity you will use to process customer payments. Switch to that legal entity.

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Intercompany accounting**.

2.  Select an intercompany relationship record for a legal entity that you will process payments on behalf of.

3.  Click the **Centralized payments** FastTab.

4.  In the **Centralized customer payments** field group, select whether to post cash discounts to the legal entity of the payment (or other transaction that decreases the balance of the customer account), or to the legal entity of the invoice (or other transaction that increases the balance of the customer account).
    
    This selection works together with the **Cash discount administration** field in the **Accounts receivable parameters** form. For overpayments and penny difference tolerances, the setting in the legal entity of the payment is used. For underpayments and penny difference tolerances, the setting in the legal entity of the invoice is used. For more information, see [About cross-company payment settlements](about-cross-company-payment-settlements.md).

5.  Select whether to post currency exchange gain or loss amounts to the legal entity of the payment or to the legal entity of the invoice.

6.  Repeat steps 2 through 5 for the remaining intercompany relationships. You must set up intercompany posting information for each combination of intercompany relationships that you will use.

## Map customer accounts across legal entities

If you receive payments from a customer from one legal entity and you want to select invoices for that customer that are in other legal entities, you must make sure that the corresponding customer accounts in each legal entity all use the same address book ID. For more information, see [Global address book overview](global-address-book-overview.md) and [Merge party IDs for customer accounts across multiple legal entities](merge-party-ids-for-customer-accounts-across-multiple-legal-entities.md).

## Set up currency codes for centralized payments

When you create a payment in one legal entity that settles invoices in other legal entities, the currency codes for the transactions are compared. If the currency codes in both legal entities are the same, they are recognized as the same currency. If the currency codes differ, currency exchange rate calculations are performed. To make sure that payments are created correctly, set up a currency code in each invoice legal entity that corresponds to the accounting currency of the legal entity of the payment. For example, if the accounting currency of the legal entity of the payment is USD, you must set up a USD currency code in each invoice legal entity. You can see the accounting currency for the legal entity of the payment in the **Ledger** form.

Before you begin, make a list of all the invoice legal entities that you will use with the selected legal entity of the payment. Switch to the first legal entity of the invoice and then follow these steps.

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**.

2.  If a currency code that corresponds to the accounting currency code of the legal entity of the payment already exists, go to step 4. Otherwise, click **New** and create a currency.

3.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency exchange rates**.

4.  Set up exchange rate information for the new currency. This information is used for exchange rate calculations when cross-company payments are settled, if the payment currency and the invoice currency differ. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/en-us/library/hh209477\(v=ax.60\)).

5.  Switch to the next legal entity of the invoice and repeat steps 1 through 4.

If you selected to post cash discount amounts to the legal entity of the payment in the **Intercompany accounting** form, you must also set up currency codes in the legal entity of the payment that correspond to all the accounting currency codes in each invoice legal entity. Switch to the legal entity of the payment, and then follow these steps.

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**.

2.  Press CTRL+P to print a list of currency codes that have been defined for the legal entity of the payment.

3.  Switch to each legal entity of the invoice and print a list of currency codes for each.

4.  If any currency codes are missing from the legal entity of the payment, switch back to the legal entity of the payment and add them.

## Set up posting profiles for centralized payments

When you create a payment in one legal entity that settles invoices in other legal entities, the posting profile IDs must be the same in both legal entities. To make sure that payments are created correctly, set up a posting profile in each invoice legal entity that corresponds to the posting profiles that are used in the legal entity of the payment. Switch to the first legal entity of the invoice and then follow these steps.

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  If a posting profile that corresponds to a posting profile that is used in the legal entity of the payment already exists, go to step 4. Otherwise, click **New** to create a posting profile.

3.  Set up the posting profile. The selections that you make for the posting profile in the legal entity of the invoice do not have to match the way that the posting profile is set up in the legal entity of the payment.

4.  Repeat steps 1 through 3 for the remaining posting profiles.

5.  Switch to the next legal entity of the invoice and repeat steps 1 through 4.

## Set up methods of payment for centralized payments

When you create a payment in one legal entity that settles invoices in other legal entities, the method of payment IDs must be the same in both legal entities. To make sure that payments are created correctly, set up a method of payment in each invoice legal entity that corresponds to the methods of payment that are used in the legal entity of the payment. Switch to the first legal entity of the invoice and then follow these steps.

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  If a payment method that corresponds to one of the payment methods that are used in the legal entity of the payment already exists, go to step 4. Otherwise, click **New** to create a method of payment.

3.  Set up the method of payment. The selections that you make for the method of payment in the legal entity of the invoice do not have to match the way that the method of payment is set up in the legal entity of the payment.

4.  Repeat steps 1 through 3 for the remaining methods of payment.

5.  Switch to the next legal entity of the invoice and repeat steps 1 through 4.

## Set up default descriptions

You can define default descriptions for intercompany settlement vouchers. The default description is included on the due-to and due-from transactions during the cross-company settlement process.

1.  Click **Organization administration** \> **Setup** \> **Default descriptions**.

2.  Click **New** to create a description.

3.  In the **Description** column, select **Intercompany customer settlement**, select a language, and enter text.

4.  Click **New**.

5.  Select **Intercompany vendor settlement**, select a language, and enter text.

## See also

[About cross-company payment settlements](about-cross-company-payment-settlements.md)

[Scenario: Single-company and cross-company payment settlements](scenario-single-company-and-cross-company-payment-settlements.md)

[Select invoices to settle with payments on behalf of multiple legal entities](select-invoices-to-settle-with-payments-on-behalf-of-multiple-legal-entities.md)

  



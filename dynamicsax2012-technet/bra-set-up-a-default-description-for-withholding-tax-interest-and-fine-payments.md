---
title: (BRA) Set up a default description for withholding tax, interest, and fine payments
TOCTitle: (BRA) Set up a default description for withholding tax, interest, and fine payments
ms:assetid: a229d48e-d373-4e8c-8d5a-2dc73bf76d9d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710575(v=AX.60)
ms:contentKeyID: 49384474
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- default description
- fine payment
- interest payment
- withholding tax payment
- fine payment to customer
- fine payment to vendor
- interest payment ot customer
- interest payment to vendor
- withholding tax payment to vendor
- withholoding tax payment to customer
- witholding tax
---

# (BRA) Set up a default description for withholding tax, interest, and fine payments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Default descriptions** form to set up default descriptions and corresponding transaction texts for withholding tax, interest, and fine payments that are made to a vendor or customer. When a transaction for withholding tax, interest, or fine payments is posted to the ledger, the transaction text is also posted. The transaction text is printed on the day book and analytical ledger reports. You must use the %7 variable as part of the text. When the texts are printed on the reports, the %7 variable is replaced with the vendor name in purchase invoice transactions or the customer name in sales invoice transactions. For more information, see [(BRA) Setting up standard text in accounting transactions](bra-setting-up-standard-text-in-accounting-transactions.md).

## Set up a default description for withholding tax, interest, and fine payments to a vendor

1.  Click **Organization administration** \> **Setup** \> **Default descriptions**.

2.  Create a default description.

3.  In the **Description** field, select **Vendor - withholding tax**, **Vendor - interest**, or **Vendor - fine**.

4.  In the **Language** field, select a language.

5.  In the **Text** field, enter the text that is to be used as the default description. The text must include the %7 variable.

## Set up a default description for withholding tax, interest, and fine payments to a customer

1.  Click **Organization administration** \> **Setup** \> **Default descriptions**.

2.  Create a default description.

3.  In the **Description** field, select **Customer - withholding tax**, **Customer - interest**, or **Customer - fine**.

4.  In the **Language** field, select a language.

5.  In the **Text** field, enter the text that is to be used as the default description. The text must include the %7 variable.

## See also

[(BRA) Create and post a vendor payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-vendor-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[(BRA) Create and post a customer payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-customer-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[(BRA) Day book report (LedgerJournalDayBookReport\_BR)](https://technet.microsoft.com/en-us/library/jj710413\(v=ax.60\))

[(BRA) Analytical ledger report (LedgerJournalAnalytReasonReport\_BR)](https://technet.microsoft.com/en-us/library/jj710455\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


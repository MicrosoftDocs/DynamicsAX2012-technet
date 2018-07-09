---
title: (BRA) Set up journal descriptions for withholding tax, interest, and fine payments
TOCTitle: (BRA) Set up journal descriptions for withholding tax, interest, and fine payments
ms:assetid: 5ce01e29-6dc7-4299-a9e3-2268155a386f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710514(v=AX.60)
ms:contentKeyID: 49384407
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- journal text
- BRA
- Brazil
- fine payment
- interest payment
- withholding tax payment
---

# (BRA) Set up journal descriptions for withholding tax, interest, and fine payments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal descriptions** form to set up journal descriptions for withholding tax, interest, and fine payments. You can set up standard descriptions for journals by using defined variables. The variables are replaced by corresponding values when the journal is posted. You can use the following variables to set up journal descriptions for withholding tax, interest, and fine payments:

  - %1 – The payment date

  - %3 – The voucher number

  - %4 – The account number, based on the type of account: customer, vendor, bank, fixed asset, project, or ledger

  - %7 – The account name, based on the type of account

<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal descriptions**.

2.  Click **New** to create a journal description, and then in the **Identification** and **Search name** fields, enter an identification code and short name.

3.  In the **Description** field, enter the description and one or more of the variables to be displayed in the current journal.

## See also

[(BRA) Create and post a general journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-general-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[(BRA) Create and post a vendor payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-vendor-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[(BRA) Create and post a customer payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-customer-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


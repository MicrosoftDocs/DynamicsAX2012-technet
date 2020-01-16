---
title: (BRA) Create and post a customer payment journal with a default description for withholding tax, interest, and fine payments
TOCTitle: (BRA) Create and post a customer payment journal with a default description for withholding tax, interest, and fine payments
ms:assetid: 3fa7e68a-fcf4-4d31-88da-749feefb2d6b
ms:mtpsurl: https://technet.microsoft.com/library/JJ710475(v=AX.60)
ms:contentKeyID: 49384367
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- withholding tax
- interest
- BRA
- Brazil
- default description
- create customer payment journal
- customer payment journal
- fine payment
- post a customer payment journal
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a customer payment journal with a default description for withholding tax, interest, and fine payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal voucher** form to create and post a journal that has a default description for withholding tax, interest, and fine payments that are made to a customer. You can also use a payment proposal to post a customer payment that includes a default description. When you mark transactions for settlement or transfer payment proposal lines, the transaction type is identified by using the default description, and the corresponding text that you set up for the transactions is updated in the ledger. For withholding tax, interest, and fine payments, the transactions are updated with the transaction text that is set up for the **Customer - withholding tax**, **Customer - interest**, and **Customer - fine** descriptions. For payment proposals, the transactions are updated with the transaction text that is set up for the **Customer - payment, customer** description. For more information, see [(BRA) Set up a default description for withholding tax, interest, and fine payments](bra-set-up-a-default-description-for-withholding-tax-interest-and-fine-payments.md).

You must specify a journal description before you post a journal. When you post a journal, the %1, %3, %4, and %7 variables that are used in the journal description are replaced with the payment date, voucher number, account number, and account name. If the %2, %5, and %6 variables are used in the journal description, they are replaced with blank spaces. For more information, see [(BRA) Set up journal descriptions for withholding tax, interest, and fine payments](bra-set-up-journal-descriptions-for-withholding-tax-interest-and-fine-payments.md). After you post a journal, you can generate the day book and analytical ledger reports that contain the transaction text for the withholding tax, interest, and fine payments.

## Create and post a payment journal by using the Journal voucher form

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines**.

3.  In the **Account** field, select a customer account.

4.  Click **Functions** \> **Settlement**, and then select the **Mark** check box to mark transactions for settlement.

5.  Close the form.

6.  In the **Journal voucher** form, in the **Description** field, enter or select a journal description.

7.  Click **Validate** \> **Validate** to validate the journal.

8.  Click **Post** \> **Post** to post the journal.

## Create and post a customer payment by using a payment proposal

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines**.

3.  Click **Payment proposal** \> **Create payment proposal**, and then in the **Proposal type** field, select a proposal type.

4.  Enter other criteria for the proposal, and then click **OK**. For more information, see [Customer payment proposal (class form)](https://technet.microsoft.com/library/aa550814\(v=ax.60\)).

5.  Click **Transfer** to transfer the proposal lines to the payment journal.

6.  In the **Journal voucher** form, in the **Description** field, enter or select a journal description.

7.  Click **Validate** \> **Validate** to validate the journal.

8.  Click **Post** \> **Post** to post the journal.

## See also

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/library/aa556141\(v=ax.60\))

[Settle open transactions - customer (form)](https://technet.microsoft.com/library/aa558602\(v=ax.60\))

[(BRA) Day book report (LedgerJournalDayBookReport\_BR)](https://technet.microsoft.com/library/jj710413\(v=ax.60\))

[(BRA) Analytical ledger report (LedgerJournalAnalytReasonReport\_BR)](https://technet.microsoft.com/library/jj710455\(v=ax.60\))

  



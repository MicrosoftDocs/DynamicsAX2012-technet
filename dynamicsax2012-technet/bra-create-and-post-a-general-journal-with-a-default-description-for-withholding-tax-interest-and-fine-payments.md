---
title: (BRA) Create and post a general journal with a default description for withholding tax, interest, and fine payments
TOCTitle: (BRA) Create and post a general journal with a default description for withholding tax, interest, and fine payments
ms:assetid: ddf2a07f-642b-44f9-b707-9a0b2cfdc48a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ663953(v=AX.60)
ms:contentKeyID: 49384540
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- withholding tax
- interest
- general journal
- BRA
- Brazil
- default description
- create and post a general journal
- fine payments
---

# (BRA) Create and post a general journal with a default description for withholding tax, interest, and fine payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal voucher** form to create and post a journal that has a default description for withholding tax, interest, and fine payments that are made to a customer.

You must specify a journal description before you post a journal. When you post a journal, the %1, %3, %4, and %7 variables that are used in the journal description are replaced with the payment date, voucher number, account number, and account name. If the %2, %5, and %6 variables are used in the journal description, they are replaced with blank spaces. For more information, see [(BRA) Set up journal descriptions for withholding tax, interest, and fine payments](bra-set-up-journal-descriptions-for-withholding-tax-interest-and-fine-payments.md). After you post a journal, you can generate the day book and analytical ledger reports that contain the transaction texts for the withholding tax, interest, and fine payments.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Create a journal, and then click **Lines**.

3.  In the **Account type** field, select **Customer** or **Ledger**.

4.  Follow one of these steps, depending on the account type that you selected:
    
      - If the account type is **Customer**, click **Functions** \> **Settlement**, and then select the **Mark** check box to mark transactions for settlement. Close the form. In the **Journal voucher** form, in the **Offset account type** field, select **Bank**.
    
      - If the account type is **Ledger**, in the **Account** field, select an account number. In the **Debit** field, enter the amount to debit. Then, in the **Offset account type** and **Offset account** fields, select **Ledger** and the offset account for the transaction.

5.  In the **Description** field, select a journal description for the transaction.

6.  Click **Validate** \> **Validate** to validate the journal.

7.  Click **Post** \> **Post** to post the journal.

## See also

[Journal voucher - General journal (form)](https://technet.microsoft.com/en-us/library/aa591466\(v=ax.60\))

[(BRA) Set up a default description for withholding tax, interest, and fine payments](bra-set-up-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[(BRA) Day book report (LedgerJournalDayBookReport\_BR)](https://technet.microsoft.com/en-us/library/jj710413\(v=ax.60\))

[(BRA) Analytical ledger report (LedgerJournalAnalytReasonReport\_BR)](https://technet.microsoft.com/en-us/library/jj710455\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


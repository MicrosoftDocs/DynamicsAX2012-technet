---
title: (IND) Reverse TCS and post the payment journal
TOCTitle: (IND) Reverse TCS and post the payment journal
ms:assetid: d0e6883f-7027-42ee-a647-f0f2f0f89700
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664935(v=AX.60)
ms:contentKeyID: 49386265
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Reverse TCS and post the payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can activate bank parameters to cancel payments and reverse deposit slip transactions for the transferred journals.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Set up bank parameters

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Click **General**.

3.  Select the **Use review process for payment reversals** check box to specify if the journals should be used to review the checks that are pending reversal.

4.  Select the **Use review process for deposit slip payment cancellations** check box to specify if journals should be used to review the deposit slips receipts that are pending for cancellation.

## Post and transfer the journal

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines**.

2.  Create payment lines with information about the customer accounts and the amounts. Enter the correct bank account that the payment will be deposited to as the offset account on each line.

3.  Select the **Use a deposit slip** check box for all the payment lines that are to be included on a bank deposit slip.

4.  On the **Tax information** tab in the **Journal voucher** form, select the tax information details to attach to the transaction.

5.  Click **Post** to post and transfer the journal.

## Cancel payments and reverse deposit slip transactions

A payment journal is automatically created in the **Deposit slip payment cancellations** form. You need to post this journal to post the reversed entries. When you post this journal, all the voucher entries that were posted at the time of posting the original payment journal, including the taxes, will be reversed.

1.  Click **Cash and bank management** \> **Common** \> **Deposit slips**.

2.  Select the deposit slip number to cancel the payment.

3.  Click **Cancel payment**.

4.  Click **Ok** to cancel the payment and return to the **Deposit slip** form.

## See also

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj677901\(v=ax.60\))

  



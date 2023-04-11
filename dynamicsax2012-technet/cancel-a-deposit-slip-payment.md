---
title: Cancel a deposit slip payment
TOCTitle: Cancel a deposit slip payment
ms:assetid: af4ff158-a48e-4e53-8088-ab28a9188210
ms:mtpsurl: https://technet.microsoft.com/library/Gg243104(v=AX.60)
ms:contentKeyID: 37832525
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Cancel a deposit slip payment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can cancel a payment from a deposit slip by using two methods. In one method, cancellations are posted immediately when you click **Cancel payment** in the **Deposit slip** form. In the other method, when you click **Cancel payment** in the **Deposit slip** form, the reversal first is sent to the **Deposit slip payment cancellations** journal. A reviewer can then post or reject the cancellation. This topic describes both methods.

You might cancel a deposit slip payment if a customer payment is not valid. However, if a deposit slip has been reconciled in the bank statement, the payment cannot be canceled and must instead be reversed.


> [!NOTE]
> <P>To see which method is used, open the <STRONG>Bank parameters</STRONG> form. If the <STRONG>Use review process for deposit slip payment cancellations</STRONG> check box is selected, reversals are sent to the <STRONG>Deposit slip payment cancellations</STRONG> journal for review.</P>



## Cancel a posted deposit slip payment

1.  Click **Cash and bank management** \> **Common** \> **Deposit slips**.

2.  Select the single payment to cancel.
    

    > [!TIP]
    > <P>When you cancel a deposit slip payment, the single payment is canceled, not the whole deposit slip.</P>



3.  Click **Cancel payment**.

4.  Enter the date, and select a reason for the cancellation. If your organization uses the **Deposit slip payment cancellations** journal for reviews, you must also select a journal name.

5.  Click **OK** to post the cancellation or send the cancellation for review, depending on the method that your organization uses.

## Review the cancellation of a deposit slip payment

To review cancellations of deposit slip payments, follow these steps. You can approve and post the journal, or you can reject the cancellation.

1.  Click **Cash and bank management** \> **Journals** \> **Deposit slip payment cancellations**.

2.  Select the journal to review, and then click **Lines**.

3.  Review the cancellation of the deposit slip payment, and then select one of the following options:
    
      - To approve and post the cancellation journal, click **Post** \> **Post**, or click **Post** \> **Post and transfer**.
    
      - To reject the cancellation, click **Delete**.
        

        > [!NOTE]
        > <P>When you delete a journal, the cancellation of the deposit slip payment is removed from the review journal, but the original transaction is not removed from the <STRONG>Deposit slip</STRONG> form.</P>



## Results of posting a payment

When you post a cancellation, the following actions occur:

  - The original customer payment from the customer invoice is unapplied. In other words, the settlement is reversed. The settlement that is reversed is the payment that was settled when you posted the reversing entry that had **Customer** as the offset account for the **Bank** account type.

  - A transaction is posted to the customer account for the canceled payment, and the canceled payment is settled against the original payment. The **Last settlement voucher** field on the original customer payment is updated to reflect the voucher number of the reversed transaction. The reversed transaction is the transaction that has **Customer** as the offset account for the **Bank** account type.

  - The **Canceled** field is selected for the deposit slip transaction.

  - The reversal voucher is posted against the bank account in which the payment was originally deposited.

  - The reversal voucher is posted to the general ledger.

  - A deposit slip transaction that was reversed is posted by using the same deposit slip number as the original deposited payment.

  - The **Posted** field is selected in the **Deposit slip payment cancellations** journal.

  - If customer invoices in multiple legal entities, or centralized payments, were related to the voucher that you canceled, the original settlement is reversed. The original settlement includes the settlement between the original voucher transaction and all documents in all legal entities in which the voucher was settled.


> [!NOTE]
> <P>When you cancel a deposit slip payment for an intercompany transaction, the offsetting entries come from the intercompany accounting setup, not from the original transaction.</P>



## See also

[Deposit slip payment cancellations lines (form)](https://technet.microsoft.com/library/hh242809\(v=ax.60\))

  



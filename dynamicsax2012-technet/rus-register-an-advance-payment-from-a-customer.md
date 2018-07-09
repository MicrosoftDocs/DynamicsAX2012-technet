---
title: (RUS) Register an advance payment from a customer
TOCTitle: (RUS) Register an advance payment from a customer
ms:assetid: 78046714-b31c-4c71-ad73-6c35d50c72ed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678376(v=AX.60)
ms:contentKeyID: 49387606
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Register an advance payment from a customer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  On the **Overview** tab, press CTRL+N to create a new line, and enter the required details.

3.  In the **Date** field, select the date of the payment.

4.  In the **Account** field, select the customer account number.

5.  In the **Description** field, select the transaction text.

6.  In the **Credit** field, enter the sum of the payment.

7.  In the **Offset account type** field, select the account type for the offset transaction.

8.  In the **Offset account** field, select the account number for the offset account type.

9.  In the **Currency** field, select the payment currency.

10. Click the **Payment** tab, and then select the **Prepayment journal voucher** check box.

11. Select the **Automatically facture creation** check box to automatically create a facture when posting prepayments.
    

    > [!NOTE]
    > <P>You can set the default value in the <STRONG>Accounts receivable parameters</STRONG> form. If the check box is not marked, the facture on prepayment is created in postponed mode.</P>



12. Click **Post** \> **Post** to post the advance payment to the journal.
    

    > [!NOTE]
    > <P>After the advance payment is registered, a facture is created automatically, and is posted in the sales book. The number for the facture is based on the number sequence that is set up in the <STRONG>General ledger parameters</STRONG> form for <STRONG>Prepayment facture</STRONG>, on the <STRONG>Number sequences</STRONG> tab.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


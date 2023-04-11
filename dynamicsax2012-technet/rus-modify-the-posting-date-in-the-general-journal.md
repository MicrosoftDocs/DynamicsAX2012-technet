---
title: (RUS) Modify the posting date in the general journal
TOCTitle: (RUS) Modify the posting date in the general journal
ms:assetid: 2d546d50-1b0c-4953-8480-d0ca0fcaf897
ms:mtpsurl: https://technet.microsoft.com/library/JJ665239(v=AX.60)
ms:contentKeyID: 49387329
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- general journal
- (RUS)
- (RUS) Modify the posting date in the general journal
- posting date
audience: Application User
ms.search.region: Russia
---

# (RUS) Modify the posting date in the general journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can settle vendor payments by using dimension control. If the dimension set that is specified in the **Vendor posting profiles** form does not match the dimension set that is specified for the transaction, the settlement is canceled. You can also settle payments for customers and advance holders by using dimension control.


> [!NOTE]
> <P>When different dimension sets are specified for two transactions, settlement transactions are controlled by the summary set.</P>
> <P>For example, you want to settle a payment transaction and an invoice transaction. For the payment transaction, you specify a posting profile that has dimension set D1. Dimension set D1 contains the d1 and d2 dimensions for control. For the invoice transaction, you specify a posting profile that has dimension set D2. Dimension set D2 contains the d2, d3, and d4 dimensions for control. When transactions are settled, transactions are controlled by the summary set d1, d2, d3, and d4.</P>



Use this procedure to validate and modify the posting date before you post a general ledger journal.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Create a new journal.

3.  In the **Name** field, select the name of the journal.
    

    > [!NOTE]
    > <P>The date in the <STRONG>Date</STRONG> field is set by the system.</P>



4.  Click **Lines** to open the **Journal voucher** form.

5.  Press CTRL+N to create a new journal line, and then enter the required details.

6.  In the **Account type** field, select the type of account.

7.  In the **Account** field, select the account number.

8.  Specify the debit amount in the **Debit** field, or specify the credit amount in the **Credit** field.

9.  In the **Offset account type** and **Offset account** fields, select the type of offset account and the offset account number.

10. Click **Functions** \> **Change date** to open the **Change date** form.

11. In the **Date of journal** field, select the date when the journal lines are posted.

12. Click **OK** to close the form.

13. In the **Journal voucher** form, click **Validate** \> **Validate** to validate the journal.
    

    > [!NOTE]
    > <P>If you selected the <STRONG>Posting date control</STRONG> check box in the <STRONG>Journal names</STRONG> form, and if lines have different dates, the journal is not validated.</P>



14. Click **Post** \> **Post** to post the journal.

  



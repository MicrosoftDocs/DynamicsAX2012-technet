---
title: (EEUR) Settle advance holder balances
TOCTitle: (EEUR) Settle advance holder balances
ms:assetid: a1a58b52-26e1-4cb4-b24a-dfc6771a4202
ms:mtpsurl: https://technet.microsoft.com/library/JJ911002(v=AX.60)
ms:contentKeyID: 51554522
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advance holder
- advance holder transactions
- settle advance holder
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Settle advance holder balances 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to settle advance holder balances. When you settle advance holder balances, journal entries for closing the advance holder balances are created in the general journal.

You can close balances for an advance holder in the following ways:

  - Close through cash. For more information, see [(RUS) Close via cash (form)](https://technet.microsoft.com/library/jj711592\(v=ax.60\)).

  - Close through a bank. For more information, see [(RUS) Close via bank (form)](https://technet.microsoft.com/library/jj665454\(v=ax.60\)).

## Close through cash

1.  Click **Accounts payable** \> **Inquiries** \> **Advance holders** \> **Balance**.

2.  In the **To date** field, enter the date to obtain advance holder balances.

3.  Click **Balance closing**, and then select **Close via cash**.

4.  In the **Date of payment** field, enter the date of payment.

5.  In the **Amount to be transferred.** field, enter the balance amount while closing.
    

    > [!NOTE]
    > <P>The amount that is indicated in the <STRONG>Amount</STRONG> field in the <STRONG>Balance</STRONG> form is displayed by default.</P>



6.  Select the **Automatic** check box to create and post the slip journal automatically.
    

    > [!NOTE]
    > <P>If the <STRONG>Automatic</STRONG> check box is cleared, a journal is created automatically, and the journal number is displayed. You can also enter advance holder transactions manually by using the general journal or the slip journal.</P>



7.  Click **OK** to generate the slip journal.
    

    > [!NOTE]
    > <P>After the slip journal is processed, if the amount in the <STRONG>Amount to be transferred.</STRONG> field is negative, a disbursement slip is generated for the advance holder when the balances are closed. If the amount in the <STRONG>Amount to be transferred.</STRONG> field is positive, a reimbursement slip is generated. For more information, see <A href="eeur-generate-a-cash-reimbursement-and-disbursement-slip.md">(EEUR) Generate a cash reimbursement and disbursement slip</A>.</P>



## Close through a bank

The procedure for closing balances through a bank is similar to the procedure for closing through cash. You can set up the code for the journal and the bank in the **Advance holders** area in the **Accounts payable parameters** form.


> [!NOTE]
> <P>In the <STRONG>Balance</STRONG> form, you must click <STRONG>Balance closing</STRONG>, and then select <STRONG>Close via bank</STRONG> to open the <STRONG>Close via bank</STRONG> form.</P>



## See also

[(EEUR) Create and post vendor invoices with advance holder details](eeur-create-and-post-vendor-invoices-with-advance-holder-details.md)

[(EEUR) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj720358\(v=ax.60\))

  



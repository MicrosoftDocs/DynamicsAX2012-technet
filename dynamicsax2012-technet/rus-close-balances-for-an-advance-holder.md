---
title: (RUS) Close balances for an advance holder
TOCTitle: (RUS) Close balances for an advance holder
ms:assetid: c688100a-3e23-47ad-913d-b25f81963b4c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711601(v=AX.60)
ms:contentKeyID: 49387925
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Close balances for an advance holder [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can close balances for an advance holder in one of the following ways:

  - Close via cash

  - Close via bank


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Closing via cash

1.  Click **Accounts payable** \> **Inquiries** \> **Advance holders** \> **Balance**.

2.  In the **To date** field, enter the date to obtain advance holder balances.

3.  Click **Balance closing**, and then select **Close via cash**.

4.  In the **Date of payment** field, enter the date of payment.

5.  In the **Amount to be transferred** field, enter the balance amount while closing.
    

    > [!NOTE]
    > <P>The amount indicated in the <STRONG>Amount</STRONG> field in the <STRONG>Balance</STRONG> form is displayed by default.</P>



6.  Select the **Automatic** check box to create and post the slip journal automatically.
    

    > [!NOTE]
    > <P>If the <STRONG>Automatic</STRONG> check box is cleared, a journal will be created automatically, and the journal number is displayed. This journal must be posted manually.</P>



7.  Click **OK** to generate the slip journal.
    

    > [!NOTE]
    > <P>After the slip journal is processed, either a disbursement slip (if the amount in the <STRONG>Amount to be transferred</STRONG> field is negative) will be generated, or a reimbursement slip (if the amount in the <STRONG>Amount to be transferred</STRONG> field is positive) will be generated for the advance holder when the balances are closed.</P>



8.  Press CTRL+S or close the form.

## Closing via bank

The procedure for closing balances through a bank is similar to closing through cash. You can set up the code for the journal and the bank on the **Advance holders** tab in the **Accounts payable parameters** form.


> [!NOTE]
> <P>In the <STRONG>Balance</STRONG> form, you must click <STRONG>Balance closing</STRONG>, and then select <STRONG>Close via bank</STRONG> to open the <STRONG>Close via bank</STRONG> report.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


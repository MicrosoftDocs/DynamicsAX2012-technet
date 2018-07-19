---
title: (IND) Reverse TDS payments and post the payment journal
TOCTitle: (IND) Reverse TDS payments and post the payment journal
ms:assetid: 11449c7d-d5a6-412d-8e5f-7000f7d94b5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664492(v=AX.60)
ms:contentKeyID: 49385571
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Reverse TDS payments and post the payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can reverse TDS payments that have been made by using checks.

## Set up bank parameters

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Click the **General** tab.

3.  Select the **Use review process for payment reversals** check box to specify if journals should be used to review the checks that are pending reversal.

4.  Press CTRL+S or close the form.

## Generate a check and post the journal

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  On the **Action Pane**, on the **Setup** tab, click **Checks**, and then click **Create checks**.

3.  Enter the first check number in the check series and the number of checks to create, and click **OK**.

4.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Select or create a journal, and then click **Lines**.

5.  Enter information about the date, account, and amount.

6.  On the **Tax information** tab, select the tax information details to attach to the transaction.

7.  Click **Post** to post and transfer the journal.

## Reverse payments

A payment journal is automatically created in the **Deposit slip payment cancellations** form. You need to post this journal for the reversal entries to be posted. When you post this journal, all the voucher entries that were posted at the time of posting the original payment journal, including the taxes, will be reversed as is.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. On the **Action Pane**, on the **Manage payments** tab, click **Checks**.
    
    –or–
    
    Click **Cash and bank management** \> **Common** \> **Checks**.

2.  Select the transaction to be reversed and click **Payment reversal**.
    

    > [!NOTE]
    > <P>For more information, see <A href="reverse-a-posted-check.md">Reverse a posted check</A>.</P>



3.  Press CTRL+S or close the form.

## See also

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj677901\(v=ax.60\))

  



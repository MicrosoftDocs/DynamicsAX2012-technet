---
title: (JPN) Set up a T-account journal and T-accounts
TOCTitle: (JPN) Set up a T-account journal and T-accounts
ms:assetid: 019f4fff-944b-41a4-b84e-4ffa40820a10
ms:mtpsurl: https://technet.microsoft.com/library/JJ710995(v=AX.60)
ms:contentKeyID: 49386408
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- journal
- voucher
- (JPN)
- Japan
- T-account
- t-account journal
- JP - 00005
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up a T-account journal and T-accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can enter transaction credit and debit amounts in a T-account journal. A debit line and a credit line can exist for the same transaction. Use the following procedures to enable T-account journals and to create a T-account journal.


> [!NOTE]
> <P>T-account journals can be used only in general journals.</P>



## Enable T-account journals

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Ledger**, and then on the **General** FastTab, select the **T-account (JP)** check box to enable journal entries in the T-account format.

## Set up a T-account journal

1.  Click **General ledger** \> **Journals** \> **General journal**. Select a journal in the list, or click **New** to create a journal. Click **Lines**.

2.  In the **Journal voucher** form, click **T-account (JP)**.

3.  On the **Debit** side of the form, do the following:
    
    1.  In the **Date** field, enter the transaction date.
    
    2.  In the **Account** field, select the account to post the debit amount to.
    
    3.  In the **Debit** field, enter the debit amount.

4.  On the **Credit** side of the form, do the following:
    
    1.  Press CTRL+N to create a new line.
    
    2.  In the **Account** field, select the account to post the credit amount to.
    
    3.  In the **Credit** field, enter the credit amount.

5.  In the **Sales tax group** and **Item sales tax group** fields, select the sales tax group and the item sales tax group to calculate taxes for the debit and credit amounts.

6.  Close the form. The payment lines that you enter in the **T-account journal voucher** form are transferred to the **Journal voucher** form.
    

    > [!NOTE]
    > <P>The debit and credit entries that appear on the same line in the <STRONG>T-account journal voucher</STRONG> form appear in two separate lines in the <STRONG>Journal voucher</STRONG> form. If you delete a line in the <STRONG>T-account journal voucher</STRONG> form, it is deleted from the <STRONG>Journal voucher</STRONG> form.</P>



7.  Select the transaction and then click **Post** \> **Post** to post the transaction.

## See also

[(JPN) T-account journal voucher (form)](https://technet.microsoft.com/library/jj711040\(v=ax.60\))

[(JPN) Journal voucher - General journal (modified form)](https://technet.microsoft.com/library/jj711027\(v=ax.60\))

  



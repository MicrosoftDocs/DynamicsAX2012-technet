---
title: (POL) Reverse a customer transaction
TOCTitle: (POL) Reverse a customer transaction
ms:assetid: 801cf1a2-7284-4f77-bbb6-347ce0877085
ms:mtpsurl: https://technet.microsoft.com/library/JJ678265(v=AX.60)
ms:contentKeyID: 49386987
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Reverse a customer transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can reverse a customer transaction as correction to a customer invoice or other sales transaction. Before you post a reversal of a customer transaction, set up parameters that define how the reversal is posted to the General ledger.


> [!NOTE]
> <P>You cannot reverse transactions that are posted in a closed fiscal year.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Set parameters for corrections

Set up parameters for customer credits in the **Accounts receivable parameters** form.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, click the **Updates** link.

3.  To enable credit notes as corrections to customer invoices, select the **Credit note as correction** check box.

4.  Click the **Number sequences** link. In the **Reference** field, locate the **Sales credit note** row, and then in the **Number sequence code** field, select the number sequence to use for credit notes.

## Enter a correction

Use this procedure to reverse a customer transaction.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. On the **All customers** list page, on the **Action Pane**, click **New** to create a customer account, or select an existing customer.

2.  In the **Customers** form, on the **Action Pane**, on the **Customer** tab, click **Transactions**.

3.  In the **Customer transactions** form, select the transaction to reverse.

4.  On the top menu, click **Reverse transaction**.

5.  In the **Transaction reversal** form, in the **Reversal posting date** field, select the date on which to post the transaction reversal.

6.  Enter a reason code and an optional reason comment for the reversal.
    

    > [!NOTE]
    > <P>Your organization might require a reason code for a transaction reversal.</P>



7.  Click **OK** to complete the reversal.

## See also

[(POL) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj678183\(v=ax.60\))

  



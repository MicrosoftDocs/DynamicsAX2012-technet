---
title: (CZE) Reverse a customer transaction
TOCTitle: (CZE) Reverse a customer transaction
ms:assetid: 37beda58-750c-43e2-9ca2-f625f45a9468
ms:mtpsurl: https://technet.microsoft.com/library/JJ677503(v=AX.60)
ms:contentKeyID: 49384808
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Reverse a customer transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Customer transactions that are reversed can be posted as correction transactions in the general ledger.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  On the **Ledger** tab, under the **Transaction reversal** field group, select the **Correction** check box to post the customer transaction as a correction.

3.  Press CTRL+S or close the form.

4.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. On the **Action Pane**, click **Customer** to create a customer record, or select a customer record, and then click **Edit**.

5.  Click **Transactions** to open the **Customer transactions** form.

6.  Select the transaction to reverse.

7.  Click **Reverse transaction**.
    

    > [!NOTE]
    > <P>For more information, see <A href="reverse-a-transaction.md">Reverse a transaction</A>.</P>



8.  In the **Reversal posting date** field, select the date for reversing the transaction.

9.  In the **Reason code** field, select a reason code.

10. In the **Reason comment** field, enter a reason comment.

11. Click **OK** to return to the **Customer transactions** form.
    

    > [!NOTE]
    > <P>The transaction is displayed as a reversed transaction with a negative sign (-) in the <STRONG>Amount currency</STRONG> field. The <STRONG>Correction</STRONG> check box on the <STRONG>General</STRONG> tab is automatically selected for the transaction that is reversed.</P>



12. Press CTRL+S or close the form.

  



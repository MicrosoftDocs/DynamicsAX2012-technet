---
title: (CZE) Reverse a vendor transaction
TOCTitle: (CZE) Reverse a vendor transaction
ms:assetid: 6d538504-4a47-4705-9491-6b30711df559
ms:mtpsurl: https://technet.microsoft.com/library/JJ677563(v=AX.60)
ms:contentKeyID: 49384866
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Reverse a vendor transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Vendor transactions that are reversed can be posted to the general ledger as correction transactions.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  On the **Ledger** tab, under the **Transaction reversal** field group, select the **Correction** check box to post the vendor transaction as a correction.

3.  Press CTRL+S or close the form.

4.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, click **Vendor** to create a vendor record, or select a vendor record, and then click **Edit**.

5.  Select a vendor account.

6.  Click **Transactions** to open the **Vendor transactions** form.

7.  Select the transaction to reverse.

8.  Click **Reverse transaction**.
    

    > [!NOTE]
    > <P>For more information, see <A href="reverse-a-transaction.md">Reverse a transaction</A>.</P>



9.  In the **Reversal posting date** field, select the date for reversing the transaction.

10. Click **OK** to return to the **Vendor transactions** form.
    

    > [!NOTE]
    > <P>The transaction is displayed as a reversed transaction with a negative sign (-) in the <STRONG>Amount currency</STRONG> field. The <STRONG>Correction</STRONG> check box on the <STRONG>General</STRONG> tab is automatically selected for the transaction that is reversed.</P>



11. Press CTRL+S or close the form.

## See also

[(CZE) Reverse a customer transaction](cze-reverse-a-customer-transaction.md)

  



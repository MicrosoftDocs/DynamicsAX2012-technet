---
title: (RUS) Register an incoming bank payment from a customer
TOCTitle: (RUS) Register an incoming bank payment from a customer
ms:assetid: ff71cb73-90d3-48c0-a98d-abeda7d706ff
ms:mtpsurl: https://technet.microsoft.com/library/JJ678665(v=AX.60)
ms:contentKeyID: 49388147
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Register an incoming bank payment from a customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines**.

2.  Create a new journal line.

3.  In the **Date** field, select the date of the payment.

4.  In the **Account** field, select the customer code.
    

    > [!NOTE]
    > <P>If a vendor payment, such as a refund, is being made, select <STRONG>Vendor</STRONG> in the <STRONG>Account type</STRONG> field on the <STRONG>General</STRONG> tab. On the <STRONG>Overview</STRONG> tab in the <STRONG>Account</STRONG> field, select the vendor code.</P>



5.  In the **Transaction text** field, enter or select the transaction text.

6.  In the **Credit** field, enter the sum of the payment.

7.  In the **Offset account type** field, select **Bank**.

8.  In the **Offset account** field, select the bank account.

9.  In the **Currency** field, select the payment currency.

10. On the **General** tab, in the **Contracts group** field, select the contract group.
    

    > [!NOTE]
    > <P>If the payment is a prepayment, select the <STRONG>Prepayment</STRONG> check box on the <STRONG>Payment</STRONG> tab. The <STRONG>Sales tax group</STRONG>, <STRONG>Item sales tax group</STRONG>, and <STRONG>Posting profile</STRONG> fields will be entered automatically to calculate VAT for prepayment.</P>



11. Click **Post**, and then click **Post** again to post the incoming payment.
    
    When the journal is posted, transactions will be generated for the bank account, customer account, and ledger. The debit account will be the account in the ledger configured for the bank account. The credit account will be determined by the posting profile that is selected for the customer.

  



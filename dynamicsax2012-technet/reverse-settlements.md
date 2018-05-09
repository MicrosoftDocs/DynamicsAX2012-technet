---
title: Reverse settlements
TOCTitle: Reverse settlements
ms:assetid: 71fa746c-b524-4990-972c-e4cc6160922e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549970(v=AX.60)
ms:contentKeyID: 36655933
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Reverse settlements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Closed transaction editing in several currencies** form to reverse settlements for customers or vendors. You might do this if the wrong date or settlement amount was used. When you reverse a settlement, all transaction distributions that were involved in settling an invoice with a payment are reversed, such as general ledger postings, exchange rate gains or losses, penny differences, and cash discount transactions.


> [!NOTE]
> <P>The original invoice and payment transactions are not reversed automatically when you reverse settlements. For information about how to reverse or settle those transactions, see <A href="reverse-a-transaction.md">Reverse a transaction</A> or <A href="settle-transactions-with-payments.md">Settle transactions with payments</A>.</P>



1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a customer or vendor account whose closed transactions you are reversing.

3.  If you are working with a customer account, click the **Collect** tab on the **Action Pane**, and then click **Closed transaction editing**.
    
    –or–
    
    If you are working with a vendor account, click **Invoice** on the **Action Pane**, and then click **Closed transaction editing**.

4.  In the **Settlement reversal posting date** field, select how to determine the settlement reversal posting date to use:
    
      - **Latest date** – Use the date of the most recent original settlement.
    
      - **Today's date** – Use today's date.
    
      - **Selected date** – Use the date that you specify. The date must be the same as, or later than, the date of the most recent transaction that is involved in the settlement.

5.  Select the line that contains the settlement to reverse.

6.  Select the **Mark** check box for an invoice or payment. The transaction that offsets the transaction that you have marked is selected automatically.
    

    > [!NOTE]
    > <P>To preview the transactions that will be reversed, select a line, and then click <STRONG>Inquiry</STRONG> &gt; <STRONG>Voucher</STRONG>.</P>



7.  Click **Reverse**.

## See also

[Key tasks: Prepayments](key-tasks-prepayments.md)

[Reverse a transaction](reverse-a-transaction.md)

[Revoke a reversed transaction](revoke-a-reversed-transaction.md)

[Settle transactions with payments](settle-transactions-with-payments.md)

[Specify the cross rate](specify-the-cross-rate.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


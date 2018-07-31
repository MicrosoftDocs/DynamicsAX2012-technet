---
title: Revoke a reversed transaction
TOCTitle: Revoke a reversed transaction
ms:assetid: 8bb3c3c4-cae0-498d-9693-e1601ed24434
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498253(v=AX.60)
ms:contentKeyID: 36058473
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Revoke a reversed transaction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You might have to revoke a transaction that has been reversed. For example, you must revoke a reversed transaction if you have to change the transaction date of the original posting.


> [!NOTE]
> <P>If you revoke a reversed transaction that involves a fixed asset, the field values of the fixed asset are reset to their previous values. For example, an asset status might be changed from <STRONG>Not yet acquired</STRONG> to <STRONG>Open</STRONG>.</P>
> <P>You cannot revoke a reversed <STRONG>Transfer from reserve</STRONG> transaction if you already applied the amount to another asset. For example, if you create a 1,000 <STRONG>Transfer from reserve</STRONG> transaction for asset A, reverse that transaction, and then attempt to create a new 1,000 <STRONG>Transfer from reserve</STRONG> transaction for asset B, you cannot revoke the reversal transaction for asset A, because the 1,000 is already allocated to asset B.</P>



1.  Open the form.
    
      - Click **General ledger** \> **Common** \> **Main accounts**.
    
      - Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
      - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
      - Click **Fixed assets** \> **Inquiries** \> **Fixed asset transactions**.
    
      - Click **Fixed assets** \> **Inquiries** \> **Depreciation book transactions**.

2.  Select an account, fixed asset transaction, or depreciation book transaction.

3.  If you are working with a main account, click **Posted** on the **Action Pane**. If you are working with a fixed asset transaction or depreciation book transaction, go to the next step. Otherwise, click **Transactions**.

4.  Select the reversed or original transaction to revoke the reversed transaction for.
    
    A check mark in the **Reversed** check box on the **History** tab indicates that you selected a reversed transaction.

5.  Click **Reverse transaction**.

6.  Select the date of posting for the revocation transaction and then click **OK**.
    
    The reversed transaction and all transactions that were created for the reversal are revoked. The revocation transactions share the same trace number.

7.  To view all the transactions that have the same trace number, select a transaction and then click **Reversed tracing**.
    
    The **Reversed tracing** button is available only for reversed transactions and reversed transactions that have been revoked.

## See also

[Reverse a transaction](reverse-a-transaction.md)

[About financial reason codes](about-financial-reason-codes.md)

  



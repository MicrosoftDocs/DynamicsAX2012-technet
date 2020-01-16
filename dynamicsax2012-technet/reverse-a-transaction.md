---
title: Reverse a transaction
TOCTitle: Reverse a transaction
ms:assetid: 1f711ff8-4cad-493f-9a98-8ff1a5439f15
ms:mtpsurl: https://technet.microsoft.com/library/Aa496782(v=AX.60)
ms:contentKeyID: 36056151
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Reverse a transaction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The transaction reversal process reverses the original transaction and all related transactions that were created when the original transaction was posted. Before you reverse a transaction for the first time, select a number sequence for the **Transaction reversal** and **Trace number** references in the **Number sequences** area of the **General ledger parameters** form.

## About reversing transactions

The following requirements apply when you reverse transactions:

  - You must perform the reversal where the transaction originated. For example, you cannot reverse from General ledger if the transaction originated in Accounts payable.

  - You must reverse transactions in the correct sequential order. For example, if you applied a cash receipt to a **Disposal - sale** transaction, you must reverse the receipt settlement before you reverse the **Disposal - sale** transaction.

## Reversals that affect fixed assets

The following additional requirements apply when you reverse a transaction that affects a fixed asset:

  - For **Provision for reserve**, **Transfer from reserve**, or **Disposal - sale** type reversals, the fixed asset must have a status of **Open** or **Sold**. For **Disposal - scrap** type reversals, the fixed asset must have a status of **Open** or **Scrapped**. For all other asset reversals, the asset involved in the transaction must have a status of **Open**.

  - You can reverse the transfer of a fixed asset if it is the most recent transfer of the fixed asset. You cannot reverse a transfer that occurred before the most recent transfer, and you cannot reverse a transfer that has already been reversed. For more information, see [Transfer fixed assets](transfer-fixed-assets.md).


> [!NOTE]
> <P>Fixed asset transaction reversals reset fixed asset field values to their previous values. For example, an asset status might be reset from <STRONG>Open</STRONG> to <STRONG>Not yet acquired</STRONG>, or the <STRONG>Depreciation periods</STRONG> field might be reset from <STRONG>119</STRONG> to <STRONG>120</STRONG>.</P>



## Reverse a transaction

1.  Click **General ledger** \> **Common** \> **Main accounts**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Fixed assets** \> **Inquiries** \> **Fixed asset transactions**.
    
    –or–
    
    Click **Fixed assets** \> **Inquiries** \> **Depreciation book transactions**.
    

    > [!NOTE]
    > <P>Invoices that are partially paid or settled (fully paid) cannot be reversed. You must reverse the settlement first, and then you can reverse the transaction. For more information, see <A href="reverse-settlements.md">Reverse settlements</A>.</P>



2.  Select an account, fixed asset transaction, or depreciation book transaction.

3.  If you are working with a main account, click **Posted** on the **Action Pane**. If you are working with a fixed asset transaction or depreciation book transaction, go to the next step. Otherwise, click **Transactions**.

4.  Select the transaction to reverse.

5.  Click **Reverse transaction**.

6.  Select the posting date for the reversed transaction. The date cannot be before the original posting date or in a closed period.
    

    > [!NOTE]
    > <P>The parameter settings for the module determine whether you must enter a reason for the reversal. For more information, see <A href="about-financial-reason-codes.md">About financial reason codes</A>.</P>



7.  Click **OK**.

## See also

[Revoke a reversed transaction](revoke-a-reversed-transaction.md)

[Examples: Depreciation effects with reversals](examples-depreciation-effects-with-reversals.md)

[Transfer fixed assets](transfer-fixed-assets.md)

  



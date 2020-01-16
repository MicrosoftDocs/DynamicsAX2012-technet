---
title: Place a General ledger transaction on hold
TOCTitle: Place a General ledger transaction on hold
ms:assetid: d96eea23-327e-48c4-8948-1e7ddf7ed428
ms:mtpsurl: https://technet.microsoft.com/library/Gg213714(v=AX.60)
ms:contentKeyID: 36059651
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- general ledger
- general ledger transaction hold
- hold general ledger transaction
- general ledger transaction
- hold transaction
audience: Application User
ms.search.region: Global
---

# Place a General ledger transaction on hold 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To help make data entry flexible, you can enter a transaction on one date, and then put it on hold to prevent users from posting it until a specified date. This is useful if you have an agreement with someone, such as a customer or your manager, about when a transaction can be posted.

To prevent a transaction from being posted until a specified date, enter a release date until which the transaction is on hold. You can edit and save transactions that are on hold, but you cannot post them unless you first remove the hold.

## To place a General ledger transaction on hold

1.  Click **General ledger** \> **Journals** \> **General journal**. Select a journal and then click **Lines**.
    
    –or–
    
    Click **Fixed assets** \> **Journals** \> **Fixed assets**. Select a journal and then click **Lines**.
    
    –or–
    
    Click **Fixed assets** \> **Journals** \> **Fixed asset budget**. Select a journal and then click **Lines**.
    
    –or–
    
    Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation books**. Select a journal and then click **Lines**.
    
    –or–
    
    Click **Fixed assets** \> **Journals** \> **Inventory to fixed assets**. Select a journal and then click **Lines**.
    
    –or–
    
    Click **General ledger** \> **Journals** \> **Elimination**. Select a journal and then click **Lines**. Select a journal voucher and then click **Proposals** \> **Elimination proposal**.
    
    –or–
    
    Click **General ledger** \> **Periodic** \> **Process allocation request**.
    
    –or–
    
    Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Online\]**.

2.  In the **Release date** field, enter the date when the transaction is no longer on hold and becomes available for posting.
    
    To remove a hold on a transaction, you can clear the entry in this field.

3.  Press CTRL+S to save the transaction.

## About the release date in different time zones

If your organization includes users who work across multiple time zones, the date and time when a transaction is released from a hold is based on the time zone of the user who most recently modified the **Release date** value. Because the transactions are released at midnight on the specified date in that user's time zone, the actual date and time of the release will be adjusted accordingly for users in other time zones.

**Example**

On December 31 in New York, a user puts a transaction on hold at noon Eastern Time, and enters a release date of January 1 (the next day). The transaction is set up to be on hold until midnight Eastern Time. Therefore, the user must wait 12 hours for the transaction to be released.

Users in London, which is five hours ahead of New York, must also wait 12 hours. However, because the transaction was put on hold at 17:00 Greenwich Mean Time on December 31, the transaction will not be released until 05:00 Greenwich Mean Time on January 1.

For users in Seattle, which is three hours behind New York, the transaction was put on hold at 09:00 Pacific Time on December 31. When the transaction is released 12 hours later (at 21:00 Pacific Time), it will still be December 31 for these users.

## See also

[Place an Accounts receivable transaction on hold](place-an-accounts-receivable-transaction-on-hold.md)

  



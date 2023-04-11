---
title: Place an Accounts receivable transaction on hold
TOCTitle: Place an Accounts receivable transaction on hold
ms:assetid: 6d432440-ea98-432f-b30c-85385eb33244
ms:mtpsurl: https://technet.microsoft.com/library/Gg231801(v=AX.60)
ms:contentKeyID: 36058025
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Place an Accounts receivable transaction on hold 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To make data entry flexible, you can enter a transaction on one date, and then put it on hold to prevent users from posting it until a specified date. This is useful if you have an agreement with a customer about when a transaction can be posted.

To prevent a transaction from being posted until a specified date, enter a release date, until which the transaction is on hold. You can edit and save transactions that are on hold, but you cannot post them unless you first remove the hold.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**. Double-click a free text invoice.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**. Enter or select a journal and then click **Lines**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment transfers**.
    
    –or–
    
    Click **Lines** in any bill of exchange journal (**Accounts receivable** \> **Journals** \> **Bill of exchange**).

2.  In the **Release date** field, enter the date when the transaction is no longer on hold and becomes available for posting.
    
    To remove a hold on a transaction, clear the entry in this field. Any user can clear the release date, regardless of who first entered it.

3.  Press CTRL+S to save the transaction.

## About the release date in different time zones

For users in multiple time zones, the transaction release date and time depend on the time zone of the user who last modified the **Release date** field. The transactions are released at midnight on the specified date in that user's time zone. Therefore, the actual date and time of the release will be adjusted accordingly for users in other time zones.

**Example**

On December 31 in New York, a user puts a transaction on hold at noon Eastern Time, and enters a release date of January 1. The transaction is set up to be on hold until midnight Eastern Time. Therefore, the user must wait 12 hours for the transaction to be released.

Users in London, which is five hours ahead of New York, must also wait 12 hours. The transaction was put on hold at 17:00 Coordinated Universal Time (UTC) on December 31. Therefore, the transaction will not be released until 05:00 UTC on January 1.

For users in Seattle, which is three hours behind New York, the transaction was put on hold at 09:00 Pacific Time on December 31. When the transaction is released 12 hours later (at 21:00 Pacific Time), it will still be December 31 for these users.

## See also

[Free text invoice (form)](https://technet.microsoft.com/library/aa556897\(v=ax.60\))

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/library/aa556141\(v=ax.60\))

[Payment transfers (form)](https://technet.microsoft.com/library/aa617641\(v=ax.60\))

[Journal voucher - Bill of exchange journal (form)](https://technet.microsoft.com/library/aa553272\(v=ax.60\))

  



---
title: (RUS) Set up a charges code by using a transit account
TOCTitle: (RUS) Set up a charges code by using a transit account
ms:assetid: 3cbb1874-bb92-43ae-9315-43d38fcbb8d6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ856168(v=AX.60)
ms:contentKeyID: 50407007
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a charges code by using a transit account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up a charges code by using a transit account. Use the **Charges code** form to set up a charges code. You can use a transit account to account for charges for delayed property transfers. These charges are paid by the customer.

1.  Click **Accounts receivable** \> **Setup** \> **Charges** \> **Charges code**.

2.  Create a charges code, or select an existing charges code. For more information, see [Create charges codes](create-charges-codes.md).

3.  On the **Posting** FastTab, in the **Debit** field group, in the **Type** field, select **Customer/Vendor**.

4.  In the **Posting** field, select a posting type for the debit account.

5.  In the **Account** field, select the account number that the charge is debited from.

6.  In the **Type** field, select **Ledger account**.

7.  In the **Credit posting** field, select the posting type for the credit account.

8.  In the **Credit account** field, select the account number that the charge is credited to.

9.  Select the **Use transit account** check box to use the transit general ledger account for charges when you post a sales invoice that has a delayed property transfer.

## See also

[(RUS) Set up a ledger posting group to post tax for shipped goods](rus-set-up-a-ledger-posting-group-to-post-tax-for-shipped-goods.md)

[(RUS) Set up a posting type for a customer and an agreement](rus-set-up-a-posting-type-for-a-customer-and-an-agreement.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


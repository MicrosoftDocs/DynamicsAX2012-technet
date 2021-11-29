---
title: (RUS) Set up a charges code
TOCTitle: (RUS) Set up a charges code
ms:assetid: fe98b694-8a16-4047-85c1-81177380c901
ms:mtpsurl: https://technet.microsoft.com/library/JJ733413(v=AX.60)
ms:contentKeyID: 49685280
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a charges code 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you purchase a service item, you can allocate any charges that you incur by using a purchase order or an invoice journal. The charges can be allocated to other item invoices that have been updated. For example, you can allocate the charges to an item cost price, redraw debt to third parties, or write off the charges to the general ledger cost account.

After you allocate the charges on invoices, you can view the allocation history in the **Charges allocation** form. You can also cancel the allocations.

Use this procedure to set up a charges code. You can allocate the charges to other item invoices that have been updated.

1.  Click **Accounts payable** \> **Setup** \> **Charges** \> **Charges code**.

2.  Press CTRL+N to create a new charges code. For more information, see [Create charges codes](create-charges-codes.md).

3.  On the **Posting** FastTab, in the **Debit** field group, in the **Type** field, select **Ledger account**.

4.  In the **Debit** field group, in the **Posting** field, select **Allocation** as the posting type for the debit account.

5.  In the **Debit** field group, in the **Account** field, select the account number to which the amount on the purchase order or invoice journal line is debited.

6.  In the **Credit** field group, in the **Type** field, select **Customer/Vendor**.

## See also

[(RUS) Set up a transit account to redraw miscellaneous charges to third parties](rus-set-up-a-transit-account-to-redraw-miscellaneous-charges-to-third-parties.md)

  



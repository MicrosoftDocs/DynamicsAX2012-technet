---
title: (RUS) Set up reverse transactions
TOCTitle: (RUS) Set up reverse transactions
ms:assetid: 92d5b927-3eb0-49c1-b770-2f883c15f39a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678490(v=AX.60)
ms:contentKeyID: 49387719
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up reverse transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post an inventory transaction as a reverse transaction, rather than as a return. Inventory transactions that are posted as reverse have singular parameters that distinguish them in reports. Ledger postings are performed as reverse transactions.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



A cancelation option is available for the following types of inventory journals:

  - Transaction

  - Profit & Loss

  - BOM

  - Item (Project Module)

<!-- end list -->

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  On the **Journals** tab, select the **Extended verification** check box to confirm consistency between financial and inventory dimensions of reverse and canceled inventory transactions during inventory journal validation and posting. Activate this check box to not allow reverse transactions to be posted for dimensions that are different from the reversed transaction dimensions.
    

    > [!NOTE]
    > <P>When this parameter is activated, you cannot always determine if there is a complete match between inventory dimensions for the transaction. When different transaction dimensions are used for the reversed lot, journal posting will be performed without displaying the error.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


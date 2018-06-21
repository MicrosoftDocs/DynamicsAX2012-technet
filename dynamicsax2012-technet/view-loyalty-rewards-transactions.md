---
title: View loyalty rewards transactions
TOCTitle: View loyalty rewards transactions
ms:assetid: ded60a0a-4f77-4026-9f1b-9d84b8f56590
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720769(v=AX.60)
ms:contentKeyID: 62231566
ms.date: 04/29/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailLoyaltyCardRewardPointTrans
---

# View loyalty rewards transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to view loyalty transactions for loyalty cards and loyalty programs. You can view loyalty transactions by using one of the following methods:

  - View transactions that originated in a retail brick-and-mortar store or in an online store

  - View all loyalty card transactions for a specific loyalty program

  - View all loyalty card transactions for all loyalty programs that are assigned to a specific loyalty card

## View rewards transactions in a retail channel

Use the following procedure to view loyalty transactions for individual retail transactions that originated in a retail brick-and-mortar store or in an online store. The transaction results show one transaction at a time, so one retail transaction can have multiple loyalty transactions associated with it.

1.  Click **Retail** \> **Inquiries** \> **Retail store transactions**.
    
    –or–
    
    Click **Retail** \> **Inquiries** \> **Online store transactions**.

2.  In the form that opens, click **Transactions** \> **Loyalty card transactions**.

## View rewards transactions for a loyalty program

Use the following procedure to view rewards transactions for a specific loyalty program. You can view all rewards activity for all loyalty cards that are assigned to the loyalty program. These transactions are stored in the loyalty subledger, and you can view them even if the retail transactions have not yet been uploaded from the retail store. If you have set up Retail to track loyalty earning transactions offline, offline transactions are not included in this view.

1.  Click **Retail** \> **Setup** \> **Loyalty** \> **Loyalty programs**.

2.  In the **Loyalty programs** form, select a loyalty program, and then click **Card transactions**.

3.  In the **Card transactions** form, view the loyalty card transaction by transaction number and register number.

## View rewards transactions for a loyalty card

Use this procedure to view rewards transactions for a specific loyalty card. You can view all rewards activity in the loyalty programs that are assigned to the loyalty card. These transactions are stored in the loyalty subledger, and you can view them even if the retail transactions have not yet been calculated and posted by the retail store. If you have set up Retail to track loyalty earning transactions offline, offline transactions are not included in this view.

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty cards**. On the **Loyalty cards** list page, select a loyalty card, and then, on the **Action Pane**, click **Card transactions**.

2.  In the **Card transactions** form, view the loyalty card transaction by transaction number and register number.

## See also

[Set up loyalty programs](set-up-loyalty-programs.md)

[Set up loyalty cards in AX 2012 R3](set-up-loyalty-cards-in-ax-2012-r3.md)

[About setting up loyalty programs in AX 2012 R3](about-setting-up-loyalty-programs-in-ax-2012-r3.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


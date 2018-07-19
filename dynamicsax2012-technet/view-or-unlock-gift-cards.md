---
title: View or unlock gift cards
TOCTitle: View or unlock gift cards
ms:assetid: fe09fe9e-aa17-4bf5-ac41-025481e1c0a8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597303(v=AX.60)
ms:contentKeyID: 39519392
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailGiftCardTable
audience: Application User
ms.search.region: Global
---

# View or unlock gift cards 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

To prevent gift cards balances from being overdrawn, gift cards are locked until each transaction is posted. This topic explains how to manually unlock a gift card if a network failure or other problem prevents transactions from posting.

You can use the **Gift cards** form to view information about retail gift cards that have been issued, and the transactions that are linked to them. In the form, gift card numbers are displayed in the upper pane, and transactions that are related to each card are displayed in the lower pane.


> [!NOTE]
> <P>Gift card transactions are displayed in real time through the Commerce Data Exchange: Real-time Service. For more information about Commerce Data Exchange: Real-time Service, see <A href="commerce-data-exchange-real-time-service.md">Commerce Data Exchange: Real-time Service</A>.</P>



In Microsoft Dynamics AX 2012 R3, if you have set up intercompany gift cards, you can sell and redeem gift cards across legal entities. One legal entity, the parent legal entity, holds the liability for the gift cards. When you open the **Gift cards** form, gift cards appear only in the legal entity that holds the liability for the gift cards. For more information about setting up intercompany gift cards, see [Setting up gift cards](setting-up-gift-cards.md).

To unlock a gift card and update other information, follow these steps:

1.  Click **Retail** \> **Inquiries** \> **Gift cards**.

2.  Select the gift card in the list, click **Functions**, and then click **Unlock**.

3.  In AX 2012 R3, you can do the following:
    
      - To check the balance of a gift card, select a gift card in the list. Then view the current balance in the **Balance** field.
    
      - To void a gift card, select the gift card in the list, click **Functions**, and then click **Void**.
        

        > [!NOTE]
        > <P>You can only void gift cards that have not been used.</P>



## See also

[About gift cards in AX 2012 R3](about-gift-cards-in-ax-2012-r3.md)

[Set up gift cards](set-up-gift-cards.md)

[Sell gift cards or add funds to them](sell-gift-cards-or-add-funds-to-them.md)

[View inquiries and reports overview](view-inquiries-and-reports-overview.md)

  



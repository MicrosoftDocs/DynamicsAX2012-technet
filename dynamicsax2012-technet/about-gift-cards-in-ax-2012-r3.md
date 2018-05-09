---
title: About gift cards in AX 2012 R3
TOCTitle: About gift cards in AX 2012 R3
ms:assetid: d457f119-8160-4253-a9b9-567b27aca8d3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497834(v=AX.60)
ms:contentKeyID: 62200164
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About gift cards in AX 2012 R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic discusses functionality that has been added for gift cards in Retail in Microsoft Dynamics AX 2012 R3. In Retail, you can create gift cards that can be issued at one store and redeemed at any store in the organization. Retail keeps track of gift card balances, so a card can be reused until its available balance reaches zero. Funds can also be added to an existing gift card at any time. Gift cards in AX 2012 R3 offer additional options that aren’t available in earlier versions of Microsoft Dynamics AX.

## New functionality for gift cards in Retail in Microsoft Dynamics AX 2012 R3

In Retail in AX 2012 R3, the following functionality was added for gift cards:

  - **Support for electronic gift cards**. In addition to supporting the sale and redemption of physical gift cards, Retail in AX 2012 R3 lets you sell electronic gift cards in the online store and the call center. Customers can redeem electronic gift cards in any channel. To issue electronic gift cards, you must set up the gift card number template in the **Retail parameters** form. When the sales order for the electronic gift card is invoiced, the gift card number is generated and sent in an email message to the gift card recipient.

  - **More options for adding funds to gift cards**. In previous releases, you could add funds to gift cards only through the point of sale. Now, you can also add funds to gift cards that are issued from the call center.

  - **The ability to void unused gift cards.** When a gift card is issued in error, you can void the gift card, if it hasn’t been used in a transaction.

  - **Support for cross-company gift cards**. Gift cards can be sold and accepted by retail stores across legal entities. In this scenario, one legal entity in an organization holds the liability balance for gift cards and other legal entities transfer the value of their gift card sales and redemptions to that legal entity.
    
    If your organization supports intercompany transactions, you can set up one company as the parent company. This company can hold the liability for all gift card sales from all stores that are participating in the gift card program. The other stores can be assigned to a different legal entity, but must roll up to the parent company’s legal entity for the purpose of retail gift card sales. When gift cards are sold or redeemed, the liability is increased or decreased accordingly in the parent company based on intercompany posting rules. When the gift card is invoiced, the gift card liability is increased for the parent company. When payments are made with the gift card, the gift card liability is decreased for the parent company.
    

    > [!NOTE]
    > <P>When you redeem gift cards that are in a currency that is different from the retail channel’s currency, the following restrictions apply:</P>
    > <UL>
    > <LI>
    > <P>Gift cards that are redeemed in the online store must be in the same currency as the online store.</P>
    > <LI>
    > <P>Gift cards that are redeemed in the call center can be in a different currency than the call center, but you must change the currency for the sales order to match the currency of the gift card.</P>
    > <LI>
    > <P>Gift cards that are redeemed in brick-and-mortar stores can be in a currency that is different from the store’s currency. Currency conversion rules apply.</P></LI></UL>



## Example of intercompany accounting entries for gift card sales

The following diagram illustrates the accounting entries that are generated when a gift card is sold. In this example, company A, which is assigned to legal entity CEU, holds the liability for the gift cards. Company B, which is assigned to legal entity CEE, sells a gift card for 100.00.

![Intercompany accounting for gift card sales](images/Dn497834.GiftCardAccountingExample(AX.60).gif "Intercompany accounting for gift card sales")

## Setting up gift cards in AX 2012 R3

To set up gift cards in AX 2012 R3, complete the following tasks:

1.  Purchase physical gift cards from the vendor of your choice. Electronic gift cards are generated when the gift card is invoiced and sent to the customer in an email message.

2.  Set up a gift card product in Microsoft Dynamics AX. When you set up the gift card, set it up as an item. If your gift cards have bar codes, make sure that the correct bar codes are associated with the gift card product.
    
    For more information about how to set up products, see [Set up retail products](set-up-retail-products.md). For more information about how to set up bar codes, see [Setting up bar codes](setting-up-bar-codes.md).

3.  Set up intercompany posting rules for the legal entities that are participating in the gift card program. This step is required only if your organization supports selling and redeeming gift cards across legal entities.
    
    For more information about how to set up intercompany posting rules, see [Intercompany accounting (form)](https://technet.microsoft.com/en-us/library/aa619468\(v=ax.60\)).

4.  In the **Retail parameters** form, on the **Posting** tab, set the parameters to use to sell and redeem gift cards. For more information about how to set up gift cards parameters in AX 2012 R3, see [Set up gift cards](set-up-gift-cards.md).

## See also

[Set up gift cards](set-up-gift-cards.md)

[View or unlock gift cards](view-or-unlock-gift-cards.md)

[Sell gift cards or add funds to them](sell-gift-cards-or-add-funds-to-them.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


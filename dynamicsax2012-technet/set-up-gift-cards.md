---
title: Set up gift cards
TOCTitle: Set up gift cards
ms:assetid: 915538c7-f0a5-4fa3-ae11-71a740566290
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597173(v=AX.60)
ms:contentKeyID: 39519233
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up gift cards 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to set up retail gift cards that can be issued at one store and redeemed at any store in your organization. At the point of sale (POS), cashiers can accept a gift card as payment, see the balance on a gift card, issue a gift card, and add money to a gift card.

This topic explains how to set up gift cards in Microsoft Dynamics AX. You must purchase the physical gift cards separately. Also, we recommend that you evaluate the legal and tax requirements in your area before you set up gift cards for your organization.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for <STRONG>Retail</STRONG> in Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



## Set up gift cards

To set up gift cards, follow these steps:

1.  Set up a retail service product to represent gift cards. For more information about how to set up products, see [Set up retail products](set-up-retail-products.md).
    
    If your gift cards have bar codes, make sure that the correct bar codes are associated with the gift card product. For more information about how to set up bar codes, see [Setting up bar codes](setting-up-bar-codes.md).

2.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

3.  In the **Retail parameters** form, in the left pane, click **Posting**, and then, in the **Gift card product** field, select the gift card product.

4.  Set up at least one gift card payment method. For more information about how to set up payment methods, see [Setting up payment methods (Retail)](setting-up-payment-methods-retail.md).

After you set up gift cards, you can add gift card operations to Microsoft Dynamics AX for Retail POS screen layouts to make it easier for cashiers to work with gift cards. For information about how to set up screen layouts, see [Setting up screen layouts](setting-up-screen-layouts.md).

## Set up gift cards in Retail in Microsoft Dynamics AX 2012 R3

In Retail in AX 2012 R3, several features are available for gift cards that weren’t available in earlier versions of Microsoft Dynamics AX. For more information about the expanded functionality of gift cards in AX 2012 R3, see [About gift cards in AX 2012 R3](about-gift-cards-in-ax-2012-r3.md).


> [!IMPORTANT]
> <P>If your organization supports selling and redeeming gift cards across legal entities, you must set up intercompany posting rules for the legal entities that are participating in the gift card program. For information about how to set up intercompany posting rules, see <A href="https://technet.microsoft.com/en-us/library/aa619468(v=ax.60)">Intercompany accounting (form)</A>.</P>



To set up gift card parameters in AX 2012 R3, follow these steps:

1.  Set up a retail service product to represent gift cards. For more information about how to set up products, see [Set up retail products](set-up-retail-products.md).
    
    If your gift cards have bar codes, make sure that the correct bar codes are associated with the gift card product. For more information about how to set up bar codes, see [Setting up bar codes](setting-up-bar-codes.md).

2.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**. In the left pane, click **Posting**.

3.  On the **Gift card** FastTab, in the **Gift card product** field, select the gift card product. This is the product that represents the physical or electronic gift cards. The settings on the gift card product are used when statements that include gift card transactions are processed.

4.  In the **Gift card company** field, select the legal entity that holds the liability for gift cards. Depending on how your organization supports gift card transactions, do one of the following:
    
      - If your organization supports gift card transaction only within the same legal entity, select the same legal entity that you are setting up retail parameters for.
    
      - If your organization supports gift card transactions across legal entities, and the legal entity that you are setting up retail parameters for holds the liability for the gift card transactions, select the same legal entity.
    
      - If your organization supports gift card transactions across legal entities, and the legal entity that you are setting up retail parameters for does not hold the liability for the gift card transactions, select the legal entity that does hold the gift card transaction liability.

5.  In the **Journal** field, enter the name of the journal to use when intercompany journal entries are created. Journal entries are creating during the statement posting process.

6.  In the **Void journal name** field, enter the name of the journal to use when a journal entry to void a gift card is created.

7.  In the **Serial number templates** fields, enter the start date, end date, and gift card numbering template to use when generating electronic gift cards. If the gift card template doesn’t expire, leave the **End date** field blank.
    

    > [!NOTE]
    > <P>This field applies only to electronic gift cards that are issued from the online store or the call center.</P>



8.  Set up at least one gift card payment method. For more information about how to set up payment methods, see [Setting up payment methods (Retail)](setting-up-payment-methods-retail.md).

## See also

[About gift cards in AX 2012 R3](about-gift-cards-in-ax-2012-r3.md)

[View or unlock gift cards](view-or-unlock-gift-cards.md)

[Sell gift cards or add funds to them](sell-gift-cards-or-add-funds-to-them.md)

[Retail parameters (form)](https://technet.microsoft.com/en-us/library/hh597194\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


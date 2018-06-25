---
title: Set up payment card types and card numbers (Retail essentials)
TOCTitle: Set up payment card types and card numbers (Retail essentials)
ms:assetid: 368d3684-0659-40ec-b556-2c5eb3fb6c64
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716072(v=AX.60)
ms:contentKeyID: 62200338
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Set up payment card types and card numbers (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up the types of cards that your organization accepts as payment, such as credit cards, debit cards, loyalty cards, and gift cards.

You set up the length and range of card numbers that are acceptable for each card type. Then, when a customer presents a card for a purchase and the payment is processed, the card number is validated against the criteria that you specified. For example, some credit cards are identified by a unique starting number, such as the number 4.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



1.  Click **Retail essentials** \> **Financials** \> **Setup** \> **Payment methods** \> **Card types**.

2.  Click **New** to set up a new card.

3.  Enter the following information:
    
      - **Card ID** – A unique identifier that is displayed to the cashier at the point of sale, such as “VISA.”
    
      - **Card type name** – The descriptive name of the card, such as “VISA credit card.”
    
      - **Card types** – Select one of these card types:
        
          - **International credit card**
        
          - **International debit card**
        
          - **Loyalty card**
        
          - **Gift card**
    
      - **Card issuer** – The card-issuing authority. For example, for a loyalty card, enter the name of the store’s loyalty program. Or, for a corporate card, enter the name of the corporation.

4.  Click **Card numbers**.

5.  In the **Card numbers** form, in the **Card number from** field, enter a starting number, and in the **Card number to** field, enter an ending number.
    
    For example, some cards have numbers that always begin with a specific number, such as the number 4. To identify this card type in the system, enter **4** in the **Card number from** and **Card number to** fields. Any time a card is used that begins with the number 4, the system identifies the card as this specific card type.
    
    You can also identify a card type whose numbers always start within a range of values; for example between 4200 and 4300. In this case, enter **4200** in the **Card number from** field and **4300** in the **Card number to** field.

6.  In the **Digits to identify** field, enter the number of digits to use to validate the card. This number should match the number of digits that you entered in the **Card number from** and the **Card number to** fields. For example, if you entered a four-digit number in those fields, enter **4** in the **Digits to identify** field.

7.  To add card numbers to this card type, click **New**, and then repeat steps 5 and 6.

## See also

[Set up card payment methods for stores (Retail essentials)](set-up-card-payment-methods-for-stores-retail-essentials.md)

[Setting up payment methods (Retail essentials)](setting-up-payment-methods-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


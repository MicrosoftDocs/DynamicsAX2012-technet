---
title: Set up card types and card numbers
TOCTitle: Set up card types and card numbers
ms:assetid: 8ba5b506-d984-4d70-93d9-93e33f6e43e4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597162(v=AX.60)
ms:contentKeyID: 39519219
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up card types and card numbers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Create a card type for each type of card that your business accepts, such as debit cards, credit cards, loyalty cards, and corporate cards.

Card number validation is required for payment processing when a customer presents a card. You set up the length and range of card numbers that are acceptable for each card type.

For example, some credit cards are identified by a unique starting number, such as the number 4. To identify and validate this card type in the system, you enter **4** in the **Card number from** and **Card number to** fields, and enter **1** in the **Digits to identify** field. Any time a card is used that begins with the number 4, the system identifies the card as this specific card type.

You can also enter a range of values to identify a specific card type. For example, if you want to identify a specific card that always starts with a value of 4200 to 4300, you enter **4200** in the **Card number from** field and **4300** in the **Card number to** field, and enter **4** in the **Digits to identify** field.

1.  Click **Retail** \> **Setup** \> **Payment methods** \> **Card types**.

2.  Click **New** to set up a new card type.

3.  Enter the following information:
    
      - **Card ID** – The card ID that is assigned to the store to use as a store payment type. You must create card IDs for all cards that your business accepts.
    
      - **Card type name** – The name of the card.
    
      - **Card types** – Select a type of card from the following types: **International credit card**, **International debit card**, **Loyalty card**, or **Corporate card**. Each card ID must be assigned a card type.
    
      - **Card issuer** – The card-issuing authority.

4.  Click **Card number** to open the **Card number** form.

5.  Type a starting number in the **Card number from** field and an ending number in the **Card number to** field.

6.  In the **Digits to identify** field, enter the number of digits to use to validate the card. This number should match the number of digits that you entered in the **Card number from** and the **Card number to** fields. For example if you entered a 4 digit number in those fields, enter **4** in this field.

7.  To add card numbers to this card type, click **New**, and then repeat steps 5 and 6.

## See also

[About payment methods](about-payment-methods.md)

[Set up card payment methods for stores](set-up-card-payment-methods-for-stores.md)

  



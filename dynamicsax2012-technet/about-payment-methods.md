---
title: About payment methods
TOCTitle: About payment methods
ms:assetid: f407860f-2097-46cd-9be6-bbe1de466ff0
ms:mtpsurl: https://technet.microsoft.com/library/Hh597280(v=AX.60)
ms:contentKeyID: 39519364
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About payment methods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Retailers can accept various types of payments in exchange for the products and services that they sell. Although cash is the most common form of payment, retailers can also receive payment in the form of checks, cards, vouchers, and so on. Each payment type that the retailer accepts must be configured in Retail when the system is set up.

The following list describes each payment type that can be set up in Retail:

  - **Cash** – Money in the physical form of currency, such as banknotes and coins. This currency can be either the company currency or the store's local currency.

  - **Check** – A negotiable instrument that instructs payment of a specific amount of a specific currency, and that is drawn on a specific bank. A check is typically valid indefinitely or for six months after the date of issue, unless another period of validity is specified. This period varies, depending on the bank on which the check is drawn. There are various kinds of checks, such as order checks, counter checks, bearer checks, and account payee checks.
    
    You can set up checks as a payment method for each store. The checks can be accepted in the currency that is defined either at the company level or at the store level. You must set up checks as a payment method before you can accept a check as payment in a store.

  - **Currency** – The primary form of payment other than the company's default currency. Coins and paper money are both forms of currency.
    
    The currency payment method represents all currency that is used in Retail. Before you can use this payment method, you must set up currencies and specify retail exchange information for the currencies.

  - **Card** – All the kinds of cards that are used in Retail, such as debit cards and credit cards. We recommend that, at the organization level, you set up one card payment method that represents every kind of card. Then, at the store level, set up a payment method for each card or set of cards that is processed by using the same settings.
    
    You must set up the manufacturer cards that are available in the market, such as debit cards and credit cards, before you can accept the cards as payment in a store.

  - **Credit memo** – Credit memos that are issued or redeemed at the point of sale. The credit memo can be a credit or a return credit memo that is issued against a return sale. If credit memos are only partially redeemed, the program issues a new credit memo for the new balance. The new credit memo has a new number. A credit memo can be used only one time, and the system keeps a record of all the numbers that are used. The record can be viewed in the **Credit memo table** form. Click **Retail** \> **Inquiries** \> **Credit memos**. A customer cannot redeem more than the value of the credit memo.

  - **Gift Card** – Gift cards that are issued and redeemed at the point of sale. Overpayment is not allowed on gift cards. For more information about how to set up gift cards, see [Set up gift cards](set-up-gift-cards.md).

  - **Customer account** – Payments that can be charged to a customer account at the register at the time of the sale. You can also use this payment method to collect sales information or customer-specific discounts when the customer makes a payment by using another payment method. In this case, you must set up customer-specific information.

To set up payment methods in Retail, you must complete the following tasks:

1.  [Set up payment methods for an organization](set-up-payment-methods-for-an-organization.md) – Create the payment methods that are accepted by the whole organization.

2.  [Create organization-wide card types and card numbers](create-organization-wide-card-types-and-card-numbers.md) – If credit cards or debit cards are accepted, you must create one payment method for cards, and then create the organization-wide card types and card numbers.

3.  [Set up store payment methods](set-up-store-payment-methods.md) – Associate payment methods with each store, and then enter the store-specific settings for each payment method.

4.  [Set up card payment methods for stores](set-up-card-payment-methods-for-stores.md) – For any card payment methods that the store accepts, complete the card setup.
    
    For more information about how to set up card types and card numbers, see [Set up card types and card numbers](set-up-card-types-and-card-numbers.md).

  



---
title: Set up payment methods for an organization
TOCTitle: Set up payment methods for an organization
ms:assetid: 9af04082-4ba5-4bbf-a5fb-940422b7655c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597188(v=AX.60)
ms:contentKeyID: 39519253
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- organization
- method
- payment
- methods
audience: Application User
ms.search.region: Global
---

# Set up payment methods for an organization 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Your business might accept payment in forms other than cash. If you accept payments that are made by using checks, credit cards, debit cards, corporate charge cards, gift cards, customer credit, and other forms of payment, you must set up each payment method for your organization in **Retail**. You can assign specific payment methods to each store and then set up store-specific settings for each payment method.

1.  Click **Retail** \> **Setup** \> **Payment methods** \> **Payment methods**.

2.  In the **Payment methods** form, press CTRL+N to create a new payment method.

3.  In the **Payment method** field, enter a unique name for the payment method.

4.  In the **Payment method name**, enter a brief description of the payment method.

5.  In the **Default function** field, select a function. The payment methods that are described for the following functions are examples of typical retail payment methods:
    
      - **Normal** – Use this function for currency.
    
      - **Card** – Use this function for debit cards, credit cards, corporate cards, and other forms of card payment.
    
      - **Check** – Use this function for personal checks and other negotiable documents.
    
      - **Customer** – Use this function if you extend credit to customers and then collect payment later.
    
      - **Tender remove/float** – Use this function if you add cash to, or remove cash from, the point of sale (POS) register drawer.


> [!NOTE]
> <P>Each default function applies special settings to the store-specific payment methods that are based on the organization-wide payment methods.</P>



## See also

[About payment methods](about-payment-methods.md)

[Payment methods (form) (Retail)](https://technet.microsoft.com/en-us/library/hh597294\(v=ax.60\))

[Create organization-wide card types and card numbers](create-organization-wide-card-types-and-card-numbers.md)

[Set up store payment methods](set-up-store-payment-methods.md)

  



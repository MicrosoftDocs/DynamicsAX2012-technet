---
title: Set up payment methods for an organization (Retail essentials)
TOCTitle: Set up payment methods for an organization (Retail essentials)
ms:assetid: 59d4410e-602e-4d9b-91ec-17941c0a4933
ms:mtpsurl: https://technet.microsoft.com/library/Dn736881(v=AX.60)
ms:contentKeyID: 62200359
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up payment methods for an organization (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up the payment methods that your organization accepts. If you accept payments that are made by using checks, credit cards, debit cards, gift cards, and other forms of payment in addition to cash, you must set up each payment method for your organization in Retail essentials. You can assign specific payment methods to each store and then specify store-specific settings for each payment method.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



1.  Click **Retail essentials** \> **Financials** \> **Setup** \> **Payment methods** \> **Payment methods**.

2.  In the **Payment methods** form, click **New** or press CTRL+N to create a new payment method.

3.  In the **Payment method** field, enter a unique identifier for the payment method, such as a number or a combination of numbers and characters.

4.  In the **Payment method name**, enter a brief description of the payment method, such as **Cash**, **Check**, or **Cards** for credit and debit cards.

5.  In the **Default function** field, select a function. The payment methods that are described for the following functions are examples of typical retail payment methods:
    
      - **Normal** – Use this function for currency.
    
      - **Card** – Use this function for debit cards, credit cards, corporate cards, and other forms of card payment.
    
      - **Check** – Use this function for personal checks and other negotiable documents.
    
      - **Customer** – Use this function if you extend credit to customers and then collect payment later.
    
      - **Tender remove/float** – Use this function if you add cash to, or remove cash from, the point of sale (POS) register drawer.


> [!NOTE]
> <P>Each default function applies special settings to the store-specific payment methods that are based on the organization-wide payment methods.</P>



## See also

[Setting up payment methods (Retail essentials)](setting-up-payment-methods-retail-essentials.md)

  



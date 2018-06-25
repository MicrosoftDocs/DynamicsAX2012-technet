---
title: About credit card authorizations
TOCTitle: About credit card authorizations
ms:assetid: 9656981e-9988-40ef-822b-57980706188f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232216(v=AX.60)
ms:contentKeyID: 36058629
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- authorization
- card
- credit
- cards
- authorize
- preauthorization
- preauthorize
---

# About credit card authorizations [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can authorize a credit card that is submitted for the payment of a sales order without charging the customer's credit card. Microsoft Dynamics AX can work with a payment service that acts as a bridge between your legal entity and the bank that processes the customer's credit card charges.

When a credit card is authorized, the card number and card holder's name are verified, and the available credit balance is confirmed. Optionally, the credit card verification number and card holder’s address are verified. The customer's available credit balance then is reduced by the amount of the invoice. The payment service sends information that the credit card has been approved or declined. When the sales order is invoiced, the credit card is charged for the invoice amount.

## Card verification value

You can require the card verification value, sometimes referred to as a security code. For American Express, this is a four-digit value. For Discover, MasterCard, and Visa, this is a three-digit value.

## Address verification

Address verification information is always sent to Payment Services for Microsoft Dynamics ERP. You can decide how much information is required in order to accept the transaction.

  - **Always accept transaction** – Accept the transaction, regardless of address verification results.

  - **Account holder** – Compare the card holder’s name on the transaction with the credit card company’s information.

  - **Billing address** – Compare the card holder’s name and billing address for the transaction with the credit card company’s information.

  - **Billing postal code** – Compare the card holder’s name, billing address, and postal code for the transaction with the credit card company’s information.

## Data support

For each credit card type that is supported, you can specify the level of data support. The level controls how much information about a transaction is transferred to the payment service.

  - **Level 1** – Transaction date, transaction amount, and description

  - **Level 2** – Level 1 information, plus shipping and merchant addresses, and tax information

  - **Level 3** – Level 2 information, plus order line information

## Partial payments

If you ship part of an order, the amount of the partial order is captured, and the authorization, which was for the amount of the whole order, is closed. Then, a new authorization is submitted for the remaining amount of the order that has not been shipped.

If a credit card transaction for a partial payment is sent to Microsoft Dynamics AX from the online services website, the authorization has already been performed by the website. However, because Microsoft Dynamics AX does not support partial authorizations, the authorization is voided.

## Getting started

To use credit card authorizations, you must activate Payment Services for Microsoft Dynamics ERP as the payment service. You must visit the Payment Services for Microsoft Dynamics ERP website and set up a services account, and link the account to Microsoft Dynamics AX. Then you must select the service and set up options using the **Payment services** form. You must also follow these steps:

  - Set up credit card types for American Express, Discover, MasterCard, and Discover in the **Credit card types** form.

  - Specify parameters for using credit card authorizations in the **Accounts receivable parameters** form.

  - Set up payment terms for credit cards in the **Terms of payment** form. In the **Payment type** field, select **Credit card**.

  - Enter credit card information for customers in the **Customer credit cards** form.

When you enter sales orders, you can enter new credit card records for new or existing customers using the **Credit Card Wizard**, which is opened from the **Customer credit cards** form or the **Sales order** form. To start the authorization process, when you are entering a sales order by using the **Sales order** form, click the **Manage** tab on the **Action Pane**. Then click **Credit card** \> **Authorize**.

## See also

[Set up credit card authorizations](set-up-credit-card-authorizations.md)

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

[Credit card types (form)](https://technet.microsoft.com/en-us/library/hh209565\(v=ax.60\))

[Customer credit cards (form)](https://technet.microsoft.com/en-us/library/hh227616\(v=ax.60\))

[Payment services (form)](https://technet.microsoft.com/en-us/library/hh227622\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


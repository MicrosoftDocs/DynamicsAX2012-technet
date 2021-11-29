---
title: (RUS) Set up parameters to process gift card operations as prepayments
TOCTitle: (RUS) Set up parameters to process gift card operations as prepayments
ms:assetid: 60251fbc-a129-4fd1-bdd6-6455eb05f1e5
ms:mtpsurl: https://technet.microsoft.com/library/Dn497737(v=AX.60)
ms:contentKeyID: 62200266
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- prepayment
- Forms.RetailParameters
- prepayments
- gift card
- gift cards
- MsDynAx060.Forms.RetailParameters
- gift card operation
- gift card operations
- set up parameters
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up parameters to process gift card operations as prepayments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

This topic provides information about how to set up Microsoft Dynamics AX for Retail to process gift card operations as prepayment transactions, and how to set up a default gift card customer.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 and AX 2012 R2, this functionality is available only if you have installed the hotfix that is available in KB2918936.</P>



When you issue a gift card or add money to a gift card in Retail point of sale (POS), a value-added tax (VAT) amount is calculated for the prepayment amount that is associated with the gift card operation. The VAT amount is printed on the fiscal receipt. When the retail transaction data is transferred to Microsoft Dynamics AX for Retail, a prepayment is generated for each gift card operation that includes the VAT amount for the prepayment that was calculated by the fiscal printer. The liability of this prepayment transaction is associated with the default gift card customer account that you set up.

When you register a purchase that is paid by a customer using a gift card at the POS, the liability for the items that are paid using the gift card is associated with the default gift card customer. The liability is settled against the prepayment transactions that were registered previously for the same gift card.

Depending on the settings in the fiscal printer configuration file, a payment that is made using a gift card can be treated as a regular payment or a cash discount in a fiscal receipt. When you register a return transaction for items that were paid by a customer using a gift card, the refund amount is added to an existing gift card or a new gift card is issued and refunded in the same return transaction.

Use the following procedure to set up parameters to process the payments that are made by customers for gift cards as prepayments.

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

2.  Click **Posting**, and then in the **Posting** area, in the **Gift card** field group, select the **Process gift card operations as prepayments** check box to process gift card operations as prepayment transactions.

3.  In the **Posting profile for prepayments** field, select a posting profile to post the gift card prepayment transactions.

4.  In the **Customer account** field, select a default gift card customer.

5.  Set up additional parameters, if required. For more information, see [Set up gift cards](set-up-gift-cards.md).

## See also

[(RUS) View gift card payment journals](rus-view-gift-card-payment-journals.md)

  



---
title: Sell gift cards or add funds to them
TOCTitle: Sell gift cards or add funds to them
ms:assetid: 945b56ae-58a5-4c41-b5fc-82b617d5eec2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497803(v=AX.60)
ms:contentKeyID: 62200121
ms.date: 01/12/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailGiftCardTable
- gift card
- Forms.MCRGiftCardPromptDialog
- MsDynAx060.Forms.MCRGiftCardUpdatePromptDialog
- Forms.MCRGiftCardUpdatePromptDialog
- MsDynAx060.Forms.RetailGiftCardTable
- MsDynAx060.Forms.MCRGiftCardPromptDialog
- gift card balance
- redeem gift card
---

# Sell gift cards or add funds to them [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to sell gift cards from a call center and add funds to an existing gift card. Retail supports selling and redeeming both physical gift cards and electronic gift cards. You can sell physical gift cards from any retail channel. You can sell electronic gift cards only in the call center and the online store. You can add funds to an existing gift card only in the call center or in Microsoft Dynamics AX for Retail POS.

## Sell a gift card

You can sell gift cards from the online store, in brick-and-mortar stores by using the point-of-sale (POS) system, or from a call center. The following procedure describes how to sell a gift card in Microsoft Dynamics AX 2012 R3 Call center. For information about how to sell gift cards in a brick-and-mortar store, see the topic “Issue a gift card” in the Microsoft Dynamics AX for Retail POS help. To sell a gift card in an online store, search for a gift card product in the online store, and then follow the checkout instructions in the online store.


> [!NOTE]
> <P>Before you can sell gift cards in any retail channel, gift cards must be set up in Microsoft Dynamics AX. For more information about how to set up gift cards, see <A href="set-up-gift-cards.md">Set up gift cards</A>.</P>



To sell a gift card in the call center, follow these steps:

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  On the **Action Pane**, in the **New** group, click **Sales order**, and then enter customer information and click **OK**.

3.  In the **Sales order** form, on the **Sales order lines** FastTab, in the **Item number** field, enter the item number of the gift card. Then select the site and warehouse for the gift card and enter an amount in the **Unit price** field. You must enter information in the **Site** and **Warehouse** fields for both physical gift cards and electronic gift cards.
    

    > [!NOTE]
    > <P>You can enter only one gift card per sales order line.</P>
    > <P>For legal entities whose primary address is in Russia, you must select the site and warehouse for the gift card and the field amount in the sales order line must be equal to 0.</P>



4.  On the **Line details** FastTab, click the **Packing** tab. In the **Gift card** section, in the **Gift card type** field, select whether the gift card is a physical gift card or an electronic gift card, and then do one of the following:
    
      - For a physical gift card, select **Physical card** as the gift card type and enter the recipient’s name. Then in the **Gift card number** field, enter the gift card number that is printed on the card.
    
      - For an electronic gift card, select **Email** as the gift card type. Then enter the customer's name and email address and the recipient’s name and email address.
        
        The card number for electronic gift cards is generated when the sales order is invoiced by using the serial number template that is defined in the **Retail parameters** form. The card number and gift card details are emailed to the recipient.
        
        For more information about how to set up email in Microsoft Dynamics AX, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

5.  For legal entities whose primary address is in Russia: Specify the amount that was added to the gift card.

6.  Optional: In the **Gift message** field, enter a message. The gift message is included on the invoice for a physical gift card, and in the email message for an electronic gift card.

7.  Complete the remaining sales order fields, and then enter payment information. For more information about how to enter payment information, see [Apply payments in sales orders](apply-payments-in-sales-orders.md).

## Add funds to a gift card

You can add funds to gift cards only in the call center or in Microsoft Dynamics AX for Retail POS. To add funds to a gift card by using the POS system in a brick-and-mortar store, see the topic “Add money to a gift card” in the Microsoft Dynamics AX for Retail POS help.

To add funds to a gift card in the call center, follow these steps:

1.  Click **Call center** \> **Journals** \> **Payment management** \> **Gift cards** \> **Add amount**.

2.  In the **Add to gift card balance** form, enter the gift card number, the amount to add, and the customer number.

3.  Click **Payments**, and add a payment for the transaction.

4.  To verify that the funds were added correctly, follow these steps:
    
      - Click **Retail** \> **Inquiries** \> **Gift cards**.
    
      - In the **Gift cards** form, select the card number from the list and verify that the amount in the **Balance** field includes the funds that you added.

## Related tasks

[Set up gift cards](set-up-gift-cards.md)

[View or unlock gift cards](view-or-unlock-gift-cards.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Retail gift card</strong> configuration key</p>
<p><strong>Call center</strong> configuration key (for selling gift cards in <strong>Call center</strong>)</p>
<p><strong>Payment</strong> (for adding funds to gift cards in <strong>Call center</strong>)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>You must be a member of the following security roles:</p>
<ul>
<li><p>Sales clerk</p></li>
<li><p>Sales manager</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Set up payment methods (Call center)](set-up-payment-methods-call-center.md)

[Apply payments in sales orders](apply-payments-in-sales-orders.md)

[Set up gift cards](set-up-gift-cards.md)

[About gift cards in AX 2012 R3](about-gift-cards-in-ax-2012-r3.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


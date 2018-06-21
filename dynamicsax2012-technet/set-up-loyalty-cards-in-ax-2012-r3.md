---
title: Set up loyalty cards in AX 2012 R3
TOCTitle: Set up loyalty cards in AX 2012 R3
ms:assetid: 87b01f2c-e502-4592-8f97-d72d57d0cd7e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn720766(v=AX.60)
ms:contentKeyID: 62231564
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailLoyaltyCard
- Forms.RetailLoyaltyCardListPage
---

# Set up loyalty cards in AX 2012 R3 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up loyalty cards that entitle card holders to participate in your organization’s loyalty programs. Loyalty cards can be issued anonymously, or they can be assigned to a specific customer. If a loyalty card is assigned to a customer, the customer can redeem loyalty points from multiple associated loyalty cards, if the loyalty program allows this. Loyalty cards can be issued from any retail channel, and loyalty points can be redeemed in any retail channel that participates in the loyalty programs that are assigned to the loyalty card.

Loyalty customers can apply loyalty cards to their online transactions if they sign into the online store. If the customer does not sign in to the online store, but shops as a guest instead, they can only apply loyalty cards that were issued anonymously to their transactions.

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty cards**. In the **Loyalty cards** list, double-click a loyalty card, or, on the **Action Pane**, click **Loyalty card** to create a new loyalty card.

2.  In the **Loyalty card** form, on the **Loyalty card** FastTab, enter the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Card number</strong></p></td>
    <td><p>Enter the loyalty card number. If number sequences are set up for loyalty cards, this number can be automatically generated.</p>
    <p>For more information about how to set up number sequences, see <a href="set-up-number-sequences.md">Set up number sequences</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Card type</strong></p></td>
    <td><p>Select one of the following options to specify how the loyalty card can be used:</p>
    <ul>
    <li><p><strong>As card tender</strong> – The card can earn or redeem points. Reward points that are used for payment must be earned by this card.</p></li>
    <li><p><strong>As contact tender</strong> – The card can earn or redeem points. The reward points that the customer uses for payment can be earned by any card that that customer is assigned to.</p></li>
    <li><p><strong>No tender</strong> – The card is a secondary card that can earn reward points but can’t redeem them.</p></li>
    <li><p><strong>Blocked</strong> – The card is blocked and can’t earn or redeem reward points.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Customer name</strong></p></td>
    <td><p>Select a customer to assign to the loyalty card. You don’t have to assign a customer to the card if the card is issued anonymously. If the loyalty card is issued as contact tender, a customer name is required.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Replacement card number</strong></p></td>
    <td><p>The number of the new loyalty card if a loyalty card was lost and a replacement card was issued.</p></td>
    </tr>
    </tbody>
    </table>


3.  On the **Loyalty programs** FastTab, click **Add line** to add the loyalty programs that the loyalty card is eligible to participate in. For each loyalty program, specify a loyalty tier, if applicable. Then, in the **Start date** field, enter the date when the customer began participating in the loyalty program. You can also enter an end date, if applicable.

4.  On the **Reward point summary** FastTab, view the accumulated rewards and reward points for the loyalty card, and the different statuses for the reward points.
    
    To view the posted transactions for the loyalty card, on the **Action Pane**, click **Card transactions**. For more information about how to view and maintain loyalty cards, see [View loyalty rewards transactions](view-loyalty-rewards-transactions.md).

## See also

[Adjust loyalty cards](adjust-loyalty-cards.md)

[Set up loyalty programs](set-up-loyalty-programs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


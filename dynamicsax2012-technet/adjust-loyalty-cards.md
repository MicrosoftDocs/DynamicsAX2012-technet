---
title: Adjust loyalty cards
TOCTitle: Adjust loyalty cards
ms:assetid: 76cb25f7-c6d8-4bf6-ab99-d3dc0594a81f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497789(v=AX.60)
ms:contentKeyID: 62231562
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailLoyaltyCardRewardPointAdjustment
- Classes.RetailLoyaltyCardTransferBalance
audience: Application User
ms.search.region: Global
---

# Adjust loyalty cards 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to manually adjust loyalty cards, transfer balances between loyalty cards, and update loyalty tiers for a specific loyalty card. After you set up loyalty programs for your customers, you might have situations when you need to make manual adjustments to the customer’s loyalty card or reward balance.

You can adjust loyalty card data in the following ways:

  - Manually increase or decrease a customer’s reward points balance when the incorrect number of points was applied to the customer’s loyalty card.

  - Easily transfer the reward balance from one card to another when cards are lost so that the customer can maintain their loyalty reward balance.

  - Run the **Update loyalty card tiers** process to evaluate a customer’s loyalty card for the next loyalty tier level. This process can also be run in a batch for all loyalty card holders.

## Manually adjust loyalty rewards for a loyalty card

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty cards**. On the **Loyalty cards** list page, double-click a loyalty card.

2.  In the **Loyalty card** form, on the **Action Pane**, click **Card adjustments**.

3.  In the **Card adjustments** form, click **New** to enter a new loyalty card adjustment.

4.  On the **Adjustment** FastTab, do the following:
    
      - In the **Reward point** field, select the reward point that you want to adjust.
    
      - In the **Amount or quantity** field, enter a positive or negative value.
    
      - In the **loyalty program** list, select the loyalty program that you are adjusting reward points for.
    
      - In the **Transaction date** field, enter the date when you want the reward point adjustment to be posted. By default, the current date is used as the transaction date.
    
      - In the **Comment** field, enter any comments for the transaction.

5.  Click **Post adjustment** to generate the adjustment transaction.

## Transfer loyalty rewards from one card to another

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty cards**. On the **Loyalty cards** list page, double-click a loyalty card.

2.  In the **Loyalty card** form, on the **Action Pane**, click **Transfer balance**.

3.  In the **Transfer balance** dialog box, do the following:
    
      - In the **Source loyalty card number** field, enter the loyalty card number that you are transferring loyalty points from.
    
      - In the **Destination loyalty card number** field, enter the loyalty card number that you are transferring loyalty points to.
    
      - Click **OK**

After the process is completed, all loyalty data is transferred from the source loyalty card number to the destination loyalty card number. The card number from the source loyalty card is not transferred to the new card. The card number of the replacement card is automatically entered in the **Loyalty card** form, on the **Loyalty card** FastTab, in the **Replacement card number** field.

The **Update loyalty card tiers** process is also automatically run to validate the card holder’s loyalty tier levels.

## Update loyalty card tiers

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty cards**. On the **Loyalty cards** list page, double-click a loyalty card.

2.  In the **Loyalty card** form, on the **Loyalty programs** FastTab, click **Update card tiers**.

3.  In the **Evaluate card tiers** dialog box, click **Yes** to run the process.

If the card holder qualifies for the next loyalty tier, a new line is added to the **Loyalty programs** FastTab for the new loyalty tier after the process is completed. The start date and end date for the existing loyalty tier and the new loyalty tier are also updated.

You can also run the update loyalty tier process in a batch for all loyalty cards. To run this process for all loyalty cards, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Loyalty** \> **Update loyalty card tiers**.

2.  In the **Update loyalty card tiers** dialog box, select the **Batch processing** check box, and then select a batch group, if you need to. Click **OK** to run the process.

## See also

[Set up loyalty cards in AX 2012 R3](set-up-loyalty-cards-in-ax-2012-r3.md)

[Set up loyalty programs](set-up-loyalty-programs.md)

  



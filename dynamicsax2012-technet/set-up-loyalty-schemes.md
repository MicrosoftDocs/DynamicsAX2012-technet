---
title: Set up loyalty schemes
TOCTitle: Set up loyalty schemes
ms:assetid: c0e47e4e-589e-43ff-9013-0259a73e05a0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597233(v=AX.60)
ms:contentKeyID: 39519306
ms.date: 04/29/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailLoyaltySchemes
- MsDynAx060.Forms.RetailLoyaltySchemes
---

# Set up loyalty schemes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to set up loyalty schemes for loyalty programs. A loyalty program can help increase customer loyalty by rewarding customers for buying products in your retail stores. You build a loyalty program by creating loyalty schemes that specify how loyalty points are calculated and managed. You assign the loyalty schemes to loyalty cards. When a customer uses a loyalty card, the loyalty scheme that is applied depends on the loyalty points that are earned and redeemed.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



You can create the following rules to control how loyalty points are calculated:

  - Calculation rule

  - Calculation types

  - Redemption rules

The rules can be applied to specific items, to the total amount of the transaction, or to the number of items in the transaction. You can also assign a fixed number of points per rule.

## Set up loyalty schemes in AX 2012 R2 and AX 2012 Feature Pack

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty schemes**.

2.  On the **Loyalty schemes** list page, double-click an existing loyalty scheme in the list to open it, or, on the **Action Pane**, click **Loyalty scheme** to create a new loyalty scheme.

3.  In the **Loyalty schemes** form, on the **Loyalty scheme** FastTab, enter the scheme ID, a description, and the calculation data for the loyalty scheme.

4.  On the **Lines** FastTab, click **Add line** to add a new rule to the loyalty scheme.

5.  In the **Type** field, select the type of line that is used to create a rule for a product or a payment method. Select one of the following options:
    
      - **Tender** – Loyalty points are calculated based on the tender that is used. For example, you can create a rule that awards points when cash is used. In the case of a payment, you can create a rule that subtracts points when a customer uses a loyalty card for a purchase.
    
      - **Product** – Loyalty points are calculated based on the product or product variant that is purchased.

6.  Enter the first date and last date that the rule is valid.

7.  Enter the quantity or amount of the line item that qualifies for loyalty points. The loyalty points are defined in the **Loyalty points** column.

8.  In the **Loyalty points** field, enter the loyalty points that are awarded or subtracted when the rule for the line item is applied to the scheme.

## Set up loyalty schemes in AX 2012 R3

In AX 2012 R3, you link loyalty schemes to a loyalty program. Then, in the loyalty scheme, you specify the earning and redemption rules that apply to the loyalty program. You also assign retail channels to the loyalty scheme to identify the loyalty program that the retail store is participating in.

Loyalty schemes are no longer assigned to specific loyalty cards. Instead a loyalty card is linked to one or more loyalty programs and the loyalty program is linked to a loyalty scheme.

To set up loyalty schemes in AX 2012 R3, following these steps:

1.  Click **Retail** \> **Common** \> **Loyalty** \> **Loyalty schemes**. On the **Loyalty schemes** list page, double-click a loyalty scheme in the list to open it, or, on the **Action Pane**, click **Loyalty scheme** to create a new loyalty scheme.

2.  In the **Loyalty schemes** form, on the **General** FastTab, enter a scheme ID and description. Then in the **Loyalty program** field, select a loyalty program to assign to the loyalty scheme. Loyalty programs include the discounts and loyalty tiers that apply to a loyalty scheme. For more information about how to set up loyalty programs, see [Set up loyalty programs](set-up-loyalty-programs.md).

3.  On the **Earning rules** FastTab, click **Add line**, and then enter the earning activities that earn loyalty rewards for the customer. Earning rules can be specific to a loyalty program tier.
    
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
    <td><p><strong>Program tier</strong></p></td>
    <td><p>Select the loyalty program tier that the earning rule applies to.</p>
    <p>For example, customers who are part of a <strong>Gold</strong> level tier earn additional reward points at a rate of 10 percent of their total purchase when they purchase shoes. When you specify the gold tier in the <strong>Program tier</strong> field and enter the appropriate rule criteria, customers who are in the gold level tier in the loyalty program can earn the additional reward points.</p>
    <p>If you don’t select a program tier, the earning rule applies to all customers who are participating in the loyalty program.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Activity type</strong></p></td>
    <td><p>Select the activity that the earning rule applies to.</p>
    <ul>
    <li><p>If a customer can earn rewards by spending a specific amount or buying a specific quantity of products, select <strong>Purchase products by amount</strong> or <strong>Purchase products by quantity</strong>.</p></li>
    <li><p>If the customer can earn rewards for each sales transaction, regardless of what or how much is purchased, select <strong>Sales transaction count</strong>.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Category</strong></p></td>
    <td><p>Select the product category that the earning rule applies to. All products that are assigned to the selected category are included in the earning rule. If you don’t select a product category, the earning rule applies to all product categories.</p>
    <p>This field is available only if you selected <strong>Purchase products by amount</strong> or <strong>Purchase products by quantity</strong> in the <strong>Activity type</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Product</strong></p></td>
    <td><p>Select the product that the earning rule applies to. If you don’t select a product, the earning rule applies to all products.</p>
    <p>This field is available only if you selected <strong>Purchase products by amount</strong> or <strong>Purchase products by quantity</strong> in the <strong>Activity type</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Product variant</strong></p></td>
    <td><p>Select the product variant that the earning rule applies to. If you don’t select a product variant, the earning rule applies to all product variants.</p>
    <p>This field is available only if you selected <strong>Purchase products by amount</strong> or <strong>Purchase products by quantity</strong> in the <strong>Activity type</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Activity amount/quantity</strong></p></td>
    <td><p>Enter the amount or quantity of products that must be purchased. If you selected <strong>Sales transaction count</strong> in the <strong>Activity type</strong> field, enter <strong>1.0</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reward point ID</strong></p></td>
    <td><p>Select the reward that the earning rule applies to. Rewards points are the rewards that customers can earn. Reward points can be redeemable or non-redeemable. If the reward points are redeemable, customers can earn and then spend the rewards. Non-redeemable reward points can be used for tracking or to help the customer move to the next tier in the reward program.</p>
    <p>For more information about how to set up reward points, see <a href="set-up-loyalty-programs.md">Set up loyalty programs</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reward points</strong></p></td>
    <td><p>Enter the rewards point amount that the customer can earn for the earning activity.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Enter the date on which the earning rule becomes valid. This is an optional field that can be used if the rule is applicable for only a specific period of time.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>End date</strong></p></td>
    <td><p>Enter the last date on which the earning rule is valid. This is an optional field that can be used if the rule is applicable for only a specific period of time.</p></td>
    </tr>
    </tbody>
    </table>


4.  On the **Redemption rules** FastTab, click **Add line**, and then enter the rules that determine how a customer can redeem loyalty rewards. For example, a customer can purchase one dollar’s worth of products for every reward point that they spend. Redemption rules can be specific to a loyalty program tier.
    
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
    <td><p><strong>Program tier</strong></p></td>
    <td><p>Select the loyalty program tier that the redemption rule applies to.</p>
    <p>For example, customers who are part of a <strong>Gold</strong> level tier might be able to redeem their rewards points for any product, while standard loyalty customers might be restricted to redeeming their rewards for products in a certain category. By specifying the gold tier in the <strong>Program tier</strong> field and entering the appropriate rule criteria, customers who are in the gold level tier in the loyalty program can redeem their rewards points for additional products.</p>
    <p>If you don’t select a program tier, the redemption rule applies to all customers who are participating in the loyalty program.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reward point ID</strong></p></td>
    <td><p>Select the reward that the redemption rule applies to. Rewards points are the rewards that customers can redeem. Only select redeemable reward points in this field.</p>
    <p>For more information about how to set up reward points, see <a href="set-up-loyalty-programs.md">Set up loyalty programs</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reward points</strong></p></td>
    <td><p>Enter the number of rewards points that the customer must spend to receive the reward.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Redemption type</strong></p></td>
    <td><p>Select whether the reward points can be redeemed for currency or for a product quantity. For example, if the customer can receive a free espresso drink with the purchase of 9 espresso drinks, you can set up a redemption rule with a redemption type of <strong>Payment by quantity</strong> for products that are assigned to a coffee category.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Category</strong></p></td>
    <td><p>Select the product category that the redemption rule applies to. All products that are assigned to the selected category are included in the redemption rule. If you don’t select a product category the redemption rule applies to all product categories.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Product</strong></p></td>
    <td><p>Select the product that the redemption rule applies to. If you don’t select a product, the redemption rule applies to all products.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Product variant</strong></p></td>
    <td><p>Select the product variant that the redemption rule applies to. If you don’t select a product variant, the redemption rule applies to all product variants.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount or quantity</strong></p></td>
    <td><p>Enter the amount or product quantity that can be redeemed by using the specified rewards points</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Enter the date on which the redemption rule becomes valid. This is an optional field that can be used if the rule is applicable for only a specific period of time.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>End date</strong></p></td>
    <td><p>Enter the last date on which the redemption rule is valid. This is an optional field that can be used if the rule is applicable for only a specific period of time.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Retail channels** FastTab, click **Add line**, and then select the retail channels that the loyalty scheme applies to.
    
    You can select individual retail channels or you can select portions of the retail organization hierarchy. If you use the hierarchy, the loyalty scheme is automatically applied when retail channels are added to the hierarchy. If you select individual retail channels, you need to add the new retail channels to this form when they are created.

To apply the loyalty scheme to the channels, you must process the loyalty scheme. To process the loyalty scheme, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Loyalty** \> **Process loyalty schemes**.

2.  In the **Process loyalty schemes** form, select the appropriate settings, and then click **OK**.

## See also

[About setting up loyalty programs](about-setting-up-loyalty-programs.md)

[About setting up loyalty programs in AX 2012 R3](about-setting-up-loyalty-programs-in-ax-2012-r3.md)

[Loyalty schemes (list page)](https://technet.microsoft.com/en-us/library/hh580627\(v=ax.60\))

[Loyalty schemes (form)](https://technet.microsoft.com/en-us/library/hh580612\(v=ax.60\))

[Set up loyalty programs](set-up-loyalty-programs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


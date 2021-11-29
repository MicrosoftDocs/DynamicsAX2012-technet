---
title: Set up loyalty programs (Retail essentials)
TOCTitle: Set up loyalty programs (Retail essentials)
ms:assetid: 3b12a1b8-6ae6-4736-81c5-54e83937404f
ms:mtpsurl: https://technet.microsoft.com/library/Dn859561(v=AX.60)
ms:contentKeyID: 63820135
author: Khairunj
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Set up loyalty programs (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic describes how to set up the components of a loyalty program. Loyalty programs identify the various loyalty opportunities that you offer. You can set up very simple loyalty programs that all customers can participate in and that offer basic rewards. You can also set up more complex loyalty programs that have multiple levels, so that you can reward your customers based on their shopping habits.

Loyalty programs are at the heart of the loyalty feature. You use them to connect the various components that are required to set up a loyalty plan for your organization. You connect loyalty components to loyalty programs in the following ways:

  - Assign price groups to loyalty programs and program tiers to identify the discounts or special pricing that your loyalty participants can qualify for.

  - Assign loyalty schemes to loyalty programs to identify the earning and redemption rules that apply to the program.

  - Assign loyalty schemes to stores to identify the stores that can participate in the loyalty programs.

  - Assign loyalty programs to loyalty cards to identify the programs that the loyalty card holder can participate in.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p>Discounts</p></td>
<td><p>Set up the discounts that you offer to your loyalty customers. If you set up a loyalty program that lets customers earn and spend only points, discounts are not required.</p>
<p>For more information, see <a href="setting-up-prices-price-adjustments-and-discounts-retail-essentials.md">Setting up prices, price adjustments, and discounts (Retail essentials)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail stores</p></td>
<td><p>Set up retail stores for your organization. For more information, see <a href="set-up-a-retail-store-retail-essentials.md">Set up a retail store (Retail essentials)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Loyalty payment method</p></td>
<td><p>Set up a payment method, so that loyalty cards can be used at a register and loyalty points can be redeemed as part of a loyalty program. For more information, see <a href="setting-up-payment-methods-retail-essentials.md">Setting up payment methods (Retail essentials)</a> and <a href="set-up-store-payment-methods-retail-essentials.md">Set up store payment methods (Retail Essentials)</a>.</p></td>
</tr>
</tbody>
</table>


## Set up date intervals for loyalty tiers

If your loyalty program includes tiers, you must set up date intervals. Date intervals provide a flexible way to set the time span that applies to loyalty tiers. Date intervals let you track data over a period without having to set up a specific date range repeatedly. You can use date intervals to specify the length of time that a customer can stay in a tier or the period during which the customer must complete an activity to qualify for a tier.

For example, you have a loyalty program that lets customers qualify for a gold-level tier if they purchase 30 products in a year. In this case, you can set up a date interval to capture the one-year period and assign the date interval to the tier rule. You can then track and evaluate a customer’s purchase activities to determine whether the customer qualifies for the next loyalty tier.

To set up date intervals, follow these steps.

1.  Click **Retail essentials** \> **Customers** \> **Setup** \> **Loyalty** \> **Date intervals**.

2.  In the **Date intervals** form, click **New** to create a new date interval. Then enter a name and description.

3.  On the **General** FastTab, enter date criteria to define the date interval. Use the information in the following table to determine which criteria you should enter to create the date intervals that your loyalty tiers and loyalty tier rules require.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Set start date</strong> and <strong>Set end date</strong></p></td>
    <td><p>Use these fields to set the start and end of the date range. You can set fixed dates or specify a period. To use the system date as the start and end dates, leave these fields blank.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Adjust start date</strong> and <strong>Adjust end date</strong></p></td>
    <td><p>Use these fields to adjust the date range that is defined by the <strong>Set start date</strong> and <strong>Set end date</strong> fields.</p>
    <p>For example, you want to track the number of products that a customer purchased in the previous year to determine whether the customer qualifies for a loyalty tier. In the <strong>Units</strong> field, select <strong>Years</strong>. Then, in the <strong>Number of units</strong> field, enter <strong>-1</strong> to adjust the start date to the previous year.</p>
    <p>To set a one-year date range, so that customers can remain in a loyalty tier for one year, in the <strong>Adjust end date</strong> section, in the <strong>Units</strong> field, select <strong>Years</strong>. Then, in the <strong>Number of units</strong> field, enter <strong>1</strong> to adjust the start date to the next year.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Secondary interval</strong></p></td>
    <td><p>Use these fields to set up a date interval in another date interval. For example, you want to track the number of items that are purchased at the start of every quarter. In this case, you can set up a date interval that begins at the start of the fiscal year. In the <strong>Interval type</strong> field, select <strong>Quarter</strong>, and then, in the <strong>Start/end</strong> field, select <strong>Start</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date calculation</strong></p></td>
    <td><p>These fields show the results of the date calculations. The results include any date adjustments that you entered.</p></td>
    </tr>
    </tbody>
    </table>


## Set up reward points

Set up reward points to define the types of rewards that you offer to your customers. Reward points can be redeemable or non-redeemable. Customers can exchange redeemable reward points for discounts or products. Non-redeemable reward points can be used for tracking or to let customers advance to the next loyalty tier.

To set up reward points, follow these steps.

1.  Click **Retail essentials** \> **Customers** \> **Setup** \> **Loyalty** \> **Loyalty reward points**.

2.  In the **Loyalty reward points** form, click **New** to create a new loyalty reward.

3.  Enter a rewards point ID and description. Then, in the **Reward point type** field, select whether the reward point is based on an amount or a quantity.
    
      - Use an amount-based reward if you want customers to earn reward points that can be redeemed for products or discounts. Amount-based rewards are rounded based on the reward currency.
    
      - Use a quantity-based reward to reward customers after they purchase a specific quantity of a product. For example, you can specify the number of espresso drinks that a customer must purchase to earn a free espresso drink. Quantity-based rewards are rounded to an integer by truncating the decimals.

4.  Click **Translations** to enter the description of the loyalty reward in other languages.

5.  On the **General** FastTab, enter the information that is described in the following table.
    
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
    <td><p><strong>Currency</strong></p></td>
    <td><p>Enter the currency that the amount-based reward is tracked in.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Redeemable</strong></p></td>
    <td><p>Select this check box if the reward is redeemable. For example, clear this check box for rewards that are set up for tracking or to let customers advance to the next loyalty tier. If the check box is selected for these types of rewards, a customer can redeem the reward points and might never reach the next tier.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Redeem ranking</strong></p></td>
    <td><p>Enter the priority of the reward. The priority determines the order in which rewards are redeemed. This field applies only if the <strong>Redeemable</strong> check box is selected and multiple types of reward points can be redeemed at the same time.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Expiration time value</strong></p></td>
    <td><p>If the reward expires after a specific period, enter the number of days, months, or years after which the reward expires.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Expiration time unit</strong></p></td>
    <td><p>If the reward expires after a specific period, enter the type of period after which the reward expires.</p></td>
    </tr>
    </tbody>
    </table>


6.  On the **Summary** FastTab, view the usage summary for the reward.

## Set up loyalty price groups

Price groups are used to create and manage prices and discounts for all retail products. To apply discounts to your loyalty programs, you must define the discounts and then assign them to loyalty price groups. Loyalty price groups are assigned to the loyalty program, and you can assign a price group either to the whole loyalty program or to a selected loyalty tier. Price groups that are assigned to the whole loyalty program apply to all participants in the loyalty program. Price groups that are assigned to a selected loyalty tier apply only to participants who qualify for that loyalty tier. To assign different discounts to the loyalty program and the loyalty tiers, set up separate price groups.

For general information about how to set up price groups, see [Set up price groups (Retail essentials)](set-up-price-groups-retail-essentials.md).

To set up loyalty price groups, follow these steps.

1.  Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Price and discount setup** \> **Price groups**.

2.  In the **Price groups** form, click **New** to create a new price group.

3.  In the **Price groups** field, enter a unique ID number for the price group. Then, in the **Name** field, enter a descriptive name for the price group. Set up a price group for each loyalty program or program tier in which you want to apply specific discounts.

4.  Select the **Retail** check box.

After you set up your loyalty price groups, assign the appropriate loyalty discounts to them. For information about how to set up discounts, see [Setting up prices, price adjustments, and discounts (Retail essentials)](setting-up-prices-price-adjustments-and-discounts-retail-essentials.md).

## Set up loyalty programs

Set up loyalty programs to identify the various loyalty opportunities that you offer. You can assign multiple loyalty tiers, or no loyalty tiers, to each loyalty program. If you define loyalty tiers for the loyalty program, you must also set up the qualifying rules that apply to each loyalty tier. Use price groups to assign special discounts to the loyalty program and each loyalty tier.

To set up loyalty programs, follow these steps.

1.  Click **Retail essentials** \> **Customers** \> **Setup** \> **Loyalty** \> **Loyalty programs**.

2.  In the **Loyalty programs** form, click **New** to create a new loyalty program. Then enter a name and description.

3.  Select the **Combine related loyalty cards** check box if you want to combine the rewards on all cards that are linked to the same customer when reward points are evaluated to determine loyalty tiers. If a customer qualifies for a tier, the tier is granted to all cards that are linked to that customer.
    

    > [!NOTE]
    > <P>If you want to redeem loyalty points across multiple loyalty cards, the loyalty cards must be assigned to the same customer.</P>



4.  Optional: On the **Program tiers** FastTab, click **Add line** to add a new program tier. Program tiers are optional, but if you set up program tiers, you must also set up program tier rules.

5.  In the **Level** field, enter a numeric value for the level.

6.  Enter a name and description for the level. Click **Translations** to enter the level description in other languages.

7.  In the **Date interval** field, select the date interval that defines how long customers can remain in a tier after they have qualified for that tier. For example, a one-year period is selected as the date interval for the gold-level tier. In this case, any customer who qualifies for the gold-level tier can receive the rewards that are assigned to that tier for one year. If a customer requalifies for the gold-level tier while he or she is in that tier, the expiration date of the customer’s tier status is extended by another year, starting on the date when the customer requalifies.

8.  On the **Tier rules** FastTab, click **New** to add the reward points or qualifying rules that apply to each tier.

9.  In the **Reward point** field, select the reward point that applies to the selected loyalty tier.

10. In the **Minimum issued points** field, enter the minimum number of loyalty points that the customer must earn to qualify for the loyalty tier. If all customers qualify for the loyalty tier just by participating in the program, enter **0** (zero).

11. In the **Evaluation date interval** field, select the date interval that defines the period in which customers must earn the reward to qualify for the tier.

12. Assign price groups to the loyalty program.
    
      - To assign price groups and discounts that apply to the whole loyalty program, at the top of the form, click **Price groups**.
    
      - To assign price groups to a specific loyalty tier, on the **Program tiers** FastTab, select a loyalty tier, and then click **Price groups**.

13. To view all transactions for loyalty cards that are assigned to this loyalty program, at the top of the form, click **Loyalty card transactions.**

  



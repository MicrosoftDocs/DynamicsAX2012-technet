---
title: Set up loyalty programs
TOCTitle: Set up loyalty programs
ms:assetid: 5d763287-ae82-40da-aa44-6117cfae102e
ms:mtpsurl: https://technet.microsoft.com/library/Dn497760(v=AX.60)
ms:contentKeyID: 62231561
author: Khairunj
ms.date: 06/17/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailLoyaltyPrograms
audience: Application User
ms.search.region: Global
---

# Set up loyalty programs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up the components for a loyalty program. Loyalty programs identify the various loyalty opportunities that you offer. You can set up very simple loyalty programs that all customers can participate in and that offer basic rewards. You can also set up more complex loyalty programs that have multiple levels that enable you to reward your customers based on their shopping habits.

Loyalty programs are at the heart of the loyalty feature. You use them to connect the various components that are required to set up a loyalty plan for your organization. Connect loyalty components to loyalty programs in the following ways:

  - Assign price groups to loyalty programs and program tiers to identify which discounts or special pricing your loyalty participants can qualify for.

  - Assign loyalty schemes to loyalty programs to identify the earning and redemption rules that apply to the program.

  - Assign the retail channels to the loyalty scheme to identify the retail stores that can participate in the loyalty programs.

  - Assign loyalty programs to loyalty cards to identify the loyalty programs that the loyalty card holder can participate in.

The following illustration shows the tasks that are included in setting up a loyalty program.

![Set up loyalty programs](images/Dn497760.LoyaltyProgram(AX.60).gif "Set up loyalty programs")

## This task is part of a bigger process

The following illustration shows how setting up loyalty programs relates to the overall setup process for the loyalty feature in Retail in AX 2012 R3. For an overview of the process, see [About setting up loyalty programs in AX 2012 R3](about-setting-up-loyalty-programs-in-ax-2012-r3.md).

![Loyalty setup process flow](images/Dn720457.LoyaltyProcess(AX.60).gif "Loyalty setup process flow")

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
<td><p>Set up the discounts that you offer to your loyalty customers. If you set up a loyalty program that enables customers to earn and spend points only, discounts are not required.</p>
<p>For more information, see <a href="about-price-adjustments-and-discounts.md">About price adjustments and discounts</a> and <a href="set-up-a-simple-discount.md">Set up a simple discount</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail channels</p></td>
<td><p>Set up retail channels for your organization. Retail channels are the stores that participate in your loyalty programs, such as brick-and-mortar stores or online stores. For more information, see <a href="set-up-a-retail-store.md">Set up a retail store</a> and <a href="set-up-an-online-store.md">Set up an online store</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Loyalty payment method</p></td>
<td><p>Set up a payment method before a loyalty card can be used at a register and loyalty points can be redeemed as part of a loyalty program. For more information, see <a href="set-up-loyalty-payment-methods.md">Set up loyalty payment methods</a> and <a href="set-up-store-payment-methods.md">Set up store payment methods</a>.</p></td>
</tr>
</tbody>
</table>


## Set up date intervals for loyalty tiers

If your loyalty program includes tiers, you must set up date intervals. Date intervals provide a flexible way to set the time span that applies to loyalty tiers. Date intervals enable you to track data over a period of time without having to set up a specific date range again and again. You can use date intervals to specify the length of time a customer can stay in a tier or to determine the time period in which the customer must complete an activity to qualify for a tier.

For example, if you have a loyalty program that allows a customer to qualify for a gold level tier if they purchase 30 products in a year, you can set up a date interval to capture the one year time span. You can then assign the date interval to the tier rule to track the customer’s purchase activity and evaluate their activities to qualify them for the next loyalty tier.

To set up date intervals, follow these steps:

1.  Click **Retail** \> **Setup** \> **Loyalty** \> **Date intervals**.

2.  In the **Date intervals** form, click **New** to create a new date interval. Then, enter a name and description.

3.  On the **General** FastTab, enter the date criteria to define the date interval. Use the information in the table below to determine which criteria to enter to create the date intervals that you need to support your loyalty tiers and loyalty tier rules.
    
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
    <td><p>Used these fields to set the start and end of the date range. To use the system date as the start and end date, leave these fields blank. Otherwise, you can set a static fixed date or a period as the start and end date.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Adjust start date</strong> and <strong>Adjust end date</strong></p></td>
    <td><p>Use these fields to adjust the date range based on the settings in the <strong>Set start date</strong> and <strong>Set end date</strong> fields.</p>
    <p>For example, if you want to track the number of products that a customer has purchased in the prior year to qualify them for a loyalty tier, in the <strong>Units</strong> field, select <strong>Years</strong>. Then, in the <strong>Number of units</strong> field, enter <strong>-1</strong> to adjust the start date to the previous year.</p>
    <p>To set a one year date range to apply to the length of time that a customer can remain in a loyalty tier, in the <strong>Adjust end date</strong> section, in the <strong>Units</strong> field, select <strong>Years</strong>. Then, in the <strong>Number of units</strong> field, enter <strong>1</strong> to adjust the start date to the following year.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Secondary interval</strong></p></td>
    <td><p>Use these fields to set up a date interval within a date interval. For example if you want to track the number of items purchased at the start of every quarter, you could set up a date interval that started at the beginning of the fiscal year. In the <strong>Interval type</strong> field, select <strong>Quarter</strong>, and then, in the <strong>Start/end</strong> field, select <strong>Start</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date calculation</strong></p></td>
    <td><p>These fields show the results of the date calculations, including any date adjustments that you entered.</p></td>
    </tr>
    </tbody>
    </table>


## Set up reward points

Set up reward points to define the types of reward that you offer to your customers. Rewards points can be redeemable or non-redeemable. Customers can exchange redeemable reward points for discounts or products. Non-redeemable reward points can be used for tracking purposes or to advance a customer to the next loyalty tier.

To set up reward points, follow these steps:

1.  Click **Retail** \> **Setup** \> **Loyalty** \> **Loyalty reward points**.

2.  In the **Loyalty reward points** form, click **New** to create a new loyalty reward.

3.  Enter a rewards point ID and description, and then, in the **Reward point type** field, select whether the reward point is based on an amount or a quantity.
    
    Use an amount-based reward if you want the customer to earn reward points that can be redeemed for products or discounts. Amount-based rewards are rounded based on the reward currency.
    
    Use a quantity-based reward if you want to reward the customer after they purchase a certain quantity of a product. For example, you can set the number of espresso drinks that a customer must purchase to earn a free espresso drink. Quantity-based rewards are rounded to an integer by truncating the decimals.

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
    <td><p>Select this check box if the reward is redeemable. For example, clear this check box for rewards that are set up for tracking purposes or to enable customers to advance to the next loyalty tier. If the check box is selected for these types of rewards, the customer can redeem the reward points, and might never reach the next tier level.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Redeem ranking</strong></p></td>
    <td><p>Enter the priority in which the rewards should be redeemed. This field applies only if the <strong>Redeemable</strong> check box is selected and if multiple types of reward points can be redeemed at one time.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Expiration time value</strong></p></td>
    <td><p>If the reward expires within a certain period of time, enter the number of days, months, or years in which the reward expires.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Expiration time unit</strong></p></td>
    <td><p>If the reward expires within a certain period of time, enter the time period in which the reward expires.</p></td>
    </tr>
    </tbody>
    </table>


6.  On the **Summary** FastTab, view the usage summary for the reward.

## Set up loyalty price groups

Price groups are used to create and manage prices and discounts for all retail products. To apply discounts to your loyalty programs, you must define the discounts and then assign them to loyalty price groups. Loyalty price groups are assigned to the loyalty program, and you can assign a price group to the whole loyalty program or to a selected loyalty tier. Price groups that are assigned to the whole loyalty program are applicable to all participants in the loyalty program. Price groups that are assigned to a loyalty tier only apply to the participants who qualify for that loyalty tier. To assign different discounts to the loyalty program and the loyalty tiers, set up separate price groups.

For general information about how to set up price groups, see [About setting prices by using price groups](about-setting-prices-by-using-price-groups.md).

To set up loyalty price groups, follow these steps:

1.  Click **Retail** \> **Setup** \> **Pricing and discounts** \> **Price groups**.

2.  In the **Price groups** form, click **New** to create a new price group.

3.  In the **Price groups** field, enter a unique ID number for the price group, and then, in the **Name** field, enter a descriptive name for the price group. Set up a price group for each loyalty program or program tier in which you want to apply specific discounts.

4.  Select the **Retail** check box.

After you set up your loyalty price groups, assign the appropriate loyalty discounts to them. For information about how to set up discounts, see [About price adjustments and discounts](about-price-adjustments-and-discounts.md).

## Set up loyalty programs

Set up loyalty programs to identify the various loyalty opportunities that you offer. Each loyalty program can have multiple loyalty tiers or no loyalty tiers assigned to them. If you define loyalty tiers for the loyalty program, you also must set up the qualifying rules that apply to each loyalty tier. Use price groups to assign special discounts to the loyalty program and each loyalty tier.

To set up loyalty programs, follow these steps:

1.  Click **Retail** \> **Setup** \> **Loyalty** \> **Loyalty programs**.

2.  In the **Loyalty programs** form, click **New** to create a new loyalty program. Then, enter a name and description.

3.  Select the **Combine related loyalty cards** check box if you want to combine the rewards on all cards that are linked to the same customer when evaluating reward points to earn loyalty tiers. If rewards qualify the customer for a tier, all cards that are linked to the same customer are granted the tier.
    

    > [!NOTE]
    > <P>To redeem loyalty points across multiple loyalty cards, the loyalty cards must be assigned to the same customer. For more information about setting up loyalty cards, see <A href="set-up-loyalty-cards-in-ax-2012-r3.md">Set up loyalty cards in AX 2012 R3</A>.</P>



4.  On the **Program tiers** FastTab, click **Add line** to add a new program tier. Program tiers are optional, but if you set up program tiers, you must also set up program tier rules.

5.  In the **Level** field, enter a numerical value for the level.

6.  Enter a name and description for the level. Click **Translations** to enter the level description in other languages.

7.  In the **Date interval** field, select the date interval that indicates the length of time that a customer can stay in a tier after they have qualified for the tier. For example, if the date interval that is selected for gold level tier is a one year period, any customer who qualifies for the gold level tier can receive the rewards that are assigned to the gold level tier for one year. If the customer requalifies for the gold level tier while they are in that tier, the date that their tier status expires is extended by another year, starting at the date when they requalify.

8.  On the **Tier rules** FastTab, click **New** to add the reward points or qualifying rules that apply to each tier.

9.  In the **Reward point** field, select the reward point that applies to the selected loyalty tier.

10. In the **Minimum issued points** field, enter the minimum number of loyalty points the customer must earn to qualify for the loyalty tier. If all customers can qualify for the loyalty tier simply by participating in the program, enter 0 (zero) in this field.

11. In the **Evaluation date interval** field, select the date interval that represents the time period in which the reward must be earned to qualify the customer for the tier.

12. Assign price groups to the loyalty program. To assign price groups and discounts that apply to the entire loyalty program, at the top of the form, click **Price groups**. To assign price groups to a specific loyalty tier, on the **Program tiers** FastTab, select a loyalty tier and then click **Price groups**.

13. To view all transactions for loyalty cards that are assigned to this loyalty program, at the top of the form, click **Loyalty card transactions.**

## Next step

After you set up your loyalty programs, you must set up loyalty schemes and loyalty cards. For more information, see [Set up loyalty schemes](set-up-loyalty-schemes.md) and [Set up loyalty cards in AX 2012 R3](set-up-loyalty-cards-in-ax-2012-r3.md).

## Related tasks

[Set up a simple discount](set-up-a-simple-discount.md)

[Set up a retail store](set-up-a-retail-store.md)

[Set up an online store](set-up-an-online-store.md)

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
<td><p>Retail</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>RetailOperationsManager</p>
<p>RetailStoreManager (View loyalty transactions)</p></td>
</tr>
</tbody>
</table>

  



---
title: About setting up loyalty programs in AX 2012 R3
TOCTitle: About setting up loyalty programs in AX 2012 R3
ms:assetid: 41bb0f47-fe72-4e1d-9600-2f4a80d7796a
ms:mtpsurl: https://technet.microsoft.com/library/Dn720457(v=AX.60)
ms:contentKeyID: 62224165
author: Khairunj
ms.author: daxcpft
ms.date: 05/20/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About setting up loyalty programs in AX 2012 R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A loyalty program can help increase customer loyalty by rewarding customers for buying products in your retail stores. In Microsoft Dynamics AX 2012 R3, you can set up simple or complex loyalty programs that apply across your legal entities in any retail channel. You can set up the loyalty feature in AX 2012 R3 to include the following options:

  - Set up the types of rewards that you offer in your loyalty programs and track participation in your loyalty programs.

  - Set up loyalty programs to represent the different reward incentives that you offer. You can include loyalty program tiers to offer greater incentives and rewards to customers who shop more frequently or spend more money in your stores.

  - Define earning rules to identify the activities that a customer must complete to earn rewards. You can also define redemption rules to identify when and how a customer can redeem rewards.

  - Issue loyalty cards from any retail channel that participates in your loyalty programs, and link loyalty cards to one or more loyalty programs that the customer can participate in. You can also link a customer record to a loyalty card to enable the customer to pool loyalty points from multiple cards and redeem them.

  - Manually adjust loyalty cards or transfer the loyalty rewards balance from one card to another to accommodate or reward a customer.


> [!NOTE]
> <P>This topic applies to AX 2012 R3. For information about how to set up loyalty programs in prior versions of Retail, see <A href="about-setting-up-loyalty-programs.md">About setting up loyalty programs</A>.</P>



## Setting up loyalty programs in Retail

You must set up several components to enable the loyalty feature in Retail. The following diagram illustrates the loyalty components and how they relate to one another.

![Loyalty setup process flow](images/Dn720457.LoyaltyProcess(AX.60).gif "Loyalty setup process flow")

  

The following table describes each component and where it is used in the loyalty setup.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>Where it’s used</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up discounts<br />
(prerequisite)</p></td>
<td><p>Set up the discounts that you offer to your loyalty customers. For example, 5 percent off all apparel products.</p></td>
<td><p>Discounts must be added to price groups in order to be included in a loyalty program. Price groups are assigned to loyalty programs and loyalty tiers.</p></td>
<td><p><a href="set-up-a-simple-discount.md">Set up a simple discount</a></p></td>
</tr>
<tr class="even">
<td><p>Set up price groups<br />
(prerequisite)</p></td>
<td><p>Price groups are used to create and manage prices and discounts for retail products. Set up the price groups that include the discounts that apply to your loyalty programs.</p></td>
<td><p>Price groups are assigned to your loyalty programs and loyalty program tiers.</p></td>
<td><p><a href="create-a-price-group.md">Create a price group</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up channels<br />
(prerequisite)</p></td>
<td><p>Retail channels are the stores that participate in your loyalty programs, such as a brick-and-mortar store or an online store. You must set up your retail channels before you can assign loyalty programs to them.</p></td>
<td><p>You assign retail channels to a loyalty program if the retail channel is participating in the loyalty program.</p></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p>
<p><a href="set-up-an-online-store.md">Set up an online store</a></p></td>
</tr>
<tr class="even">
<td><p>Set up loyalty payment method<br />
(prerequisite)</p></td>
<td><p>You must set up a payment method before a loyalty card can be used at a register and loyalty points can be redeemed as part of a loyalty program. You must also add the loyalty payment method to the retail channel for customers to be able to redeem their loyalty points as payment for products.</p></td>
<td><p>Set up a loyalty type payment method, and then assign the loyalty payment method to the retail channels that are participating in the loyalty program.</p></td>
<td><p><a href="set-up-loyalty-payment-methods.md">Set up loyalty payment methods</a></p>
<p><a href="set-up-store-payment-methods.md">Set up store payment methods</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up date intervals</p></td>
<td><p>Date intervals provide a flexible way to set the time span that applies to loyalty tiers. Use date intervals to specify the length of time a customer can stay in a tier or to determine the time period in which the customer must complete an activity to qualify for a tier.</p></td>
<td><p>Date intervals only apply if you use tiers in your loyalty programs. You select the date interval that applies to program tiers, and also the date intervals that apply to program tier rules.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
<tr class="even">
<td><p>Set up reward points</p></td>
<td><p>Reward points are the types of reward that you offer to your customers. Rewards points can be redeemable or non-redeemable. Redeemable reward points can be exchanged for products. Non-redeemable reward points are used for tracking purposes or to advance a customer to the next tier in a loyalty program.</p></td>
<td><p>Reward points are referenced in tier rules and are used to qualify a customer for a specific tier. Reward points are also referenced in loyalty schemes in earning and redemption rules. In earning rules, you specify the rewards that a customer can earn for a specific activity. In redemption rules, you specify the reward that the customer can redeem.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up loyalty programs</p></td>
<td><p>Loyalty programs are the core loyalty entity that you offer. Each loyalty program can also have zero to many loyalty tiers assigned to it.</p>
<p>Discounts and price groups are assigned to the loyalty programs at either the program level or the loyalty tier level.</p></td>
<td><p>You create loyalty schemes for your loyalty programs. You assign loyalty cards to your loyalty programs, and loyalty cards can be assigned to a customer. Retail channels participate in the loyalty programs that are assigned to the loyalty schemes. Any customer who holds a loyalty card can participate in the loyalty programs that are assigned to the card.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
<tr class="even">
<td><p>Set up loyalty tiers and tier rules</p></td>
<td><p>Loyalty tiers are optional levels that you can define for your loyalty programs. You can set up base discounts and rewards for all customers who participate in the loyalty program, and you can set up additional discounts and rewards for customers who earn the different levels in the program. For each loyalty tier you define, you can set up the rules that qualify a customer for each tier. You can also define how long a customer can remain in that tier after they have reached it.</p></td>
<td><p>Loyalty tiers and loyalty tier rules are defined in the loyalty programs. If you don’t define any loyalty tiers, all customers who participate in the loyalty program qualify for the discounts that you assign in the loyalty program price group.</p>
<p>If you define loyalty tiers, you can set up earning rules and redemption rules for the loyalty tiers in the loyalty scheme.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up loyalty schemes</p></td>
<td><p>Loyalty schemes specify the earning rules and redemption rules that apply to a selected loyalty program. You assign retail channels to a loyalty scheme to identify which loyalty program, earning rules, and redemption rules apply to a retail store.</p></td>
<td><p>A loyalty scheme is assigned to a loyalty program and to retail channels. You can assign many loyalty schemes to the same loyalty program, and you can assign many loyalty schemes to many retail channels.</p></td>
<td><p><a href="set-up-loyalty-schemes.md">Set up loyalty schemes</a></p></td>
</tr>
<tr class="even">
<td><p>Set up loyalty cards</p></td>
<td><p>A loyalty card entitles the card holder to participate in the loyalty programs that are assigned to the card. Loyalty cards can be issued anonymously, or they can be assigned to a specific customer. You can view the loyalty transactions for a specific card, and you can view a summary of loyalty points that have been accumulated on the card. You can issue loyalty cards from any retail channel.</p>
<p>You can also manually adjust a loyalty card to upgrade the customer to a different tier, add loyalty points, or transfer the loyalty point balance from one card to another.</p></td>
<td><p>You assign loyalty programs to a loyalty card.</p></td>
<td><p><a href="set-up-loyalty-cards-in-ax-2012-r3.md">Set up loyalty cards in AX 2012 R3</a></p></td>
</tr>
</tbody>
</table>


## Loyalty processes

The following table describes the processes that must be run to send the loyalty configurations and data to your stores.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Process name</p></th>
<th><p>Description</p></th>
<th><p>To open the process form</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>1050</strong> <br />
(loyalty information)</p></td>
<td><p>Run this process to send the loyalty configuration data from Microsoft Dynamics AX to the retail stores.</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Periodic</strong> &gt; <strong>Data distribution</strong> &gt; <strong>Distribution schedule</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Process loyalty schemes</strong></p></td>
<td><p>Run this process to associate loyalty schemes with the retail channels that the loyalty scheme is assigned to. This process can be scheduled to run as a batch process.</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Periodic</strong> &gt; <strong>Loyalty</strong> &gt; <strong>Process loyalty schemes</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Process offline loyalty transactions</strong></p></td>
<td><p>Run this process to update loyalty cards to include transactions that were processed offline.</p>
<p>This process is applicable only if the <strong>Earn offline</strong> check box is selected in the <strong>Retail shared parameters</strong> form to enable earning rewards offline.</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Periodic</strong> &gt; <strong>Loyalty</strong> &gt; <strong>Process offline loyalty transactions</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Update loyalty card tiers</strong></p></td>
<td><p>Run this process to evaluate the customer’s earning activity against the tier rules for a loyalty program and update the customer’s tier status.</p>
<p>This process is needed only if you change the tier rules in loyalty programs and you want the updated rules to be retroactively applied to loyalty cards that have already been issued.</p>
<p>This process can be run as a batch process or for individual cards.</p></td>
<td><p>Click <strong>Retail</strong> &gt; <strong>Periodic</strong> &gt; <strong>Loyalty</strong> &gt; <strong>Update loyalty card tiers</strong>.</p></td>
</tr>
</tbody>
</table>


## See also

[Set up loyalty programs](set-up-loyalty-programs.md)

  



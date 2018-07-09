---
title: Loyalty programs
TOCTitle: Loyalty programs
ms:assetid: 86ba1cec-4b39-42bb-a971-45b5f2ae37dd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn804648(v=AX.60)
ms:contentKeyID: 62959180
ms.date: 05/20/2015
mtps_version: v=AX.60
---

# Loyalty programs [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Loyalty programs can help increase customer loyalty by rewarding customers for buying products in your retail stores. In Microsoft Dynamics AX, you can set up simple or complex loyalty programs that apply across your legal entities in any retail channel. This topic describes the components that are included in the loyalty program for Retail and provides information about the tasks that are required to configure the loyalty program for your organization.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Gg723980.TopicIcon_Lifecycle(AX.60).png" title="Lifecycle" alt="Lifecycle" />
<p>Get to know the loyalty feature</p>
<p>Configure loyalty programs</p>
<p>Maintain loyalty programs</p>
<p>Upgrade loyalty programs from earlier versions</p>
<p>Support for earlier versions</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="retail-for-application-users.md">Retail for application users</a></p>
<p><a href="microsoft-dynamics-ax-retail-for-it-pros-and-developers.md">Microsoft Dynamics AX Retail for IT pros and developers</a></p></td>
</tr>
</tbody>
</table>


## Get to know the loyalty feature

The loyalty feature lets you specify the types of rewards that you offer your customers. You can offer additional incentives to customers who spend more in your stores and you can also set up the rules that apply to the earning and redemption of those rewards and how those rules apply to your customer’s activities. The following table lists resources that you can use to learn more about the loyalty feature.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Find out how the loyalty feature works in AX 2012 R3</p></td>
<td><p>Learn about the components of the loyalty feature and how the components interact with each other to support reward point transactions and tracking.</p></td>
<td><p><a href="about-setting-up-loyalty-programs-in-ax-2012-r3.md">About setting up loyalty programs in AX 2012 R3</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Configure loyalty programs

To offer a loyalty program to your customers and to issue and apply loyalty points to retail transactions in Microsoft Dynamics AX, you must set up the various components that the loyalty feature requires. The following tables describe the configuration tasks that must be completed in Microsoft Dynamics AX to set up the loyalty feature.

## Prerequisites

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up discounts</p></td>
<td><p>Loyalty reward offers often consist of discounts that you offer your customers. To determine which discounts you want to include in a loyalty program, you must set up the discount and then assign it to a price group. The price group is then either assigned to a loyalty program or a reward level (tier) within a loyalty program.</p>
<div class="alert">

> [!NOTE]
> <P>If you set up your loyalty programs to offer only loyalty points, setting up discounts and price groups for loyalty programs is optional.</P>


</div></td>
<td><p><a href="set-up-a-simple-discount.md">Set up a simple discount</a></p>
<p><a href="about-price-adjustments-and-discounts.md">About price adjustments and discounts</a></p></td>
</tr>
<tr class="even">
<td><p>Set up price groups</p></td>
<td><p>You can use price groups to group prices and discounts and apply them to retail products. To apply special discounts to your loyalty programs, you must first add the discounts to a price group and then assign the price group to either a loyalty program or to a specific loyalty program tier.</p>
<p>For example, a gold loyalty tier customer might be eligible for additional discounts. To apply those discounts to gold tier customers only, you would set up a price group that includes the discounts that apply to gold tier members.</p></td>
<td><p><a href="create-a-price-group.md">Create a price group</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up retail channels</p></td>
<td><p>Retail channels are the stores in your organization. You set up your retail channels and then assign the loyalty programs to retail channels. This task identifies which stores are participating in specific loyalty programs.</p></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p>
<p><a href="set-up-an-online-store.md">Set up an online store</a></p></td>
</tr>
<tr class="even">
<td><p>Set up loyalty cards as a payment method</p></td>
<td><p>To allow customers to redeem loyalty reward points for products in your stores you must complete two tasks. First, set up a loyalty type payment method. Then, assign the loyalty payment method to the retail channels that are participating in the loyalty program. The second step identifies the loyalty card as a valid form of payment.</p></td>
<td><p><a href="set-up-loyalty-payment-methods.md">Set up loyalty payment methods</a></p>
<p><a href="set-up-store-payment-methods.md">Set up store payment methods</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Set up loyalty programs

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up date intervals</p></td>
<td><p>Date intervals apply only to loyalty tiers. Date intervals specify the length of time that a customer can stay in a tier or determine the time period in which the customer must complete an activity to qualify for a tier.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
<tr class="even">
<td><p>Set up reward points</p></td>
<td><p>Reward points represent the types of rewards that you offer to your loyalty customers. Reward points are referenced in loyalty tier rules and loyalty schemes.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up a loyalty program</p></td>
<td><p>The loyalty program is the core of the loyalty feature. Price groups, loyalty tiers, loyalty schemes, retail channels, and loyalty cards are all associated with the loyalty program.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
<tr class="even">
<td><p>Optional: Set up loyalty program tiers and tier rules</p></td>
<td><p>You use loyalty program tiers to set up levels of discounts that apply to customers who reach each tier. If you set up loyalty tiers, you must also define the rules that apply to each tier. For example, a customer must purchase 30 espresso drinks in a year to reach the gold tier.</p>
<p>You can also reference loyalty tiers in loyalty schemes to define separate earning and redemption rules by tier.</p></td>
<td><p><a href="set-up-loyalty-programs.md">Set up loyalty programs</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Set up loyalty schemes and loyalty cards

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up loyalty schemes</p></td>
<td><p>Loyalty schemes include the earning and redemption rules that apply to your loyalty programs. You can assign multiple loyalty schemes to a single loyalty program.</p></td>
<td><p><a href="set-up-loyalty-schemes.md">Set up loyalty schemes</a></p></td>
</tr>
<tr class="even">
<td><p>Set up loyalty cards</p></td>
<td><p>Set up loyalty cards so that your customers can participate in loyalty programs. A loyalty card can be issued anonymously, or it can be assigned to a specific customer. Link your loyalty programs to loyalty cards to identify the loyalty programs that the cardholder can participate in.</p></td>
<td><p><a href="set-up-loyalty-cards-in-ax-2012-r3.md">Set up loyalty cards in AX 2012 R3</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Maintain loyalty programs

After you set up loyalty programs, you can monitor and maintain them and review the activity of your cardholders. You can continue to offer rewards to your customers based on their level of activity and you can manually adjust a customer’s loyalty rewards if necessary.

The following tables describe the tasks in Microsoft Dynamics AX that you perform to maintain the loyalty feature.

## View loyalty transactions

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View loyalty transactions for loyalty cards</p></td>
<td><p>View rewards transactions for a specific loyalty card. You can view all rewards activity in the loyalty programs that are assigned to the loyalty card.</p></td>
<td><p><a href="view-loyalty-rewards-transactions.md">View loyalty rewards transactions</a></p></td>
</tr>
<tr class="even">
<td><p>View loyalty transactions for loyalty programs</p></td>
<td><p>View rewards transactions for a specific loyalty program. You can view all reward activity for all loyalty cards that are assigned to the loyalty program.</p></td>
<td><p><a href="view-loyalty-rewards-transactions.md">View loyalty rewards transactions</a></p></td>
</tr>
<tr class="odd">
<td><p>View loyalty transactions for retail channels</p></td>
<td><p>View loyalty transactions for individual retail transactions that originated in a retail brick-and-mortar store or in an online store.</p></td>
<td><p><a href="view-loyalty-rewards-transactions.md">View loyalty rewards transactions</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Adjust loyalty cards

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Adjust loyalty cards</p></td>
<td><p>Adjust loyalty card reward points manually, transfer balances between loyalty cards, and update loyalty tiers for a specific loyalty card.</p></td>
<td><p><a href="adjust-loyalty-cards.md">Adjust loyalty cards</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Upgrade loyalty programs from earlier versions

In earlier versions of Microsoft Dynamics AX, you could use the same loyalty scheme ID and loyalty card numbers to represent different loyalty programs in different legal entities in your organization. However, in AX 2012 R3, the loyalty scheme ID and card numbers must be unique. Conflicts in duplicate scheme IDs are automatically resolved during the upgrade process, but you must manually review loyalty card numbers after the upgrade and resolve any duplicates.

The following table describes the task in Microsoft Dynamics AX to upgrade the loyalty feature.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Resolve conflicts in loyalty card numbers after upgrade</p></td>
<td><p>Manually resolve conflicts in loyalty card numbers. We recommend that you resolve any conflicts before you process any loyalty transactions for new or existing customers.</p></td>
<td><p><a href="resolve-conflicts-in-loyalty-card-numbers-after-upgrade-retail.md">Resolve conflicts in loyalty card numbers after upgrade (Retail)</a></p>
<p><a href="upgrade-to-microsoft-dynamics-ax-2012.md">Upgrade to Microsoft Dynamics AX 2012</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Support for earlier versions

In AX 2012 R3, the loyalty feature has been redesigned. Loyalty programs and loyalty rewards were introduced, and loyalty schemes were redesigned to work with the loyalty programs. Also, the concept of loyalty customers was deprecated. In addition, in earlier versions of Retail, the loyalty feature recognized only one loyalty scheme and one type of loyalty point.

When you upgraded from an earlier version of Retail to the current version, in earlier versions of Microsoft Dynamics AX 2012 for Retail, after the main system upgrade was complete, all Microsoft Dynamics AX for Retail POS registers had to be upgraded at the same time to maintain data connectivity. In Microsoft Dynamics AX 2012 R2, new functionality was introduced that lets an earlier version of Retail POS communicate with the current version of Retail POS.

All POS registers in a specific retail channel must use the same version of Microsoft Dynamics AX. However, by using the new upgrade functionality, loyalty transactions from registers that are still using an earlier version of Microsoft Dynamics AX can be sent to headquarters as you work to upgrade all your retail stores.

If backward compatibility mode is enabled for Microsoft Dynamics AX, the following loyalty options are not available on registers that are using an earlier version of Retail. Also, if you try to use any of these features in the Microsoft Dynamics AX client, a warning message is displayed.

  - Adding loyalty program tiers to earning rules

  - Adding the sales transaction count activity type to earning rules

  - Adding loyalty program tiers to redemption rules

  - Adding categories, products, or product variants to redemption rules

  - Adding the **Payment by quantity** redemption type to redemption rules

  - Using non-redeemable reward points in earning or redemption rules

  - Deleting redemption rules in a valid period

  - Associating more than one reward point ID to one loyalty scheme

  - Associating more than one loyalty scheme with one loyalty program

  - Creating program tiers for loyalty programs

  - Associating more than one loyalty program with one loyalty card


> [!NOTE]
> <P>Follow these steps to determine whether backward compatibility mode is enabled for your system. Click <STRONG>System administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Licensing</STRONG> &gt; <STRONG>License configuration</STRONG>. In the <STRONG>License configuration</STRONG> form, expand the <STRONG>Retail</STRONG> node, and then expand the <STRONG>Retail scheduler</STRONG> node.</P>
> <P>If the <STRONG>Retail Commerce Data Exchange backward compatibility</STRONG> check box is selected, backward compatibility mode is enabled.</P>



The following table describes the task in Microsoft Dynamics AX that you perform to support earlier versions of the loyalty feature.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Upgrade your point-of-sale (POS) registers to use the AX 2012 R3 loyalty features</p></td>
<td><p>As you upgrade your point-of-sale registers to AX 2012 R3, POS registers that still use an earlier version of Microsoft Dynamics AX can continue to process loyalty transactions.</p></td>
<td><p><a href="scenario-upgrade-a-retail-system.md">Scenario: Upgrade a Retail system</a></p>
<p><a href="support-for-previous-pos-versions.md">Support for Previous POS Versions</a></p></td>
</tr>
</tbody>
</table>


Back to top

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


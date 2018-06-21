---
title: Set up information for trade allowance agreements
TOCTitle: Set up information for trade allowance agreements
ms:assetid: dcaf3d9a-1dc1-4f60-9645-99414f898b75
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497837(v=AX.60)
ms:contentKeyID: 62395573
ms.date: 05/30/2014
mtps_version: v=AX.60
---

# Set up information for trade allowance agreements [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The procedures in this topic explain how to set up the information that you need in order to create trade allowance agreements. A trade allowance agreement is an agreement between a producer and a distributor to temporarily reduce prices for items or services. This temporary reduction allows the distributor to offer a sale or promotion to customers for a limited time. The information that you enter by using these procedures becomes options that you can select in the form that you use to set up a trade allowance agreement.

## Prerequisites

Before you set up trade allowance agreements, you must create customer category hierarchy groups. For more information, see [Set up customer category hierarchies for trade allowance](set-up-customer-category-hierarchies-for-trade-allowance.md).

## Set up periods for trade allowance agreements

Use this procedure to set up periods during which a promotion or sale will be active. For example, every year you may offer a New Year’s promotion that is available from December 26 through January 5.

1.  Click **Trade allowance management** \> **Setup** \> **Trade allowance agreement period**.

2.  In the **Trade allowance agreement period** form, click **New**.

3.  In the **Trade allowance agreement period** field, enter the name of the period. For example, **New Year’s Celebration** or **Summer sale**.

4.  On the **Dates** FastTab, in the **Order** field group, enter the first and last date on which a customer can order an item to qualify for the promotion.

5.  In the **Request** field group, enter the first and last date on which an item can be shipped to qualify for the promotion. For example, if the trade allowance agreement period is active between 1 May, 2014 and 30 June, 2014, your organization might determine that the ship dates can fall outside of the trade allowance agreement period.

6.  In the **Requested receipt** field group, enter the first and last date on which an order can be entered for receipt to qualify for the promotion. Following the example above, with a trade allowance agreement period between 1 May, 2014 and 30 June, 2014, your organization might determine that the customer receipt dates can extend the period end date by two weeks, or 14 July, 2014,

7.  In the **Performance** field group, enter the first and last date that any action can be taken in order to receive a lump sum payout from the promotion.

## Set up marketing objectives

Use this procedure to set up marketing objectives or explanations of the promotions and sales that are offered by your organization. For example, you might create an objective called **End of summer special** that includes a description of **Discounts for all summer apparel**.

1.  Click **Trade allowance management** \> **Setup** \> **Marketing objective**.

2.  In the **Marketing objective** form, click **New**.

3.  In the **Marketing objective** field, enter the name of the objective, and then add a brief description or explanation of the objective.

## Set up categories for merchandising events

Use this procedure to set up categories for the merchandising events held by your organization. For example, you might create a category for holiday discounts, a category for seasonal sales, and another for yearly discount savings.

1.  Click **Trade allowance management** \> **Setup** \> **Merchandising event category**.

2.  In the **Merchandising event category** form, click **New**.

3.  In the **Category** field, enter the category name for the event and then enter a brief description of the category.

4.  In the **Default type** field, select the category type for the event.

## See also

Create a trade allowance agreement

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


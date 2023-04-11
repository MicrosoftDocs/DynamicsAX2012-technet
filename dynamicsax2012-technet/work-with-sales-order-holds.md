---
title: Work with sales order holds
TOCTitle: Work with sales order holds
ms:assetid: 14cdea9d-2abb-4551-b340-7f059d8242aa
ms:mtpsurl: https://technet.microsoft.com/library/Dn631649(v=AX.60)
ms:contentKeyID: 62224164
author: tonyafehr
ms.date: 04/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Work with sales order holds 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to place customer sales orders on hold, how to work with order hold checkouts, and how to remove order holds. An order might be placed on hold for a variety of reasons. For example, you might hold an order until a customer address or payment method can be verified or until a manager can review the customer’s credit limit.

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
<td><p>Set up order hold codes</p></td>
<td><p><a href="set-up-codes-for-order-holds.md">Set up codes for order holds</a></p></td>
</tr>
<tr class="even">
<td><p>Create sales orders</p></td>
<td><p>Create a sales order in Call center</p></td>
</tr>
</tbody>
</table>


## Place a customer order on hold

Use this procedure to place a sales order on hold.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  Select the sales order to be placed on hold, and on the **Action Pane**, on the **Sales order** tab, in the **Functions** group, click **Order holds**.

3.  In the **Order hold** form, click **New**.

4.  In the **Hold code** field, select the appropriate order hold code for the sales order.

5.  In the **Comment** field, enter a comment about the hold.

6.  In the lower pane, on the **Hold notes** tab, enter additional information about the sales order hold and close the form.

## Check out a sales order that is on hold

When a sales order is on hold, you might need to update the order with additional information, or you might want to check out the sales order for a length of time as you continue to work on it. You can check out a sales order, check the order back in, and when necessary, override the checkout of another user. Use this procedure to check out or check in a sales order, or override the checkout of a sales order that is on hold.

1.  Click **Call center** \> **Common** \> **Sales orders on hold**. To check out or check in a sales order, or override a checkout, do one of the following:
    
      - Check out – Select the sales order that you want to check out, and on the **Action Pane**, on the **Manage** tab, in the **Modify** group, click **Check out**.
    
      - Check in – Select the sales order that you want to check in, and on the **Action Pane**, on the **Manage** tab, in the **Modify** group, click **Clear checkout**.
    
      - Override a checkout – Select the sales order that you want to check in by overriding another user’s checkout, and on the **Action Pane**, on the **Manage** tab, in the **Modify** group, click **Override checkout**.

## Remove holds on sales orders

When an order is ready to be completed, you must remove the hold before you can complete the order process. Use this procedure to remove a hold on a sales order.

1.  Click **Call center** \> **Common** \> **Sales orders on hold**.

2.  Select the sales order that you want to remove the hold from, and on the **Action Pane**, on the **Manage** tab, in the **Modify** group, click **Clear holds**.

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
<td><p>Call center</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager</p>
<p>Customer service representative</p></td>
</tr>
</tbody>
</table>


## See also

Create a sales order in Call center

  



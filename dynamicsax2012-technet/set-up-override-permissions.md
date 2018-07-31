---
title: Set up override permissions
TOCTitle: Set up override permissions
ms:assetid: 263c7700-0b0f-4aa0-ba1b-fb3ed17e61f3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497732(v=AX.60)
ms:contentKeyID: 62221421
ms.date: 07/24/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRPriceOverrideMarkUpGroup
audience: Application User
ms.search.region: Global
---

# Set up override permissions 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up permissions to allow users to override item prices, margin costs, discounts, and order charges. Overrides can be used to increase or decrease original charge amounts at either the header level or line level of an order. To complete an override, a user must be assigned to a role that has been given the appropriate permissions. When override permissions are assigned, the maximum amount by which an override can increase or decrease costs is determined.

## Prerequisite: Enable order price control

Before you can set up overrides, you must enable order price control for the call center. Enabling order price control enables overrides, price details, and margin alerts.

To enable order price control, follow these steps:

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Call centers**.

2.  Select a call center, and on the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  In the **Call center - %1** form, on the **General** FastTab, select the **Enable order price control** check box.

## Set up permissions for overrides

Use this procedure to set up override permissions for one or more roles. You can set up permissions for more than one role, and each role can have a different level of permissions. For example, you might create a new charge override permission for the Sales clerk role to allow sales clerks to override charges on a sales order for up to 5 percent less than the amount on the sales order. You could then create another charge override permission for the Sales manager role to allow sales managers to override charges on a sales order for up to 10 percent more than the amount on the sales order lines or header.

1.  Click **Call center** \> **Setup** \> **Sales order** \> **Overrides** \> **Override permissions**.

2.  In the **Override permissions** form, click **New**.

3.  In the **Role** field, select a role from the list.

4.  In the **Price override costs** field, select whether the override is based on the primary cost of an item or on the marginal cost.

5.  In the **Cost markup percentage** field, enter the percentage over the selected cost that represents the lowest price that users in this role can set. For example, if the limit is set at 5% over the Item cost, users in the role will not be able to set a new price that is less than Item cost+5% \*Item cost.
    
    If this field contains zero (0), users can still override the item price to *less* than the item cost.

6.  In the **Total discount override percentage** field, enter the total percentage by which a user can decrease the sales total on a sales order.

7.  If users are allowed to increase or decrease additional charges to a sales order, in the **Miscellaneous charges** field group, select the **Add** check box, and then enter the allowed percentages in the **Override increase percentage** and **Override decrease percentage** fields.

8.  To allow overrides for a customer on the return payment method, on the **Returns** FastTab, select the **Allow alternate payment** check box.

9.  In the **Customer credit adjustments** field group, enter the maximum and minimum percentages by which a user can increase or decrease the customer’s return credit amount.
    
    If these fields contain a zero (0), users can increase or decrease the return credit by any amount.

  



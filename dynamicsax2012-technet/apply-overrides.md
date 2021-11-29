---
title: Apply overrides
TOCTitle: Apply overrides
ms:assetid: 972a780a-263c-4072-a571-a0c065a1c7d8
ms:mtpsurl: https://technet.microsoft.com/library/Dn631657(v=AX.60)
ms:contentKeyID: 62504014
author: Khairunj
ms.author: daxcpft
ms.date: 06/11/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Apply overrides 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to override item prices or charges on a sales order and how to complete a discount override on a sales order. Use overrides to increase or decrease an original charge amount at either the header level or line level of an order. To complete an override, you must be assigned to a role that has been given the appropriate permissions, or your manager must be present to enter their operator ID and password.

## Prerequisites

Before you can override prices, charges, or discounts, price details must be enabled and you must be given permissions to complete an override. For more information, see [Set up override permissions](set-up-override-permissions.md).

## Override item prices on a sales order

When you create a sales order for a customer, you can override the price of one or more line items on the sale order. You can override a price based on it item cost or the margin cost of the item. Use this procedure to override an item price on a sales order. For more information about creating a sales order in the **Call center**, see [Create sales orders in the call center](create-sales-orders-in-the-call-center.md).

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

3.  In the **Create sales order** form, enter the customer and sales order information, and then click **OK**.

4.  In the **Sales order** form, enter additional information about the sales order.

5.  On the **Action Pane**, on the **Sales order** tab, in the **Show** group, click **Line view**.

6.  On the **Sales order lines** FastTab, click **Add line**.

7.  Select the item and related information, and in the **Unit price** field, enter the override price of the item and then tab out of the field.

8.  In the **Price override** form, select the code for the override. At this point, if you don’t have the required permissions, your manager must enter their operator ID and password.

9.  Click **OK**. The item unit price on the sales order line is updated to reflect your change.

## Override charges on a sales order line or a sales order

You can override charges that are applied to a sales order total or a sales order line. For example, you might lower the freight charge for a customer or raise the item processing charges. Use the following procedures to override charges on a sales order or on a sales order line.

## Override charges on a sales order line

Use this procedure to override charges on a sales order.

1.  In the **Sales order** form, on the **Action Pane**, on the **Sales order** tab, in the **Show** group, click **Line view**.

2.  On the **Sales order lines** FastTab, click **Add line**.

3.  Select the item, and then click **Financials** \> **Maintain charges**.

4.  In the **Charges transactions** form, select a charge code line, or click **New** to add a new charge code.
    
    If you created a new charge code, enter the information.

5.  In the **Charges value** field, enter the amount removed or added by the charge override and then tab out of the field.

6.  In the **Charge override login** form, select the code for the override. At this point, if you don’t have the required permissions, your manager must enter their operator ID and password.

7.  Click **OK**. The charge on the sales order line is updated to reflect your change.

## Override charges on a sales order

Use this procedure to override charges on a sales order line.

1.  In the **Sales order** form, on the **Action Pane**, on the **Sell** tab, click **Charges**.

2.  In the **Charges transactions** form, click **New**, and in the **Charges code** field, select the charge code for the override.

3.  In the **Charges value** field, enter the overriding charge amount, and then tab out of the field.

4.  In the **Charge override login** form, select the code for the override At this point, if you don’t have the required permissions, your manager must enter their operator ID and password.

5.  Click **OK**. The charges on the sales order are updated to reflect your change.

## See also

[Create sales orders in the call center](create-sales-orders-in-the-call-center.md)

  



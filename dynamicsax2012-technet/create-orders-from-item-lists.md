---
title: Create orders from item lists
TOCTitle: Create orders from item lists
ms:assetid: 02b52340-d827-47a3-b54b-34c3873748cc
ms:mtpsurl: https://technet.microsoft.com/library/Dn631645(v=AX.60)
ms:contentKeyID: 62433322
author: Khairunj
ms.author: daxcpft
ms.date: 06/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create orders from item lists 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to use item lists to add items to sales orders. An item list is a list of items that a customer habitually buys, including quantities. When you create a new sales order for a customer, instead of adding items line by line, you can select the item list that has been created for the customer.

For information about how to create item lists for customers, see [Set up item lists](set-up-item-lists.md).

## Add an item list to a sales order

Use this procedure to add an item list to a sales order.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

3.  In the **Create sales order** form, enter the necessary information and click **OK**.
    
    For more information about how to create a sales order, see Create a sales order in Call center.

4.  In the **Sales order** form, on the **Action Pane**, on the **Sales order** tab, in the **Show** group, click **Line view**.

5.  On the **Sales order lines** FastTab, click **Sales order line** \> **From item list**.

6.  In the **Item list** form, select the item list to add to the sales order.

7.  If you are adding more than one item list to the sales order, click **Copy**.
    
    Repeat this step to add more item lists.

8.  If you are adding just one item list, or when you are ready to add the last item list, click **Copy and close**.

9.  Finish adding the necessary information to the sales order.

## Modify an item list in a sales order form

After you copy an item list to a sales order, you can modify information or remove items from the list. Changes that you make to the item list after you have copied it in to the **Sales order** form don’t affect the stored item list. To modify the original item list, use the **Item list** form. Use this procedure to modify the contents of an item list that is copied to a sales order.

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order** or open an existing sales order.

3.  In the **Sales order** form, on the **Sales order lines** FastTab, select the line item that you want to modify.

4.  Modify or remove the line item.

5.  Update any other line items as necessary and then close the form.

## Create an item list from a sales order

Use this procedure to automatically generate a customer-specific item list from a sales order that is created for the customer.

1.  Click **Call center** \> **Common** \> **All customers**.

2.  In the **All customers** list, select a customer record, and then, on the **Action Pane**, on the **Customer** tab, in the **Maintain** group, click **Edit**.

3.  On the **Sales order defaults** FastTab, in the **Item list** field group, select the **Enable item list** check box and then close the form.

4.  Click **Sales and marketing** \> **Periodic** \> **Item list generation**.

5.  In the **Generate item lists per customer** form, on the **General** tab, select whether to generate the item list based on days or orders, and then, in the **Value** field, the enter the number of days or orders that you want to base the list on. For example, if you select **Number of days**, the item list is generated based on the sales orders that were created within the number of days that you specify. If you select **Number of orders**, the item list is generated based on the number of previous orders that you specify.

6.  In the **Minimum quantity** field, enter the minimum quantity of items that must be ordered to be included in the item list. For example, if you enter 5, only order lines that include five or more units of an item will be included in the item list.

7.  In the **Customer account** field, select the customer account that you are generating the item list for, and then click **OK**.

## See also

[Create orders from item lists](create-orders-from-item-lists.md)

  



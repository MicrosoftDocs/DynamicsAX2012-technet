---
title: Create sales orders in the call center
TOCTitle: Create sales orders in the call center
ms:assetid: f82432c3-df07-4130-8865-a49b6c1be630
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn631664(v=AX.60)
ms:contentKeyID: 62490078
ms.date: 06/07/2014
mtps_version: v=AX.60
---

# Create sales orders in the call center 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create a sales order in the call center and how to complete additional tasks in the sales order. For example, you can search for products, add items for up-selling or cross-selling, add a coupon to a sales order, and add notes to a sales order header or line.

## Create a sales order in the call center

1.  Click **Call center** \> **Common** \> **All sales orders**.

2.  On the **Action Pane** on the **Sales order** tab, in the **New** group, click **Sales order**.

3.  In the **Create sales order** form, select the customer account, enter additional information about the customer, and then click **OK**.

4.  In the **Sales order** form, on the **Action Pane**, click **Header view** and enter information about the sales order.

5.  After you enter the general information for the sales order, on the **Action Pane**, click **Line view** to add line items to the sales order.

6.  On the **Sales order lines** FastTab, click **Add line** to add a single line item, or click **Add lines** to add multiple lines.
    
    For information about how to add an item list to the sales order, see [Create orders from item lists](create-orders-from-item-lists.md).

## Search for products from a sales order

You can perform full-text searches in the **Sales order** form. Use this procedure to search for a product from within a sales order.

1.  Click **Call center** \> **Common** \> **All sales orders**. Create a new sales order or select an existing order.

2.  In the sales order, on the **Sales order lines** FastTab, click **Add line**.

3.  In the **Item number** field, enter a search term, and then press the TAB key.
    
    The **Item Search** form opens and shows the search results. The **Available physical** column shows how many items are available in inventory.

4.  To add an item in the search results to the sales order, select the item, and then, in the **Sales quantity** field, enter a quantity.

5.  Click **Apply** to add the selected item to the sales order and keep the **Item Search** form open.
    
    –or–
    
    Click **Create** to add the item to the sales order and close the **Item Search** form.

## Add items that are eligible for cross-sell or up-sell

When you add an item to a sales order and that item has been marked as eligible for cross-sell or up-sell, you will be prompted to offer the corresponding item. For more information about how to set up items for cross-sell or up-sell, see [Set up products for cross-selling and up-selling](set-up-products-for-cross-selling-and-up-selling.md). Use this procedure to add an item that is eligible for cross-sell or up-sell to a sales order.

1.  Click **Call center** \> **Common** \> **All sales orders**. Create a new sales order or select an existing order.

2.  In the **Sales order** form, on the **Sales order lines** FastTab, click **Add line**.

3.  In the **Item number** field, select the item number of the item that the customer is purchasing, and then, in the **Quantity** field, enter the quantity of the item that the customer is purchasing.

4.  Press CTRL+S to save your changes, or tab out of the field.
    
    The **Up-sell/cross-sell items** form will open.

5.  Use the item information and the script in the **Up-sell/cross-sell items** form to offer the customer an alternative item.

6.  Update the sales order line items as necessary.

## Add a coupon to a sales order

You can add a coupon to a sales order. The coupon can offer either an amount discount or a percentage discount on the sales order total. For information about how to set up coupons, see [Set up coupons for customer orders in the call center](set-up-coupons-for-customer-orders-in-the-call-center.md). Use this procedure to add a coupon to a sales order.

1.  Click **Call center** \> **Common** \> **All sales orders**. Create a new sales order or select an existing order.

2.  In the **Sales order** form, on the **Action Pane**, on the **Manage** tab, in the **Coupons** group, click **Coupons**.

3.  In the **Coupons** form, select a coupon from the list and then click **Close**, or click **New** to add a coupon to the list.

4.  If you select to add a new coupon, in the **Coupon ID** field, select the ID of the coupon that you want to add to the sales order.

5.  Close the form.

## Add notes to a sales order header or sales order line

You can attach a note to a sales order as a whole or attach one to a sales order line. Notes that are attached to a sales order or sales order line can then be printed on the picking list, packing slip, or invoice. Use these procedures to add a note to a sales order header or sales order line.

To add a note to the sales order header, follow these steps:

1.  Click **Call center** \> **Common** \> **All sales orders**. Create a new sales order or select an existing order.

2.  In the **Sales order** form, on the **Action Pane**, on the **Sales order** tab, in the **Attachments** group, click **Notes**.

3.  In the **Notes** form, click **New**, and in the **Select note category** field, select **Order header**.

4.  On the **Overview** tab, select the note type and then enter a brief description of the note.

5.  In the **Restriction** field, select whether the note should remain internal to the organization, and then, in the **Note** text box, enter the text of the note. Click **Close**.

To add a note to a sales order line, follow these steps:

1.  Click **Call center** \> **Common** \> **All sales orders**. Create a new sales order or select an existing order.

2.  In the **Sales order** form, on the **Sales order lines** FastTab, select the line item that you want to add a note to, and then click **Sales order line** \> **Attachments** \> **Notes**.

3.  In the **Notes** form, click **New**, and in the **Select note category** field, select **Order line**.

4.  On the **Overview** tab, select the note type and then enter a brief description of the note.

5.  In the **Restriction** field, select whether the note should remain internal to the organization, and then, in the **Note** text box, enter the text of the note. Click **Close**.

## See also

[Complete common tasks in the Call center by using the Customer service form](complete-common-tasks-in-the-call-center-by-using-the-customer-service-form.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


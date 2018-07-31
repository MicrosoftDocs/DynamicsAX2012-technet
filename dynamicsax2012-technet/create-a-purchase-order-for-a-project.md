---
title: Create a purchase order for a project
TOCTitle: Create a purchase order for a project
ms:assetid: c55b6a87-2aa0-4fc0-b1e4-9b83f79142bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550751(v=AX.60)
ms:contentKeyID: 36811428
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- item requirement
- create purchase order
audience: Application User
ms.search.region: Global
---

# Create a purchase order for a project 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create purchase orders in **Project management and accounting** by using one of the four procedures in this topic. The method that you use to create a purchase order is determined by the purpose of the purchase order, by when the purchased items are consumed, and by when they are charged to a project. For more information about how to choose a method, see [About creating purchase orders for projects](about-creating-purchase-orders-for-projects.md).

## Create a purchase order for a project

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select or open a project for which you want to create a purchase order.

3.  On the **Action Pane**, on the **Manage** tab, in the **New** group, click **Item task**, and then click **Purchase order**.

4.  In the **Create purchase order** form, select the vendor that you want to place the purchase order with, enter other information as appropriate, and then click **OK**
    

    > [!TIP]
    > <P>For information about the field on the form, see <A href="https://technet.microsoft.com/en-us/library/aa570189(v=ax.60)">Create purchase order (form)</A>.</P>



5.  In the **Purchase order** form, in the **Purchase order lines** table, click **Add line**.

6.  Enter an item number, quantity, unit, and unit price.

7.  On the **Line details** FastTab, enter additional information as appropriate.

8.  Repeat step 5 through 7 for each order line that is required for the purchase order.


> [!TIP]
> <P>To add multiple purchase order lines at the same time, click <STRONG>Add lines</STRONG> in the <STRONG>Purchase order lines</STRONG> table to open the <STRONG>Create lines</STRONG> form for purchase orders.</P>



## Create a project purchase order from the project purchase order list

1.  Click **Project management and accounting** \> **Common** \> **Item tasks** \> **Project purchase orders**.

2.  On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

3.  In the **Create purchase order** form, select the vendor that you want to place the purchase order with, enter other information as appropriate, and then click **OK**.

4.  In the **Purchase order** form, in the **Purchase order lines** table, click **Add line**.

5.  Enter an item number, quantity, unit, unit price, and other information as appropriate.

6.  On the **Line details** FastTab, enter additional information as appropriate.

7.  Repeat step 4 through 6 for each order line that is required for the purchase order.

## Create a project purchase order from an item requirement

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select or open a project for which you want to create a purchase order from an item requirement.

3.  On the **Action Pane**, on the **Manage** tab, in the **Related information** group, click **Item tasks**, and then click **Item requirements**.

4.  In the **Item requirements** form, click **Functions**, and then click **Create purchase order**.

5.  In the **Create purchase order** form, on the **Overview** tab, in the **Include** column, select the check box for each item line that you want to include in the purchase order. To add all the items to the purchase order, select the **Include all** check box.

6.  Optional: Select the **Adjust quantity to within permitted range** check box to adjust the quantity ordered to a minimum or maximum amount from the item table.

7.  Optional: Select the **Search for purchase agreements** check box to automatically search for purchase agreements.

8.  On the **Price/discount** tab, in the **Discount** group, enter any discount amounts or percentages that apply to the selected line.

9.  If necessary, in the **Price unit** field, change the number of units to which the specified price applies.

10. If you want to add a one-time fixed charge to the invoice, enter the charge amount in the **Charges on purchases** field.

## Create a project purchase order from a sales order

1.  Click **Project management and accounting** \> **Common** \> **Item tasks** \> **Project sales orders**.

2.  Select or open a sales order.

3.  On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Purchase order**.

4.  In the **Create purchase order** form, on the **Overview** tab, in the **Include** column, select the check box for each item that you want to include in the purchase order. To include all the items in the sales order, select the **Include all** check box.

5.  Optional: Select the **Adjust quantity to within permitted range** check box to adjust the quantity ordered to a minimum or maximum amount from the item table.

6.  Optional: Select the **Search for purchase agreements** check box to automatically search for purchase agreements.

7.  On the **Price/discount** tab, in the **Discount** group, enter any discount amounts or percentages that apply to the selected line.

8.  If necessary, in the **Price unit** field, change the number of units to which the specified price applies.

9.  If you want to add a one-time fixed charge to the invoice, enter the charge amount in the **Charges on purchases** field.

## See also

[About creating purchase orders for projects](about-creating-purchase-orders-for-projects.md)

[View item requirements](view-item-requirements.md)

[Consume item requirements in a project](consume-item-requirements-in-a-project.md)

[Item requirements (form)](https://technet.microsoft.com/en-us/library/aa552021\(v=ax.60\))

[Create a purchase order from a sales order](create-a-purchase-order-from-a-sales-order.md)

[Create a sales order for a project](create-a-sales-order-for-a-project.md)

[Update quantity on purchase orders and sales orders](update-quantity-on-purchase-orders-and-sales-orders.md)

[Create purchase order (form)](https://technet.microsoft.com/en-us/library/aa570189\(v=ax.60\))

  



---
title: Working with purchase orders (Retail essentials)
TOCTitle: Working with purchase orders (Retail essentials)
ms:assetid: d52094cb-311e-48ce-a716-d87247443c39
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736961(v=AX.60)
ms:contentKeyID: 62200438
ms.date: 01/14/2015
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.PurchTableListPage
---

# Working with purchase orders (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create purchase orders. You can create a purchase order from an existing sales order, or you can create a purchase order of one of the following types:

  - **Journal** – Use this type as a purchase order draft. This type does not affect stock quantities or generate item transactions.

  - **Purchase order** – Use this type when the vendor confirms an order.

  - **Returned order** – Use this type when you return purchased items to the vendor. The returned item number, or RMA number, that the vendor gives you must be entered on the **Other** tab.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Create a purchase order

Use this procedure to create a purchase order that has all the information that is required to purchase specific products at a specific price or for a specific delivery date from a vendor.

1.  Click **Retail essentials** \> **Inventory management** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order** to create a new purchase order.

2.  In the **Create purchase order** form, select a vendor account.

3.  On the **General** FastTab, in the **Purchase type** field, select the type of purchase order to create.

4.  Optional: Enter or modify the remaining information in the **Create purchase order** form, and then click **OK**. The new purchase order is displayed.

5.  In the **Line** view, on the **Purchase order lines** FastTab, click **Add line** or press CTRL+N to create a new purchase order line.

6.  On the purchase order line, specify at least an item or a procurement category, a purchase quantity, a unit of measure, and a unit price.

7.  On the **Line details** FastTab, on the **Delivery** tab, in the **Delivery date** field, enter a delivery date. If the purchase order is based on a purchase agreement, the delivery date must be in the validity period of the associated purchase agreement line.

8.  Repeat steps 5 through 7 to create additional lines for the purchase order.


> [!TIP]
> <UL>
> <LI>
> <P>To display inventory dimensions on the line in the <STRONG>Purchase order lines</STRONG> grid, click <STRONG>Purchase order line</STRONG> &gt; <STRONG>Dimensions</STRONG>.</P>
> <LI>
> <P>To validate a purchase order with a vendor before the purchase order is confirmed, on the <STRONG>Action Pane</STRONG>, on the <STRONG>Purchase</STRONG> tab, in the <STRONG>Generate</STRONG> group, click <STRONG>Purchase inquiry</STRONG>.</P></LI></UL>



## Create a purchase order from a sales order

Use this procedure to create a purchase order that is based on a sales order. The purchase order that is created reflects the products that you must purchase to fulfill the sales order.

1.  **Navigation Path Not Found** Select the sales order to create a purchase order for. Then, on the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Purchase order**.
    

    > [!TIP]
    > <P>You can also create a purchase order from a sales order on the <STRONG>All purchase orders</STRONG> list page. On the <STRONG>Action Pane</STRONG>, click <STRONG>From a sales order</STRONG>.</P>



2.  The **Create purchase order** form lists all open sales order lines and includes the preferred vendors. In the **Vendor account** field, change the vendor account number if a different account number is required.

3.  Select the **Include** check box to select the lines to generate purchase orders for. To select all lines, select the **Include all** check box.

4.  Click **Adjust quantity to within permitted range** to adjust the ordered quantity so that it matches the minimum or maximum quantity that is specified for the item.

5.  Click **Search for purchase agreements** to search for valid purchase agreements that you can base the new purchase order on.

6.  Click **Validate** to validate the lines that you have selected for the purchase order.

7.  Click **OK** to generate purchase orders that are based on your selections. Retail essentials creates one purchase order for each vendor account that is specified for the selected sales order lines.


> [!NOTE]
> <P>Each purchase order line is associated with the sales order line that led to the purchase. The relation to the purchase order is indicated on the sales order line. You can view the information about the relation in the <STRONG>Sales order</STRONG> form, on the <STRONG>Line details</STRONG> FastTab, on the <STRONG>Product</STRONG> tab, in the <STRONG>Reference lot</STRONG>, <STRONG>Reference type</STRONG>, and <STRONG>Reference number</STRONG> reference fields. This relation guarantees that the costs from the current purchase are charged on the attached sales order.</P>
> <P>To create a direct delivery from a vendor to a customer, in the <STRONG>Sales order</STRONG> form, on the <STRONG>Action Pane</STRONG>, on the <STRONG>Sales order</STRONG> tab, in the <STRONG>New</STRONG> group, click <STRONG>Direct delivery</STRONG>. In the <STRONG>Create direct delivery</STRONG> form that is displayed, the <STRONG>Transfer delivery address</STRONG> check box is selected and is for information only.</P>



## See also

[Working with vendors (Retail essentials)](working-with-vendors-retail-essentials.md)

  



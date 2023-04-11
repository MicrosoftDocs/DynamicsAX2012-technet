---
title: Create a purchase order from a sales order
TOCTitle: Create a purchase order from a sales order
ms:assetid: 8fbb76c4-df41-4d31-bd52-2cb3a035bb56
ms:mtpsurl: https://technet.microsoft.com/library/Aa498365(v=AX.60)
ms:contentKeyID: 37832517
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a purchase order from a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a purchase order that is based on a sales order. When you create the purchase order, it reflects the products that you need to purchase in order to fulfill the sales order.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Select the sales order to create a purchase order for, and then on the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Purchase order**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select the sales order to create a purchase order for, and then on the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Purchase order**.
    

    > [!TIP]
    > <P>You can also create a purchase order from a sales order on the <STRONG>All purchase orders</STRONG> list page. On the <STRONG>Action Pane</STRONG>, click <STRONG>From a sales order</STRONG>.</P>



2.  The **Create purchase order** dialog box lists all open sales order lines and includes the preferred vendors. In the **Vendor account** field, change the vendor account number, if a different account number is required.
    

    > [!NOTE]
    > <P>You can set up a preferred vendor for an item in the <STRONG>Released products</STRONG> form. On the <STRONG>Plan</STRONG> tab, click <STRONG>Item coverage</STRONG> to open the <STRONG>Item coverage</STRONG> form. Here, you can set up the item per site, warehouse, location, color, size, and configuration. For more information, see <A href="https://technet.microsoft.com/library/aa619147(v=ax.60)">Item coverage (form)</A>.</P>



3.  Select the **Include** check box to select the lines to generate purchase orders for. To select all lines, select the **Include all** check box.

4.  Click **Adjust quantity to within permitted range** to adjust the ordered quantity so that it matches the minimum or maximum quantity that is specified for the item.

5.  Click **Search for purchase agreements** to search for valid purchase agreements that you can base the new purchase order on.

6.  Click **Validate** to validate the lines that you have selected for the purchase order.

7.  Click **OK** to generate purchase orders based on your selections. Microsoft Dynamics AX creates one purchase order for each vendor account that is specified for the selected sales order lines.


> [!NOTE]
> <P>Each purchase order line is associated with the sales order line that led to the purchase. On the sales order line, the relation to the purchase order is indicated on the <STRONG>Line details</STRONG> FastTab, on the <STRONG>Product</STRONG> tab, in the <STRONG>Reference lot</STRONG>, <STRONG>Reference type</STRONG>, and <STRONG>Reference number</STRONG> reference fields. This relation guarantees that the costs from the current purchase are charged on the attached sales order.</P>
> <P>To create a direct delivery from a vendor to a customer, on the <STRONG>Action Pane</STRONG>, on the <STRONG>Sales order</STRONG> tab, click <STRONG>Direct delivery</STRONG>. In the <STRONG>Create direct delivery</STRONG> form that is displayed, the <STRONG>Transfer delivery address</STRONG> check box is selected and is for information only.</P>



## See also

[Create a purchase order](create-a-purchase-order.md)

[Create a purchase order for a project](create-a-purchase-order-for-a-project.md)

[Create a purchase order for items that have an environmental impact](create-a-purchase-order-for-items-that-have-an-environmental-impact.md)

  



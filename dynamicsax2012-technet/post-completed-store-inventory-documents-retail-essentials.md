---
title: Post completed store inventory documents (Retail essentials)
TOCTitle: Post completed store inventory documents (Retail essentials)
ms:assetid: 2b586be1-23a4-4fc6-ba1c-a28938d24658
ms:mtpsurl: https://technet.microsoft.com/library/Dn716064(v=AX.60)
ms:contentKeyID: 62200329
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Post completed store inventory documents (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to validate and post store inventory documents after a purchase order or transfer order has been received. This topic also explains how to post a stock count when a physical count has been completed.


> [!NOTE]
> <P>The procedures in this topic describe one method that you can use to post purchase orders, transfer orders, and stock counts. However, your business might have different steps for these procedures.</P>



## Post a purchase order

To create and post a purchase order, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **All purchase orders**.

2.  In the **All purchase orders** list, click **Purchase order**.

3.  In the **Create purchase order** form, enter information about the vendor. You must enter a value in the **Vendor account** field.
    

    > [!NOTE]
    > <P>When you select a vendor account, the base data from the <STRONG>Vendors</STRONG> form is automatically added to the <STRONG>Create purchase order</STRONG> form. You can modify this information.</P>



4.  On the **General** FastTab, enter information about the purchase order. You must enter values in the **Invoice account** and **Currency** fields.

5.  Under **Storage dimensions**, select the warehouse and site that receive the items in the purchase order.

6.  Click **OK**.

7.  In the **Purchase order** form, click **Line view**, and then, on the **Purchase order lines** FastTab, select an item number.

8.  In the **Quantity** field, select the number of items to purchase.

9.  Enter or modify information in the remaining fields on the purchase order line.

10. To enter another item in the purchase order, click **Add line**, and then enter information about the item.

11. To enter sales tax, discounts, and other information about a line, select the line, and then click **Line details**. For more information about the fields in the **Purchase order** form, see [Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\)).

## Post a transfer order

To create and post a transfer order, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the **Transfer orders** form, click **New**.

3.  In the **From warehouse** field, select the warehouse that sends the products. In the **To warehouse** field, select the warehouse that receives the products.

4.  Click **Add** to add individual products, or click **Add products** to add groups or categories of products. For more information about the fields in the **Transfer orders** form, see [Transfer orders (form)](https://technet.microsoft.com/library/aa634530\(v=ax.60\)).

## Post a stock count

To enter and post a stock count, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Counting**.

2.  In the **Counting** form, click **New**.

3.  In the **Dimensions display** form, select the **Warehouse** check box, and then click **OK**.

4.  In the **Name** field, select **Inventory counting journal**.

5.  On the **Store inventory** tab, select the site and warehouse to create the count for. The site and warehouse are automatically copied to the lines. You can modify the site and warehouse if the products on the line are intended for a separate site or warehouse.

6.  On the top menu, click **Lines**.

7.  In the **Journal lines, inventory** form, in the **Item number** field, select the item to count.
    
    To add groups or categories of products, click **Add products**. In the **Add products** form, in the **Available products** section, select products, and then click **Add**. When you have finished selecting products to count, click **OK**.

8.  On the **Inventory dimensions** tab, you can modify the site and warehouse where the physical count of the item is performed, if a different site or warehouse is required.

9.  In the **Counted** field, enter the quantity of the item from the physical count.

10. In the **Quantity** field, enter the quantity of the item to post to inventory.

11. Optional: In the **Worker** field, enter the name of the worker who counted the item.

12. Click **Validate** to update quantities in a batch process, and then click **Post** to post the stock count.

## See also

[About working with store inventory](about-working-with-store-inventory.md)

  



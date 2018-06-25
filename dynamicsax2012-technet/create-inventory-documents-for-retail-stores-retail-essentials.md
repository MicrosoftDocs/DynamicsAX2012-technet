---
title: Create inventory documents for retail stores (Retail essentials)
TOCTitle: Create inventory documents for retail stores (Retail essentials)
ms:assetid: fa864c46-18e2-40e7-8e33-c879c8ab1dc4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736982(v=AX.60)
ms:contentKeyID: 62200459
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Create inventory documents for retail stores (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to track inventory in your stores by creating transfer orders and scheduled stock counts in Retail essentials.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Create a transfer order

You use transfer orders to handle items that are in transit between warehouses or stores within the same legal entity, but across different sites. You can receive transfer orders at a store by using Retail essentials. Use the following procedure to create a transfer order.

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the **Transfer orders** form, click **New**, or press CTRL+N to create a new transfer order.

3.  In the **From warehouse** and **To warehouse** fields, select the warehouses that send and receive the order.

4.  Click **Add** to add individual products, or click **Add products** to add groups or categories of products.

## Create a scheduled stock count

Use the following procedure to create a scheduled stock count.

Unscheduled stock counts can be created at a store. For more information, see Retail POS Help.

1.  Click **Retail essentials** \> **Inventory management** \> **Counting**.

2.  In the **Counting** form, click **New**, or press CTRL+N to create a new count record.

3.  In the **Dimensions** form, select the **Warehouse** check box, and then click **OK**.

4.  In the **Counting** form, in the **Name** field, select **Inventory counting journal**, and then click **Lines**.

5.  In the **Journal lines, inventory** form, click **New** to add individual items, or click **Add products** to add a group or multiple categories of items.

6.  Enter the item number or item numbers, and then, on the **Inventory dimensions** tab, in the **Site** field, select a location for the item to be counted.

7.  To update the quantity of the selected item, click **Validate**.

8.  To record the updated quantity, click **Post**.

## See also

[Manage store inventory overview (Retail essentials)](manage-store-inventory-overview-retail-essentials.md)

[Working with purchase orders (Retail essentials)](working-with-purchase-orders-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


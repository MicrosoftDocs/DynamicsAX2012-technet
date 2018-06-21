---
title: Create production orders manually
TOCTitle: Create production orders manually
ms:assetid: 16b0d630-522a-4dd7-92c5-d6eb494b3117
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569893(v=AX.60)
ms:contentKeyID: 37008244
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create production orders manually [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can add a new production order manually for any item in production. When you add a new production order manually, all base data information that is associated with the selected item is automatically available in the new order, and you can change it if necessary. The **Item number** and **Quantity** fields are blank when the order is first created. Select or enter the relevant information.

1.  Click **Production** \> **Production orders**.

2.  On the **Overview** tab, press CTRL+N to create a new order.
    
    The **Create production order** form opens.

3.  Select the item that you want to create a production order for in the **Item number** field. Each item is associated with a BOM, (a list of component items that are used to produce the item), a route, and a sequence of operations that produce the finished product.

4.  You must enter a value in the **Site** field. When you enter a site, the program displays a message asking whether to insert the active BOM version and the active route version that are associated with the site.

5.  In the **Type** field, select whether the production type is **Standard** or **Vendor**. (If the production type is **Vendor**, the production order is produced by a subcontractor.)

6.  Enter the number of items that you want to produce in the **Quantity** field.

7.  Select the delivery date from the calendar in the **Delivery** field, and enter the time that you want the production to be delivered.

8.  Click **OK**.

The production order is listed with the status **Created** in the **Production orders** form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


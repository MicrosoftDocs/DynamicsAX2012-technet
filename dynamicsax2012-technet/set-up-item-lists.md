---
title: Set up item lists
TOCTitle: Set up item lists
ms:assetid: c18fea21-376d-4cdf-9de0-18ef88bb69ce
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn631660(v=AX.60)
ms:contentKeyID: 62336122
ms.date: 05/14/2014
mtps_version: v=AX.60
---

# Set up item lists [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up item lists for customers. An item list is a list of items that a customer has purchased repeatedly during a time period that you specify. A customer service representative can quickly create a new sales order for the customer by selecting the list instead of adding items line by line. After the items in the list are added to the sales order, the information about each item can be changed as needed.

## Set up an item list

Use this procedure to create an item list for a customer.

1.  Click **Sales and marketing** \> **Setup** \> **Item list**.

2.  In the **Item list** form, click **New**, and then, in the **Item list** field, enter the item list ID if one is not automatically created.

3.  Enter a brief description of the item list, and then, on the **Items** FastTab, click **Add**.

4.  In the **Item number** field, select the item number for the item that you are adding to the list and then, in the **Quantity** field, enter the quantity ordered.

5.  Click **Dimensions** to add dimension information to the item.

6.  Add additional items as necessary, and then click **Item list generation** to generate the item list.

7.  In the **Generate item lists per customer** form, on the **General** tab, select whether the item list should be generated based on days or orders and then enter the number of days or orders in the **Value** field. For example, if you select **Number of days**, the item list will be generated based on the sales orders that were created within the number of days specified in the **Value** field. If you select **Number of orders**, the item list will be generated based on the number of previous orders that you specify in the **Value** field.

8.  In the **Minimum quantity** field, enter the minimum quantity of items that must be ordered to be included in the list. For example, if you enter 5, only order lines that include five or more units of an item will be included in the item list.

9.  Select the customer account that you are generating the item list for, and then click **OK**.

## Update an item list

Use this procedure to update the information in an item list.

1.  Click **Sales and marketing** \> **Setup** \> **Item list**.

2.  In the **Item list** form, select the item list that you want to update.

3.  Update the description, item list, or item dimensions as necessary.

4.  Click **Item list generation** to generate the updated item list.

## See also

Create orders from item lists

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


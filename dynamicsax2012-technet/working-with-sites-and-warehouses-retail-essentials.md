---
title: Working with sites and warehouses (Retail essentials)
TOCTitle: Working with sites and warehouses (Retail essentials)
ms:assetid: d5bc4e89-8568-4c02-8863-fca16fdacabd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736962(v=AX.60)
ms:contentKeyID: 62200439
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Working with sites and warehouses (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up a site to store products, and how to set up a warehouse for the site. A site is a grouping of business resources, such as warehouses and production units that share interrelated transactions, are located at a particular geographic location, and belong to a single legal entity. A single site cannot be shared by multiple legal entities.

Warehouses are usually a geographic location or a location that is set up for a particular function, such as a warehouse for spare parts. A warehouse can be assigned to only one site.

## Create a site

To set up a site, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Sites**.

2.  In the **Sites** form, click **New**.

3.  In the **Site** field, enter a unique identifier for the site.

4.  Optional: In the **Name** field, enter a short description of the site.

5.  On the **General** FastTab, in the **Order entry deadline group** field, select the order entry deadline group that applies to the selected site. The order entry deadline group specifies the order entry deadline for a transfer order.

6.  Select a time zone. If you do not specify a time zone, the time zone that is defined in the **Company information** form is used as the default time zone.

7.  Select the **Use transfer journals for movements within site** check box to automatically create a transfer journal to record the movement of items between warehouses at the same site.

8.  On the **Address** FastTab, click **Add**, and then enter address information for the site.

9.  On the **Hierarchy** FastTab, view a tree structure of sites. Click **Expand** to view the warehouses that are assigned to a site. Click **Collapse** to view only the sites.

10. On the **Warehouse management** FastTab, select the **Default inventory status ID** check box to set the default status that is entered for items at a site. You can change the inventory status for items before arrival, during arrival, or when the items are moved between sites.

## Create a warehouse and assign it to a site

To create a warehouse and then assign it to a site, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Warehouses**.

2.  In the **Warehouses** form, click **New**.

3.  In the **Warehouse** field, enter a unique identifier for the site.

4.  Optional: In the **Name** field, enter a descriptive name for the warehouse.

5.  On the **General** FastTab, in the **Site** field, select the site where the warehouse is located.

6.  Select a type for the warehouse. There are three types of warehouse: **Default**, **Quarantine**, and **Transit**.

7.  On the **Address** FastTab, view or modify the default delivery address for the warehouse.

8.  On the **Hierarchy** FastTab, view the resources that are associated with the site. These resources can include warehouses and production units. This information is presented in a tree structure that you can expand and collapse.

9.  On the **Retail** FastTab, set up the default warehouse information that is entered for retail product inventory. For example, you can specify the warehouse that is added automatically for returned products. You can overwrite this default information for specific transactions.

10. For information about the other fields in the **Warehouses** form, see [Warehouses (form)](https://technet.microsoft.com/en-us/library/aa620570\(v=ax.60\)).

## See also

[Set up site and warehouse hierarchies](set-up-site-and-warehouse-hierarchies.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


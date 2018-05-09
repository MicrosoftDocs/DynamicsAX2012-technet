---
title: (POL) Register external inventory availability
TOCTitle: (POL) Register external inventory availability
ms:assetid: 4f7f646b-49a6-4c58-a598-850b3b015483
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678200(v=AX.60)
ms:contentKeyID: 49386924
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Register external inventory availability 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Ext. inventory journal lines** form to register that items that are located in an external warehouse are available to be sold to customers.

Registering the availability of external inventory does not affect standard inventory management or inventory financial reporting.

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **External inventory**.

2.  Click **New** to create a new journal.

3.  Select the journal name.
    

    > [!NOTE]
    > <P>You must select the journal with the journal type of <STRONG>Ext. inventory transactions</STRONG>.</P>



4.  Click **Lines** to open the **Ext. inventory journal lines** form, where you can register the receipt of items in an external inventory warehouse.

5.  Select an item number for the item that is available in an external inventory warehouse, and then enter the date when the item will be available to be sold to customers.

6.  In the **Vendor account** field, select the vendor account that is associated with the external inventory.
    

    > [!NOTE]
    > <P>This vendor account is used for any purchase orders that you create from sales orders that include the item that you selected in step 5.</P>



7.  Enter the quantity of items that are available from the selected vendor in the external inventory warehouse.

8.  Select the unit of measurement for the selected item number.

9.  On the **Dimensions** tab, select the site where the external inventory warehouse is located.

10. In the **Warehouse** field, select the external inventory warehouse that contains the items.
    

    > [!NOTE]
    > <P>You must select a warehouse that is of the type <STRONG>External Inventory</STRONG>.</P>



11. Click **Post** to register that the items are available to be sold to customers.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


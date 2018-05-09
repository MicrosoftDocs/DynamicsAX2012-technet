---
title: (RUS) Create a BOM production order based on an inventory profile
TOCTitle: (RUS) Create a BOM production order based on an inventory profile
ms:assetid: e25e80ef-eb2b-4eac-8f79-6c3154885c03
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711712(v=AX.60)
ms:contentKeyID: 49388035
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create a BOM production order based on an inventory profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create a new bill of materials (BOM) production order for an item, the value of the **Inventory profile** field is specified on the BOM lines of the production order.

  - If the **Inventory profile** field is not active for the specified item, the dimension value is not specified.

  - If the **Inventory profile** field is specified on the BOM lines, the value of the **Inventory profile** field is specified on the BOM journal lines.

  - If the **Inventory profile** field is specified in the **Bills of materials** area of the **Inventory and warehouse management parameters** form, the specified value of the dimension inventory profile is entered on the BOM journal lines.

<!-- end list -->

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**. Create a new production order. For more information, see [Create production order (form)](https://technet.microsoft.com/en-us/library/aa497150\(v=ax.60\)).

2.  Select a production order, and then, on the **Action Pane**, click **Production details** \> **BOM** to manage a BOM production order.

3.  Click the **Inventory dimensions** tab.

4.  In the **Inventory profile** field, view the inventory profile for the BOM item.

## See also

[(RUS) Production orders (modified form)](https://technet.microsoft.com/en-us/library/jj733275\(v=ax.60\))

[(RUS) Specify an inventory profile in sales and purchase order lines when exploding a BOM](rus-specify-an-inventory-profile-in-sales-and-purchase-order-lines-when-exploding-a-bom.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


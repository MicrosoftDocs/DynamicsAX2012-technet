---
title: (RUS) Specify an inventory profile in sales and purchase order lines when exploding a BOM
TOCTitle: (RUS) Specify an inventory profile in sales and purchase order lines when exploding a BOM
ms:assetid: 9bfba623-6486-4ee4-a56d-82862b1d662d
ms:mtpsurl: https://technet.microsoft.com/library/JJ678533(v=AX.60)
ms:contentKeyID: 49387762
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Specify an inventory profile in sales and purchase order lines when exploding a BOM 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you explode a bill of materials (BOM) on sales order lines or purchase order lines, the value of the **Inventory profile** field is specified on the order lines that correspond to the BOM lines:

  - If the **Inventory profile** field is not active for the specified item, the dimension value is not specified.

  - If the **Inventory profile** field is specified in an order header, the value of the **Inventory profile** field is specified on the order lines.

  - If the **Inventory profile** dimension is specified on a BOM line, the value of the **Inventory profile** dimension is specified on the order lines.

  - If the inventory profile parameter is specified in the **Bills of materials** area of the **Inventory and warehouse management parameters** form, the value of the **Inventory profile** dimension on the order lines is populated with the value that is set in the **Inventory and warehouse management parameters** form.

<!-- end list -->

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double-click an existing purchase order to open the **Purchase order** form.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click an existing sales order to open the **Sales order** form.

2.  Select a purchase order line or a sales order line.

3.  On the **Purchase order lines** FastTab or the **Sales order lines** FastTab, in the **Item number** field, select an item for the BOM.

4.  Click **Sales order line** or **Purchase order line**, and then click **BOM lines** to open the **Explode BOM** form. For information about how to explode a BOM from a purchase order line or a sales order line, see [Explode a BOM from a purchase order line](explode-a-bom-from-a-purchase-order-line.md) or [Explode a BOM from a sales order line](explode-a-bom-from-a-sales-order-line.md).

5.  Click **OK** to move transactions from the **Explode BOM** form to the **Purchase order** form or the **Sales order** form.

6.  In the **Purchase order** form or the **Sales order** form, click the **Line details** FastTab, and then click the **Product** tab.

7.  In the **Inventory profile** field, select the inventory profile.

## See also

[(RUS) Explode BOM lines in purchase order (modified form)](https://technet.microsoft.com/library/jj711365\(v=ax.60\))

[(RUS) Explode BOM lines in sales order (modified form)](https://technet.microsoft.com/library/jj678426\(v=ax.60\))

[(RUS) Purchase orders (modified form)](https://technet.microsoft.com/library/jj733294\(v=ax.60\))

[(RUS) Sales orders (modified form)](https://technet.microsoft.com/library/jj733272\(v=ax.60\))

  



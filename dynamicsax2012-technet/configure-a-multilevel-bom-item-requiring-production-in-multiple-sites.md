---
title: Configure a multilevel BOM item requiring production in multiple sites
TOCTitle: Configure a multilevel BOM item requiring production in multiple sites
ms:assetid: 5afc2c06-a820-4234-8bba-42026a8ebf87
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242488(v=AX.60)
ms:contentKeyID: 36057355
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure a multilevel BOM item requiring production in multiple sites 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure a multilevel BOM requiring production in multiple sites, the following conditions must be true:

  - A product model exists. For more information, see [Create a product model](create-a-product-model.md).

  - Two production sites are set up.

  - The production warehouse assigned to the top level item is replenished by the production warehouse.

  - A product model for the top level item creates BOM and route versions at one site.

  - Subassembly product models create BOM and route versions at a different site than the top level model.

Use the **Product models** form to configure a multilevel BOM that requires production in multiple sites.

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Select the appropriate product model number and then click **Product model**.

3.  Click the **System** tab.

4.  Select **Site ID** in the **System variable** field to create the site ID system variable.

5.  Create a code that assigns the site ID system modeling variable to the product models of top-level item and subassemblies to create the BOM and route lines at different sites.
    
    For more information, see [Insert a node in the modeling tree](insert-a-node-in-the-modeling-tree.md).

6.  Add BOM lines to the product model.
    
    For more information, see [Insert a node in the modeling tree](insert-a-node-in-the-modeling-tree.md).
    
    The BOM lines are added to the BOM version assigned to the site ID identified by the site ID system variable.

7.  Add route lines to the product model.
    
    For more information, see [Insert a node in the modeling tree](insert-a-node-in-the-modeling-tree.md).
    
    The route lines are to the route version assigned to the site ID that is identified by the site ID system variable.

8.  Close the **Product model** form.

9.  In the **Product models** form, select **Approve** for the selected item number and close the form.

10. Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    Use the **Simple** view. For information about views, see [Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\)).

11. Click CTRL+N to create a new sales order header.

12. In the **Create sales order** form, select a customer.
    
      - Click **Yes** to copy existing customer information to the sales order.
    
      - Click **No** to create the new form without previous customer sales information.

13. In the **Order type** field, select the type of sales to create. For more information about order types, see [About sales order types](about-sales-order-types.md).

14. Enter or modify the remaining information in the **Create sales order** form, as needed, and then click **OK**.

15. In the sales order line, select or type a modeling enabled item number, quantity, unit, and unit price.

16. Press CTRL+N to create additional lines for the sales order, or press the Down arrow to add a new line.

17. Click **Configure line** to open the **Product Builder configuration** window and enter the configuration information.
    
    The product is configured according to the customer's specifications.

18. Click **OK** to approve the configuration.

19. In the **Product Builder approval** form, click **Calculate price**.

20. Click **Calculate delivery date** to calculate the earliest date available for shipping the item.

21. Click **OK** to approve the configuration and close the **Product Builder approval** form. The configured BOM and route versions are created.

22. Select the sales order line and then click the **Other** tab to confirm that the newly created BOM and route versions are assigned to the sales order line.

23. Close the **Sales order** form.

## See also

[Product models (form)](https://technet.microsoft.com/en-us/library/aa572853\(v=ax.60\))

  



---
title: Configure a product model to use a distribution site
TOCTitle: Configure a product model to use a distribution site
ms:assetid: 85ee2eac-d6f3-4e5a-a8e5-5e3fe0975b3f
ms:mtpsurl: https://technet.microsoft.com/library/Gg213179(v=AX.60)
ms:contentKeyID: 36676396
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure a product model to use a distribution site 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before the product model can be configured to a distribution site the following conditions must be set up:

  - A single level product model exists. For more information, see [Create a product model](create-a-product-model.md).

  - A distribution site exists.

  - A production site exists.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Use the **Product models** form to configure the product model.

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Select the appropriate product model number and then click **Open**.

3.  Click the **System** tab.

4.  Select **Site ID** in the **System variable** field to create the site ID system variable.

5.  Create code that assigns the site ID system modeling variable to the product model.
    
    For more information, see [Insert a node in the modeling tree](insert-a-node-in-the-modeling-tree.md).

6.  Add BOM lines to the product model.
    
    For more information, see [Insert a node in the modeling tree](insert-a-node-in-the-modeling-tree.md).
    
    The BOM lines will be added to the BOM version assigned the site ID identified by the site ID system variable.

7.  Add route lines to the product model.
    
    For more information, see [Insert a node in the modeling tree](insert-a-node-in-the-modeling-tree.md).
    
    The route lines are added to the route version assigned the site ID that is identified by the site ID system variable.

8.  Close the **Product model** form.

9.  In the **Product models** form, select **Approve** for the selected item number and close the form.

10. Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    Use the Simple view. For more information about views, see [Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\)).

11. Click **Sales order** on the **Action Pane**.

12. In the **Create sales order** form, select a customer.

13. In the **Order type** field on the **General** FastTab, select the type of sales order that you want to create. For more information about order types, see [About sales order types](about-sales-order-types.md).

14. Enter or modify the remaining information in the **Create sales order** form as needed, and then click **OK**.

15. In the sales order line, select or type a modeling-enabled item number, quantity, unit, and unit price.

16. Press CTRL+N to create additional lines for the sales order.

17. Click **Configure line** to open the **Product Builder configuration** window and enter the configuration information.
    
    The product is configured according to the customer's specifications.

18. Click **OK** to approve the configuration.

19. In the **Product Builder approval** form, click **Calculate price**.

20. Click **Calculate delivery date** to calculate the earliest date available for shipping the item.

21. Click **OK** to approve the configuration and close the **Product Builder approval** form. Approving the configuration initiates the creation of the configured BOM and Route versions.

22. Click the sales order line and then click the **Other** tab to confirm that the newly created BOM and Route versions are assigned to the sales order line.

23. Close the **Sales order** form.

## See also

[Configure a multilevel BOM item requiring production in multiple sites](configure-a-multilevel-bom-item-requiring-production-in-multiple-sites.md)

[Overview of Product Builder and multisite](overview-of-product-builder-and-multisite.md)

  



---
title: Set up a retail vendor hierarchy
TOCTitle: Set up a retail vendor hierarchy
ms:assetid: 742c505e-6f8e-419e-8f63-dbe822bb05a3
ms:mtpsurl: https://technet.microsoft.com/library/Hh597128(v=AX.60)
ms:contentKeyID: 39519182
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a retail vendor hierarchy 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

When you import products from a vendor, those products can be assigned to product categories in the vendor’s organization. In Retail, you can use the category hierarchy feature in Microsoft Dynamics AX to set up a category hierarchy. You can use the category hierarchy to group the products that you sell into the product categories that your organization uses. The retail product category hierarchy is referenced when you import products from vendors, create assortments, assign products to loyalty programs, and so on. When you import product data from vendors, you must map the vendor’s product categories to the categories that you create in the retail product category hierarchy. Complete the following tasks:

1.  Set up a retail product hierarchy.
    
    For more information about how to set up a retail product hierarchy, see [Set up a retail hierarchy](set-up-a-retail-hierarchy.md).

2.  Set up a retail vendor product hierarchy.

3.  Map the retail vendor product hierarchy to the vendor.

4.  Assign the vendor and vendor categories to the corresponding categories in the retail product hierarchy.
    
    For more information about how to assign vendors to a category in a retail product hierarchy, see [Set up a retail hierarchy](set-up-a-retail-hierarchy.md).

Use the following procedures to set up a retail vendor product hierarchy and assign the hierarchy to a vendor.


> [!NOTE]
> <P>You can assign only one retail vendor product hierarchy to each vendor.</P>



## Set up a retail vendor product hierarchy

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**. On the **Category hierarchies** list page, on the **Action Pane**, click **Category hierarchy**.

2.  In the **Create a category hierarchy** form, enter a unique name and an optional description for the hierarchy, and then click **Create**. By default, the new category hierarchy **Active** status is set to **Yes**.

3.  In the **Category hierarchy** form, on the **Action Pane**, click **New category node** to add the parent and child categories that your retail vendor uses to categorize its products. The first category that you create for a new category hierarchy is always the parent category of all other categories in the hierarchy.

4.  On the **Category attributes** FastTab, click **Add** to assign attributes to the category.

5.  On the **Commodity codes** FastTab, add subcategories from imported commodity codes.

6.  After you have finished setting up the category hierarchy, click **Close** to save the category hierarchy and return to the **Category hierarchies** list page.

7.  On the **Category hierarchies** list page, select the vendor category hierarchy that you created, and then, on the **Action Pane**, in the **Set up** group, click **Associate hierarchy type**.

8.  In the **Category hierarchy types** form, click **New** to add a new row.

9.  In the **Category hierarchy type** field, select **Retail vendor product hierarchy** in the list.

10. In the **Category hierarchy** field, select the vendor category hierarchy that you created.

For detailed information about the fields in the **Create a category hierarchy** form, see [Category hierarchy (form)](https://technet.microsoft.com/library/hh209524\(v=ax.60\)).

## Map a retail vendor product hierarchy to a vendor

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  On the **All vendors** list page, double-click the vendor to assign the retail vendor product hierarchy to.

3.  In the **Vendors** form, on the **Retail** FastTab, in the **Hierarchy** field, select the retail vendor product hierarchy for this vendor.

## See also

[About importing products from a vendor](about-importing-products-from-a-vendor.md)

[Set up a retail hierarchy](set-up-a-retail-hierarchy.md)

  



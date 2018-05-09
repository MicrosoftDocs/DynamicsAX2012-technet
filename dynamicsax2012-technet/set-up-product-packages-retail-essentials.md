---
title: Set up product packages (Retail essentials)
TOCTitle: Set up product packages (Retail essentials)
ms:assetid: 7e6bcea8-f99a-4af2-adf4-ff47a8586370
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736907(v=AX.60)
ms:contentKeyID: 62200385
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up product packages (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up products so that they can be ordered as a group from a vendor. This can make it easier to create purchase orders because you don’t have to select products individually when you add them to an order. Instead, you can select a package that includes the products. Order lines are updated automatically when the products in a package are changed.


> [!TIP]
> <P>The same item can be included in various packages for one or more vendors.</P>



After you add a package to a purchase order, you cannot remove a product from the order line if that product is part of a package. Instead you must remove the entire package and add the products to the purchase order individually.

To set up product packages, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Replenishment** \> **Product packages**.

2.  In the **Packages** form, click **New** to create a new package.

3.  Enter a package number and a description.

4.  Select the vendor that supplies the products in the package. This field is used to filter the list of available packages. To limit the availability of this package to a specific vendor, you can select the vendor account. Otherwise you can leave this field blank.

5.  On the **Line details** FastTab, click **Add** to add a product to the package, and then enter settings for the new product.

6.  To add multiple products to the package at the same time, follow these steps:
    
    1.  On the **Line details** FastTab, click **Add products**.
    
    2.  In the **Add products** form, select the products to add to the package.
        
        You can filter the list of products by selecting a category hierarchy. You can then select all products that are assigned to a specific category, and add those products to the package.
    
    3.  Enter settings for the new products.
        
        For more information, see the [Packages (form)](https://technet.microsoft.com/en-us/library/hh597320\(v=ax.60\)).


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Replenish inventory overview (Retail essentials)](replenish-inventory-overview-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


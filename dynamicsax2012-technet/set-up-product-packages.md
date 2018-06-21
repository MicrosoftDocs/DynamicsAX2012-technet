---
title: Set up product packages
TOCTitle: Set up product packages
ms:assetid: c8092119-b677-4904-80fa-7f9e36f4cabd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597239(v=AX.60)
ms:contentKeyID: 39519315
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up product packages [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A product package is a group of products that are ordered from a supplier. Packages can help you create purchase orders, because you do not have to select items individually. Instead, you can select a package that includes the items. Order lines are updated automatically when the items in a package are changed.

The same item can be included in various packages for one or more vendors. After you add a package to a purchase order, you cannot remove a product from the order line if that product is part of a package. Instead you must remove the entire package and add the products to the purchase order individually.

1.  Click **Retail** \> **Setup** \> **Replenishment** \> **Product packages**.

2.  In the **Packages** form, click **New** to create a new package.

3.  Enter a package number and a description.

4.  Select the vendor that supplies the products in the package. This field is used to filter the list of available packages. To limit the availability of this package to a specific vendor, you can select the vendor account. Otherwise you can leave this field blank.

5.  On the **Line details** FastTab, click **Add** to add a product to the package, and then enter settings for the new product.

6.  To add groups of products to the package at the same time, follow these steps:
    
    1.  Click **Add products** at the top of the form.
    
    2.  In the **Add products** form, select the products to add to the package.
        
        You can filter the list of products by selecting a category hierarchy. You can then select all products that are assigned to a specific category, and add those products to the package.
    
    3.  Enter settings for the new products.

## See also

[Packages (form)](https://technet.microsoft.com/en-us/library/hh597320\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


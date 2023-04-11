---
title: About inventory dimensions and dimension groups
TOCTitle: About inventory dimensions and dimension groups
ms:assetid: 553fd9b1-a2b9-42e2-a0ea-7168bf29838b
ms:mtpsurl: https://technet.microsoft.com/library/Aa549043(v=AX.60)
ms:contentKeyID: 39519140
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About inventory dimensions and dimension groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Inventory dimensions are assigned to products. Before you can assign inventory dimensions, you must set up inventory dimension groups.

## Inventory dimensions and inventory dimension groups

The inventory dimensions can be assigned to inventory dimension groups:

  - Product dimension group:
    
      - **Configuration**
    
      - **Color**
    
      - **Size**

  - Storage dimension group:
    
      - **Site**
    
      - **Warehouse**
    
      - **Location**
    
      - **Pallet ID**

  - Tracking dimension group:
    
      - **Batch number**
    
      - **Serial number**

Storage dimension groups and tracking dimension groups are set up in a similar manner. However, product dimension groups are configured and used differently.

## Product dimension groups

A product dimension group is used as the basis for variants that are created for a product master. Products of the **Product master** subtype must be associated with a product dimension group.

After you have created a product master and associated it with a product dimension group, you can create product dimensions for the product master. The dimensions control the product variants that are created for the product master. The number of product variants equals the number of possible combinations of product dimensions. For more information about product dimensions, see [About product dimensions](about-product-dimensions.md). For information about how to create product variants based on product dimensions, see [Key tasks: Define products](key-tasks-define-products.md).


> [!NOTE]
> <P>A product of the <STRONG>Product</STRONG> subtype has no variants. Products of this subtype are not associated with a product dimension group.</P>



## Storage dimension groups and tracking dimension groups

The storage dimension group and the tracking dimension group do not have to be associated with a product until after the product has been created. A shared product definition that does not have a storage dimension group or a tracking dimension group can also be released to a company.


> [!NOTE]
> <P>A product cannot be applied on a transaction line unless a storage dimension group and a tracking dimension group are associated with the product.</P>



The method that you use to associate a storage dimension group and a tracking dimension group with a product varies, depending on the method that you use to create the product:

  - If you create a shared product definition from the **All products and product masters** list page, the storage dimension group and the tracking dimension group are assigned after you create the product.

  - If you create a released product from the **Released products** list page, you can assign the storage dimension group and the tracking dimension group when you create the released product. However, you do not have to add this information to create a released product.

  - A shared product can be released to one or more companies even if a storage dimension group or a tracking dimension group has not been assigned. In this case, you must add this information to the company-specific product after the product has been released.

### Add a storage dimension group and a tracking dimension group to an existing product

1.  Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**.

2.  Select a product, and then, on the **Action Pane**, in the **Set up** group, click **Dimension groups**.

3.  In the **Storage dimension group** field, select the storage dimension group for the product. In the **Tracking dimension group** field, select the tracking dimension group.

### Define a storage dimension group and a tracking dimension group when a released product is created

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, in the **New** group, click **Product**.

3.  In the **New Released product** dialog box, click **Show more fields**.

4.  In the **Storage dimension group** field, select the storage dimension group for the released product. In the **Tracking dimension group** field, select the tracking dimension group.

## Changing the product dimension group for a product master

The setup of the product dimension group for a product master can be changed if the product master has not been released, and if no dimensions have been created. Otherwise, the following rules apply:

  - If a product master has been shared, the setup of the product dimension group cannot be changed. This rule applies both to the shared instance of the product master and to any company-specific instances.

  - If a product master is created as a released product master, the product dimension group cannot be changed.

  - If dimensions have been created for a product master, the product dimension group cannot be changed. However, if the dimension setup of a new product dimension group is identical to the dimension setup of the original product dimension group, the new product dimension group can be changed.
    

    > [!TIP]
    > <P>To change the product dimension group of a product master, use the same procedure that you use to add a dimension group to an existing product.</P>



## Changing the storage dimension group and the tracking dimension group for a product

If a product has transactions, the storage dimension group and the tracking dimension group cannot be changed. However, if the product is not used in any transactions, the following rules apply:

  - For a shared product, the storage dimension group and the tracking dimension group can be changed if the product has not been released.

  - For a released product, you must follow these steps to change the storage dimension group and the tracking dimension group:
    
    1.  Delete the setup of the storage dimension group and the tracking dimension group for the shared instance of the product.
    
    2.  Delete the setup of the storage dimension group and the tracking dimension group for the released instance or instances of the product.
    
    3.  Select a new storage dimension group and a new tracking dimension group for the shared instance of the product.
        
        The new storage dimension group and the new tracking dimension group are replicated in the released instance or instances of the product.

## See also

[About mandatory inventory dimensions](about-mandatory-inventory-dimensions.md)

  



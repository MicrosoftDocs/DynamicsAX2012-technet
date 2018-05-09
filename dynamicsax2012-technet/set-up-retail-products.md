---
title: Set up retail products
TOCTitle: Set up retail products
ms:assetid: f24ee310-09fa-42ba-9868-b794eaf87706
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597279(v=AX.60)
ms:contentKeyID: 39519363
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00038
- retail product
- retail products
---

# Set up retail products 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Before you can offer products for resale in your retail channels, you must create and configure the products in Microsoft Dynamics AX. Retail uses the product features in Microsoft Dynamics AX to create organization-wide products in the product master.

A product must be defined at the shared company level before the product can be used by Microsoft Dynamics AX. After the product is defined, the product definition must be released, or authorized for use. During the release, the product definition is associated with one or more companies.

1.  Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**.

2.  On the **Products** list page, on the **Action Pane**, in the **New** group, click **Product**.

3.  In the **New product** dialog box, enter the following values:
    
      - In the **Product type** field, select **Item** or **Service**.
    
      - In the **Product subtype** field, select **Product** or **Product master**.
        
        Select **Product master** if the product that you are defining includes product variants.
        

        > [!NOTE]
        > <P>Only predefined variants are supported in Microsoft Dynamics AX for Retail POS.</P>

    
      - In the **Product name** field, enter the name of the product.
    
      - In the **Search name** field, enter a search name that can make it easier to search for the product.
    
      - In the **Category** field, select the retail product category that the product is assigned to.
        

        > [!NOTE]
        > <P>You can assign the product properties and attributes for the retail product at the category level. Any products that are assigned to a specific category inherit those properties and attributes. However, you can override the properties and attributes for a specific product.</P>



4.  Enter any additional information that is required for the product. If the product is a product master and includes product variants, configure the data for the product variants.
    
    For more information about how to configure products, product masters, and product variants, see [Key tasks: Define products](key-tasks-define-products.md).

5.  After you have finished defining the product, release the product to the legal entities in which it is available. In the **Product details** form, on the **Action Pane**, in the **Product authorization** group, click **Release products**.
    
    For more information about how to release products to legal entities, see [Key tasks: Release products](key-tasks-release-products.md).

## See also

[Product details (form)](https://technet.microsoft.com/en-us/library/hh545519\(v=ax.60\))

[Released product details (form) (Retail)](https://technet.microsoft.com/en-us/library/hh580615\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


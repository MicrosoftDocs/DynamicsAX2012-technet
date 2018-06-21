---
title: Set up retail products (Retail essentials)
TOCTitle: Set up retail products (Retail essentials)
ms:assetid: 21187749-cd62-4f3f-9f62-88155e4214ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716056(v=AX.60)
ms:contentKeyID: 62200320
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up retail products (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Before you can offer products for resale in your retail channels, you must create and configure the products in Retail essentials. Retail essentials uses the product features to create organization-wide products in the product master. This topic explains how to create and configure products in Retail essentials.

A product must be defined at the shared company level before the product can be used by Retail essentials. After the product is defined, the product definition must be released, or authorized for use. During the release, the product definition is associated with one or more companies.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



1.  Click **Retail essentials** \> **Merchandising** \> **Products by category**.

2.  In the **Product details** form, on the **Action Pane**, in the **New** group, click **Product**.

3.  In the **New product** dialog box, enter the following values:
    
      - In the **Product type** field, select **Item** or **Service**.
    
      - In the **Product subtype** field, select **Product** or **Product master**.
        
        Select **Product master** if the product that you are defining includes product variants.
    
      - In the **Product number** field, enter the identification number for the product.
    
      - In the **Product name** field, enter the name of the product.
    
      - In the **Search name** field, enter a search name that can make it easier to search for the product.
    
      - In the **Retail category** field, select the retail product category that the product is assigned to.
        

        > [!NOTE]
        > <P>You can assign the product properties and attributes for the retail product at the category level. Any products that are assigned to a specific category inherit those properties and attributes. However, you can override the properties and attributes for a specific product.</P>

    
      - If the product is sold by weight, select the **CW product** check box.

4.  Enter any additional information that is required for the product. If the product is a product master and includes product variants, configure the data for the product variants.

5.  After you have finished defining the product, you must release the product to the legal entities where it is available. In the **Product details** form, on the **Action Pane**, in the **Product authorization** group, click **Release products**.

## See also

[Setting up retail products (Retail essentials)](setting-up-retail-products-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


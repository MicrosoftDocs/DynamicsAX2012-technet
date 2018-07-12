---
title: 'Key tasks: Define products'
TOCTitle: 'Key tasks: Define products'
ms:assetid: 0a7ebc8c-8684-4349-a403-3b30c33350ad
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242124(v=AX.60)
ms:contentKeyID: 36055986
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- products
- product
- authorize product definition for use
- create products
- define products
- product definitions
- product masters
- products of the type Item
- products of the type Service
- shared products
---

# Key tasks: Define products 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the tasks that you must complete to define products, product masters, and product variants.

A product must be defined at the shared company level before being available for use by Microsoft Dynamics AX 2012. After the product is defined, the product definition must be released, or authorized for use. During the release, the product definition is associated with one or more companies.


> [!NOTE]
> <P>Properties that are related to the shared product definition differ from company-specific properties that are related to a product that has been released. Company-specific properties are only defined for a product that has been released.</P>



Products can be of the **Product** or **Product master** subtype. After you define a product as a product master, you can create product variants that are based on the product master.

  - Product – A fixed product definition that does not have any variants.

  - Product master – A product definition that forms the basis of product variants.

  - Product variant – A product that is based on a product master. Product variants are distinguished by the setup of their product dimensions and through configurations.

## What do you want to do?

Learn more about...

Define products and create product variants

Define a product of the Product subtype

Define a product master

Create product variants

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About product dimensions](about-product-dimensions.md)

[Setting up and maintaining product configurations](setting-up-and-maintaining-product-configurations.md)

[Setting up and maintaining product builder](setting-up-and-maintaining-product-builder.md)

## Define products and create product variants

You define products from the following locations:

  - **Products** – Use this list page to define products of the **Product** subtype.

  - **Product masters** – Use this list page to define products of the **Product master** subtype.

  - **All products and product masters** – Use this list page to define products of both subtypes.

  - **Product details** – Use this form to create a detailed product definition. For example, for a product master, you can specify new variants to be generated at the time when new dimensions are associated with the product master.
    

    > [!TIP]
    > <P>To open the <STRONG>Product details</STRONG> form, define a product on the <STRONG>Products</STRONG>, <STRONG>Product masters</STRONG>, or <STRONG>All products and product masters</STRONG> list page. Then, on the <STRONG>Action Pane</STRONG>, in the <STRONG>Maintain</STRONG> group, click <STRONG>Edit</STRONG>.</P>



  - **Released products** – Use this list page to create product definitions and release product definitions.
    

    > [!NOTE]
    > <P>If you use this list page to create a product definition, you can specify information, such as the item model group, when you create the product definition. However, if you create a product definition in, for example, the <STRONG>Products</STRONG> list page and then subsequently release the product definition to a company, you must add the item model group to the product after the release.</P>



The following procedures use the **Products** and **Product masters** list pages to create shared product definitions.

Back to top

## Define a product of the Product subtype

1.  Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**.

2.  On the **Action Pane**, in the **New** group, click **Product**.

3.  In the **Product type** field, select **Item**.
    

    > [!TIP]
    > <P>If you are defining a service product, select <STRONG>Service</STRONG>.</P>



4.  In the **Product subtype** field, select **Product**.

5.  In the **Product number** field, enter a product number.

6.  In the **Search name** field, enter a search name to make it easier to search for the product.
    

    > [!TIP]
    > <P>A search name is optional. You only have to specify a search name if it differs from the product number and product name.</P>



Back to top

## Define a product master

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  On the **Action Pane**, in the **New** group, click **Product**.

3.  In the **Product type** field, select **Item**. Then, in the **Product subtype** field, select **Product master**.

4.  In the **Product number** field, enter a product number.

5.  In the **Search name** field, enter a search name to make it easier to search for the product master.
    

    > [!TIP]
    > <P>A search name is optional. You only have to specify a search name if it differs from the product number and product name.</P>



6.  In the **Product dimension group** field, select a product dimension group.
    

    > [!NOTE]
    > <P>By selecting a product dimension group, you limit the variants that can be created for the product master:</P>
    > <UL>
    > <LI>
    > <P>The active product dimensions in the product dimension group determine the dimensions that must be defined for the product master.</P>
    > <LI>
    > <P>The dimensions that you define for the product master determine the variants that can be created.</P></LI></UL>
    > <P>The <STRONG>Constraint-based configuration</STRONG> configuration technology requires a product dimension group in which the <STRONG>Configurations</STRONG> dimension is active.</P>



7.  In the **Configuration technology** field, select a configuration technology. The following table describes the configuration technologies that are available.
    

    > [!TIP]
    > <P>The configuration technology determines how and when product variants that are based on the current product master are configured.</P>

    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Configuration technology</strong></p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Predefined variant</strong></p></td>
    <td><p>Variants are configured by using the product dimensions when the variants are created. Therefore, after you create the product master, you can assign product dimensions and create product variants.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dimension-based configuration</strong></p></td>
    <td><p>Variants are configured by using the <strong>Configuration</strong> dimension when the variants are added to transaction lines. The <strong>Configuration</strong> dimension must be active in the product dimension group that is associated with the product master.</p>
    <div>

    > [!TIP]
    > <P>The <STRONG>Size</STRONG> and <STRONG>Color</STRONG> dimensions can also be used with this configuration technology.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rule-based configuration</strong></p></td>
    <td><p>Variants are configured by using Product Builder when the variants are added to transaction lines.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Constraint-based configuration</strong></p></td>
    <td><p>Variants are configured by using the Product configurator when the variants are added to transaction lines.</p></td>
    </tr>
    </tbody>
    </table>


8.  Click **OK**.

After you create the definition for the product master, you must complete the following procedures to set up the product master so that product variants can be created:

  - Define product dimensions for the product master.

  - Specify whether variants that are based on the product master can have identical configurations.

  - Specify whether new variants are generated when new product dimensions are assigned to a product master.

### Define product dimensions for a product master

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  Select a product master, and then click **Product dimensions**.

3.  Click the **Sizes**, **Colors**, and **Configurations** links to define dimensions for the size, color, and configuration.
    

    > [!NOTE]
    > <P>The links that are available depend on the dimensions that are active in the associated product dimension groups.</P>



4.  Click **New** to create a new dimension.

### Allow identical configurations

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  Select a product master. Then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  Select the **Allow identical configurations** check box.
    

    > [!NOTE]
    > <P>If the check box is cleared, you cannot create a new variant that is identical to an existing variant.</P>

    

    > [!TIP]
    > <P>This check box is available only if the configuration technology for the product master is set to <STRONG>Dimension-based configuration</STRONG>.</P>



### Generate variants for new product dimensions

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  Select a product master. Then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  Select the **Generate variants automatically** check box.
    

    > [!TIP]
    > <P>This check box is available only if the configuration technology for the product master is set to <STRONG>Dimension-based configuration</STRONG> or <STRONG>Predefined variant</STRONG>.</P>



Back to top

## Create product variants

You can create product variants by using three different methods:

  - Create product variants manually.

  - Create product variants based on suggestions. When you use this method, a list of the variants that can be created for the product master is displayed. The list is based on all the combinations of product dimensions that exist for the product master.

  - Create additional product variants based on new product dimensions. When you use this method, new product variants are generated for any additional dimensions that are associated with the product master.

### Create product variants manually

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  Select a product master, and then click **Product variants**.

3.  Click **New**, and then select a combination of dimensions of the **Size**, **Color**, and **Configuration** types.
    

    > [!TIP]
    > <P>The dimensions that are available depend on the dimensions that are created for the product master.</P>



4.  Press CTRL+S to save the product variant.

5.  Repeat steps 1 through 4 for each variant that you want to create.

### Create product variants based on suggestions

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  Select a product master, and then click **Product variants**.

3.  Click **Variant suggestions** to display a list of possible product variants.

4.  Select the check box next to each product variant that you want to create, or click **Select all** to select all the product variants in the list.

5.  Click **Create**.

### Create additional product variants based on new product dimensions

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  Select a product master. Then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  Select the **Generate variants automatically** check box.

4.  On the **Product masters** list page or in the **Product details** form, on the **Action Pane**, in the **Product master** group, select **Product dimensions**.

5.  Create the product dimensions that you want to add to the product master.

6.  On the **Product masters** list page or in the **Product details** form, on the **Action Pane**, in the **Product master** group, click **Product variants**. The additional product variants that have been created are displayed.

Back to top

## Find form help

[Product details (form)](https://technet.microsoft.com/en-us/library/hh545519\(v=ax.60\))

[Released product details (form)](https://technet.microsoft.com/en-us/library/aa615563\(v=ax.60\))

## Find related tasks

[Key tasks: Release products](key-tasks-release-products.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


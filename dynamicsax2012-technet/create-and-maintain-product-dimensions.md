---
title: Create and maintain product dimensions
TOCTitle: Create and maintain product dimensions
ms:assetid: 4777254f-329d-421d-aaf5-c0d30265b242
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496995(v=AX.60)
ms:contentKeyID: 42518527
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create product dimension
---

# Create and maintain product dimensions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You create product dimensions by using a product dimension group. The product dimensions in a product dimension group control in which product dimension values you can create for product masters that are associated with the product dimension group. The product dimension values control the product variants that can be created for a product master. For more information about how to create product variants, see “Create product variants” in [Key tasks: Define products](key-tasks-define-products.md).

## Create and maintain product dimension values

Dimension values are often referred to as dimensions. However, dimensions are the fixed dimension set that is part of the product dimension group. You can define dimension values to distinguish individual product variants. To create and maintain such dimension values, you must associate a product master with a product dimension group. It is the set of dimensions in the dimension group that controls the dimension values that you can create for the product master.

## Create product dimension values for a product master

1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  On the **Action Pane**, in the **Product master** group, click **Product dimensions**.

3.  Click the **Configurations**, **Sizes**, and **Colors** links to create values for configuration, size and color.
    

    > [!NOTE]
    > <P>The links that are available when you open this form are determined by the active dimensions on the associated product dimension group.</P>



4.  Press CTRL+N or click **New** to create new dimension values and specify an ID and, optionally, a name for each new dimension value that you create.

## Example: Create a product dimension group and assign dimension values

In the following example, a product master for which you can create small, medium, and large dimension values sizes, and the colors red, green, and black, is associated with a product dimension group that uses the **Size** and **Color** dimensions.

1.  Click **Product information management** \> **Setup** \> **Dimension groups** \> **Product dimension groups**.

2.  Press CTRL+N or click **New** to create a new dimension group.

3.  In the **Name** field, enter a name for the dimension group.

4.  Optional: In the **Description** field, enter a description for the dimension group.

5.  Save the group.
    
    The dimension group is created, the **Configuration** dimension is set to **Active**, and the **For purchase prices** and **For sales prices** check boxes are selected.

6.  Select or clear the **Active** check boxes for **Configuration**, **Size**, and **Color**, according to the dimensions to define for the dimension group.

7.  Select or clear the **For purchase prices** and **For sales prices** check boxes, which are used for price search purposes. For more information, see [Product dimension groups (form)](https://technet.microsoft.com/en-us/library/hh227672\(v=ax.60\)).
    

    > [!TIP]
    > <P>The <STRONG>Size</STRONG> and the <STRONG>Color</STRONG> dimensions can be used for other purposes than to specify sizes and colors. Click <STRONG>Rename</STRONG> to rename the dimensions.</P>



## See also

[Rename product dimensions](rename-product-dimensions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


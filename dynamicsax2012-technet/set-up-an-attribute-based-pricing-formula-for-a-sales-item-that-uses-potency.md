---
title: Set up an attribute-based pricing formula for a sales item that uses potency
TOCTitle: Set up an attribute-based pricing formula for a sales item that uses potency
ms:assetid: ee19405e-c09e-4e24-9f90-3a33f941f20d
ms:mtpsurl: https://technet.microsoft.com/library/Dn527700(v=AX.60)
ms:contentKeyID: 59626233
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up an attribute-based pricing formula for a sales item that uses potency 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use this procedure to set up an attribute-based pricing formula to calculate sales prices for potency items.

## Create a formula for attribute-based price calculations

Create a formula that can be associated with a product. The formula can be used to define how the potency of the item affects the sales price. For example, the sales price of a pharmaceutical product can depend on the concentration of a specific chemical ingredient in the product. The concentration of the chemical ingredient makes up the potency of the product.

To create a formula for attribute-based price calculations, follow these steps:

1.  Click **Sales and marketing** \> **Setup** \> **Price/discount** \> **Attribute-based pricing details**.

2.  Click **New** and create a new attribute-based pricing ID.

3.  In the **Name** and **Description** fields, add a name and a description.

4.  On the **Equation** FastTab, in the **Equation** field, enter the equation for the pricing formula.

5.  On the **Elements** FastTab, click **Add variable** to add an equation variable.

6.  In the **Equation element** field, enter the equation element that identifies a set of values that are used in the equation. Use only alphabetical characters for the equation element.

7.  In the **Equation element type** field, select the type of equation element from the following options:
    
      - **Transaction quantity** – The transaction quantity of the inventory item.
    
      - **Unit price** – The unit price of the inventory item.
    
      - **Batch attribute - Actual** - The actual percentage of potency for an inventory batch.
    
      - **Constant** - The standard percentage of potency for an inventory batch.
    
      - **Select the element type** - The default value for the type of equation element.
    
      - **Batch attribute - Target** - The target percentage of potency for an inventory batch.

8.  Click **Validate equation** to validate the equation and the equation elements.

9.  In the **Attribute** field, select the batch attribute.

## See also

[About potency management](about-potency-management.md)

[Create price calculations for sales order items that have a potency](create-price-calculations-for-sales-order-items-that-have-a-potency.md)

  



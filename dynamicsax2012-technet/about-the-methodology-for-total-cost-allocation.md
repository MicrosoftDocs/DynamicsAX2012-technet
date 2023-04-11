---
title: About the methodology for total cost allocation
TOCTitle: About the methodology for total cost allocation
ms:assetid: 05a97501-8a5e-4cc3-b57b-f63bfbae21f1
ms:mtpsurl: https://technet.microsoft.com/library/Hh352179(v=AX.60)
ms:contentKeyID: 36687810
author: tfehr
ms.author: daxcpft
ms.date: 04/10/2017
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About the methodology for total cost allocation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Total Cost Allocation (TCA) is a method of calculating the cost between the main formula item for a batch order and the co-products that are defined for the formula. The method is dynamic. It calculates the cost as a weighted average between the quantities that are reported as finished for the formula item and the co-products. When this method is used, the user does not have to review cost allocations for every batch order. If TCA is not selected, the formula calculation uses existing functionality.

## Using TCA with co-products

Some of the guidelines for using TCA for co-products include the following:

  - If you select the **Total Cost Allocation** check box for a formula version, co-products must have a cost price that is larger than zero. The value can be retrieved from the active cost version for the same site, or the first site for a non-site specific formula. This feature is validated when the formula is approved.
    
      - You don’t need to manually enter cost allocation percentages for co-products. Instead, the system automatically creates the cost allocation percentage as the average of active cost prices of co-products.
    
      - You don’t need to enter standard cost for non-standard cost items that are co-products. There are two types of costing versions in the system:standard cost and planned cost
    
      - If an item isn’t valuated by the standard cost valuation method, we recommend you use an active cost price in the planned cost version. This price is used for cost estimation, for example, BOM calculation, production cost estimation, and fallback price in the inventory valuation process.

  - If you select the **Total Cost Allocation** check box on the formula version and the following conditions are true:
    
      - You have added co-products.
    
      - You have used a different method of cost allocation for the co-products.
    
    Then the method of cost allocation uses TCA, and the percentage of cost allocation is unchanged.

  - If you clear the **Total Cost Allocation** check box on the formula version and the following conditions are true:
    
      - You have added co-products.
    
      - The percentage of cost allocation is larger than zero.
        
        Then the method of cost allocation is changed to **Manual**, and the percentage of cost allocation is unchanged.

  - Before you can successfully perform a formula calculation, you must estimate the percentages of cost allocation. You can do this either manually or by using the new **Estimate cost** option in the **Co-products** form.

  - When a batch order is created manually or a planned batch order is firmed, the **Total Cost Allocation** check box on the formula version is copied to the batch order. However, you can change this setting on the batch order.
    
    If the **Total Cost Allocation** check box is not selected on the formula version and is selected on the batch order, the method of cost allocation for each line that was set to **Manual** is changed to **TCA**. The cost allocation of **None** is unchanged.
    
    If the **Total Cost Allocation** check box is selected for the formula version and you clear it on the batch order, the method of cost allocation for each co-product of the type **Production** is changed to **Manual**. Any estimated percentage of cost allocation is unchanged.

  - The **Estimate cost** option is available only when the **Total Cost Allocation** check box is set on the formula version. You can view the expected allocation if the batch order quantities that are reported as finished match quantities that appear on the formula.

  - The **Co-product cost allocation** form displays the calculated cost allocation percent. You can access the form from the **Batch order** form. This information is useful when the products and quantities that are reported differ from the scheduled or started quantities on the batch order. When cost is complete, these new percentage allocations from TCA are displayed in the **Co-product cost allocation** form.

## Calculating the burden for by-products

The **Burden** field in the **Co-products** form is an enumerator field and is only used with by-products. For co-products, the value for this field is always **None**. For by-product lines, this field determines how cost amount for the by-product line is added to the total cost of the production. The options are as follows:

  - **None** ─ No amount is added to the total cost of the production for this by-product line.

  - **Percent** ─ The cost amount is calculated as a percentage of the total cost of raw materials that are consumed in the production. The percentage that is used for the calculation is entered in the field.

  - **Per series** ─ The cost amount is calculated as an amount per standard batch size of the production order. This amount is independent of the reported quantity in production. The amount that is used for the calculation is entered in the field.

  - **Per quantity** The cost amount is calculated as an amount per reported quantity of the formula item in the production. The amount that is used for the calculation is entered in the field.

## See also

[Co-products (form)](https://technet.microsoft.com/library/hh328754\(v=ax.60\))

[Co-product cost allocation (form)](https://technet.microsoft.com/library/hh328679\(v=ax.60\))

  



---
title: About co-products and by-products
TOCTitle: About co-products and by-products
ms:assetid: 9ddb40e1-afe6-486d-8404-9b3b61f490c8
ms:mtpsurl: https://technet.microsoft.com/library/Hh352310(v=AX.60)
ms:contentKeyID: 36687939
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- materials
- by-product
- process industries
- goods
- coproduct
- byproduct
- co-product
audience: Application User
ms.search.region: Global
---

# About co-products and by-products 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Co-products are desirable secondary goods that are generated during the manufacturing process and can be sold or reused profitably. They might also be products that are usually manufactured together or sequentially because of product or process similarities. Although co-products are usually planned, desirable outputs from the manufacturing process, they can also be used as ingredients in other production processes.

By-products are materials of value that are produced as a residual of, or incidental to, the production process. By-products can be recycled, sold as is, or used for other purposes. You can set up by-products to contribute costs, burden, to the overall production process.

## Cost allocation for co-products

When you set up a co-product in the **Co-products** form in **Inventory and warehouse management**, you specify the type of cost allocation to use to allocate costs to the batch order for each co-product. Cost allocation does not apply to by-products. You can select from the following types of cost allocation:

  - **None** ─ No cost allocation is applicable for the co-product item.

  - **Manual** ─ Use a cost allocation percentage. The percentage is specified in the corresponding **Cost allocation percent** field.

  - **TCA** ─ Cost allocation calculations are dynamic based on the quantity that is reported as finished by using dollarized weighting. The percentages are estimated automatically, or you can use the **Estimate cost** form to check the suggested cost allocation. For more information about the Total Cost Allocation method, see [About the methodology for total cost allocation](about-the-methodology-for-total-cost-allocation.md).

## Burden for by-products

When you set up a by-product in the **Co-products** form in **Inventory and warehouse management**, you specify the type of burden that is associated with the by-product. Burden does not apply to co-products. You can select from the following types of burden:

  - **None** ─ Always used for co-products.

  - **Percent** ─ Cost of disposing of the by-product is a percentage of the total production cost.

  - **Per series** ─ Burden amount is applied to the cost of the batch order, regardless of the quantity reported as finished. The burden amount is scaled up and down depending on the ratio of the batch order quantity and per series for the by-product on the formula.

  - **Per quantity** ─ Burden is applied to the cost of the batch based on the quantity reported as finished. In this case, the burden amount is scaled up and down depending on the ratio of the report as finished quantity of the by-product in the batch order and the per series for the by-product on the formula.

## See also

[Co-products (form)](https://technet.microsoft.com/library/hh328754\(v=ax.60\))

[Formula (form)](https://technet.microsoft.com/library/hh328668\(v=ax.60\))

  



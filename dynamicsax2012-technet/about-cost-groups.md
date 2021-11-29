---
title: About cost groups
TOCTitle: About cost groups
ms:assetid: 0fe1d738-dde7-47fc-8d89-2c1281ecf15c
ms:mtpsurl: https://technet.microsoft.com/library/Aa496553(v=AX.60)
ms:contentKeyID: 36056021
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About cost groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Cost groups provide the basis for segmenting and analyzing cost contributions in a manufactured item’s calculated cost, such as the cost contributions for material, labor, and overhead. Cost group segmentation has several synonyms within manufacturing environments, such as cost breakdown, cost decomposition, or cost classification.

Cost group segmentation can serve several purposes, such as the following:

  - Segment costs for different types of material, such as ingredients and packaging material for a canned goods product, based on the cost groups that are assigned to items.

  - Segment costs for different types of operations resources, such as different types of labor or machines, based on the cost groups that are assigned to cost categories related to operations resources and routing operations.

  - Segment costs for setup and run time in routing operations, based on the cost groups that are assigned to cost categories related to the routing operations.

  - Segment costs for different types of overheads, such as labor-related and machine-related overheads, based on cost groups that are assigned to indirect costs in the costing sheet setup.

  - Act as the basis for calculating various manufacturing overheads in the costing sheet setup. This can include different overheads related to routing information about operations resources or about setup and run time. Manufacturing overheads can also be related to cost contributions of component material, reflecting a lean manufacturing philosophy that eliminates the need for routing information.

Cost group segmentation applies to a manufactured item’s calculated cost whether it was based on standard costs or planned costs. The **Summary** form displays this segmentation by cost group or by level or by both.

The ability to retain cost group segmentation across multiple levels in a product structure only applies to manufactured items that use a standard cost inventory model. The term splitting refers to this ability to retain cost group segmentation across multiple levels. Without splitting, the cost for a manufactured component is treated as a material cost contribution. The inventory parameter for cost breakdown by subledger indicates that cost group segmentation will be retained across multiple levels in standard cost calculations. Whereas a policy of no levels means that cost group segmentation only applies to a single level calculation. The **Cost rollup by cost group** form, for example, displays the cost group segmentation across multiple levels for standard cost items.

Cost group segmentation can also apply to variances for a standard cost item. A second inventory parameter defines whether variances will be identified by cost group, or just summarized.

A cost group can be assigned a cost group type and a behavior for supplemental segmentation purposes.

  - Cost group type − Each cost group must be assigned a cost group type, which designates it as pertaining to direct material, direct manufacturing, direct outsourcing, indirect or undefined. A cost group designated as direct material can be assigned to items. A direct manufacturing cost group can be assigned to cost categories. A direct outsourcing cost group can be assigned to a product type of service, which enables you to classify costs associated with the service purchase to subcontracting activities. An indirect cost group can be assigned to indirect costs for surcharges or rates. A cost group designated as undefined can be assigned to items, cost categories or indirect costs.
    
    The assignment of a cost group type serves several purposes. First, it constrains the ability to assign a cost group and to view a drop-down list of applicable cost groups. Second, it provides supplemental segmentation for reporting purposes. Third, it can be used to assign ledger accounts for variances.

  - Behavior − Each cost group can optionally be assigned a behavior, which designates the cost group as pertaining to fixed costs or variable costs. A cost group that has a null value for behavior is treated as a variable cost. The assignment of a behavior only serves a reporting purpose. For example, costs can be displayed with segmentation of fixed and variable costs on the costing sheet, and in the **Cost rollup by cost group** form.
    
    If you assign a profit-setting percentage to each cost group, the BOM calculation provides a suggested sales price based on a cost-plus-markup approach.

## See also

[About BOM calculations](about-bom-calculations.md)

[About BOM calculation of a suggested sales price](about-bom-calculation-of-a-suggested-sales-price.md)

  



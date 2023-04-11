---
title: About cost categories used in production routings
TOCTitle: About cost categories used in production routings
ms:assetid: bd761559-f3df-4ef2-9a49-7b3d930358ab
ms:mtpsurl: https://technet.microsoft.com/library/Gg213616(v=AX.60)
ms:contentKeyID: 36059155
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About cost categories used in production routings 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Cost categories apply to manufacturing environments that use routings. Cost categories are assigned to operations resources and routing operations to define hourly costs and segment cost contributions in a manufactured item’s calculated costs. That is, the cost groups that are assigned to cost categories classify manufacturing cost contributions by operation resources and type of activity, such as setup and run time. The specificity of cost group assignment provides the foundation for calculating manufacturing overheads based on routing information.


> [!NOTE]
> <P>Cost categories have several synonyms within manufacturing environments, such as labor rate codes or machine rate codes.</P>



Each cost category has its associated cost records and an assigned cost group. Different cost categories are needed to support different production purposes.

  - Assign different hourly costs by operations resource, such as different costs for various types of labor skills, machines, or manufacturing cells.

  - Assign different hourly costs for the setup time or run time that is associated with a routing operation.

  - Assign operations resource costs on the basis of output quantity rather than hourly costs, such as the piece rates for paying labor.

  - Provide cost group segmentation of cost contributions to a manufactured item’s calculated cost, such as segmentation of labor and machine costs.

  - Provide the cost group basis for overhead calculation formulas, such as labor-related and machine-related overheads or overheads that are related to setup and run time.

A cost category can be assigned to the setup time, process time, and the quantity for a routing operation. When costs or cost group segmentation differ between setup and process time, for example, different cost categories should be defined and assigned to them. The selective usage of cost categories for setup time, process time, and quantity is determined by the route group that is assigned to an operation. Assignment of cost categories to time and quantity can be mandated based on the company-wide policies that are embedded within the **Production parameters** form.

Each cost category has its associated costs that are based on the definition of cost records within a costing version. Use the **Cost category price** form to define the cost records for a specified costing version and site. The cost record for a cost category is initially entered with a pending status and an intended effective date. Activating the cost record updates the status (to current active) and the effective date (to the activation date). Different cost records may reflect different sites, effective dates, or status. Bills of material (BOM) calculations for a future or historical date will use cost records that have the relevant effective date. The current active cost record will be used for estimating production order costs and valuing reported time against a production order.

The cost record for a cost category can be site-specific or company-wide. The cost record will be site-specific if you assign a site to it. Otherwise, a blank value means that the cost record will apply to all sites within the company. Costs may differ between sites, for example, so that the cost records must be defined as site-specific.

A routing operation generally inherits the cost categories that are assigned to the operations resource or master operation. When a production order is created, the routing operations in the production route reflect the selected route version. You can override the cost categories that are assigned to the operations in the production route.

Certain types of production work may apply to project time estimates and reporting, which requires a cost category that can be used for production and project purposes. Additional project-related information must be defined when a cost category is flagged for use in projects.

## See also

[About cost groups](about-cost-groups.md)

[About cost categories used in Production control and in Project management and accounting](about-cost-categories-used-in-production-control-and-in-project-management-and-accounting.md)

  


